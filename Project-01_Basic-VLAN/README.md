# Project 01 – Basic VLAN Configuration

## Description
This project demonstrates how to create and configure VLANs on a single Cisco 2960 switch.  
We divide the network into separate VLANs to isolate devices logically. 
PCs in the **same VLAN** can communicate and ping each other successfully, while PCs in **different VLANs** cannot ping each other. This illustrates the concepts of **network segmentation** and **VLAN isolation**.

## Tools and Devices Used
- **Switch:** Cisco 2960
- **PCs:** 8
- **VLANs:** 10, 20, 30, 40

## VLAN Assignment to PCs
| VLAN | PCs Assigned |
|------|--------------|
| 10   | PC1, PC2     |
| 20   | PC3, PC4     |
| 30   | PC5, PC6     |
| 40   | PC7, PC8     |

## Steps Performed
1. Created VLANs 10, 20, 30, and 40 on the switch.
2. Assigned switch ports to the appropriate VLANs.
3. Verified VLAN configuration using:
   ```bash
   show vlan brief

