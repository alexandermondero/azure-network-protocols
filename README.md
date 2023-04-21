<p align="center">
<img src="https://www.vectorlogo.zone/logos/microsoft_azure/microsoft_azure-ar21.png" alt="Microsoft Azure logo"/>
</p>

<h1>Network Security Groups and Inspecting Network Protocols</h1>
This tutorial explains how to view and change network traffic through the Network Security Group in Microsoft Azure. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10</b>
- macOS (Able to connect to Windows 10 and Virtual Machines via Microsoft Remote Desktop)

<h2>List of Steps</h2>

- Create 2 virtual machines in Microsoft Azure. Virtual machine 1 was running Windows 10 and virtual machine 2 was running Ubuntu/Linux
- Downloaded Wireshark to observe network traffic.
- In Microsoft Azure added new inbound security rules in a network security group to deny all incoming ICMP traffic.
- Viewed all ICMP traffic through virtual machine 1 in Wireshark.
- Gained access to virtual machine 2's command line. This will allow SSH network traffic to be viewed.

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/Tq2muG2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Through Microsoft Azure, 2 virtual machines were created. Connections to the virtual machines were accessed by Microsoft Remote Desktop.
</p>
<br />

<p>
<img src="https://i.imgur.com/0wwSVfF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here you can view and add inbound security rules. This allows you to view if traffic is allowed or denied throughout the network. You can also allow or deny different network protocols.
</p>
<br />

<p>
<img src="https://i.imgur.com/Xe9TajW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Accessed the command line of virtual machine 2 running Linux through powershell. By doing this, this will allow me to view SSH traffic.
</p>
<br />

<p>
<img src="https://i.imgur.com/DMpFUR0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Viewed SSH traffic via Wireshark.
</p>
<br />
