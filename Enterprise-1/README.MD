# Enterprise Multi-Site Network

## Overview

Enterprise-grade multi-site network architecture simulating a corporate environment with Data Center and branch segmentation (Gold, Silver, Bronze).

This project demonstrates:
- Dynamic routing with OSPF
- Site-to-site VPN (IPSec)
- SD-WAN failover strategy
- VLAN segmentation and access control
- NAT and firewall policies (FortiGate)
- High availability and redundancy across sites

## Network Topology

Full Topology:

![image alt]()

### Site Classification:

- Gold:

High-availability site with:
- Dual WAN (MPLS + Internet)
- SD-WAN enabled
- Full OSPF participation
- Redundant routing and failover

![image alt](https://github.com/GiovaniSerra/enterprise-network/blob/main/Enterprise-1/Topology/Gold%20site/Gold%20-%20topology.png)


- Silver:

![image alt](https://github.com/GiovaniSerra/enterprise-network/blob/main/Enterprise-1/Topology/Silver%20Site/Silver%20-%20topology.png)


- Silver+:

![image alt](https://github.com/GiovaniSerra/enterprise-network/blob/main/Enterprise-1/Topology/Silver%20Site/Silver%2B%20-%20Topology.png)


- Bronze:

![image alt](https://github.com/GiovaniSerra/enterprise-network/blob/main/Enterprise-1/Topology/Bronze%20Site/Bronze%20-%20Topology.png)


- DC:

![image alt]()


## Core Technologies

- Routing: OSPF (Area 0 design)
- VPN: IPSec Site-to-Site (AES256, SHA256)
- WAN: SD-WAN with dynamic failover
- Segmentation: VLAN + ACL
- NAT: PAT and policy-based NAT
- Security: FortiGate (Firewall + UTM)

## Key Features
- Redundancy and failover
- Multi-site routing
- Security segmentation

## Documentation

- [HLD – High Level Design](Enterprise-1/HLD/)
- [LLD – Low Level Design](Enterprise-1/LLD/)
- [Implementation Guide](Enterprise-1/Implementation/)

## Example Flows

- Routing:
![image alt]()

- NAT:
![image alt]()

- VPN:
![image alt]()

## Repository Structure

## Engineering Context

This project is based on real-world networking concepts applied in ISP/NOC environments, including:
- Multi-site architecture design
- High availability and failover strategies
- Network segmentation and security enforcement
- Monitoring and operational validation

The goal is to simulate a production-ready enterprise network.

## Troubleshooting

(Enterprise-1/Troubleshooting/)
