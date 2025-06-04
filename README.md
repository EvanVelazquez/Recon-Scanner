📄 README: Bash Network Scanner Script
🔧 Description
This script automates basic reconnaissance on a given IP address or CIDR network. It performs:

ICMP ping sweep using nping to identify live hosts.

Port scanning using nmap on the top 25 ports of the detected IPs.

Outputs a summarized list of open ports per host.

🛑 Important Notes
Use this script only on networks you have permission to scan.

ICMP and SYN scans may trigger security alerts on protected networks.

The grep lines assume standard output formatting from nping and nmap.
