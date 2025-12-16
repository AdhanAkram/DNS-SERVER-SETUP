# DNS Server Setup using Cisco Packet Tracer

## Project Description
This project demonstrates the configuration and working of a DNS (Domain Name System) server in a computer network using Cisco Packet Tracer. The DNS server is used to translate human-readable domain names into IP addresses, allowing efficient and user-friendly communication between network devices.

## Network Topology
The network consists of:
- DNS Server
- Switch
- Multiple PCs (Clients)

All devices are connected within the same Local Area Network (LAN). A router is optional and not required for local DNS resolution.

## Objectives
- To understand the working of DNS in a computer network
- To configure a DNS server in Cisco Packet Tracer
- To enable name resolution for client PCs
- To verify DNS functionality using testing commands

## Configuration Details
- DNS service is enabled on the server
- Domain name records (A records) are added to map domain names to IP addresses
- Client PCs are configured with the DNS server’s IP address
- All devices are assigned IP addresses within the same subnet

## Testing and Verification
DNS functionality is tested using:
- `ping domain_name`
- `nslookup domain_name`

Successful responses confirm proper DNS resolution.

## Tools Used
- Cisco Packet Tracer

## Conclusion
The DNS server setup successfully resolves domain names to IP addresses within the local network. This project helps in understanding client-server communication and basic network services used in real-world environments.

## Author
Student Name
