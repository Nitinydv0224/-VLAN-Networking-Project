# -VLAN-Networking-Project

                                       ******** About VLAN ********
A VLAN (Virtual Local Area Network) is used to segment a physical network into multiple logical networks.
It reduces broadcast traffic, enhances security, and improves network efficiency.
In this repository, you’ll find step-by-step labs showing how VLANs are created, connected, and managed across multiple switches and routers.

                                       *****🏗️ Repository Structure *****
VLAN_Networking/
│
├── README.md                        → Main overview (this file)
│
├── Project-01_Basic-VLAN/           → Create and assign VLANs on one switch
├── Project-02_VLAN-Trunking/        → Connect multiple switches using trunk ports
├── Project-03_Inter-VLAN-Routing/   → Enable communication between VLANs using router
├── Project-04_VTP-Server-Client/    → Manage VLANs using VTP protocol
└── Project-05_VLAN-Troubleshooting/ → Identify and fix VLAN-related issues

                                       **💻 Tools & Devices Used**
| Category            | Details                                                                                |
| ------------------- | -------------------------------------------------------------------------------------- |
| **Simulation Tool** | Cisco Packet Tracer                                                                    | 
| **Devices**         | Cisco 2960 Switches, Cisco 2911 Router, PCs                                            |
| **Protocols**       | VLAN, Trunking (802.1Q), VTP, Inter-VLAN Routing                                       |
| **Commands Used**   | `vlan`, `switchport mode`, `encapsulation dot1Q`, `show vlan`, `show interfaces trunk` |
