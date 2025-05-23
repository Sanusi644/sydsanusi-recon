Sydsanusi Recon Suite

A Kali Linux-inspired toolkit for network reconnaissance


---

Overview

Welcome to Sydsanusi Recon Suite!
This is a powerful collection of tools for network, web, and cryptographic reconnaissance — built for ethical hackers, security professionals, and cybersecurity enthusiasts.

🛠️ It helps you gather information about targets using various scanning and analysis methods — all from one simple Python-based interface.


---

✨ Features

🌐 Network Tools

🧑‍🔬 Network Scan (ARP request): Discover active devices in your local network.

🔍 Port Scan (TCP SYN scan): Identify open ports on a target IP.

📍 Traceroute (ICMP trace): Track the path packets take to reach a target.


🌍 Web Tools

🧬 robots.txt Fetcher: Retrieve hidden paths blocked from web crawlers.

🔐 SSL Certificate Checker: Inspect a website’s SSL certificate info.


🔐 Cryptographic Tools

✉️ Base64 Encoder/Decoder: Encode or decode messages in Base64.

🧮 SHA256 Hash Generator: Securely hash text with SHA256.


🖥️ System Tools

⏱️ System Uptime: Display how long the system has been running.


🧩 Miscellaneous

🔳 QR Code Generator: Generate QR codes from text or URLs.

📄 Wordlist Generator: Create custom password lists.



---

⚙️ Requirements

Make sure you have:

🐍 Python 3.x
Then install the following Python libraries:


pip install scapy requests qrcode[pil]


---

⬇️ Installation Guide

Step 1: Clone the Repository

Use git to download the project:

git clone https://github.com/Sanusi644/sydsanusi-recon.git
cd sydsanusi-recon

Step 2: Install All Dependencies

Use the requirements.txt to install everything needed:

pip install -r requirements.txt


---

▶️ How to Run

Simply launch the tool using:

python sydsanusi_recon.py

A menu will appear, letting you choose the tool you want to run.

Example:

[1] Network Scan
[2] Port Scan
...
[10] Wordlist Generator

Select the number for the task, and the tool will do the rest!


---

⚠️ Warning

This tool is for educational and ethical hacking purposes only.
You must only scan systems you own or have explicit permission to test.
Unauthorized scanning is illegal and may lead to criminal charges.


---

Developed By

Sanusi Saminu (Cyrus Valen)
GitHub: @Sanusi644


