# Lab 3 – EtherChannel

## Objectives

- Configure Layer 2 EtherChannel using LACP
- Configure Layer 2 EtherChannel using PAgP
- Configure Layer 3 EtherChannel using static EtherChannel
- Configure routing between networks
- Configure EtherChannel load balancing

## Configuration

### LACP

A Layer 2 EtherChannel was configured between ASW1 and DSW1 using LACP.

The EtherChannel was configured as a trunk.

### PAgP

A Layer 2 EtherChannel was configured between ASW2 and DSW2 using PAgP.

The EtherChannel was configured as a trunk.

### Layer 3 EtherChannel

A Layer 3 EtherChannel was configured between DSW1 and DSW2 using a static EtherChannel.

Routes were then configured to allow the PCs to reach SRV1.

## Load Balancing

The default EtherChannel load-balancing method was checked on the switches.

The switches were then configured to use source and destination IP addresses for load balancing.

## Skills

- EtherChannel
- LACP
- PAgP
- Layer 2 EtherChannel
- Layer 3 EtherChannel
- Trunking
- Routing
- Load balancing