
# Extended ACL Lab

## Overview

This lab focuses on configuring and applying Extended Access Control Lists (ACLs) on Cisco routers. Extended ACLs were used to control traffic based on source IP, destination IP, protocol, and port numbers.

## Objectives

- Configure Extended ACLs on R1
- Configure numbered and named ACLs
- Control traffic between networks
- Block specific protocols and ports
- Apply ACLs to router interfaces
- Verify ACL configurations and traffic restrictions

## ACL Configuration

### R1 Extended ACL 100

- Blocks DNS traffic from 172.16.1.0/24 to SRV1
- Allows other IP traffic

### R1 Extended ACL 101

- Blocks traffic from 172.16.2.0/24 to PC1
- Blocks HTTP traffic to SRV2
- Blocks HTTPS traffic to SRV2
- Allows other IP traffic

## Verification

The ACLs were verified using:

```cisco
show access-lists
show ip access-lists
show running-config
