# Lab 1 – VLSM & Static Routing

## Objectives

- Subnet a 192.168.5.0/24 network using VLSM
- Configure IP addresses on PCs and routers
- Configure a point-to-point connection between R1 and R2
- Configure static routes
- Verify end-to-end connectivity

## Network

The 192.168.5.0/24 network is divided into four subnets:

| LAN | Network |
|---|---|
| LAN 1 | 192.168.5.0/26 |
| LAN 2 | 192.168.5.64/26 |
| LAN 3 | 192.168.5.128/26 |
| LAN 4 | 192.168.5.192/26 |

The first usable IP address is assigned to each PC, while the last usable IP address is assigned to the router interface.

## Configuration

The routers were configured with static routes so that all PCs can communicate with each other.

## Verification

Connectivity was tested using `ping` between the PCs.

## Skills

- IPv4 subnetting
- VLSM
- IP addressing
- Static routing
- Connectivity testing
- Cisco IOS configuration