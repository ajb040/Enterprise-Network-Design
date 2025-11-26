# Multi-Site Enterprise Network Design

Enterprise network simulation with 2 sites, 3 VLANs, dynamic routing, and security controls.

## Features
- **Network Architecture:** 2 sites connected via serial WAN link
- **VLANs:** 3 VLANs with inter-VLAN routing (router-on-a-stick)
- **Routing:** OSPF dynamic routing between sites
- **Services:** DHCP server with centralized IP management
- **Security:** ACLs for traffic filtering, port security with sticky MAC addressing

## Technologies
- Cisco IOS routing and switching
- OSPF (Open Shortest Path First)
- 802.1Q VLAN trunking
- Access Control Lists (ACLs)
- Port security (sticky MAC, violation detection)

## How to Use
1. Open `.pkt` file in Cisco Packet Tracer
2. Explore router/switch configurations
3. Test connectivity between sites
4. Verify ACLs and security policies

## Network Topology
- **HQ:** Router with subinterfaces for VLANs 10 and 20
- **Branch:** Single VLAN (40) with local router
- **WAN:** Serial link with OSPF

## Skills Demonstrated
Network design, Cisco IOS configuration, routing protocols, VLANs, security controls

## Author
Andrew Bond | Bucknell University  
[LinkedIn](https://linkedin.com/in/andrewbond007) | [GitHub](https://github.com/ajb040)
