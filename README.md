# Fortinet Enterprise Network Security Capstone

This project was developed as part of the NTI Cybersecurity Training Program.

## Project Overview
The project simulates a multi-site enterprise network consisting of:

- Headquarters (HQ)
- Branch 1
- Branch 2
- Remote Users

The environment was built using FortiGate, Cisco networking devices, and PNETLab.

## Technologies Used

- FortiGate Firewall
- Cisco Switching & Routing
- VLANs
- EtherChannel
- OSPF
- IPsec VPN
- NAT
- High Availability (HA)
- Antivirus
- Web Filtering
- IPS
- Application Control
- SSL Inspection
- Active Directory
- Syslog
- PNETLab

## Main Features

- Network segmentation using VLANs
- Inter-VLAN routing
- DHCP for user networks
- OSPF dynamic routing
- Site-to-Site IPsec VPN
- OSPF over IPsec tunnels
- HQ to Branch connectivity
- Branch-to-Branch communication through HQ
- Internet access using NAT
- FortiGate Active-Passive HA
- Firewall security policies
- UTM Security Profiles
- DMZ implementation
- VIP / DNAT for Web Server publishing
- Active Directory and Syslog integration
- Network troubleshooting and traffic analysis

## High Availability

The HQ site uses two FortiGate firewalls configured in Active-Passive HA mode.

The configuration includes:

- Heartbeat communication
- Configuration synchronization
- Primary and Secondary roles
- Device priority
- Override
- Failover testing

## VPN Architecture

Two Site-to-Site IPsec VPN tunnels were implemented:

- HQ ↔ Branch 1
- HQ ↔ Branch 2

OSPF was configured over the IPsec tunnels to dynamically advertise internal networks.

## Security Profiles

FortiGate security profiles were implemented including:

- Antivirus
- Web Filtering
- IPS
- Application Control
- SSL Inspection

## Testing & Troubleshooting

The project was validated using:

- Ping
- Traceroute
- FortiGate Debug Flow
- Packet Sniffer
- Routing Tables
- IPsec Tunnel Monitoring
- Firewall Logs
- HA Failover Testing

## Tools

- FortiGate
- Cisco IOS
- PNETLab

## Training

This project was completed as part of the **National Telecommunication Institute (NTI) Cybersecurity Training Program**.
