# Lab 07 – Troubleshooting Static Routing

## Objective

Learn how to identify and resolve common static routing issues in a Cisco network using Packet Tracer.

## Tools Used

- Cisco Packet Tracer
- Cisco IOS CLI

## Devices Used

- 3 Cisco Routers
- PCs
- Ethernet Cables

## Concepts Covered

- Static Routing
- Routing Tables
- Default Gateway
- Interface Configuration
- Connectivity Testing
- Network Troubleshooting

## Commands Used

```text
show ip route
show ip interface brief
show running-config
show interfaces
ping
traceroute
```

## Problems Encountered

- Incorrect static route configuration.
- Wrong destination network or subnet mask.
- Interface was administratively down.
- Incorrect next-hop IP address.
- Missing route on one of the routers.

## Troubleshooting Steps

1. Verified interface status using `show ip interface brief`.
2. Checked IP addressing on all interfaces.
3. Reviewed the routing table using `show ip route`.
4. Verified static route configurations.
5. Corrected incorrect next-hop addresses.
6. Tested connectivity using `ping`.
7. Confirmed packet path using `traceroute`.

## Verification

- All router interfaces were up.
- Static routes appeared in the routing table.
- End devices successfully communicated across networks.
- Ping tests were successful.

## Skills Learned

- Reading routing tables.
- Troubleshooting static routes.
- Verifying interface status.
- Identifying routing misconfigurations.
- Using Cisco IOS troubleshooting commands.

## Outcome

Successfully identified and resolved static routing issues, restoring end-to-end network connectivity.

## Screenshots

- Network topology
- Routing table (`show ip route`)
- Interface status (`show ip interface brief`)
- Successful ping results

## Next Lab

Lab 08 – Dynamic Routing
