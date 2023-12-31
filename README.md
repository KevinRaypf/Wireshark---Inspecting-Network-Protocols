# Wireshark---Inspecting-Network-Protocols-and Inspecting Traffic Between Azure Virtual Machines
In this project, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />
<p align="center">
<img width="398" alt="Screenshot 2023-11-10 113701" src="https://github.com/KevinRaypf/Wireshark---Inspecting-Network-Protocols/assets/143427903/5b8c3324-0e87-4377-b6aa-45e27d7b9799">
</p>

# -Wireshark-Network-Protocol-Analyzer
<img width="323" alt="hardware" src="https://github.com/KevinRaypf/Wireshark---Inspecting-Network-Protocols/assets/143427903/5c14e493-8a4c-4509-a8c1-7d6c67b6113c"> <img width="310" alt="Screenshot 2023-11-10 142531" src="https://github.com/KevinRaypf/Wireshark---Inspecting-Network-Protocols/assets/143427903/765d7ea9-8b7f-461c-9197-7810be17ae0a">
      


Allows you to see what is happening on your network in real time. Read <a href="https://1drv.ms/w/s!AhpxyIePAuQGgzONME_Cm_jET6w8?e=UvxASQ">About Wireshark


<p align="center">
<img width="301" alt="wireshark0" src="https://github.com/KevinRaypf/Wireshark---Inspecting-Network-Protocols/assets/143427903/585342de-553c-47df-8469-c84357cddb84">
<p/>
  
# -Network-Security-Groups-NSGs-and-Inspecting-Network-Protocols
<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>

<h2>Video Demonstration</h2>⬇️

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2> :art:Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- 🐿️Remote Desktop or Ssh protocol
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)
- Powershell

<h2>🌐Operating Systems Used </h2>
<img width="499" alt="windo" src="https://github.com/KevinRaypf/Wireshark---Inspecting-Network-Protocols/assets/143427903/3a60a7db-4493-41c5-b12e-eab7325cd23d">


- Windows 11 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Using Powershell to remote desktop into different system with Ssh protocol.
- Use icmp to determine web connection.
- (NSG)Adjust firewall to control traffic
- Obtain IP address (icmp)

<h2>Actions and Observations</h2>
<img width="952" alt="powershell2" src="https://github.com/KevinRaypf/Wireshark---Inspecting-Network-Protocols/assets/143427903/b1c1a410-c29a-4407-9bf9-7aedf25400a5">

Using Powershell to verify system is able to connect to an outside network.

<img width="952" alt="remote desktop" src="https://github.com/KevinRaypf/Wireshark---Inspecting-Network-Protocols/assets/143427903/d836682f-f6f4-433f-9b20-3e7d0e1f2b70">

Example of icmp protocol communicating from one IP address to another.

<img width="376" alt="powershell" src="https://github.com/KevinRaypf/Wireshark---Inspecting-Network-Protocols/assets/143427903/506d27c5-81e1-4c3f-a0b0-7fd5e7c109df">
Powershell is what open-source and cross platform.

<img width="921" alt="VMpic" src="https://github.com/KevinRaypf/Wireshark---Inspecting-Network-Protocols/assets/143427903/31a8ab26-a94e-4143-ab5a-4fa74ccc06a6">

Azure VM are used to control the traffic that is able to be seen by using Wireshark

<p>
</p>
<p>
</p>
<br />

<p>
</p>
<p>
</p>
<br />

</p>
<p>
</p>
<br />
