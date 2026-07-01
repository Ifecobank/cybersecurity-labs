Lab 03 – Basic Device Security

## Objective
Configure basic security settings on a Cisco router or switch to protect unauthorized access.

## Tools Used
- Cisco Packet Tracer
- Cisco IOS CLI

## Security Configurations
- Set the hostname.
- Configure an encrypted enable password.
- Configure a console password.
- Configure a VTY (Telnet/SSH) password.
- Encrypt all plain-text passwords.
- Display a login banner.

## Sample Commands

text
enable
configure terminal

hostname R1

enable secret class

line console 0
password cisco
login
exit

line vty 0 4
password cisco
login
exit

service password-encryption

banner motd # Unauthorized access is prohibited! #

end
write memory


## Verification
- Verified that console login requires a password.
- Verified that VTY lines require a password.
- Confirmed passwords are encrypted in the running configuration.
- Confirmed the login banner is displayed.

## Skills Learned
- Securing Cisco devices with passwords.
- Encrypting passwords.
- Configuring login banners.
- Saving configurations.

## Outcome
Successfully applied basic security configurations to protect the Cisco device from unauthorized access.

## Next Lab
Lab 04 – Basic Router Configuration
