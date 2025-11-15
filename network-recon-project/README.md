# Network Recon Project
Network Reconnaissance & Firewall Analysis Using Nmap and Wireshark
Overview

This project demonstrates hands-on experience with network scanning, packet capture, and troubleshooting filtered ports on a modern firewall-protected network using Nmap and Wireshark.
It includes full documentation, packet analysis, and a controlled environment setup.

🔧 Tools Used

Nmap

Wireshark

Windows 10

Home Wi-Fi Network

📌 Key Skills Demonstrated

Network enumeration

SYN stealth scanning (-sS)

Packet-level traffic analysis

Wireshark filtering

Firewall behavior investigation

NAT and device isolation analysis

📂 Project Contents

Full write-up (/docs/full_project_writeup.pdf)

Screenshots of Nmap and Wireshark (/screenshots/)

PCAP packet capture file (/pcaps/recon_capture.pcapng)

All Nmap commands used (/commands/nmap_commands.txt)

🧪 How to Reproduce

Install Nmap

Install Wireshark

Identify the target device on LAN

Run a full SYN scan

Capture packets while scanning

Use Wireshark filters such as:

ip.addr == <target-ip>
tcp.flags.syn == 1 && tcp.flags.ack == 0
tcp.flags.reset == 1


Analyze responses (or lack of responses)

Build a local test server for known open ports

📘 Full Documentation

The entire project write-up is available here:

👉 /docs/full_project_writeup.pdf

🏁 Future Improvements
Add a Metasploitable VM
Compare filtered vs open-port scans
add automated scan scripts
Expand into service enumeration (-sV)

👨‍💻 Author

Uzair Khan
Beginner Cybersecurity & Networking Projects
