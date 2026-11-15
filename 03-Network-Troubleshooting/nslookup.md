
# DNS Troubleshooting - nslookup

## Objective
To investigate DNS resolution using the nslookup command in Windows 11.

## Environment
- Operating System: Windows 11
- Virtualization: VMware Workstation Pro 17.6
- Network Mode: NAT

## Commands Used

### 1. Default DNS Server
Command:
`nslookup google.com`

Observed Results:
- DNS Server: 192.168.20.2
- DNS query completed successfully.
- Google domain name was resolved to an IP address.
- Server name appeared as Unknown.

Note:
The Unknown label does not necessarily indicate a DNS failure. It can occur when the DNS server does not have a reverse DNS record.

### 2. Google Public DNS
Command:
`nslookup google.com 8.8.8.8`

Observed Results:
- DNS server: dns.google
- Query completed successfully.
- IPv4 and IPv6 addresses were returned.

## What I Learned
- How DNS translates domain names into IP addresses.
- How to use nslookup.
- How to query a specific DNS server.
- How to compare default DNS with Google Public DNS.

## Conclusion
Both DNS tests completed successfully. The virtual machine was able to resolve the domain name using its default DNS server and Google Public DNS.

## German IT Vocabulary

| English | Deutsch |
|---|---|
| Domain name | Domänenname |
| Name resolution | Namensauflösung |
| DNS server | DNS-Server |
| DNS query | DNS-Abfrage |
| IP address | IP-Adresse |
| Reverse DNS lookup | Reverse-DNS-Abfrage |
