# Lab 2 – VLANs & Router-on-a-Stick

## Objectives

- Configure access ports for different VLANs
- Configure a trunk between SW1 and SW2
- Configure a native VLAN
- Configure Router-on-a-Stick
- Configure router subinterfaces
- Verify connectivity between VLANs

## Configuration

PC-facing switch interfaces were configured as access ports in the appropriate VLANs.

The connection between SW1 and SW2 was configured as a trunk, allowing only the required VLANs.

An unused VLAN was configured as the native VLAN.

R1 was configured using Router-on-a-Stick with separate subinterfaces for the required VLANs.

## Verification

Connectivity was tested by sending ping requests between PCs in different VLANs.

## Skills

- VLANs
- Access ports
- Trunking
- Native VLAN
- 802.1Q
- Router-on-a-Stick
- Inter-VLAN routing