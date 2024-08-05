<p align="center">
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

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/kQcCKj9.jpeg" height="80%" width="80%" alt="Active Directory Steps"/>
</p>
<h2>Video Demonstration</h2>

- ### [YouTube: Setup Virtual Machines in Azure for Active Directory Installation Part 1](https://youtu.be/krtXtMqDtdU?si=uARK5rHaAV8WtwLX)
<p>
In this video, I will set-up resources in Azure and create two virtual machines connected to the same domain. The first one will be the Domain Controller (DC-1) on Windows Server 2022 and the second will be the client machine (Client-1) on Windows 10. 

</p>
<br />

<p>
<img src="https://i.imgur.com/E7F3RAp.jpeg" height="80%" width="80%" alt="Remote Desktop"/>
</p>
<h2>Video Demonstration</h2>

- ### [YouTube: Active Directory: Setup Remote Desktop and Non-Admin Users (Azure) - Part 2](https://youtu.be/i9fMNXR6lhQ?si=CHsIfgCcjIH7MvBk)
<p>
In part two of the "Watch Me Work" videos I will ensure connectivity between the client and Domain Controller using remote desktop, in the Domain Controller I will enable ICMPv4 traffic  on the local Windows Firewall. 
</p>
<br />

<p>
<img src="https://i.imgur.com/AEu84WS.jpeg" height="80%" width="80%" alt="DNS"/>
</p>
<h2>Video Demonstration</h2>

- ### [YouTube: Active Directory: Understanding DNS (Domain Name Systems) Part 3](https://youtu.be/Yw1dAaKV7E4?si=hhT441mat48hAxBS)
<p>
<p>
In video 3 I will use an Administrator account and try to ping the mainframe, this will cause an automatic failure and I will have to create a DNS record that connects to the Domain Controllers private IP address for proper connection. Then I will create a CNAME record pointing to a selected popular domain online.  
</p>

<p>
<img src="https://i.imgur.com/cYNOQTo.jpeg" height="80%" width="80%" alt="DNS"/>
</p>
<h2>Video Demonstration</h2>

- ### [YouTube: Active Directory: Networking, FileShare, Adding Permissions - Part 4](https://youtu.be/NP_XPORxqLw?si=o9jcBeti09yAV7QP)
<p>
In video 4 I will create some sample folders, add permissions, and attempt to access files in the folders as a user and admin. Lastly, I will create a security group, add a random user and show the results of that user accessing the file with and without the proper permissions.  
</p>
<br />

