# 🌐 Networking Basics

## Core ideas
- **IP address**: the address of a device on a network (e.g. 192.168.1.10)
- **MAC address**: the hardware ID of a network card
- **DNS**: turns names (google.com) into IP addresses
- **Port**: a door on a device (HTTP 80, HTTPS 443, SSH 22)
- **Router**: connects networks and forwards packets

## TCP vs UDP
| | TCP | UDP |
|---|---|---|
| Reliable | Yes (checks delivery) | No |
| Speed | Slower | Faster |
| Used for | Web, email | Streaming, calls, games |

## OSI model (7 layers)
Physical → Data Link → Network → Transport → Session → Presentation → Application

## Commands to practice
- `ping google.com`: test connection
- `ipconfig` (Windows) / `ip a` (Linux): see your IP
- `nslookup google.com`: DNS lookup
- `tracert google.com`: path of packets
