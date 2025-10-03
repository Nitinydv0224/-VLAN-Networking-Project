🧠 Project 6 — Dynamic IP Allocation and Inter-VLAN Communication using DHCP and Router-on-a-Stick

📘 Overview

This project demonstrates how to configure automatic IP address allocation using DHCP (Dynamic Host Configuration Protocol) and enable inter-VLAN communication through a Router-on-a-Stick configuration.

Each VLAN represents a department in a company, and all IP addresses are assigned automatically by the router, which also handles communication between VLANs.

🎯 Project Objective

Create multiple VLANs (e.g., VLAN 10 for Sales, VLAN 20 for HR).

Assign switch ports to VLANs.

Configure trunking between the switch and router.

Configure router sub-interfaces for VLANs (Router-on-a-Stick).

Configure DHCP pools on the router for automatic IP assignment.

Verify connectivity and inter-VLAN communication.

🌟 Results

✅ Each VLAN receives IP addresses automatically via DHCP.
✅ Router enables communication between VLANs using sub-interfaces.
✅ Network setup mimics real enterprise configuration.

💡 Advantages

No Manual IP Configuration Needed — DHCP automatically assigns IPs.

Easy Network Expansion — Adding new devices requires no manual setup.

Centralized Management — Router handles both IP assignment and routing.

Efficient Communication — Different VLANs can communicate securely.

Realistic Enterprise Design — Commonly used in medium and large organizations.
