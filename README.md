# VXLAN Ingress Replication Lab

A complete Cisco VXLAN fabric using Ingress Replication as the BUM traffic replication method, without relying on multicast. The underlay is built with OSPF Area 0 and IP Unnumbered.

### Features

- Layer 2 VXLAN Overlay
- Ingress Replication (Head-End Replication)
- OSPF Area 0 Underlay
- IP Unnumbered
- Ethernet Virtual Circuit (EVC)
- Bridge Domain Interface (BDI)
- Spine-Leaf Architecture
- VTEP Configuration

### Topology

![VXLAN Ingress Replication Topology](diagrams/vxlan-design-ingress-replication.png)

### Verification

- OSPF Neighbor Adjacency
- VXLAN Tunnel Establishment
- NVE Peer Verification
- End-to-End Host Connectivity
- MAC Learning Across VTEPs

### Devices
- **Spine-1** & **Spine-2**
- **Leaf-1**, **Leaf-2**, **Leaf-3** → VTEPs
- **vpc-1**, **vpc-2** , **vpc-3**

### How to Use
1. Load the configuration files from the `CONFIGS/` folder on each device.

### Why Ingress Replication?

This lab demonstrates VXLAN using Head-End (Ingress) Replication instead of multicast for BUM traffic forwarding. It is suitable for environments where multicast is unavailable or unnecessary.

---

## Author

**Sina Sayadi**

Network Engineer | Cisco | SDN | Network Automation
