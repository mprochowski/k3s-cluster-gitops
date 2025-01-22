# k3s GitOps

The structure is based on an article about GitOps Structure[^1]. 
The approach is to separate all services/applications into 3-4 layers (bootstrap, infrastructure, services, applications). 
Each layer can based only on elements from the previous layer for eg. services can use the elements from the infrastructure layer, but not from the application layer

## Reference
[^1]: [GitOps Structure - https://production-gitops.dev/gitops/structure/](https://production-gitops.dev/gitops/structure/)
