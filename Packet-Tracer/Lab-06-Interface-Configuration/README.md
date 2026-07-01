# Lab 06 – Interface Configuration

## Objective
Learn how to configure router and switch interfaces by assigning IP addresses, enabling interfaces, and verifying connectivity.

## Tools Used
- Cisco Packet Tracer
- Cisco IOS CLI

## Devices Used
- Cisco Router
- Cisco Switch
- PCs

## Concepts Covered
- Interface configuration
- IP address assignment
- Subnet mask configuration
- Enabling interfaces with no shutdown
- Interface verification

## Commands Practiced

text
enable
configure terminal
interface g0/0
ip address 192.168.1.1 255.255.255.0
no shutdown
exit
end
write memory


## Verification Commands

text
show ip interface brief
show running-config
ping


## Verification
- Configured the router interface with an IPv4 address.
- Enabled the interface using the no shutdown command.
- Verified the interface status using show ip interface brief.
- Successfully tested connectivity using the ping command.

## Skills Learned
- Configuring router interfaces.
- Assigning IPv4 addresses.
- Enabling disabled interfaces.
- Verifying interface status.
- Saving the device configuration.

## Outcome
Successfully configured and verified router interfaces, allowing devices on the network to communicate.

## Next Lab
Lab 07 – Static Routing (or the next topic in your course)
