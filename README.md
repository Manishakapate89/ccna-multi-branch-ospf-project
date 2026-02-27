# Multi-Branch Enterprise Network using OSPF

## 📌 Project Overview
This project demonstrates the design and implementation of a multi-branch enterprise network using OSPF dynamic routing protocol in Cisco Packet Tracer.

The topology consists of:
- Head Office (HO)
- Branch Office 1 (BO1)
- Branch Office 2 (BO2)

All branches are connected via WAN serial links and configured using OSPF for automatic route learning.

---

## 🛠 Technologies Used
- Cisco Packet Tracer
- OSPF (Open Shortest Path First)
- IP Addressing & Subnetting
- WAN Serial Configuration
- Routing Verification Commands

---

## 🌐 Network Topology
Refer to topology-diagram.png

---

## 🔧 Configuration Summary

### Head Office
- LAN: 192.168.1.0/24
- WAN: 10.0.0.0/30, 10.0.0.4/30

### Branch Office 1
- LAN: 192.168.2.0/24
- WAN: 10.0.0.0/30

### Branch Office 2
- LAN: 192.168.3.0/24
- WAN: 10.0.0.4/30

---

## ✅ Verification Commands
- show ip route
- show ip ospf neighbor
- ping test between branches

---

## 🎯 Learning Outcome
- Practical implementation of OSPF routing
- WAN configuration between routers
- Routing table analysis
- Troubleshooting connectivity issues

---

## 👩‍💻 Author
Manisha Kapate
