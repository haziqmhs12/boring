# Enterprise Multi-Site Campus Network Lab

A static portfolio site and lab documentation repository for a multi-site enterprise campus network simulated in GNS3. 

* **Live Portfolio Site:** [[https://github.io]](https://github.com/haziqmhs12/boring)
* **Author:** Haziq ([@haziqmhs12](https://github.com/haziqmhs12))

## 📋 Overview & Modules

The documentation is structured into an 8-part HTML/CSS module layout covering network design and verification:

1. **Overview & Topology (`index.html`)**: Architecture summary, topology goals, and physical/logical layout.
2. **IP Addressing (`part-2-addressing.html`)**: VLSM subnets, VLAN allocations, and loopback addressing.
3. **Layer 2 Switching (`part-3-layer2.html`)**: VLANs, 802.1Q trunks, LACP EtherChannel, and Rapid PVST+.
4. **Gateway Redundancy (`part-4-hsrp.html`)**: Active/standby gateway failover using HSRP.
5. **Dynamic Routing (`part-5-ospf.html`)**: Multi-site OSPF routing, adjacencies, and summarization.
6. **DHCP Services (`part-6-dhcp.html`)**: Centralized DHCP pools and `ip helper-address` configuration.
7. **Troubleshooting (`part-7-troubleshooting.html`)**: Fault isolation and CLI diagnostics.
8. **Project Roadmap (`part-8-roadmap.html`)**: Testing status and planned enhancements (ACLs, NAT, VPN).

---

## 🗂️ Repository Structure

```text
boring/
├── configs/                     # Cisco IOS startup/running configurations
├── images/                      # Network topology diagrams & CLI screenshots
├── index.html                   # Landing page & Part 1 overview
├── part-[2-8]-*.html            # Detailed breakdown modules (Part 2 to Part 8)
└── README.md                    # Project documentation
```

## 🛠️ Stack & Technologies

* **Simulation:** cisco packet tracer, GNS3 (current)
* **Protocols:** VLANs, 802.1Q, EtherChannel (LACP), Rapid-PVST+, HSRP, OSPFv2, DHCP / DHCP Relay


---

