# Azure DevOps Licensing Primer

Licensing Azure DevOps shouldn’t be scary. Let me break it down for you.

## Azure DevOps Services (cloud)

Don’t overthink how to license & pay for Azure DevOps. It’s more straightforward than you think, for 2 reasons:

1. Costs you see on the [Azure Pricing Calculator](https://azure.microsoft.com/en-us/pricing/details/devops/azure-devops-services/) are all you need to worry about. Azure DevOps doesn’t charge additional fees under the covers such as Azure Storage, database, etc. WYSIWYG, basically.
2. Did you over- or under- purchase? Azure DevOps is billed via an Azure Subscription monthly, which means you can dial up and down what you need from Azure DevOps each month.

For Azure DevOps Services (i.e. cloud-hosted), user licensing is pretty straightforward:
* Basic: $6/user/month
* Basic + Test Plans: $52/user/month

A few considerations which can reduce overall monthly cost:
* Azure DevOps Services comes with 5 free Basic users included.
* A Visual Studio Professional subscription includes a Basic license for no additional cost.
* A Visual Studio Enterprise subscription includes a Basic + Test Plan license for no additional cost.
* An MSDN Platforms subscription includes a Basic + Test Plan license for no additional cost.
* A Visual Studio Test Professional subscription includes a Basic + Test Plan license for no additional cost.
* Stakeholder users ([comparison 1/2 down this page](https://azure.microsoft.com/en-us/pricing/details/devops/azure-devops-services/)) are free.

Note: Azure DevOps Basic User licenses grant rights to use both Azure DevOps Services (cloud-hosted) AND Azure DevOps Server (on-prem). Azure DevOps Server (on-prem) CALs grant rights to Azure DevOps Server (on-prem) only.

### Other components of Azure DevOps
* Azure Pipelines – includes 1 Microsoft-hosted agent and 1 self-hosted agent. (How to choose)
  * Each additional Microsoft-hosted agent/pipeline: $40/month
  * Each additional self-hosted agent/pipeline: $15/month
* Azure Artifacts – First 2 GB free, then progressive pricing based on usage:
  * 0 – 2 GB = Free
  * 2 – 10 GB = $2 per GB
  * 10 – 100 GB = $1 per GB
  * 100 – 1,000 GB = $0.50 per GB
  * 1,000+ GB = $0.25 per GB

(You can also set Azure Artifacts to limit your feeds to 2GiB to prevent any charges)


Pricing page: [https://azure.microsoft.com/en-us/pricing/details/devops/azure-devops-services/](https://azure.microsoft.com/en-us/pricing/details/devops/azure-devops-services/)

## Azure DevOps Server (on-premises)

For Azure DevOps Server (on-premises), there is a server license, but is included with any active Visual Studio subscription (so doubtful you’d need to purchase one individually). Any active Visual Studio subscription includes both a server license and a client access license (CAL) for Azure DevOps Server.

### More information:
* Pricing page: [https://azure.microsoft.com/en-us/pricing/details/devops/server/](https://azure.microsoft.com/en-us/pricing/details/devops/server/)
