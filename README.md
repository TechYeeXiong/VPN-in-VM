<h1>VPN in Azure Virtual Machine - Installation</h1>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- ProtonVPN
- Whatismyipaddress.com

<h2>Operating Systems Used </h2>

- Windows 10</b>

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/Ld3GeSw.png" height="80%" width="80%" alt="Go to whatismyipaddress.com"/>
</p>
<p>
Allow the website to locate your area and write down your IP Address.
</p>
<br />

<p>
<img src="https://i.imgur.com/19vyGNQ.png" height="80%" width="80%" alt="Topology"/>
</p>
<p>
In this lab, we're going to create a Virtual Machine using Azure. Once the VM is created, we download the VPN and connect to a Japanese VPN server to see how it affects google and traffic.
</p>
<br />

<p>
<img src="https://i.imgur.com/vRvqXPH.png" height="80%" width="80%" alt="Create A Resource Group"/>
</p>
<p>
You need to keep the region the same for a resource group and virtual machine.
</p>
<br />

<p>
<img src="https://i.imgur.com/O91hmMz.png" height="80%" width="80%" alt="Create A Virtual Machine"/>
</p>
<p>
Choose Windows 10, RDP, and the same region as the resource group you created.
</p>
<br />

<p>
<img src="https://i.imgur.com/GDmTLhb.png" height="80%" width="80%" alt="Remote Desktop Connection"/>
</p>
<p>
Copy the public IP Adress onto the remote desktop connection.
</p>
<br />

<p>
<img src="https://i.imgur.com/LNeqMT0.jpg" height="80%" width="80%" alt="Download ProtonVPN into Windows"/>
</p>
<p>
Choose the windows download.
</p>
<br />

<p>
<img src="https://i.imgur.com/P8plfWA.jpg" height="80%" width="80%" alt="Connect To An Open Free VPN Server"/>
</p>
<p>
Connect to Japan.
</p>
<br />

<p>
<img src="https://i.imgur.com/lFkECUi.jpg" height="80%" width="80%" alt="Go onto whatismyipaddress.com"/>
</p>
<p>
The IP Address is now located in Tokyo.
</p>
<br />

<p>
<img src="https://i.imgur.com/tPGCmMt.jpg" height="80%" width="80%" alt="Go to google and observe the changes"/>
</p>
<p>
Since VPN is used in a Japan server; Google changed.
</p>
<br />

<p>
<img src="https://i.imgur.com/QGIXapN.jpg" height="80%" width="80%" alt="Look at Netflix's URL"/>
</p>
<p>
The ending of the URL is now "jp-en/".
</p>
<br />
