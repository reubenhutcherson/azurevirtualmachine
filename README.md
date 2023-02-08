<p align="center">
<img src="https://i.imgur.com/4wqxHID.png" height="40%" width="60%" alt="Microsoft Azure Logo"/>
</p>

<h1>Microsoft Azure</h1>
Azure is Microsoft's public cloud platform. Azure offers a large collection of services, which includes platform as a service (PaaS), infrastructure as a service (IaaS), and managed database service capabilities.
A virtual machine is the virtualization/emulation of a computer system
This guide will demonstrate how to create an Azure account and create a virtual machine.


<h2>Requirements</h2>

- Computer with Internet Connection
- Credit Card (Required for free Azure credits)

<h2>Configuration Steps</h2>


<h3>Step 1: Create Azure Account</h3>


Create an Azure account [here](https://azure.microsoft.com/en-us/free/).
- Select Start Free
- Follow the prompt to create the account. 
     - You will need to put in your credit card information but you will get $200 worth of Azure credit and will have 30 days to use those credits. You will not be charged until then.
- Finish prompt, click Go to Azure Portal and you are ready to start with Azure!
     - You may also go to [portal.azure.com](https://www.portal.azure.com) to start


<p align="center">
<img src="https://i.imgur.com/rk4SD27.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/f1eRIx4.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>

<h3>Step 2: Create Virtual Machine</h3>
     
- Go to search bar and search "virtual machine"
- Select create, then select Azure virtual machine
- Next you will create a resource group (optional), the region, and create a name for the virtual machine
    - For the example we will name the virtual machine "VM1"
    You will then need to select image and size
    - For image we will use Windows 10 Pro

<p>
<img src="https://i.imgur.com/KxGWwcg.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 
  
    - For size, select see all sizes and select Standard E2s_v3
  <p>
<img src="https://i.imgur.com/Q7QT1U4.jpg"" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
* You will then need to make a username and password
    - For username, we will use labuser
    - Create your own password
* Click the box under licensing and finally click Review + Create 
  <img src="https://i.imgur.com/xGjktGj.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
                                                                                                    <p>
<img src="https://i.imgur.com/zrDdNua.jpg"" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
- Once your virtual machine has been reviewed and passed validation, click create.
 <p>
<img src="https://i.imgur.com/0VkI7VF.jpg"" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
   * Next wait for your virtual machine to be deployed.   
                                                                                                   <p>
<img src="https://i.imgur.com/WBAHpZe.jpg"" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Step 3: Connect to Virtual Machine</h3>

Now that your virtual machine is completed let's begin using it via remote desktop.
- Click on virtual machine resource.
- Copy Public IP Address
<p>
<img src="https://i.imgur.com/wnefevg.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/CuweaKM.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

* Mac Users 
   - Download Microsoft Remote Desktop
   - Open application and click add PC
   - Paste IP address and select Add
   - Double click on the virtual machine and enter username and password from step 4
   - Select continue
   
* Windows Users
     - Open and use Remote Desktop
     - Paste IP Address and select Connect
     - Enter username and password from step 4
     - Select OK

     
 <p align="center">
<img src="https://i.imgur.com/14pPOdv.png" height="70%" width="70%" alt="Azure Free Account"/> 
  <p>
<img src="https://i.imgur.com/vUdypE1.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Congratulations! You have created your first virtual machine within Azure!

<p align="center">
<img src="https://i.imgur.com/rEBpL8Y.png" height="80%" width="80%" alt="Azure Free Account"/>

<h3>Tip</h3>

-  If you want to save your free $200 credits, make sure you delete ALL resource groups after finishing!    
  
  
