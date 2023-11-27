# Choose Right Tooling for Cloud ?

Greetings to my fellow Technology Advocates and Specialists.

In this Session, I will explain and walk my readers through a debatable topic -  __Choose Right Tooling for Cloud__.

| __DISCLAIMER:-__ |
| --------- |
| The contents of this article is strictly my way of looking into the subject. However, I am convinced that there are other fascinating opinions to look into this debatable topic. |

In every organisation, when you start with cloud, you land up having Hybrid Infrastructure: Part On-Prem, Part Cloud.

For the purpose of this session, please consider below -

| __#__ | __KEY__ | __VALUE__ |
| --------- | --------- | --------- |
| 1. | __Cloud__ | Azure |
| 2. | __Cloud Automation Tooling__ | Azure Devops, Github Actions, Terraform, Biceps, Powershell, AzCLI |
| 3. | __On-Prem Automation Tooling__ | Powershell, Shell Scripting, ... |

If we think, which tooling to go for in cloud, __it would be a wrong approach.__

It would also be wrong to compare between Cloud Automation Tooling and On-Prem Automation Tooling as usecase, purpose and functionality possible could vary.

| __Cloud Automation Tooling can be bifurcated like below:-__ |
| --------- |

| __#__ | __CATEGORY__ | __TOOLING__ | __NOTES__ |
| --------- | --------- | --------- | --------- |
| 1. | __Infrastructure__ | a.) Azure Devops, b.) Github Actions, c.) Terraform, d.) Biceps, e.) Powershell, f.) AzCLI |  IaaS and PaaS |
| 2. | __Database__ | a.) Sql DACPAC, b.) Sqlcmd, c.) Azure Pipelines task for Azure Database for PostgreSQL Flexible Server, d.) GitHub Actions to connect to Azure PostgreSQL, e.) Azure Pipelines for Azure Database for MySQL - Single Server, f.) GitHub Actions to connect to Azure MySQL | - |
| 3. | __Application__ | Deploying C#, F#, ASP.NET, React, Python, R, ... on Azure Services. | - |
| 4. | __Containers__ | a.) Build and deploy to Azure Kubernetes Service with Azure Pipelines, b.) Build, test, and deploy containers to Azure Kubernetes Service (AKS) using GitHub Actions, c.) Deploy to Azure Container Apps from Azure Pipelines, d.) Deploy to Azure Container Apps with GitHub Actions, e.) GitHub Actions with Azure CLI in Azure Container Apps. | - |
| 5. | __Data Orchestration__ | a.) Azure Data Factory, b.) Azure Synapse, c.) Python Code running in AKS performing ETL, ... | - |
| 6. | __API__ | Publish APIs using devops. | - |
| 7. | __Security__ | a.) DevSecOps (Security in DevOps), b.)  DevSecOps with Github | - |

| __On-Prem Automation Tooling can be bifurcated like below:-__ |
| --------- |

| __#__ | __CATEGORY__ | __TOOLING__ | __NOTES__ |
| --------- | --------- | --------- | --------- |
| 1. | __Infrastructure__ | Powershell, Shell Scripting... | IaaS - VM Based Infrastructure |
| 2. | __Application__ | Deploying C#, F#, ASP.NET, React, Python, R, ... on VM Based Infrastructure. | - |

__In my opinion, Approach should be below:-__

| __#__ | __PROJECT TYPE__ | __TOOLING__ |
| --------- | --------- | --------- |
| 1. | __Green Field Project in Azure__ | Cloud Automation Tooling |
| 2. | __Brown Field Project (Re-Factor and Re-Platform)__ | Cloud Automation Tooling |
| 3. | __Brown Field Project (Any Application which cannot be refactored and Operations heavily dependent on On-Prem Automation)__ | On-Prem Automation Tooling |

| __NOTE:-__ |
| --------- |
| __If later down the year, there is a possibility to refactor the application in a way where Infrastructure can be moved to PaaS, On-Prem Automation Tooling can then be replaced with Cloud Automation Tooling.__ |

__In this way, On Prem Automation and Cloud Automation Tooling can co-Exists in Azure Cloud.__

__Hope You Enjoyed the Session !!!__

__Stay Safe | Keep Learning | Spread Knowledge__
