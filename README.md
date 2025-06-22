<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://youtu.be/80w5eUaG-vg)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDP, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Step 1: Observe ICMP traffic
- Step 2: Configuring a Firewall [Network Security Group]
- Step 3: Observe SSH traffic
- Step 4: Observe DHCP traffic
- Step 5: Observe DNS traffic
- Step 6: Observe RDP traffic

<h2>Actions and Observations</h2>

<p>
<img width="503" alt="Step 1  (a)" src="https://github.com/user-attachments/assets/a52e3317-e98e-46a0-b2d2-0ebce5722ec3" />
<img width="504" alt="Step 1  (b)" src="https://github.com/user-attachments/assets/d5fe9626-948d-4668-9bf9-4a69a26899ef" />
<img width="503" alt="Step 1  (b" src="https://github.com/user-attachments/assets/8021874e-b192-4213-9b8a-f493f28f1f4b" />

</p>
<p>
Step 1. Install Wireshark & observe ICMP traffic
</p>
<br />

<p>
<img width="503" alt="Step 2 (a)" src="https://github.com/user-attachments/assets/1523d417-59dc-4cd9-9827-91be2d8525df" />
<img width="502" alt="Step 2 (b)" src="https://github.com/user-attachments/assets/579681cf-3bb2-4330-8e0f-781bb498ef13" />
<img width="469" alt="Step 2 (c)" src="https://github.com/user-attachments/assets/04f07f83-5824-42bb-9383-b2de264d1e38" />
<img width="503" alt="Step 2 (d)" src="https://github.com/user-attachments/assets/b27cebfc-7e4a-4322-8ea6-55502b1f40f3" />
<img width="503" alt="Step 2 (e)" src="https://github.com/user-attachments/assets/14c027c7-f8cf-4720-b97d-b04e024f0a2f" />

</p>
<p>
Step 2: Configuring a Firewall
</p>
<br />

<p>
<img width="505" alt="Step 3  (a)" src="https://github.com/user-attachments/assets/2fd2b15a-34f2-4041-9ca0-865f5ec4d426" />

</p>
<p>
Step 3: Observe SSH traffic
</p>
<br />

<p>
<img width="505" alt="Step 4  (a)" src="https://github.com/user-attachments/assets/1bd6efee-ea67-4ded-8bcb-c4d2bee54987" />
<img width="503" alt="Step 4  (b)" src="https://github.com/user-attachments/assets/c70b64bc-dad7-4223-a2b4-056f0037a076" />

</p>
<p>
Step 4: Observe DHCP traffic
</p>
<br />

<p>
<img width="505" alt="Step 5  (a)" src="https://github.com/user-attachments/assets/99bae47c-431e-4a74-811d-5b98d16c8eb3" />
</p>
<p>
Step 5: Observe DNS traffic
</p>
<br />

<p>
<img width="503" alt="Step 6  (a)" src="https://github.com/user-attachments/assets/31234805-a32c-45d8-aa3b-102b0caa1259" />

</p>
<p>
Step 6: Observe RDP traffic
</p>
<br />
