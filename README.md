## Plans for the community

A curated list of plans for the community to use.

## Kustomize

Using kustomize we can easily compose plans and build complex workflows in a structured and flexible way.
By creating simple and self contained plans, it's easy to puzzle the pieces together.

## Goal

Create a robust list of workflows with common patterns used to manage, deploy and observe software.

## Build

To build plans present in this repo run:

    kustomize build --load-restrictor LoadRestrictionsNone composers/<my-desired-composer>
    
The minimum version required of Kustomize is: **Version:kustomize/v4.1.2 GitCommit:a5914abad89e0b18129eaf1acc784f9fe7d21439 BuildDate:2021-04-15T20:38:06Z GoOs:darwin GoArch:amd64**
