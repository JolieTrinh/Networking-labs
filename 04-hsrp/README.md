# Lab 4 – HSRP

## Objectives

- Configure HSRPv2
- Configure an HSRP virtual IP address
- Configure router priority
- Enable preemption
- Test gateway redundancy
- Verify HSRP failover

## Configuration

HSRP version 2 was configured between R1 and R2.

R1 was configured with a higher priority than the default value, while R2 was configured with a lower priority.

HSRP preemption was enabled.

The HSRP virtual IP address was configured as the default gateway for PC1 and PC2.

## Verification

Connectivity to 8.8.8.8 was tested from the PCs.

The ARP table was checked to determine the MAC address associated with the HSRP virtual IP.

R1 was then shut down to test gateway redundancy.

After R1 became unavailable, R2 took over as the active HSRP router.

R1 was then restarted and HSRP preemption was verified.

## Skills

- HSRP
- First Hop Redundancy Protocols
- Gateway redundancy
- HSRPv2
- Priority
- Preemption
- Failover testing