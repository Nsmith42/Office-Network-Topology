Office Network Topology Documentation
Nicholas Smith

Router:
Router 1 – Cisco 2811 Router
-	4 Fast Ethernet interfaces
-	NM-2FE2W Module installed, giving extra 2 Fast Ethernet ports
-	Hostname R1
<img width="620" height="127" alt="image" src="https://github.com/user-attachments/assets/a66e8ef3-b344-404a-87fd-037c85f1d731" />

Switches:
Switch 1 – 2960-24TT Cisco Switch
  -	Connected to Server Room Network
  -	Network IP – 192.168.1.1
Switch 2 – 2960-24TT Cisco Switch
  -	Connected to Department 1 Network 
  -	Network IP – 192.168.2.1
Switch 3 – 2960-24TT Cisco Switch
  -	Connected to Department 2 Network 
  -	Network IP – 192.168.3.1
Switch 4 – 2960-24TT Cisco Switch
  -	Connected to Department 3 Network 
  -	Network IP – 192.168.4.1

Server:
File Server – 
 -	Connected to Switch 1
 -	Static IP – 192.168.1.100
 -	Subnet Mask - 255.255.255.0
 -	Default Gateway – 192.168.1.1

User Devices:
PC 1 -
  -	Connected to Switch 1
  -	Static IP – 192.168.2.2
  -	Subnet Mask - 255.255.255.0
  -	Default Gateway – 192.168.2.1 (Router interface IP)

PC 2 -
 -	Connected to Switch 1 
 -	Static IP – 192.168.2.3
 -	Subnet Mask - 255.255.255.0
 -	Default Gateway – 192.168.2.1 (Router interface IP)

PC 3 -
 -	Connected to Switch 2
 -	Static IP – 192.168.3.2
 -	Subnet Mask - 255.255.255.0
 -	Default Gateway – 192.168.3.1 (Router interface IP)

PC 4 -
 -	Connected to Switch 2
 -	Static IP – 192.168.3.3
 -	Subnet Mask - 255.255.255.0
 -	Default Gateway – 192.168.3.1 (Router interface IP)

PC 5 -
 -	Connected to Switch 4
 -	Static IP – 192.168.4.2
 -	Subnet Mask - 255.255.255.0
 -	Default Gateway – 192.168.4.1 (Router interface IP)

PC 6 -
 -	Connected to Switch 4
 -	Static IP – 192.168.4.3
 -	Subnet Mask - 255.255.255.0
 -	Default Gateway – 192.168.4.1 (Router interface IP)

Switch notes:
 -	24 ports
 -	PoE not supported
 -	1st ‘T’ in TT – UTP ports
 -	2nd ‘T’ – fixed 10/100/1000Base-T ports

<img width="975" height="717" alt="image" src="https://github.com/user-attachments/assets/64c659a9-4fe3-409d-8be9-756ed03299e2" />

 
