# OTX-Microsoft-Logic-App
Microsoft Logic App for consuming Open Threat Exchange (OTX) data in Microsoft Sentinel / Log Analytics Workspace

# Pre-Deployment Setup
Before you deploy the Logic App (Azure Resource) below, you first need to gather the API key and Microsoft Graph App identifiers you'll need to provide as parameters.

* Create an account on otx.alienvault.com and copy your API key.
* In the Azure portal, create a new App and assign it the "ThreatIndicators.ReadWrite.OwnedBy" permissions.
    * How to register a new app: https://docs.microsoft.com/en-us/power-apps/developer/data-platform/walkthrough-register-app-azure-active-directory
* Copy the App client ID, App secret, and your tenant ID

# Deploy to Azure
Once you have the IDs and keys from above ready, click the button below to deploy this logic app to your tenant in Azure
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FBinaryDefense%2FOTX-Microsoft-Logic-App%2Fmain%2FOTX-to-Sentinel.json)