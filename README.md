<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Created 2 Virtual Machines in Microsoft Azure
- Logged into Domain Controller Virtual Machine using Remote Desktop
- Used Powershell to generate 1000 user accounts
- Used Active Directory to access the user accounts to reset passwords

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/ESzwsTh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This image shows 2 separate virtual machines created in Azure that will be used on a Remote Desktop for Active Directory. VM Client-1 is running on Windows 10 (21H2). VM DC-1 is running on Windows Server 2022. 
</p>
<br />

<p>
<img src="https://i.imgur.com/n9LchPJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this step, once I logged in to the DC-1 virtual machince through remote desktop, I used Windows Powershell to generate 1000 user accounts that will display in Active Directory. 
</p>
<br />

<p>
<img src="https://i.imgur.com/dNOoRmO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After Windows Powershell generated the user accounts, all 1000 user accounts were now accessable on Active Directory under mydomain.com in the employees folder.
</p>
<br />

<p>
<img src="https://i.imgur.com/VPAeYqo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Used Active Directory to reset employee Password.
</p>
<br />
