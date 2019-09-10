# Episode 4 -Configuration and Settings in ASP.NET Core

## Guest

Andrew Stanton-Nurse [@anurse](https://twitter.com/anurse)

## Introduction

One of the "Factors" in cloud native applications states you should store your configuration and settings outside of your core application code. In this episode, Andrew gives us a run down on how the configuration options in .NET Core allows for layers of configurability and abstractions for your app.

## Key Points / Questions

1. Configuration has come a long way in ASP.NET…no more XML files?
1. By default .NET Core manages settings and configuration in an order of operations per se? Can you talk about that.
1. Can we mix the various options of configuration options? ENV, JSON, INI etc?
1. What about Environments?
1. Now that we have a base of what’s “in the box”, what about getting these configurations out of our code base and externalizing these? As a practice of Cloud Native we want to manage these separately and not have them tied directly to the code base.
1. What are the options?
1. Security, Practices?
1. Are there conventions we should be aware of that the framework follows?

## Show Notes

* [Configuration in ASP.NET Core](https://docs.microsoft.com/aspnet/core/fundamentals/configuration/?view=aspnetcore-2.2&WT.mc_id=cloudnativeshow-github-shboyer)
* [Azure Key Vault Configuration Provider](https://docs.microsoft.com/aspnet/core/security/key-vault-configuration?view=aspnetcore-2.2&WT.mc_id=cloudnativeshow-github-shboyer)
* [Azure Apps: Override app configuration using the Azure Portal](https://docs.microsoft.com/aspnet/core/host-and-deploy/azure-apps/index?view=aspnetcore-2.2#override-app-configuration-using-the-azure-portal&WT.mc_id=cloudnativeshow-github-shboyer)
* [Configuration: Options pattern in ASP.NET Core](https://docs.microsoft.com/aspnet/core/fundamentals/configuration/options?view=aspnetcore-2.2&WT.mc_id=cloudnativeshow-github-shboyer)
