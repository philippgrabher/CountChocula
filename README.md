
# Test Button!
This is just the Button for Testing

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fphilippgrabher%2Fcountchocula%2Fmaster%2Fazure-deploy-test.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

# Initial Setup
After installing the First VM in a new vNet Bastion wont work because it wont have a public IP.
The easiest way to create that public IP is to try to use Bastion and then follow the Wizard to enable Bastion for the first Host.
This step will take about 5 minutes.


# Provision preconfigured VMs
A test template to provision various preconfigured VMs for various scenarios.

Use to provison VMs in Azure Instance.


## AI-Lab Basic VM

**This deployment will provision an isolated VM with the following software:**
* Windows 10 Pro
* Python 3.8
* Visual Studio Code (latest)
* Git
* Google Chrome

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fphilippgrabher%2Fcountchocula%2Fmaster%2Fazure-deploy-basic.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>


## AI-Lab RStudio VM
**This deployment will provision an isolated VM with the following software:**
* Windows 10 Pro
* Python 3.8
* RStudio (latest)
* Git
* Google Chrome

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmladblum%2Fcountchocula%2Fmaster%2Fazure-deploy-rstudio.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>


## AI-Lab Special VM
**This deployment will provision an isolated VM with the following software:**
* Something special

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmladblum%2Fcountchocula%2Fmaster%2Fazure-deploy-special.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>



# Source of Idea and Inspiration

Find more information on how to use this deployment <a href=https://buildazure.com/2018/04/17/using-chocolatey-with-azure-vms/>here</a>.
