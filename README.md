# CCNA_Static_Routing_Lab
Static routing lab using Cisco Packet Tracer. Includes IP configuration, CLI commands, and screenshots for CCNA-level practice across three routers and two LANs.

# 🛰️ Static Routing Lab – CCNA Practice

This lab demonstrates a basic static routing setup across three routers, two LANs, and intermediate switches. It is designed to reinforce manual route configuration, IP addressing, and link testing rituals.

## 🧠 Objectives

- Configure IP addresses on routers and PCs
- Establish static routes between LAN 1 and LAN 2
- Shutdown unused switch interfaces for hygiene
- Verify end-to-end connectivity using ping tests

## 🗺️ Topology Overview
[PC1]──[Switch1]──[R1]──[R2]──[R3]──[Switch2]──[PC2]


- **LAN 1 Network:** `192.168.1.0/24`  
  - PC1: `192.168.1.1`  
  - R1 LAN Interface: `192.168.1.254`

- **R1–R2 Link:**  
  - R1: `192.168.12.1`  
  - R2: `192.168.12.2`

- **R2–R3 Link:**  
  - R2: `192.168.13.2`  
  - R3: `192.168.13.3`

- **LAN 2 Network:** `192.168.3.0/24`  
  - PC2: `192.168.3.1`  
  - R3 LAN Interface: `192.168.3.254`

## ⚙️ Configuration Summary

- IP addresses assigned to all router interfaces
- Static routes configured on R1, R2, and R3
- Unused switch ports administratively shut down
- Ping tests performed between PC1 and PC2

## 🔍 Observations

- Manual routing clarified packet flow logic across hops
- Shutdown of unused interfaces improved network hygiene
- Ping success confirmed correct route propagation
- Reinforced habit of verifying with `show ip route` and `show run`

## 📂 Files Included

- `Commands.txt`: Full CLI configuration steps
- Screenshots.txt : all configuration Screenshot attached
