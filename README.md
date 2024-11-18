# Python Port Scanner

A simple yet effective Python port scanner leveraging the `nmap` library. This script allows users to validate IP addresses, specify custom port ranges, and scan ports to determine their states (open, closed, filtered).

## Features
- IP address validation using the `ipaddress` module.
- Customizable port range input.
- Leverages `nmap` for robust scanning functionality.
- Handles errors gracefully to avoid crashes.

## Prerequisites
- Python 3.x
- Nmap installed on your system.

## Installation
1. Install Python and pip if not already available.
2. Install required libraries:
   ```bash
   sudo apt install python3-pip
   pip install python-nmap

Your script is a Python-based port scanner using the nmap library and ipaddress module for input validation. Here's a concise GitHub repository description for your project:
Repository Name: python-port-scanner
Description:

A simple Python-based port scanning tool that utilizes the nmap library for efficient network scanning. This tool validates IP addresses and allows users to specify custom port ranges for scanning. It is ideal for learning purposes or lightweight scanning tasks.
README.md Sample Content:

# Python Port Scanner

A simple yet effective Python port scanner leveraging the `nmap` library. This script allows users to validate IP addresses, specify custom port ranges, and scan ports to determine their states (open, closed, filtered).

## Features
- IP address validation using the `ipaddress` module.
- Customizable port range input.
- Leverages `nmap` for robust scanning functionality.
- Handles errors gracefully to avoid crashes.

## Prerequisites
- Python 3.x
- Nmap installed on your system.

## Installation
1. Install Python and pip if not already available.
2. Install required libraries:
   ```bash
   sudo apt install python3-pip
   pip install python-nmap



#Usage

1.) clone the repository:  
    git clone https://github.com/gargmradul09/portscan-nmapbymradul.py.git

2.)  Navigate to the project directory:
   cd portscan-nmapbymradul.py

3.) Run the script:  
    python3 portscan-nmapbymradul.py


#Example Output

Please enter the IP address you want to scan: 192.168.1.1

You entered a valid IP address.

Please enter the range of ports you want to scan in format: <int>-<int> (e.g., 20-80)

Port 22 is filtered
Port 23 is filtered
...
Cannot scan port 90.


#Notes
> Avoid scanning all 65,535 ports unless necessary, as it may take significant time.
> This script is for educational purposes and should be used ethically.
