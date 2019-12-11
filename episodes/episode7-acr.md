# Container Registries. Why are they important?

## Introduction

Container registries are repositories for storing container images, but who should use them? Which one should we choose and why are they imporant for cloud native applications? Steve Lasker sits with us in Building 99 today and talks about registries and more specifically Azure Container Registry and the practices around using them for your applications.


## Guest

Steve Lasker [@stevelasker](https://twitter.com/stevelasker)


## Markers 

3:50 - How do I choose the registry to use?
6:15 - Additional benefits to registries beyond to being close to my deployment?
8:10 - How do you think about life cycle management, from the point of development to long term patching support? I've seen acr build, and tasks, but what's the magic here?
11:00 - Security patching, does that happen automatically with ACR?
14:00 - Steve breaks down the trigger of an automated build by ACR
18:25 - What's coming next?

## Links

[Free Azure Account](https://aka.ms/cldntvshw/freeazure) 
[Azure Container Registry](https://aka.ms/cldntvshw/acr)


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
