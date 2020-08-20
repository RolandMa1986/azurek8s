# Kubernetes cluster with Availability Sets Master and VMSS Cluster Node 

This template allows you to deploy Kubernetes cluster infrastructrues.

## Architecture
![Architecture](Azure-self-hosted-k8s.png)
## deploy

[![Deploy to Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FRolandMa1986%2Fazurek8s%2Fmaster%2Fazuredeploy.json) [![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)](http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FRolandMa1986%2Fazurek8s%2Fmaster%2Fazuredeploy.json)


### Use az command
az group deployment create --resource-group KubeSphereVMRG --template-file ./azuredeploy.json --parameters @azuredeploy.parameters.json



