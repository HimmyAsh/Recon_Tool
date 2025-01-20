# Recon_Tool

Installation

To run the Automated Recon Tool, make sure you have Python installed on your system. Then, follow these steps:

Clone the repository:

git clone <repository_url>
cd automated-recon-tool

**Dependencies**:

PyQt5

whois

dnspython

requests

**Usage**

**GUI Mode**

Run the script:

python automated_recon_tool.py

Enter the target domain.

Specify ports to scan as a comma-separated list (e.g., 80,443,8080).

Click Run Recon to perform the tasks.

View results in the GUI or in the recon_results.json file.

**CLI Mode**

Use the --cli flag to run the tool in CLI mode:

python automated_recon_tool.py --cli --domain <domain> --ports <port1> <port2>

Example:

python automated_recon_tool.py --cli --domain example.com --ports 80 443 8080

Example Output

WHOIS:

Domain Name: EXAMPLE.COM
Registrar: Example Registrar, Inc.
Updated Date: 2023-01-01
...

DNS Records:

192.0.2.1
198.51.100.2

Port Scan:

Port 80 is open!
Port 443 is open!

**Contributions**

Contributions to this project are welcome! Feel free to fork the repository and submit a pull request with your enhancements.

**Disclaimer**

This tool is for educational and ethical purposes only. Use responsibly and ensure you have proper authorization when running reconnaissance tasks on any target.
