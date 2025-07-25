<p align="center">
<img src="https://www.ufsexplorer.com/amp/img/articles/vmdo/virtual-machine-basics.jpg"alt="osTicket logo"/>
</p>

<h1>Virtual Machine Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of a Virtual Machine.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Azure Account 
- Region Selection
- Resource Group
- Virtual Network
- VM Image
- VM Size
- Authentication Method
- Storage Type
- Public IP Address(Optinal)
- Inbound Port Rules

<h2>Installation Steps</h2>

<p>
<img src="https://github.com/Justin-Colon/microsoft-azure/blob/025cf374a8347de9f804e48843783efd72fa6cf6/Virtual%20Machine%20Tutorial/VM%201%20.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The home page of microsoft azure is where the magic happens. This is where you can create anything based off your needs like storage accounts, resource groups, vm's, etc. 
</p>
<br />

<p>
<img src="https://github.com/Justin-Colon/microsoft-azure/blob/b5ccb449bfeaf876da00d9a49b12847d6a9dac4a/Virtual%20Machine%20Tutorial/VM%202.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the search bar at the top, type "Resource Groups" and click it.
</p>
<br />

<p>
<img src="https://github.com/Justin-Colon/microsoft-azure/blob/0753a8d8c22e5c46187a1833b127f44ea58a2c8a/Virtual%20Machine%20Tutorial/vm%203%20.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click “+ Create” and the reason why we are creating a resource group is just to have a folder for our project which in this case is out VM.
</p>
<br />

<p>
<img src="https://github.com/Justin-Colon/microsoft-azure/blob/849594f033d2cb6873d16afe66a5447c689a9676/Virtual%20Machine%20Tutorial/vm%204.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configuring the basics then selecting review + create once complete.
</p>
<br />

<p>
<img src="https://github.com/Justin-Colon/microsoft-azure/blob/4a0d9aa58f22c4771b1455e066e66ae8b3ab9a98/Virtual%20Machine%20Tutorial/vm5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that we have created our resource group, let's create our vm that will be stored inside of our resource group.
</p>
<br />

<p>
<img src="https://github.com/Justin-Colon/microsoft-azure/blob/0d174a1831e11e311b7c104288acea175c5469cd/Virtual%20Machine%20Tutorial/vm6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Back to configuring the basics for our vm installation. There are a lot of settings we can change depending on what we want but in this case I have selected windows 10, created a name for my vm, selected the appropriate region and made sure I was using the correct port which is RDP (3389).Azure will auto-select a disk type (Standard SSD or HDD).Networking options will also default (you can customize later).
</p>
<br />

<p>
<img src="https://github.com/Justin-Colon/microsoft-azure/blob/0d174a1831e11e311b7c104288acea175c5469cd/Virtual%20Machine%20Tutorial/vm6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
tomize later).
</p>
<br />


