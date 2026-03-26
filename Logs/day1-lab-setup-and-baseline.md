# Day 1 — Lab Setup & Foundational Understanding

## Objective

To set up a controlled lab environment and develop a foundational understanding of system behavior, networking, and port states.

---

## Activity

- Installed and configured VirtualBox
- Deployed Kali Linux virtual machine
- Verified internet connectivity within the VM
- Explored basic Linux terminal usage
- Identified network interfaces and IP address using `ip a`
- Understood the role of loopback interface (127.0.0.1)
- Differentiated between local and network-based communication
- Introduced basic concept of ports and services
- Performed an initial scan to observe system exposure

---

## Observation

- Loopback address (127.0.0.1) represents internal system communication
- Network interface is assigned an IP via NAT (VirtualBox)
- No services were actively listening on scanned ports
- System is in a baseline state with no external exposure

---

## Learning

- Relationship between interfaces, IP addresses, and communication
- Concept of ports and their states (open, closed, filtered)
- Difference between local (loopback) and network interface traffic
- Importance of establishing a baseline before further analysis
