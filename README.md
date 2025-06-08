Task 1: Network Port Scanning – Execution Summary
For this task, I performed a basic network reconnaissance using Nmap and analyzed packets using Wireshark.

Steps I followed:
Installed Nmap and identified my local IP range (192.168.1.0/24).

Ran the command nmap -sS 192.168.1.0/24 to do a TCP SYN scan on all devices in the network.

Identified active hosts and noted open ports and running services (e.g., HTTP, MySQL, NetBIOS).

Saved a screenshot of the Nmap scan result as proof.

Used Wireshark to capture and inspect the network traffic during the scan for better understanding of how the scan works at the packet level.

Analyzed services running on open ports to understand what each port/service could potentially expose.

Noted security risks, like exposed MySQL or SMB ports, which could be entry points for attackers if not secured properly.

Tools Used:
Nmap (for scanning)

Wireshark (for packet analysis)

This task helped me understand how port scanning works, how to identify exposed services, and why it's important for network security.
