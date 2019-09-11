# Container Registries, Artifacts and where Distribution is heading

## Introduction

## Guest

Steve Lasker

## Questions & Topics

1.  What is a registry, why is it important for cloud native apps
2.  How do I choose which registry to use?
    1.  Closest to your deployment
    2.  ACR supports geo-replication to make sure it's closest to your azure, on-prem or pop, or roaming deployment
3.  How do you think about life cycle management, from the point of development to long term patching support? I've seen acr build, and tasks, but what's the magic here?
    1.  Security features
        1.  VNet & Firewall Rules
        2.  Vulnerability Scanning with best of breed and 1st party solutions
        3.  Quarantine Pattern - to secure registry content, by default
    2.  Patching
4.  What's coming next?
    1.  Looking at our top 5 User Voice requests (https://aka.ms/acr/uservoice)
    2.  Autopurge
        1.  Demo
    3.  Repo permissions
    4.  Vulnerability scanning
    5.  Audit Logs
        1.  Demo
    6.  Service Principals easier to use - tokens for IoT scenarios
5.  What's the future
    1.  OCI Artifacts

Demo of pushing random stuff into the registry
