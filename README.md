# ActiveDirectoryLab<h1>


<h2>Description</h2>
To deepen my understanding of Active Directory and Windows networking, I set up a home lab environment using Oracle VirtualBox. In this lab, I created a virtual network with multiple virtual machines, including a domain controller, member servers, and client machines.<br />
<br />
I installed Windows Server on the domain controller and configured it with Active Directory Domain Services (AD DS). This included setting up a domain, creating and managing user accounts, and configuring Group Policy settings. The member servers and client machines were joined to the domain, enabling me to simulate and test various network scenarios and administrative tasks.<br />
<br />
Through this hands-on experience, I gained practical knowledge in deploying and managing Active Directory environments, understanding domain structures, and configuring network services and security policies. This lab setup provided a solid foundation for further exploration of Windows networking concepts and Active Directory management.. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Oracle VirtualBox</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> 
- <b>Windows Server 2019</b>

<h2>walk-through:</h2>

<p align="center">
Diagram: <br/>
<img src="https://imgur.com/lFKJ6Ff.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Setting up Enternal NIC IPV4:  <br/>
<img src="https://imgur.com/M4xVb4d.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Install Active Directory Domain & Services AD DS: <br/>
<img src="https://imgur.com/WfSMQJA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Domain:  <br/>
<img src="https://imgur.com/ud2HdSh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Org unit to put admin account:  <br/>
<img src="https://imgur.com/JpGM74I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Make Domain admin account:  <br/>
<img src="https://imgur.com/F2oXMtN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Install RAS for Client1 (win10):  <br/>
<img src="https://imgur.com/pGrHURn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Config the NAT for Client1:  <br/>
<img src="https://imgur.com/pMn5Zee.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Install DHCP:  <br/>
<img src="https://imgur.com/tO6kaz0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create new scope for DHCP:  <br/>
<img src="https://imgur.com/IckU0EQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Scope created:  <br/>
<img src="https://imgur.com/lWvKCew.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
<br />
<br />
running a script on PowerShell to create 1k plus users:  <br/>
<img src=https://imgur.com/OT8pFZ2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Users being made by PowerShell script:  <br/>
<img src="https://imgur.com/QwPcKTe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create another VM this will be the client side:  <br/>
<img src="https://imgur.com/E50cyX9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
My account on client1 side you could login with any of the accounts made by the PowerShell script:  <br/>
<img src="https://imgur.com/5vSryPT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
