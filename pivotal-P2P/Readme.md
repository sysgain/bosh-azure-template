##Solution Template Overview:  Pivotal Cloud Foundry + Concourse + Apigee
Solution Templates provide customers with a highly automated process to launch enterprise ready first and 3rd party ISV solution stacks on Azure in a pre-production environment. The Solution Template effort is complimentary to the Azure Marketplace test drive program. These fully baked stacks enable customers to quickly stand up a PoC or Piloting environments and also integrate it with their systems and customization.
Customers benefit greatly from solution templates because of the ease with which they can stand up enterprise-grade, fully integrated stacks on Azure. The extensive automation and testing of these solutions will allow them to spin up pre-production environments with minimal manual steps and customization. Most importantly, customers now have the confidence to transition the solution into a fully production-ready environment with confidence.
Aspera/Wowza - Media Services Solution Template (TBD) launches a secure, on-demand, high quality and reliable audio/video streaming solution with Wowza on Azure. Combined with Aspera and Azure Media services, this solution stack will allow users to quickly instantiate a media services stack/platform and bring their custom content and configuration to be streamed. These are intended as pilot solutions and not production ready.
Please contact us if you need further info or support on this solution.

##Licenses & Costs
In its current state, solution templates come with licenses built-in – there may be a BYOL option included in the future. The solution template will be deployed in the Customer’s Azure subscription, and the Customer will incur Azure usage charges associated with running the solution stack.

##Target Audience
The target audience for these solution templates are:

Application Developers - Application developers seeking introductory understanding of Cloud Foundry and experience using it to deploy, manage, and scale applications.

Administrators & Operators - Administrators and Operators for those who require strong technical knowledge of the Pivotal Cloud Foundry platform and who are interested in deploying applications on Cloud Foundry and customizing the platform.

##Prerequisites
Azure user account with Contributor/Admin Role

Sufficiently high quota limits (Recommended: 100 cores) on your Azure account. Installing Pivotal Cloud Foundry® requires more than the default 20 cores. *Please see this link for instructions on requesting a core quota increase. *Install either the Azure CLI or Azure PowerShell on your machine, using the instructions here. Create an Azure Service Principal (TENANT-ID, CLIENT-ID, CLIENT-SECRET):
Use the Instructions here to generate Azure Service Principal file

Pivotal Network Account: If you do not already have an account, create one. You will need the API token located in your profile. Navigate to your name in the top right and select Edit Profile. The API token is located at the bottom of the page.

## Solution Summary

##Product Architecture
![Product Architecture](https://raw.githubusercontent.com/sysgain/pivotal/master/pivotal-P2P-Architecture.jpg)

##Solution contains the following
The diagram above provides the overall deployment architecture for this solution template.
As a part of deployment, the template launches the following:
Pivotal Cloud Foundry
Concourse Continuous Integration
Apigee Edge Gateway
Azure Meta Service Broker

###RESOURCES
56 Virtual Machines
Document DB
SQL Server
3 Public IP Addresses


##Deployment Steps
You can click the “deploy to Azure” button at the beginning of this document or follow the instructions for command line deployment using the scripts in the root of this repo.
Please refer to parameter descriptions if you need more information on what needs to be provided as an input.
The deployment takes about 3 Hours.
Once it is deployed refer to the user guide to take you to step by step to use the Solution
![User Guide]()
