# overview

## traditional jx
* cli
* web hooks
    * lighthouse
    * prow
    * jenkins
* pipeline
    * tekton
    * jenkins 
* nexus, charts repo, registry
* gitops, chatops

## custom jx
- jx v2.0.1263
- static jenkins
- jx boot + helm chart via argo
- artifactory & ecr

## traditional vs custom installation

| | TRADITIONAL | CUSTOM 
|---|---|---
| Installation | jx boot | jx boot + helm chart via argo
| Updates      | jx boot | helm chart via argo

References:
* [Overview and Setup](https://foxsportsau.atlassian.net/wiki/spaces/DEV/pages/1556807793/Overview+and+Setup)
