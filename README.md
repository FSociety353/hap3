📌 README - Hap3 OSINT & Port Scanner
📖 Description

Hap3 is a Python-based OSINT and Port Scanning tool designed for security researchers and penetration testers. It gathers information about a target (IP/Domain) and scans for open ports, identifying possible attack vectors.
🚀 Features

✅ WHOIS Lookup (Domain Creation Year, Registrar, Name Servers, etc.)
✅ DNS Lookup (Resolve IP from Domain)
✅ Geolocation Lookup (Country, City, ISP, etc.)
✅ Device Information (OS, Machine Type, Processor)
✅ HTTP Headers Fetching
✅ Advanced Port Scanning (Shows open/closed/filtered ports & attack possibilities)
✅ Private IP Detection & Handling
✅ Social Engineering & Brute Force (Coming Soon!)
🔥 Installation
📌 Requirements

    OS: Kali Linux (Recommended) / Any Linux OS
    Python Version: 3.x
    Dependencies: requests, whois, scapy

📥 Installation Steps

# Update & Install Python3 if not installed
sudo apt update && sudo apt install python3 -y

# Install required Python modules
pip install requests whois scapy

⚡ How to Run the Tool
🔴 Move the Script to Desktop

Before executing the script, move it to your Desktop for easy access:

mv hap3.py ~/Desktop/

🔵 Execute the Python Script

cd ~/Desktop
python3 hap3.py

🔵 Usage

Once the script starts, select an option:

Enter (1) for IP, (2) for URL, (3) Coming Soon, or (4) to Exit:

    Option (1) → Enter an IP address to scan
    Option (2) → Enter a domain name (with or without https://)
    Option (3) → Displays a message about future features
    Option (4) → Exit the tool

After entering an IP/Domain, the script will:

    Perform OSINT (WHOIS, DNS, Geolocation, Device Info).
    Fetch HTTP Headers of the target.
    Ask for a port range to scan.
    Perform a multi-threaded port scan, identifying potential attack vectors for open ports.

⚠️ Legal Disclaimer

This tool is intended for educational and ethical security research purposes only.
The author is not responsible for any misuse of this tool.
🎯 Coming Soon

🔹 Social Engineering Toolkit Integration
🔹 Brute Force Attack Simulations
🔹 More OSINT Features (Dark Web, Leak Detection, etc.)
📢 Author

Developed by fsociety 353
Stay Safe, Stay Ethical! 🚀
