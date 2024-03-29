 <img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://youtu.be/7Dun2KSSTco)

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

- Step 1: Create a Windows 10 Virtual Machine
- Step 2: Create a Linux Ubuntu Virtual Machine
- Step 3: Install Wireshark in Windows 10 VM
- Step 4: Filter for ICMP traffic in Wireshark
- Step 5: Attempt to ping Ubuntu VM from Windows VM
- Step 6: Initiate a perpetual ping from Windows 10 VM to Ubuntu VM
- Step 7: Observe SSH traffic in Wireshark
- Step 8: Observe DHCP traffic in Wireshark
- Step 9: Observe DNS traffic in Wireshark
- Step 10: Observe RDP traffic in Wireshark

<h2>Actions and Observations</h2>

<p>

  <img width="1021" alt="Screenshot 2023-11-29 at 9 05 27 PM" src="https://github.com/reginacuenta/wireshark-lab/assets/150301999/3296aa36-5d4f-4eba-9252-d3db57b95e5a">

</p>
<p>
Create a Windows 10 virtual machine.
</p>
<br />

<p>
<img width="1021" alt="Screenshot 2023-11-29 at 9 05 27 PM" src="https://github.com/reginacuenta/wireshark-lab/assets/150301999/76e1a1bb-9da2-48d8-8e7e-4b78519af775">
  
</p>
<p>
Create a Linux virtual machine.
</p>
<br />

<p>
<img width="1066" alt="Screenshot 2023-11-29 at 9 27 13 PM" src="https://github.com/reginacuenta/wireshark-lab/assets/150301999/777a71c8-6983-49b2-acc7-544c535e5478">

</p>
<p>
Install Wireshark in Windows 10 virtual machine.
</p>
<br />

<p>
  <img width="1270" alt="Screenshot 2023-11-29 at 9 28 08 PM" src="https://github.com/reginacuenta/wireshark-lab/assets/150301999/ee1d6a67-900f-47d4-bdd8-a74bc5bbfc9f">

</p>
<p>
Observe ICMP traffic.
</p>
<br />

<p>
<img width="1123" alt="Screenshot 2023-11-29 at 9 43 44 PM" src="https://github.com/reginacuenta/wireshark-lab/assets/150301999/3332d982-e694-4409-855e-c1bdf7121aad">

</p>
<p>
Initiate a perpetual ping from Windows 10 VM to Ubuntu VM.
</p>
<br />

</p>
<p>
<img width="1192" alt="Screenshot 2023-11-29 at 9 56 48 PM" src="https://github.com/reginacuenta/wireshark-lab/assets/150301999/72c53171-4b06-416d-bb3e-86ff0b9f82e1">

</p>
<br />

</p>
<p>
Observe SSH traffic.
</p>
<br />

</p>
<p>
 <img width="1246" alt="Screenshot 2023-11-29 at 10 03 04 PM" src="https://github.com/reginacuenta/wireshark-lab/assets/150301999/9fe0259f-7b6a-4f93-abea-b2f9a23c6a95">

</p>
<br />

</p>
<p>
Observe DHCP traffic.
</p>
<br />

</p>
<p>
<img width="1252" alt="Screenshot 2023-11-29 at 10 10 18 PM" src="https://github.com/reginacuenta/wireshark-lab/assets/150301999/74f5d961-0cc7-4254-987d-a85d7cac1053">

</p>
<br />

</p>
<p>
Observe DNS traffic.
</p>
<br />

</p>
<p>
<img width="1224" alt="Screenshot 2023-11-29 at 10 14 09 PM" src="https://github.com/reginacuenta/wireshark-lab/assets/150301999/3d2bfb2a-73a0-4081-b3ef-b084995e58a3">

</p>
<br />

</p>
<p>
Observe RDP traffic.
</p>
<br />


