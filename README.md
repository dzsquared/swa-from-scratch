# swa-from-scratch

select devcontainer for azure functions .net 6 (in-process)
add nodejs (select option for 18)

npm install -g @azure/static-web-apps-cli

create folders api and app folders at the root

move to api folder
func init --worker-runtime dotnet
func new --template HttpTrigger --name HelloWorld

*if you hit issues with AzureWebJobsStorage, check out Azurite*

to get rid of red squigglies, run dotnet restore in api folder