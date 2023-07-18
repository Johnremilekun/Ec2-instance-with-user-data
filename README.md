<p align="center">
<img width="757" alt="Screenshot 2023-07-17 at 9 36 21 PM" src="https://github.com/Johnremilekun/Ec2-instance-with-user-data/assets/30168186/0895cad3-8de5-43b6-a13a-d6b1657d29b7">

</p>

<h1>Create an EC2 Instance with EC2 User Data</h1>

This demonstration goes over how to observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups.

_<b>NOTE:</b> This demonstration uses materials created in the previous demonstration, ["Configuring On-premises Active Directory within Azure VMs"](https://github.com/JTYKolesar/configure-ad)._

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Setup 2 Virtual Machines within Azure:
  - Virtual Machine #1 (Windows 10)
  - Virtual Machine #2 (Linux Ubuntu) -- using same Resource Group and Vnet as VM1
- Use Remote Desktop (RDP) to VM1 and install Wireshark.
- Use Wireshark and PowerShell to Observe Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
  - Add new Inbound Rules to Deny/Allow ICMP protocol.
- Bonus: How to Display and Flush DNS.
