# IP Configuration - Network Troubleshooting

## Objective
To inspect the IP configuration of a Windows 11 virtual machine.

## Environment
- Operating System: Windows 11
- Virtualization: VMware Workstation Pro 17.6
- Network Mode: NAT

## Commands Used

### 1. ipconfig
Displays the basic network configuration.

### 2. ipconfig /all
Displays detailed network information, including:
- DHCP Enabled
- IPv4 Address
- Subnet Mask
- Default Gateway
- DHCP Server
- DNS Server

## Lab Results

| Parameter | Result |
|---|---|
| IPv4 Address | 192.168.20.128 |
| Subnet Mask | 255.255.255.0 |
| Default Gateway | 192.168.20.2 |
| DHCP Server | 192.168.20.254 |
| DNS Server | 192.168.20.2 |

## What I Learned
- How to check IP configuration.
- How DHCP assigns IP addresses.
- How to identify the default gateway.
- How to identify DNS server information.

## Conclusion
The virtual machine successfully received an IP address from the DHCP server.
