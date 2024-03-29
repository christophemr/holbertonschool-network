# Networking Basics #0

## Description

This project covers fundamental networking concepts, including the OSI model, types of networks (LAN, WAN, Internet), MAC and IP addresses, TCP/UDP, and TCP/UDP ports. Additionally, it introduces the basics of ICMP and includes a script for pinging an IP address.

## Learning Objectives

Upon completing this project, you should be able to:

- Explain the OSI model, its layers, and organization.
- Understand LAN and WAN networks, their typical usage, and geographical sizes.
- Define the Internet, IP address, and the difference between private and public addresses.
- Differentiate between IPv4 and IPv6, and comprehend the concept of localhost.
- Explain TCP and UDP, including the main difference between them.
- Define ports and memorize common port numbers (e.g., SSH, HTTP, HTTPS).
- Understand the purpose and usage of ping/ICMP.
- Familiarize yourself with positional parameters in Bash.

## Requirements

- Allowed editors: vi, vim, emacs
- All Bash script files interpreted on Ubuntu 20.04 LTS
- All files must end with a new line
- A README.md file at the root of the project folder is mandatory
- Bash script files must be executable
- Bash scripts must pass shellcheck without errors
- The first line of all Bash scripts should be `#!/usr/bin/env bash`
- The second line of all Bash scripts should be a comment explaining the script's purpose

## Tasks

### 0. OSI model

Describe the OSI (Open Systems Interconnection) model, its layers, and organization. Focus on the Transport layer (TCP/UDP) and the Network layer (IP and ICMP). Provide an image illustrating the model.

Repo:
- [GitHub: holbertonschool-network](https://github.com/your-username/holbertonschool-network)
- Directory: basics_0
- File: 0-OSI_model

### 1. Types of network

Explain LAN, WAN, and Internet networks. Answer questions related to network types and their usage.

Repo:
- [GitHub: holbertonschool-network](https://github.com/your-username/holbertonschool-network)
- Directory: basics_0
- File: 1-types_of_network

### 2. MAC and IP address

Define MAC and IP addresses. Answer questions regarding these addresses.

Repo:
- [GitHub: holbertonschool-network](https://github.com/your-username/holbertonschool-network)
- Directory: basics_0
- File: 2-MAC_and_IP_address

### 3. UDP and TCP

Explain TCP and UDP, including their characteristics. Answer questions about TCP and UDP.

Repo:
- [GitHub: holbertonschool-network](https://github.com/your-username/holbertonschool-network)
- Directory: basics_0
- File: 3-UDP_and_TCP

### 4. TCP and UDP ports

Write a Bash script that displays listening ports. The script should show only listening sockets and include the PID and name of the program to which each socket belongs.

Example:

```bash
sudo ./4-TCP_and_UDP_ports
5. Is the host on the network
Write a Bash script that pings an IP address passed as an argument. The script should accept a string as an argument, display a usage message if no argument is passed, and ping the IP five times.

Example:
./5-is_the_host_on_the_network 8.8.8.8
./5-is_the_host_on_the_network
Usage: 5-is_the_host_on_the_network {IP_ADDRESS}
