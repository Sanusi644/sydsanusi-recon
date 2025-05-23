Sydsanusi Recon Suite
A Kali Linux-inspired toolkit for network reconnaissance.

Overview
Sydsanusi Recon Suite is a collection of network, web, and cryptographic tools designed to help security professionals and enthusiasts perform reconnaissance tasks. The toolkit includes features like IP range scanning, port scanning, traceroute, SSL certificate checking, and more.

Features
Network Tools:

Network scan (ARP request)
Port scan (TCP SYN scan)
Traceroute (ICMP trace)
Web Tools:

Fetch robots.txt
SSL certificate checker
Cryptographic Tools:

Base64 encoder/decoder
SHA256 hash generator
System Tools:

System uptime
Miscellaneous:

QR Code generator
Wordlist generator
Requirements
Python 3.x
Scapy (pip install scapy)
Requests (pip install requests)
qrcode (pip install qrcode[pil])
Installation
Clone the repository:

git clone https://github.com/Sanusi644/sydsanusi-recon.git
Install required dependencies:

pip install -r requirements.txt
Usage
After installing the dependencies, run the tool by executing the following:

python sydsanusi_recon.py
