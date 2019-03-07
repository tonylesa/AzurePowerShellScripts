# azure

Credits to original author git: https://github.com/sympa18/CheckandApplyTags

Copied and updated with latest PowerShell commands:

Login-AzureRmAccount replaced with Login-AzAccount

Find-AzureRmResource replaced with get-azresource

Get-AzureRmResourceGroup replaced with Get-AzResourceGroup

Set-AzureRmResource replaced with Set-AzResource


To execute, download (click download button for Zip), extract. Open Azure portal, click on the CLI, choose PowerShell type and drag and drop CheckAndApply.ps1 file directly into the window.

Warning: this will scan EVERY resourcegroup in the CURRENT subscription and ADD tags that are set at the ResourceGroup into the individual resources underneath!

Warning2: Use Get-AzSubscription and Select-AzSubscription to ensure you are working in the desired subscription first!

Inside the powershell prompt, type "cd $home" and .\CheckAndApply.ps1
