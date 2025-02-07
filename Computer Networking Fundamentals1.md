# Computer Networking Fundamentals: A Comprehensive Guide

## Introduction & History
- The internet evolved from ARPANET (Advanced Research Projects Agency Network) in the 1960s
- Initially developed by the US Department of Defense for military communications
- Key milestones:
  - 1969: First node-to-node communication
  - 1973: TCP/IP development began
  - 1983: ARPANET adopts TCP/IP
  - 1989: World Wide Web invented by Tim Berners-Lee
  - 1990s: Commercialization and widespread adoption

## Client-Server Architecture
### Basic Concept
- Two-party architectural model where workload is divided between providers (servers) and requesters (clients)
- Server: Powerful computer that provides resources, services, and data
- Client: Device that requests and consumes these services
- Examples: Web browsers (clients) requesting websites from web servers

### Characteristics
- Servers are always-on, listening for requests
- Clients initiate communication
- Servers can handle multiple clients simultaneously
- Scalable and centralized resource management

## Protocols
### Definition
- Standardized rules for data communication between devices
- Ensures consistent communication regardless of device type or manufacturer

### Key Protocols
1. TCP/IP (Transmission Control Protocol/Internet Protocol)
   - Foundation of internet communication
   - Ensures reliable, ordered data delivery
   - Handles packet routing and addressing

2. HTTP/HTTPS (Hypertext Transfer Protocol)
   - Web communication protocol
   - HTTPS adds encryption for security

3. FTP (File Transfer Protocol)
   - Specialized for file transfers
   - Supports upload and download operations

4. DNS (Domain Name System)
   - Translates domain names to IP addresses
   - Hierarchical naming system

## Data Transfer Process
### Steps in Data Transfer
1. Data Segmentation
   - Large data broken into smaller packets
   - Each packet contains source and destination information

2. Packet Routing
   - Packets may take different paths
   - Routers determine optimal path based on network conditions

3. Reassembly
   - Destination device reconstructs original data
   - TCP ensures correct order and completeness

## IP Addresses
### IPv4
- 32-bit address (e.g., 192.168.1.1)
- Limited to approximately 4.3 billion unique addresses
- Uses NAT (Network Address Translation) to extend usefulness

### IPv6
- 128-bit address (e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334)
- Practically unlimited addresses
- Better security and efficiency features

## Port Numbers
### Purpose
- Identify specific services/applications on a device
- Enable multiple simultaneous connections

### Common Ports
- HTTP: 80
- HTTPS: 443
- FTP: 21
- SSH: 22
- DNS: 53

## Submarine Cables
### Overview
- Underwater fiber optic cables connecting continents
- Carry ~99% of international data traffic
- Typically 69-171 kilometers below sea level

### Key Features
- Protected by multiple layers including steel wire armor
- Signal boosters every 60-100 km
- Redundant paths for reliability
- Capacity: Multiple terabits per second

## Network Types
### LAN (Local Area Network)
- Limited geographical area (building/campus)
- High data transfer rates
- Typically privately owned and managed

### MAN (Metropolitan Area Network)
- City-wide coverage
- Connects multiple LANs
- Often used by organizations with multiple locations

### WAN (Wide Area Network)
- Spans large geographical areas
- Connects multiple LANs/MANs
- Internet is the largest WAN

## Network Hardware
### MODEM (Modulator-Demodulator)
- Converts digital signals to analog and vice versa
- Enables data transmission over telephone lines
- Modern versions support various connection types

### Router
#### Functions
- Connects different networks
- Determines optimal data paths
- Provides network security
- Network address translation (NAT)

#### Features
- Firewall capabilities
- DHCP server functionality
- Quality of Service (QoS) management
- Wi-Fi capabilities in modern routers

## Interview Tips
1. Understand the relationships between concepts
2. Be prepared to explain real-world applications
3. Know common troubleshooting scenarios
4. Understand basic security implications
5. Be familiar with current trends and developments
