                                                         🌐 Multi-Switch VLAN Communication
📘 Project Overview

This project demonstrates how multiple switches can be connected together using VLANs (Virtual Local Area Networks) to logically divide a large network. Even though all devices are physically connected through 5 switches, VLANs separate the network into logical groups, improving security and management. A 

total of 5 switches and 30 PCs are used, divided into three VLANs (10, 20, 30). Each VLAN has 10 PCs, with 2 PCs connected to each switch.

🧠 Objective 

Configure VLANs on multiple switches. 

Establish trunk links for inter-switch communication. 

Verify that PCs in the same VLAN can communicate. 

Ensure that PCs in different VLANs cannot communicate.

🧩 Network Topology Devices Used:

5 × Cisco Switches (2960) 

30 × PCs (2 from each VLAN on every switch) 

Straight-through cables (PC to Switch) 

Trunk links between switches

🧰 Verification Commands

Purpose	Command

View VLANs	show vlan brief

Check trunk ports	show interfaces trunk

Ping test (same VLAN)	ping <IP>

✅ Same VLAN communication works

❌ Different VLAN communication blocked (no router used)

🌍 Real-Life Example

Such a setup is used in offices, colleges, and enterprises where different departments share the same switches but must remain isolated:

VLAN 10 → Sales Department

VLAN 20 → IT Department

VLAN 30 → Accounts Department

VLANs ensure secure communication within each department and reduce unnecessary broadcast traffic.

💡 Key Learnings

VLANs logically separate a network without extra hardware.

Trunk ports allow multiple VLANs to pass between switches.

Same VLAN = communication possible

Different VLAN = communication restricted (without a router)

🏁 Final Output

✅ Intra-VLAN communication successful across all 5 switches

❌ Inter-VLAN communication restricted

🌐 Network securely divided into 3 VLANs (Sales, Accounts, HR)
