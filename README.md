# Basic-Packet-Sniffer
This packet sniffer is a Python-based tool designed to monitor and log TCP and UDP network traffic. Built using the Scapy library, it's a simple yet powerful utility for network analysis, especially suited for educational purposes.

# Features
TCP and UDP Packet Capturing: Captures TCP and UDP packets, displaying source and destination IP addresses and ports.
HTTP Traffic Filtering: Option to filter and capture HTTP traffic specifically.
Data Logging: Logs packet details to a file for further analysis and record-keeping.
Real-Time Packet Display: Shows packet information in real-time on the console.
# Prerequisites
Before running the packet sniffer, ensure you have the following installed:

Python 3.x
Scapy
WinPcap or Npcap (Windows users)
# Installation
## Clone the Repository:

git clone https://github.com/<your-username>/packet-sniffer.git
## Navigate to the Project Directory:

cd packet-sniffer
## Install Dependencies:

pip install -r requirements.txt
# Usage
To start the packet sniffer, run the following command in the terminal:

sudo python packet_sniffer.py
For Windows users, run the command prompt as Administrator:

python packet_sniffer.py
# How It Works
The script uses Scapy to capture network packets. By default, it captures all TCP and UDP packets, displaying and logging information such as IP addresses and port numbers. The script can be modified to add filters for specific protocols or ports.

# Output
The tool outputs each packet's source IP, source port, destination IP, and destination port in real-time. Additionally, this data is logged to packet_log.txt in the project directory.

# Customization
You can customize the script to capture different types of traffic, log additional information, or implement alerting for specific network events.
# Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your suggested changes.
