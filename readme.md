# Documentation
[![Deploy To Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FPrasad4455%2FInfraShieldAI_CC%2Fmain%2Fazuredeploy.json)




## How does it work
- Full infra deployment via ARM
- Code will be pulled from git hub
- User delegated permissions to authenticate on graph
- Azure App Service for the website and the code logic

## Prerequisites
- GPT enabled Subscription (https://aka.ms/oai/access)
- App registration with deligated permissions (DeviceManagementConfiguration.Read.All, DeviceManagementManagedDevices.Read.All, DeviceManagementApps.Read.All, Group.Read.All, User.Read, Device.Read.All)



## Deployment
[![Deploy To Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FPrasad4455%2FInfraShieldAI_CC%2Fmain%2Fazuredeploy.json)

## Post steps
- Fill out in the App Service Settings the variables (APPLICATION_ID, AZURE_OPENAI_KEY)

## How to contribute?
If you have a ideas for improvements or for missing features as well as bugs, contact me via my blog, social media or open an issue on the repository with an description of your idea.

## Disclosure
This is a community repository. There is no guarantee for this. Please check thoroughly before running the scripts.
