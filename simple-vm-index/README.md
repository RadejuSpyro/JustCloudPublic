# simple-vm-shutdown-on-time

Universal template with index to deploying stamp servers in AV set. You can using this template for deplyoment windows and linux before select correct variable in OS.

## Create a new simple-vm-shutdown-on-time instance
Option - 1
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FRogalaPiotr%2FJustCloudPublic%2Fmaster%2Fsimple-vm-shutdown-on-time%2Fazuredeploy-1.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https://raw.githubusercontent.com/RogalaPiotr/JustCloudPublic/master/simple-vm-shutdown-on-time/azuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>
Option - 2
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FRogalaPiotr%2FJustCloudPublic%2Fmaster%2Fsimple-vm-shutdown-on-time%2Fazuredeploy-2.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https://raw.githubusercontent.com/RogalaPiotr/JustCloudPublic/master/simple-vm-shutdown-on-time/azuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

## Variables
1. adminUsername
2. adminPassword
3. numberOfInstances
4. OS

## Command to deployment
Option - 1
```json
New-AzureRMResourceGroupDeployment -ResourceGroupName XXX -TemplateURI "https://raw.githubusercontent.com/RogalaPiotr/JustCloudPublic/master/simple-vm-index/azuredeploy-1.json" -adminUsername XXX -adminPassword XXX -vmName XXX
```
Option - 2
```json
New-AzureRMResourceGroupDeployment -ResourceGroupName XXX -TemplateURI "https://raw.githubusercontent.com/RogalaPiotr/JustCloudPublic/master/simple-vm-index/azuredeploy-2.json" -adminUsername XXX -adminPassword XXX -vmName XXX
```

## Author
Piotr Rogala
https://justcloud.pl
