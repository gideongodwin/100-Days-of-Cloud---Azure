## Day 20: Deploy Azure Resources using Arm Template

#### Task Details:
You are tasked with modifying an ARM template for deploying a virtual network. The current template is located in the /root/arm-templates directory under the filename vnet-deployment-template.json. You need to make the following changes to the template:
- Change the name and `displayName` tag of the virtual network to `arm-vnet-xfusion`
- Update the `addressPrefixes` to `192.168.0.0/16`
- Add one more tag named `Environment` with value `KKE-xfusion`
- After making these changes, you need to deploy the ARM template using the Azure CLI.
- Use the following command to find out the resource group to use:
  `az group list --query '[].name' --output table | grep 'kml'`

Step 1: Open the ARM Template for Editing /n
`vim /root/arm-templates/vnet-deployment-template.json`


