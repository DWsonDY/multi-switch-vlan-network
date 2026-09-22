# Multi-Switch VLAN Network with Inter-VLAN Routing

## Overview

This project demonstrates the implementation of VLAN segmentation across multiple switches and Inter-VLAN communication using router-on-a-stick routing in Cisco Packet Tracer.

## Objectives

- Create multiple VLANs
- Configure trunk links between switches
- Implement Inter-VLAN routing
- Verify connectivity using ping and traceroute

  ## Used Methods(Technologies)

  - Cisco Packet Tracer
  - VLANs
  - 802.1Q (dot1q) Trunking
  - ROAS(Router-on-a-stick)
  - IPv4 Addressing
 
    ## Network Topology

    diagrams/network-topology.png

    ## Vlan Configuration

    | VLAN | Department | Network |
|--------|------------|----------|
| 30 | Admin | 192.168.5.60/27 |
| 40 | HR | 192.168.5.0/26 |
| 50 | Students | 172.13.5.0/25 |
| 60 | Lab | 172.13.5.128/26 |

## Features

- Multi-switch VLAN deployment
- Trunk-port configuration
- Inter-VLAN routing
- End-to-end connectivity testing

  ## Verification

### VLAN Table
 
```bash
show vlan brief
```
 
### Trunk Status
 
```bash
show interfaces trunk
```
 
### Routing Verification
 
```bash
show ip route
```
 
### Connectivity Test
 
Successful pings were achieved between hosts in different VLANs through Inter-VLAN routing.
 
## Author
 
Ivaldo Gilson Jorge Chilundo  
