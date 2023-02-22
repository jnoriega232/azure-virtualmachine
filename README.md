<p align="center">
<img src="https://i.imgur.com/HxuGgvE.png" height="40%" width="60%" alt="Microsoft Azure Logo"/>
</p>

<h1>Azure Virtual Machines</h1>
Azure Virtual Machines give you the adjustability of virtualization without having to buy and retain the physical hardware that powers it. Although, it is still required to preserve the virtual machine by performing tasks to the same degree of configuring, patching, and installing the software that runs on it.

<h2>Requirements</h2>

- Computer with Internet Connection
- Microsoft Azure Account

<h2>Configuration Steps</h2>


<h3>Step 1: Sign in to Microsoft Azure</h3>

- Sign in to the Azure portal at https://portal.azure.com


<p align="center">
<img src="https://i.imgur.com/yi5UdJk.png" height="70%" width="70%" alt="Azure Free Account"/> 
</p>


<h3>Step 2: Create a Resource Group</h3>

- Go to the search bar at the top and enter "resource group"
- Select create resource group
- You will then need to name the resource group and select the region 
- Select Review + create > Create
    - For example, I will use RG-Lab-01 for the name and (US) West 3 for the region

<p align="center">
<img src="https://i.imgur.com/B8QT86V.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/f4CA1lx.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>


<h3>Step 3: Create a Storage Account</h3>

- Go to the search bar and enter "storage account"
- Select Create storage account
- You will need to select the resource group, the region, and create a name for the storage account
    - For example, I will name my storage account alexlab01
    - Use the same resource group and region as step 2
- Select Review > Create.

<p align="center">
<img src="https://i.imgur.com/N1Xt9HF.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/6nA7ORX.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>


<h3>Step 4: Create a Virtual Machine</h3>
     
- Go to search bar and enter "virtual machine"
- Select Create > Azure virtual machine

<p align="center">
<img src="https://i.imgur.com/Rl1K6HM.png" height="70%" width="70%" alt="Azure Free Account"/> 
</p>
 
- You will need to select the resource group, the region, and create a name for the virtual machine
    - For example, I will name my virtual machine vm-lab
    - Use same resource group and region as step 2/3
- Then select the image and size
    - For image, I will use Windows 10 Pro
    - For size, I will use 4 vCPUs
- Then make a username and password
    - For username, I will use labuser
    - Create your own password
- Check the box under licensing and finally select Review + Create > Create  
 
<p align="center">
<img src="https://i.imgur.com/vMM6rUI.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/h0lc8Pw.png" height="70%" width="70%" alt="Azure Free Account"/> 
</p>


<h3>Step 5: Connect to Virtual Machine</h3>

- First you will need to find the Public IP address of your virtual machine
   - Select the virtual machhine we just created and the IP address will be on the right hand side 
   - Copy the IP address

<p align="center">
<img src="https://i.imgur.com/nLdybGH.png" height="80%" width="80%" alt="Azure Free Account"/>

* Windows Users (I am using Windows)
     - Open and use Remote Desktop Connection
     - Paste IP Address and select Connect
     - Enter username and password from step 4
     - Select OK
  
* Mac Users 
   - Download Microsoft Remote Desktop
   - Open application and click add PC
   - Paste IP address and select Add
   - Double click on the virtual machine and enter username and password from step 4
   - Select continue     
     
 <p align="center">
<img src="https://i.imgur.com/k7q1tpE.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/XSs0kll.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>


🎉Congratulations! You have created your first virtual machine within Azure!🎉

<p align="center">
<img src="https://i.imgur.com/rEBpL8Y.png" height="80%" width="80%" alt="Azure Free Account"/>

<h3>Tip</h3>

-  If you want to save your free $200 credits, make sure you delete ALL resource groups after finishing!    
  
