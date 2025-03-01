# Deploying and Managing Virtual Machines in Azure Portal</h1>

<h2>Description</h2>
This project involves using Microsoft Azure to create and manage resource groups and virtual machines (VMs). The VM is configured with appropriate networking and security settings, allowing remote access via Remote Desktop Protocol (RDP). This demonstrates cloud infrastructure management, resource provisioning, and remote access setup.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Azure Portal</b> 
- <b>Remote Desktop Connection (RDP)</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Sign up for Azure and navigate to services subsection <br/>
<img src="https://i.imgur.com/hatCCP6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create a resource group with name and region  <br/>
<img src="https://i.imgur.com/I1dO4i3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Navigate back to Azure Services and create a VM, Use correspoding resource group name and region, Under image category select (Windows 10 Pro) You will need to make a user account information (ID and Password): <br/>
<img src="https://i.imgur.com/IW28MfB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Naviagte to the VM you created and under network settings find the IP address:  <br/>
<img src="https://i.imgur.com/6BsGRgu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Log in successfully using RDP with IP Address and corresponding USER information:  <br/>
<img src="https://i.imgur.com/YOzP4RG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
