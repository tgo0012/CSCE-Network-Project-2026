#Device Configurations

## Project Title
Design and Simulation of a Virtual Enterprise Network Using Cisco Packet Tracer and Wireshark

## Overview
This folder contains the configuration files for the network devices used in the virtual enterprise network. These configurations allow the network to provide communication, automatic IP address assignment, and name resolution.

## Router Configuration
The router is configured to:
- Provide the default gateway (192.168.1.1)
- Route traffic between network devices
- Support DHCP services

## Switch Configuration
The switch connects all devices within the local area network (LAN) and forwards data between connected devices.

## DHCP Configuration
DHCP automatically assigns IP addresses to client devices using the following settings:

- Network: 192.168.1.0/24
- Default Gateway: 192.168.1.1
- DNS Server: 192.168.1.4

## DNS Configuration
The DNS server resolves hostnames to IP addresses so users can access devices using names instead of IP addresses.

## Configuration Files
This folder will contain:
- Router_Configuration.txt
- Switch_Configuration.txt
- DHCP_Configuration.txt
- DNS_Configuration.txt
