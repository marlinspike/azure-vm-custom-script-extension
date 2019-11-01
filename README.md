## Purpose
This sample ARM template creates a VM in Azure Comercial or Azure Gov,
and runs a PowerShell Script on the VM using Custom Script Extension.

Go to Azure Docs For more about 
[Azure Custom Script Extension](https://docs.microsoft.com/en-us/azure/virtual-machines/extensions/custom-script-windows)

## Pre-requisites
* A Storage Account
* Blob Container
* Upload the included powershell script to the container you created

## Customizing
* Modify the vm-with-cse.json file with the appropriate parameters for the blob URI and SAS Token
* Modify the vm-wish-cse.json.parameters.json file with the Username and Password you'd like

## Expectations
You should see a helloworld.txt file dropped on your C:\ root folder with a little 'hello world' greeting in it.

