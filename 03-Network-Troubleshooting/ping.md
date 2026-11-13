
# Ping - Network Connectivity Testing

## Objective
To test network connectivity between the Windows 11 virtual machine and other network destinations.

## Environment
- Operating System: Windows 11
- Virtualization: VMware Workstation Pro 17.6
- Network Mode: NAT

## Commands Used

### 1. Ping Default Gateway
Command:
`ping 192.168.20.2`

Result:
- 4 packets sent
- 4 packets received
- 0% packet loss

### 2. Ping Google Public DNS
Command:
`ping 8.8.8.8`

Result:
- 4 packets sent
- 4 packets received
- 0% packet loss
- Average response time: 11 ms

## What I Learned
- How to test network connectivity using ping.
- How to test communication with the default gateway.
- How to test external IP connectivity.
- How to interpret packet loss and response time.

## Conclusion
The virtual machine successfully communicated with the default gateway and an external IP address. Both tests completed with 0% packet loss.

## German IT Vocabulary

| English | Deutsch |
|---|---|
| Network connectivity | Netzwerkkonnektivität |
| Packet loss | Paketverlust |
| Response time | Antwortzeit |
| Default gateway | Standardgateway |
| Destination host | Zielhost |
| Connection test | Verbindungstest |

