# Kubernetes cluster with Availability Sets Master and VMSS Cluster Node 

## deploy

az group deployment create --resource-group KubeSphereVMRG --template-file ./azuredeploy.json --parameters @azuredeploy.parameters.json