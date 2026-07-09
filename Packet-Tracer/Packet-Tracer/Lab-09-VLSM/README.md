
# Lab 09 – Variable Length Subnet Mask (VLSM)

## Objective

Design and configure a network using Variable Length Subnet Masking (VLSM) to efficiently allocate IP addresses based on host requirements.

## Tools Used

- Cisco Packet Tracer
- Cisco IOS CLI

## Devices Used

- Cisco Routers
- Cisco Switches
- PCs

## Concepts Covered

- Variable Length Subnet Mask (VLSM)
- IPv4 Subnetting
- Network Address
- Broadcast Address
- Usable Host Addresses
- Routing
- IP Address Allocation

## Lab Activities

- Analyzed the network requirements.
- Calculated the required subnet sizes.
- Assigned appropriate subnet masks using VLSM.
- Configured IP addresses on routers and PCs.
- Configured routing between networks.
- Verified connectivity using ping.

## Sample VLSM Table

| Network | Required Hosts | Subnet Mask | CIDR |
|---------|---------------:|-------------|------|
| LAN 1 | 100 | 255.255.255.128 | /25 |
| LAN 2 | 50 | 255.255.255.192 | /26 |
| LAN 3 | 25 | 255.255.255.224 | /27 |
| WAN | 2 | 255.255.255.252 | /30 |

> Replace this table with the actual values from your lab.

## Commands Used

```text
show ip interface brief
show ip route
show running-config
ping
```

## Verification

- Verified all interfaces were configured correctly.
- Confirmed successful communication between networks.
- Verified routing tables.
- Tested end-to-end connectivity using ping.

## Skills Learned

- Designing VLSM addressing schemes.
- Allocating IP addresses efficiently.
- Configuring router interfaces.
- Verifying network connectivity.
- Troubleshooting IP addressing issues.

## Outcome

Successfully designed and implemented a VLSM addressing scheme that optimized IP address usage while maintaining full network connectivity.

## Screenshots

- Network topology
- VLSM calculation table
- Router configuration
- `show ip interface brief`
- Successful ping results

## Next Lab

Lab 10 – Dynamic Routing (RIP, OSPF, or EIGRP)
