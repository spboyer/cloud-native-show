# Episode 5 - Azure App Configuration

## Guest

Ye Gu / Lisa Guthrie

## Introduction

Cloud native applications often run on multiple vms or containers in many regions using multiple external services. One key recommendation is to separate configuration from our code. Let's have a chat with Ye and hear how Azure App Configuration helps with our cloud native apps.

## Summary

Azure App Configuration is a developer-focused service in Azure that manages and distributes application settings. It helps implement patterns, such as the 12-factor app, and is particularly useful for cloud native and other distributed applications. In this episode, we'll discuss how you can use Azure App Configuration to simplify management of and secure access to your application settings.

## Key Points / Questions

1. What is App Configuration and what problem does it solve?
2. What languages are supported through the SDK?
3. We as .NET Developers are use to having to reload our applications when settings change. .NET Core has made some real improvements, does this middleware get us there too?
4. Is there support for Managed Identity?

## Show Notes

[What is Azure App Configuration](https://docs.microsoft.com/en-us/azure/azure-app-configuration/overview)

[Tutorial: Use dynamic configuration in an ASP.NET Core app](https://docs.microsoft.com/azure/azure-app-configuration/enable-dynamic-configuration-aspnet-core?WT.mc_id=cloudnative-github-shboyer)

[Redesigning Configuration Refresh for Azure App Configuration](https://devblogs.microsoft.com/aspnet/redesigning-configuration-refresh-for-azure-app-configuration?WT.mc_id=cloudnative-github-shboyer)

[Getting Started with Azure App Configuration | Azure Friday](https://www.youtube.com/watch?v=EIvuLLAMLZg)
