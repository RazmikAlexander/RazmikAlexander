<h1>Hi, I'm Razmik, an <a href="https://www.linkedin.com/in/razmik-a-917237280">IT Professional

<h2>👨‍💻 Information Technology Projects:</h2>
  
  - [Configuring Active Directory within Azure VMs](https://github.com/RazmikAlexander/RazmikAlexander/configure-ad)
  - <p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2016
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- 1 Navigate to the Windows Server Manager.
- 2 Click Add Roles and Features.
    
<p>
<img src="https://i.imgur.com/2yE71SN.jpg" height="80%" width="80%" alt=<>
</p>
<p>
<li> 3 It will open Add Roles and Features, wizard. Click Next.</li>
<p>

<p>
<img src="https://i.imgur.com/YRWnXtl.jpg" height="80%" width="80%" alt=<>
</p>
<p>
<li>4 Select the server from the server pool and click Next.</li>
</p>
<img src="https://i.imgur.com/loqxzX2.jpg" height="80%" width="80%" alt=<>
<br />

<p>
<li> 5 Click the Checkbox to select Active Directory Domain Services.</li>
</p>  
<img src="https://i.imgur.com/IpcbfPO.jpg" height="80%" width="80%" alt=<>

</p>
<p>

<p>
<li> 6 On the popup Window, just click Add Features.</li>
</p>
<img src="https://i.imgur.com/i49BWn8.jpg" height="80%" width="80%" alt=<>

</p>
<p>

<p>
<li> 7 On the description window of Active Directory Domain Services, click Next.</li>
</p>
<img src="https://i.imgur.com/bJb2T5W.jpg" height="80%" width="80%" alt=<>
</p>
<p>

<p>
<li> 8 Click Install on the Confirmation window.</li>
</p>
<img src="https://i.imgur.com/6GichZd.jpg" height="80%" width="80%" alt=<>
</p>
<p>

<p>
<li> 9 Installation process begins.</li>
</p>
<img src="https://i.imgur.com/0bpMsSX.jpg" height="80%" width="80%" alt=<>
</p>
<p>

<p>
<li> 10 After installing AD DS Role, you can promote this Server to a Domain Controller.</li>
</p>
<img src="https://i.imgur.com/HlIrrJD.jpg" height="80%" width="80%" alt=<>
</p>
<p>

<p>
<li> 11 Select Add a new forest and give the Root domain name, ad.gpfs.net. Click Next.</li>
</p>
<img src="https://i.imgur.com/IJ119YS.jpg" height="80%" width="80%" alt=<>
</p>
<p>

<p>
<li> 12 Enter the Directory Services Restore Mode password.</li>
</p>
<img src="https://i.imgur.com/UcseLJ8.jpg" height="80%" width="80%" alt=<>
</p>
<p>

<p>
<li> 13 Ignore the warning message.</li>
</p>
<img src="https://i.imgur.com/duRkaBK.jpg" height="80%" width="80%" alt=<>
</p>
<p>

<p>
<li> 14 Use the default NetBIOS domain name and click Next.</li>
</p>
<img src="https://i.imgur.com/sRBiQKx.jpg" height="80%" width="80%" alt=<>
</p>
<p>

<p>
<li> 15 Use the default paths and click Next.</li>
</p>
<img src="https://i.imgur.com/tg0C71m.jpg" height="80%" width="80%" alt=<>
</p>
<p>

<p>
<li> 16 Review and click Next if no errors.</li>
</p>
<img src="https://i.imgur.com/F2GYCoU.jpg" height="80%" width="80%" alt=<>
</p>
<p>

<p>
<li> 17 Click Install and wait for the installation to finish.</li>
</p>
<img src="https://i.imgur.com/uvVrjgf.jpg" height="80%" width="80%" alt=<>
</p>
<p>
<li> 18 The Domain Controller is now set up.</li>
</p>







































