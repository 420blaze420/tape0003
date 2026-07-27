### tape0003

# Home Network

## Physical Topology
Optical signals travel from Valley Fibers Winkler network through underground fiber cables into my front yard, where the fiber cable connects to an Optical Network Termination (ONT) device. Through the siding and inside, the optical signal travels over a fiber optic patch cable with an LC connector, connected an OptiCore transceiver residing in my MikroTik routers 'SFP+' slot, where the optical signal is converted into an ethernet signal. From there the MikroTik router provides local devices with connectivity via Wi-Fi or Ethernet. 
<img width="1080" height="658" alt="PhysicalTop" src="https://github.com/user-attachments/assets/80ca197f-4098-4ea8-a998-7bb2d3b72c56" />

## Logical Topology
Valley fiber Winkler sends optical signals over fiber cables to an ONT device in my network. From there, the signal is sent over fiber patch cable to my MikroTik router through an SFP+ OptiCore transceiver where the optical signal is converted to an ethernet signal. The MikroTik router provides LAN connectivity for all local devices via 5 GHz or 2.4 GHz Wi-Fi.
<img width="1080" height="658" alt="LogicalTop" src="https://github.com/user-attachments/assets/6e125146-fefe-4e00-95c9-0e9e88dd53b9" />


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

#### Optical Network Translation (ONT) Device
Make: N/A  
Model: N/A  

#### Micro-Tik router
Make: MikroTik  
Model: RB4011iGS+5HacQ2HnD-IN  
5 GHz Wi-Fi: 802.11 ac/n  
2.4 GHz Wi-Fi: 802.11 b/g/n  
#### Architecture 
ARM: 32bit  
CPU: AL21400  
CPU core count: 4    
CPU nominal frequency: auto (533 - 1900) MHz  
CPU Threads count: 4  
Switch chip model: RTL8367SB  
Dimensions: 228 x 120 x 30 mm  
RouterOS license: 5  
Operating System: RouterOS v7  
Size of RAM: 1 GB  
Storage size: 512 MB  
Storage type: NAND, MTBF  

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
##### Link to router product page
https://mikrotik.com/product/rb4011igs_5hacq2hnd_in


