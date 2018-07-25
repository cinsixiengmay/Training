# AWS AccessData Training Environment

# Create AWS WorkSpaces for FTK Lab

This template create AWS Workspaces on existing AWS Simple AD. The template requires a domain controller to already be setup.

### REQUIREMENTS
1. Existing domain controller
2. Deploy to the resource group, VNET and Subnet of the domain controller

<a href="https://console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks/new?stackName=myworkspace&templateURL=https://s3-us-west-2.amazonaws.com/ad-training-resources/CloudFormation/cfx-workspace-training.json" target="_blank">
    <img src="https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png"/>
</a>
<a href="https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F201-vm-domain-join%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/AzureGov.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F201-vm-domain-join%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>
