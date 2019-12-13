# Deploy a Windows VM and execute a custom PowerShell script.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https://raw.githubusercontent.com/ReplyQuickStart/AzureVM-SQL/master/azuredeploy.json" target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png"/>
</a>



Based on the 101-simple-windows-vm template, this template allows you to deploy a simple Windows VM and execute a custom PowerShell script using the custom script extension. The PowerShell script installs a file on the VM.  The script and file must be staged in Azure storage and that can be done automatically using the deployment scripts in the root of this repo.


