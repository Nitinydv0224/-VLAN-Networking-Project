🌐 Multi-Switch VLAN Communication
📘 Project Overview

This project demonstrates how multiple switches can be connected together using VLANs (Virtual Local Area Networks) to logically divide a large network.
Even though all devices are physically connected through 5 switches, VLANs separate the network into logical groups, improving security and management.

A total of 5 switches and 30 PCs are used, divided into three VLANs (10, 20, 30).
Each VLAN has 10 PCs, with 2 PCs connected to each switch.

🧠 Objective

Configure VLANs on multiple switches.

Establish trunk links for inter-switch communication.

Verify that PCs in the same VLAN can communicate.

Ensure that PCs in different VLANs cannot communicate.

🧩 Network Topology

Devices Used:

5 × Cisco Switches (2960)

30 × PCs (2 from each VLAN on every switch)

Straight-through cables (PC to Switch)

Trunk links between switches

VLAN Distribution:

VLAN ID	VLAN Name	PCs	Switches Used
10	Sales	10 PCs	All 5 Switches
20	Accounts	10 PCs	All 5 Switches
30	HR	10 PCs	All 5 Switches
