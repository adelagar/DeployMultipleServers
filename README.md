# Deploy Multiple Servers on Azure

### Deploy multiple servers within an existing Azure virtual network. Deploy Generation 1 or 2 virtual machines on selected SKU's. Solution options available are Windows Server 2022 Datacenter/Windows 2019 Datacenter/Windows 2016 Datacenter/Windows 2012 R2/Ubuntu 22.04-LTS/ Ubuntu 20.04-LTS/CentOS 7.9/Debian 11 /Debian 12/RedHat Enterprise Server 7.8/RedHat Enterprise Server 8.1. 
### Ubuntu 18.04-LTS has been removed since the OS has reached end of life by the vendor.
### The solution is intended for deploying either production or development workloads in Azure Commercial and Azure Government.
### Please note that at the end of the virtual machine name I am appending a "-" and the next ordinal number. Example Server-1, Server-2, etc. Hostnames should not exceed 15 characters.
### We are adding a route table, network security group, and availability set for the virtual machines that are being deployed. Please configure these objects as you see fit and associate with either the virtual network or virtual machine. You can also inherit both the existing route tables and network security groups that have already been preconfigured in your environment. The choice is yours.
### You will also have the ability to choose a data disk of various sizes with a total of 32 disks.
### We are providing the most popular server SKU's available. Please vaidate before using this solution accelerator that the region you are planning on deploying has the virtual machine SKU size. 
### Feel free to use this solution, edit, and add functionality as you see fit. This solution is being provided "as is" for the greater technical community with no guarantees. 
### Use the solution with the Azure portal Custom Template Deployment feature or most common pipeline tools.
### Please enjoy and would love to hear feedback to improve the solution! 

# Deployment Solution Below

### The following template deploys Azure virtual machines on an existing virtual network. The following prerequisite are required; the name of the virtual network Azure resource group, the name of the virtual network, and the name of the intended subnet. 

#### Microsoft Azure Commercial Click Here: ####
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fadelagar%2FDeployMultipleServers%2Fmain%2Fazuredeploy.json)

#### Microsoft Azure Government Click Here: ####

[![Deploy to Azure](https://aka.ms/deploytoazuregovbutton)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fadelagar%2FDeployMultipleServers%2Fmain%2Fazuredeploy.json)
