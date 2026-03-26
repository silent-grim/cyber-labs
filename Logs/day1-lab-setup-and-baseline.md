# Day 1 — Lab Setup & Baseline Understanding

## Objective

To set up a controlled lab environment and gain foundational understanding of system behavior, networking, and port states.

---

## Activity

- Installed and configured VirtualBox
- Deployed Kali Linux virtual machine
- Verified internet connectivity within VM
- Explored basic Linux environment and terminal usage
- Identified network interfaces and IP address using `ip a`
- Understood difference between loopback (127.0.0.1) and network interface
- Performed initial Nmap scan on localhost (127.0.0.1)
- Performed scan using assigned IP address

---

## Observation

- Loopback interface (127.0.0.1) represents internal system communication
- Network interface IP is assigned via NAT (VirtualBox)
- All scanned ports were closed, indicating no active listening services
- System is in a baseline state with no exposed services

---

## Learning

- Difference between local and network-based scanning
- Concept of ports and their states (open, closed, filtered)
- Role of network interfaces in communication
- Importance of establishing a baseline before further testing
