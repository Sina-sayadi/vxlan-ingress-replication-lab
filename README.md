# VXLAN Ingress Replication Lab

A complete **VXLAN Ingress Replication** laboratory (without multicast) built on Cisco devices.

### Features
- OSPF Area 0 in Underlay
- IP Unnumbered
- Ethernet Virtual Circuit (EVC)
- Bridge Domain Interface (BDI 10)
- VTEPs on Leaf switches
- L2/L3 VXLAN Overlay

### Topology

![VXLAN Ingress Replication Topology](DIAGRAMS/vxlan-design-ingress-replication.png)

### Implemented Technologies
- VXLAN with **Ingress Replication**
- OSPF Area 0 with IP Unnumbered
- EVC + BDI
- VTEP Configuration
- Spine-Leaf Architecture

### Devices
- **Spine-1** & **Spine-2**
- **Leaf-1**, **Leaf-2**, **Leaf-3** → VTEPs
- **vpc-1**, **vpc-2** , **vpc-3**

### How to Use
1. Load the configuration files from the `CONFIGS/` folder on each device.



---

**Made by Sina Sayadi**  
Network Engineering & SDN Lab
