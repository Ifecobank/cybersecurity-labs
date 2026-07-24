# Lab 11 – Open Shortest Path First (OSPF)

## Objective

Configure and verify Open Shortest Path First (OSPF) routing to enable dynamic communication between multiple networks.

## Tools Used

- Cisco Packet Tracer
- Cisco IOS CLI

## Devices Used

- Cisco Routers
- Cisco Switches
- PCs

## Concepts Covered

- OSPF
- Dynamic Routing
- Router ID
- OSPF Areas
- Neighbor Adjacency
- Link-State Routing
- Routing Table
- Cost Metric

## Lab Activities

- Configured IPv4 addresses on router interfaces.
- Enabled OSPF routing.
- Advertised connected networks using OSPF.
- Configured a Router ID.
- Verified OSPF neighbor relationships.
- Verified routes learned through OSPF.
- Tested end-to-end connectivity using ping.

## Commands Used

text
router ospf 1
network 192.168.1.0 0.0.0.255 area 0
router-id 1.1.1.1

show ip ospf neighbor
show ip ospf interface
show ip protocols
show ip route
show ip interface brief
ping


## Verification

- Confirmed OSPF neighbor adjacency was established.
- Verified OSPF routes in the routing table.
- Successfully pinged devices on remote networks.
- Confirmed interfaces were operational.

## Skills Learned

- Configuring OSPF on Cisco routers.
- Advertising networks using OSPF.
- Verifying OSPF neighbor relationships.
- Understanding OSPF routing tables.
- Troubleshooting OSPF configuration issues.

## Outcome

Successfully configured OSPF routing, allowing routers to exchange routing information dynamically and enabling communication between multiple networks.

## Screenshots

- Network topology
- OSPF configuration
- show ip ospf neighbor
- show ip route
- Successful ping results


