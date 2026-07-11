# Therapy Clinic Network Project

This repository contains files, configurations, and documentation for a LAN network designed for a therapy clinic. This project will be using concepts like routing, switching, DNS, IP address, and connectivity. 

| Device | Interface | IP address | Subnet | Gateway |
| ------ | --------- | ---------- | ------ | ------- |
| Router | g0/0 | 192.168.10.1 | 255.255.255.0 | none |
| Staff PC | Fa0 | 192.168.10.20 | 255.255.255.0 | 192.168.10.1 |
| Server | Fa0 | 192.168.10.10 | 255.255.255.0 | 192.168.10.1 |

**Contents**
- Network Topology
- Router, Switch, and Server Configurations
- DNS 
- Ping/Connectivity Tests
- Project Progress Report
- Screenshots and Video Footage 


**Devices Used**
- CISCO 2911 Router
- CISCO 2960 Switch
- Staff PC
- Packet Tracer Server


**Services**
- Static Routing
- DNS (clinic.local -> 192.168.10.10)
- Internal Hostname 
- LAN Connectivity

# Configuration Summary

**Router Configuraton**
- Configured LAN interface (g0/0)
- Assigned IP: 192.168.10.1
- Enabled interface with no shutdown

**Switch Configuration**
- Default configuration
- Ports enabled

**Server Configuration**
- Static IP: 192.168.10.10
- DNS Name: clinic.local
- DNS IP Address: 192.168.10.10

**PC Configuration**
- Static IP: 192.168.10.20
- Gateway: 192.168.10.1
- DNS Server: 192.168.10.10

# Protocol Demo

**DNS**
- clinic.local server ip address
- DNS enabled

**ICMP**
Ping Tests:
-  PC -> Router
-  PC -> Server
-  PC -> clinic.local

# Connectivity
Screenshot include:
- ping to router
- ping to server
- DNS
- Interface
- Device IP configuration

# Author
**Tanya Garza Saenz**
CSCE 3530 - Therapy Clinic Network Project
