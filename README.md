### tape0003

# Home Network

## Physical Topology
Optical signals travel from Valley Fibers Winkler network through underground fiber cables into my front yard, where the fiber cable connects to an Optical Network Termination (ONT) device. From here the optical signal travels over a fiber optic patch cable with an LC connector, into an OptiCore transceiver residing in the MikroTik routers 'SFP+' slot, where the optical signal is converted into an ethernet signal. From there the MikroTik router provides LAN connectivity via Wi-Fi or Ethernet. Devices may then connect to the network via Ethernet or Wi-Fi.



<img width="1408" height="768" alt="Physical Topology" src="https://github.com/user-attachments/assets/41095ea7-06b4-4659-b710-261dfd607830" />

## Logical Topology
Valley fiber 


<img width="1408" height="768" alt="Logical Topology" src="https://github.com/user-attachments/assets/bfc0d5d6-f04b-40e2-894c-51fe2cbe0372" />

## IP Addressing
#### Mikrotik Router
IPv4 Address . . . . . . . . . . . . . . . . . : 192.168.100.1

#### Nitro V16 Laptop
Hostname: goerge

Wireless LAN adapter Wi-Fi:

Description. . . . . . . . . . . . . . . . . . : Killer(R) Wi-Fi 6E AX1675i 160MHz Wireless Network Adapter (211NGW)  
DHCP Enabled . . . . . . . . . . . . . . . . . : Yes  
Autoconfiguration Enabled. . . . . . . . . . . : Yes  
Link-local IPv6 Address. . . . . . . . . . . . : fe80::634b:742a:a8a6:529f%9(Preferred)  
IPv4 Address . . . . . . . . . . . . . . . . . : 192.168.100.129(Preferred)  
Subnet Mask. . . . . . . . . . . . . . . . . . : 255.255.255.0  
Default Gateway . . . . .  . . . . . . . . . . : 192.168.100.1  
DHCP Server. . . . . . . . . . . . . . . . . . : 192.168.100.1  
DNS Servers. . . . . . . . . . . . . . . . . . : 192.168.100.1  

## Network Device Inventory

#### Micro-Tik router

Make: MikroTik  
Model: RB4011iGS+5HacQ2HnD-IN  

#### Nitro V16 Laptop
##### CPU  
Intel(R) Core(TM) i7-14650HX  
Base speed:	2.20 GHz  
Sockets:	1  
Cores:	16  
Logical processors:	24  
Virtualisation:	Enabled  
L1 cache:	1.4 MB  
L2 cache:	24.0 MB  
L3 cache:	30.0 MB  
Utilisation	4%  
Speed	3.91 GHz  
Up time	0:04:35:20  
Processes	357  
Threads	6196  
Handles	323138  

##### Memory  
32.0 GB DDR5  
Speed:	5600 MT/s  
Slots used:	2 of 4  
Form factor:	SODIMM  
Hardware reserved:	296 MB  
Available	17.8 GB  
Cached	15.3 GB  
Committed	19.6/33.7 GB  
Paged pool	817 MB  
Non-paged pool	1.2 GB  
In use (Compressed)	13.9 GB (1.1 GB)  

##### Disk 0 (C:)  
NVMe HFS001TEJ9X125N  
Capacity:	954 GB  
Formatted:	954 GB  
System disk:	Yes  
Page file:	Yes  
Type:	SSD  
Read speed	0 KB/s  
Write speed	32.7 KB/s  
Active time	0%  
Average response time	0.9 ms  

##### WiFi  
Killer(R) Wi-Fi 6E AX1675i 160MHz Wireless Network Adapter (211NGW)  
Adapter name:	Wi-Fi  
Connection type:	802.11ac  
IPv4 address:	192.168.100.129  
IPv6 address:	fe80::634b:742a:a8a6:529f%9  
Receive	8.0 Kbps  
Send	32.0 Kbps  

##### GPU 0  
NVIDIA GeForce RTX 4060 Laptop GPU  
Driver version:	32.0.16.1062  
Driver date:	2026-06-11  
DirectX version:	12 (FL 12.2)  
Physical location:	PCI bus 1, device 0, function 0  
Utilisation	11%  
Dedicated GPU memory	2.0/8.0 GB  
Shared GPU memory	0.1/15.9 GB  
GPU Memory	2.2/23.9 GB  

##### GPU 1  
Intel(R) UHD Graphics  
Driver version:	31.0.101.4502  
Driver date:	2023-06-15  
DirectX version:	12 (FL 12.1)  
Physical location:	PCI bus 0, device 2, function 0  
Utilisation	5%  
Dedicated GPU memory	2.1/8.0 GB  
Shared GPU memory	0.6/15.9 GB  
GPU Memory	0.6/15.9 GB  


## Servers and Network Services
Servers: N/A

## Relevant device configuration info
##### MikroTik Router:   
ISP default configuration for home network.  
Includes:
* Firewall protections.
* DHCP service.
* NAT service
  
## Method to store login credentials
* WPA2-Personal (WPA2-PSK) security protocol.  
* WPA2 Personal uses the IEEE 802.11i protocol.  
* Uses a single shared password and AES encryption.  

## Revision History

| Version | Date | Time | Name |
| --- | --- | --- | --- |
| 0.1 | 2026-07-25 | 16:45 | Jonathan |
| 0.5 | 2026-07-26 | 17:02 | Jonathan |
| N/A | N/A | N/A | N/A |


## References to any related materials


