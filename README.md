# Domain Expiration Checker

## Overview
The `masba.sh` script checks the expiration dates of a list of domains using WHOIS information. It formats the expiration dates into a more readable format for easier understanding.

## Features
- Retrieves WHOIS information for specified domains.
- Extracts and formats the expiration dates of the domains.
- Displays the domain names along with their corresponding expiration dates.

## Requirements
- Bash shell
- `whois` command-line utility
- `date` command
- `grep` and `awk` command-line utilities

## Installation
1. Clone this repository or download the script.
2. Ensure that you have the required utilities installed. You can install them using:
   ```bash
   sudo apt-get install whois  # For Debian/Ubuntu systems
   sudo yum install whois      # For RHEL/CentOS systems
