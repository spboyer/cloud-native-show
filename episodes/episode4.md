# Configuration and Settings in ASP.NET Core

One of the "Factors" in cloud native applications states you should store your configuration and settings outside of your core application code. In this episode, Andrew gives us a run down on how the configuration options in .NET Core allows for layers of configurability and abtractions for your app.

## Guest

Andrew Stanton-Nurse [@anurse](https://twitter.com/anurse)

## Docs

* [Configuration in ASP.NET Core](https://docs.microsoft.com/aspnet/core/fundamentals/configuration/?view=aspnetcore-2.2&WT.mc_id=cloudnativeshow-github-shboyer)

## Notes

1. So Andrew, Configuration has come a long way in ASP.NET… (some history)
2. By default .NET Core manages settings and configuration in an order of operations per se? Can you talk about that.
3. Can we mix the various options of configuration options? ENV, JSON, INI etc?
4. What about Environments?
5. Now that we have a base of what’s “in the box”, what about getting these configurations out of our code base and externalizing these? As a practice of Cloud Native we want to manage these seperatly and not have them tied directly to the code base.
6. What are the options?
7. Security, Practices?
8. Are there conventions we should be aware of that the framework follows?
