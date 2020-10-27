New-AzureVnetDynamicGateway
===========================

            

Connecting an Azure virtual network (VNet) to another Azure virtual network is very similar to connecting a virtual network to an on-premises site location. Both connectivity types use a virtual network gateway to provide a secure tunnel using IPsec/IKE.
 The VNets you connect can be in different subscriptions and different regions. You can even combine VNet to VNet communication with multi-site configurations. 


Microsoft Azure's native powershell cmdlets don't provide the functionality to create dynamic route gateways, since this concept was created later on, so using it's RestAPI, i've written this function to create Dynamic Route Gateways for a single or multiple
 Vnets


  *  Accepts pipeline input; 
  *  Accepts multiple values at a time 
  *  Does not verify if the VNet is properly configured, just sends the command. 

PS.: It can take up to an hour to create the gateway due to Azure's processing.


 


 


![Image](https://github.com/azureautomation/newazurevnetdynamicgateway/raw/master/2014-07-25-16_42_20-Windows-PowerShell-ISE.png)


 


 




 




 


 


 


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
