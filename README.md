# LogicApps unit test getting started

Modify from
https://github.com/Azure/logicapps/tree/994b3d91d57f7ce88b7d331734dcc03fe54c5816/LogicAppsSampleTestFramework
https://techcommunity.microsoft.com/t5/integrations-on-azure-blog/automated-testing-with-logic-apps-standard/ba-p/2960623



https://www.integration-playbook.io/docs/logic-app-testing
https://coffeefirst.dev/azure/how-to-test-a-logic-app/
https://www.mikestephenson.me/2021/12/11/logic-app-standard-integration-testing/

## Prerequisite

1. Install Hosting Bundle https://dotnet.microsoft.com/en-us/download/dotnet/3.1
2. Install Dotnet SDK https://dotnet.microsoft.com/en-us/download/visual-studio-sdks
3. Install azure-functions-core-tools & unzip & add path  https://github.com/Azure/azure-functions-core-tools/releases
5. VSCode extension Azurite 

## Setup
```
dotnet new sln
dotnet sln add TestCases/TestCases.csproj
dotnet sln add TestFramework/TestFramework.csproj
dotnet test
```

