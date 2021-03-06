---
services: App
platforms: .Net
author: jianghaolu
---

# Getting Started with App - Manage Function App Source Control - in .Net #

          Azure App Service basic sample for managing function apps.
           - Create 4 function apps under the same new app service plan:
             - Deploy to 1 using FTP
             - Deploy to 2 using local Git repository
             - Deploy to 3 using a publicly available Git repository
             - Deploy to 4 using a GitHub repository with continuous integration


## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-sdk-for-net/blob/Fluent/AUTH.md).

    git clone https://github.com/Azure-Samples/app-service-dotnet-configure-deployment-sources-for-functions.git

    cd app-service-dotnet-configure-deployment-sources-for-functions

    dotnet restore

    dotnet run

## More information ##

[Azure Management Libraries for C#](https://github.com/Azure/azure-sdk-for-net/tree/Fluent)
[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)
If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.