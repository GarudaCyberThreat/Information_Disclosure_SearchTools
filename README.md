InfoDisclosureSearch - Powerful Information Disclosure Scanner
Overview
InfoDisclosureSearch is a robust and highly efficient Python-based tool designed for full-power information disclosure vulnerability scanning. Developed by Hafid Fajar, one of the co-founders of Garuda CyberThreat community, this tool meticulously hunts for sensitive data exposure in web applications, quickly and efficiently uncovering exposed sensitive information.

It automates the process of identifying common misconfigurations, leaked credentials, debug information, and other sensitive files that can compromise an application's security.

Features
Comprehensive Scanning: Scans for a wide range of common information disclosure patterns, including .env files, .git artifacts, backup files, configuration files, and more.

Sensitive Data Pattern Matching: Utilizes a rich set of regular expressions to identify API keys, credentials, internal IP addresses, stack traces, and other sensitive strings within HTTP responses and JavaScript files.

Directory Listing Detection: Automatically identifies enabled directory listings that can expose file structures.

Subdomain Enumeration: Includes a passive subdomain brute-forcing feature to discover potentially vulnerable subdomains.

Header Analysis: Inspects HTTP headers for sensitive information.

Output to File: Saves all findings to a timestamped text file for easy review and reporting.

Cross-Platform Compatibility: Designed to run seamlessly on Windows (CMD), Linux (Kali Linux), and Android (Termux).

Who Developed This Tool?
InfoDisclosureSearch was proudly developed by Hafid Fajar, a dedicated cybersecurity enthusiast and one of the esteemed co-founders of the Garuda CyberThreat community. This tool embodies the community's commitment to advancing cybersecurity knowledge and contributing valuable resources to the security landscape.

Installation & Requirements
Before running InfoDisclosureSearch.pyc, you need to ensure you have Python and the necessary libraries installed.

Prerequisites:
Python 3.x: This tool is built with Python 3. Make sure you have Python 3 installed on your system. You can download it from python.org.

Required Python Libraries:

requests: For making HTTP requests.

colorama: For colorful console output.

urllib3: (Typically comes with requests, but needed for warning suppression).

How to Install Required Libraries:
Open your terminal/CMD/Termux and run the following command:

Bash

pip install requests colorama
Running the Tool (InfoDisclosureSearch.pyc)
The tool is provided as a compiled Python bytecode file (.pyc). This means you don't need the original .py source code to run it.

Important Note: .pyc files are specific to the Python version they were compiled with. Ensure your installed Python version is compatible (e.g., if it was compiled with Python 3.9, run it with Python 3.9).

1. Download the Tool:
First, download the InfoDisclosureSearch.pyc file (and place it in a dedicated folder, e.g., InfoDisclosureSearch/).

2. Running on Windows (CMD):
Open Command Prompt (CMD).

Navigate to the directory where you saved InfoDisclosureSearch.pyc. For example:

DOS

cd C:\Path\To\Your\InfoDisclosureSearch
Run the tool using the Python interpreter:

DOS

python InfoDisclosureSearch.pyc
3. Running on Kali Linux / Other Linux Distributions:
Open your Terminal.

Navigate to the directory where you saved InfoDisclosureSearch.pyc. For example:

Bash

cd /path/to/your/InfoDisclosureSearch
Run the tool using the Python interpreter:

Bash

python3 InfoDisclosureSearch.pyc
(Use python3 to explicitly call Python 3 if your system defaults to Python 2 for python).

4. Running on Android (Termux):
Install Termux from F-Droid or Google Play Store.

Update Termux packages:

Bash

pkg update && pkg upgrade
Install Python:

Bash

pkg install python
Install the required Python libraries:

Bash

pip install requests colorama
Navigate to the directory where you saved InfoDisclosureSearch.pyc (you might need to grant Termux storage permissions and use commands like termux-setup-storage and cd /sdcard/Download/YourFolder). For example:

Bash

cd /data/data/com.termux/files/home/InfoDisclosureSearch # Or wherever you put it
Run the tool:

Bash

python InfoDisclosureSearch.pyc
Usage
Once executed, the tool will prompt you to enter the target URL(s) or specify a file containing a list of URLs.

Bash

python InfoDisclosureSearch.pyc
Follow the on-screen instructions to provide your target(s). The results will be displayed in the console and automatically saved to a text file (e.g., information_disclosure_scan_results_YYYYMMDD_HHMMSS.txt) in the same directory.

Disclaimer
This tool is intended for ethical hacking, penetration testing, and educational purposes only. The Garuda CyberThreat community and Hafid Fajar are not responsible for any misuse or damage caused by this tool. Always ensure you have explicit permission from the target's owner before conducting any security scans.

Contributing
We welcome contributions! If you have suggestions for improvements, new features, or bug fixes, feel free to open an issue or submit a pull request.

Connect with Garuda CyberThreat
Stay updated and connect with our community through the following channels:

Email: garudacyberthreat@gmail.com

TikTok: @garudacyberthreat

Instagram: garuda_cyberthreat

Twitter/X: @GarudaCyberThre

License
[You might want to add a license here, e.g., MIT License. Refer to the previous response on how to create a LICENSE file.]

Support Our Work
If you find this tool useful and wish to support our efforts in developing more open-source cybersecurity tools and resources, you can donate via USDT (TRC20 Network).

USDT (TRC20) Wallet Address: TEtzPQgrmCYi6nEPaj6F7hxxmG1mKzNB3y</span>

Your support is greatly appreciated!
