# Red Dog AKS Workshop

## Purpose of this repository

Hands-on workshop to guide learning Azure Kubernetes Service (AKS) and deploy successful cloud native applications.

This repository leverages the [reddog applicaton codebase](https://github.com/Azure/reddog-code) and is created by the Global Black Belt Team from Microsoft.

## Prerequisites

* Access to an Azure Subscription
* Access to Azure Cloud Shell
  * [https://shell.azure.com/](https://shell.azure.com/)

## Workshop Modules


* [Environment Preparation (Start here)](./docs/environment-prep.md)
    * Network Planning
    * Identity Planning
* [Egress lockdown (Optional)](./docs/egress-lockdown.md)
* [Cluster Creation / Nodepool Design](./docs/cluster-creation.md)
* [Application Manifests and Deployment](./docs/app-deployment.md)
    * Version control / Image tags
    * Resource requirements (CPU, memory, etc.)
    * Secret/Config management
    * Health probes
* [Monitoring / Logging](./docs/monitoring.md)
    * Azure Monitor
    * Prometheus / Grafana
    * Alerting
    * Tracing / App Insights   
* Networking
    * [Ingress](docs/ingress.md)
    * [Network Policy](docs/network-policy.md)
* [Image Management / Container Registry](./docs/container-registry.md)
    * Bring images into ACR 
    * Image Security
* [CI/CD & GitOps](./docs/cicd-gitops.md)
* Autoscaling (Steve)
    * [Cluster and node autoscaler](./docs/autoscaling-setup.md)
    * HPA / KEDA
* AKS Cluster Management
    * [Upgrade planning](./docs/cluster-upgrades.md)
    * [Azure Policy](docs/cluster-policy.md)
* [Service Mesh](docs/service-mesh.md)
<!-- * Storage (Joey) -->



## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.