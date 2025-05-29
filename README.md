🛠️ Sydsanusi Recon Suite

Sydsanusi Recon Suite is a powerful Python-based toolkit designed for ethical hackers, cybersecurity professionals, and infosec enthusiasts. With a clean, command-line interface, this suite simplifies network, web, and cryptographic reconnaissance—turning complex tasks into streamlined operations.


---

✨ Features

🔌 Network Tools

Network Scanner (ARP Request) – Discover active devices in your local network.

Port Scanner (TCP SYN Scan) – Identify open TCP ports on a specified host.

Traceroute (ICMP Trace) – Trace the route packets take to reach a destination.


🌐 Web Tools

robots.txt Fetcher – Access hidden paths disallowed for search engines.

SSL Certificate Checker – Inspect website SSL certificate details.


🔐 Cryptographic Tools

Base64 Encoder/Decoder – Encode or decode strings using Base64.

SHA256 Hash Generator – Create secure hashes using SHA-256.


🖥️ System Tools

System Uptime – Display how long your machine has been running.


🧰 Miscellaneous Tools

QR Code Generator – Instantly generate QR codes from any text or URL.

Wordlist Generator – Create custom password lists based on a base word.



---

⚙️ Requirements

Ensure your system has:

Python 3.x

Termux or Linux environment (e.g., Kali Linux)


📦 Install Dependencies:

pkg install python3 git clang libjpeg-turbo freetype zlib whois
pip install --upgrade pip
pip install scapy requests qrcode[pil]


---

📥 Installation Guide

🔹 Method 1: One-Step Install (Termux)

pkg update -y && pkg upgrade -y && \
pkg install -y python git clang libjpeg-turbo freetype zlib whois && \
pip install --upgrade pip && \
pip install scapy requests qrcode[pil] && \
curl -o sydsanusi_recon.py https://sydsanusi-recon.s3.eu-north-1.amazonaws.com/sydsanusi_recon.py && \
python sydsanusi_recon.py

🔹 Method 2: Manual Install (Kali Linux or Termux)

# Step 1: Clone the repository
git clone https://github.com/Sanusi644/sydsanusi-recon.git
cd sydsanusi-recon

# Step 2: Install dependencies
pip install -r requirements.txt

# If requirements.txt is missing:
pip install scapy requests qrcode[pil]

# Step 3: Run the tool
python sydsanusi_recon.py
# or
python3 sydsanusi_recon.py


---

🧪 Usage Guide

Upon launch, you'll see a menu:

[1] Network Scan
[2] Port Scan
[3] Traceroute
[4] Fetch robots.txt
[5] SSL Certificate Checker
[6] Base64 Encoder/Decoder
[7] SHA256 Hash Generator
[8] System Uptime
[9] QR Code Generator
[10] Wordlist Generator
[11] Exit

📌 Example Workflows

1️⃣ Network Scan
Input: 192.168.1.0/24

2️⃣ Port Scan
Target IP: 192.168.1.10
Port Range: 20-80

3️⃣ Traceroute
Target: 8.8.8.8

4️⃣ robots.txt Fetcher
Website: https://example.com

5️⃣ SSL Checker
Website: https://example.com

6️⃣ Base64 Encode/Decode
Mode: e or d
Text: Hello, World!

7️⃣ SHA256 Hash
Text: password123

8️⃣ Uptime
Auto-displays system uptime

9️⃣ QR Code
Text or URL: https://example.com

🔟 Wordlist Generator
Base: password, Variations: 5


---

⚠️ Legal Disclaimer

This tool is built strictly for ethical and educational use. Do not use it on networks, domains, or systems without explicit permission. Unauthorized use is illegal and punishable under law.


---

✅ Real-World Compatibility

Requirement	Why It Matters	Fix (if needed)

Python 3 installed	Required to run the tool	pkg install python3
Root access (Termux)	Needed for ARP & TCP SYN scans	Use rooted device or Kali Linux
Internet connection	Needed for web-based tools	Enable Wi-Fi or mobile data
Required libraries	Essential for tool functionality	pip install scapy requests qrcode[pil]



---

🔍 Under the Hood

Feature	Real Equivalent	Technique Used

Network Scan	nmap -sn	ARP with scapy
Port Scan	nmap -sS	TCP SYN via socket
Traceroute	traceroute, mtr	ICMP TTL manipulation
SSL Checker	openssl, ssllabs	ssl module in Python
QR Generator	qrencode	qrcode Python lib



---

👨‍💻 Developed By

Sanusi Saminu (aka Cyrus Valen)
🔗 GitHub: @Sanusi644
💼 Project: Sydsanusi Recon Suite


---

✨ If you find this tool useful, give it a ⭐ on GitHub and share with the community!


