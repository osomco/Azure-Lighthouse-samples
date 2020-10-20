
# OSOMCO con Microsoft Azure Lighthouse

Azure Lighthouse provides capabilities to perform cross-tenant management at scale.  We do this by providing you the ability to view and manage multiple customers from a single context. When you log into Azure, you can see all of your customers who you are managing through Azure Lighthouse. [Learn more](https://azure.com/lighthouse).

This repository contains samples to help you use Azure Resource Manager to configure [Azure delegated resource management](https://docs.microsoft.com/azure/lighthouse/concepts/azure-delegated-resource-management) and to configure monitoring and management of customer environments.

The templates shown below can be used to [onboard a customer to Azure Lighthouse](https://docs.microsoft.com/en-us/azure/lighthouse/how-to/onboard-customer). You can deploy these manually, or use the "Deploy to Azure" buttons to deploy directly in the Azure portal.
# Deploy to Azure buttons

Name | Description   | Auto-deploy   | 
-----| ------------- |--------------- |
| Azure Lighthouse - Subscription Deployment |onboard a *subscription* | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Lighthouse-samples%2Fmaster%2Ftemplates%2Fdelegated-resource-management%2FdelegatedResourceManagement.json) 

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
