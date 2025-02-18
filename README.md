# Network-technology-simulation-

This project is a network simulation built using Cisco Packet Tracer as part of a Network
Technologies course. The objective was to design, configure, and test a network with multiple
subnets and key networking services such as routing, DHCP, DNS, VLAN, NAT, and servers (e.g.,
FTP, Email, HTTP).

Key Project Requirements:

- Minimum of two routers.
- Several different subnets.
- Network devices available in Cisco Packet Tracer.
- Network services like routing, DHCP, DNS, VLAN, NAT, and various servers.
  
Network Design Overview:
- Router 0 connected to Switch 0, which links to PC0, PC1, and a DHCP server.
- Router 1 connected to Switch 1, which links to PC2, PC3, and a DNS server.
- Router 0 and Router 1 linked via a serial connection.
- Static routing configured between subnets.
- DHCP server assigns IP addresses to Subnet 1.
- DNS server resolves domain names for Subnet 2.

Key Testing Outcomes:
- Ping tests verified connectivity across subnets.
- DHCP functionality confirmed automatic IP assignment.
- DNS server successfully resolved domain names.
- Routing table verification using 'show ip route'.

Challenges and Improvements:
- Serial connection issues between routers.
- Potential improvements: VLANs, NAT for internet access, backup DHCP server.


This project provided practical experience with network design, device configuration, and
troubleshooting in Cisco Packet Tracer
