## AnalyzerIP
IPAnalyzer is an OSINT ethical hacking tool built for Linux distributions, designed to gather detailed information about IP addresses. This tool provides geolocation, timezone, country code, ASN, and other valuable data related to any given IP address. It also integrates with the Tor network to ensure anonymity and avoid API rate limiting by frequently changing IP addresses during requests.

This tool is made specifically for Linux distributions, like Kali Linux, and has been tested on Kali Linux to ensure smooth operation.

## Features
- **IP Geolocation:** Get detailed information about the location, country code, timezone, languages, and more.
- **ASN (Autonomous System Number) Lookup:** Retrieve the ASN information of the given IP address.
- **Tor Network Integration:** Automatically routes requests through the Tor network to bypass API rate limits and provide anonymity.
- **API Requests:** Continuously fetch information using Tor by changing IP addresses for each request.
- **Interactive Menu:** User-friendly interface to interact with the tool and easily gather IP-related information.
- **Automated Dependency Installation:** Installs required dependencies automatically if they are not already present.
## Installation
To install and run IPAnalyzer, follow these steps:

1. **Clone the repository:**

```bash
git clone https://github.com/xspider2c/AnalyzerIP.git
```
2. **Navigate to the IPAnalyzer directory** 
```bash
cd IPAnalyzer
```
3. **Navigate to the IPAnalyzer directory**
 ```bash
 cd IPAnalyzer
```
4. **Run the tool:**

You can now run the IPAnalyzer tool by executing the following command:

```bash
sudo bash ipanalyzer.sh
```
This will start the tool and display the interactive menu.

## Usage
After running the script, you'll be presented with an interactive menu where you can:

- **Analyze an IP:** Enter an IP address and receive detailed information about it, including geolocation, country, timezone, ASN, and more.
- **Check Your Own IP:** View the current IP address (via Tor or your regular IP) and verify if the requests are being routed through Tor.
- **Exit the Tool:** Option to exit the tool at any time.
  
## Example:
```markdown

     

                       _               _____ _____   
     /\               | |             |_   _|  __ \  
    /  \   _ __   __ _| |_   _ _______  | | | |__) | 
   / /\ \ | '_ \ / _` | | | | |_  / _ \ | | |  ___/  
  / ____ \| | | | (_| | | |_| |/ /  __/_| |_| |      
 /_/    \_\_| |_|\__,_|_|\__, /___\___|_____|_|      
                          __/ |                      
                         |___/                       



                                Developer : MR. G

* Copyright © Sreeraj, 2025
* GitHub: https://github.com/xspider2c

  [01] My Original IP
  [02] My Tor IP 
  [03] Track an IP
  [00] Exit

  [~] Select An Option:

```

Follow the prompts to analyze any IP or check your own IP.

## How It Works
1. **IP Analysis:** When you select the option to analyze an IP address, the tool fetches geolocation details such as the city, country, region, timezone, languages, and ASN of the given IP.
2. **Tor Integration:** IPAnalyzer automatically connects to the Tor network if it's not already running, ensuring that each request is routed through a new IP address, which helps in avoiding rate limits imposed by the API.
3. **Anonymous Requests:** The tool helps maintain privacy by masking the user's real IP address during the analysis.
## Dependencies
- **curl:** Used for making HTTP requests to the API for fetching IP information.
- **jq:** A lightweight and flexible command-line JSON processor.
- **Tor:** Used for routing requests through the Tor network to maintain anonymity and avoid rate limits.
## Compatibility
- **Tested on Kali Linux:** This tool is specifically built for Linux distributions, like Kali Linux. It has been tested on **Kali Linux** to ensure compatibility and smooth functioning.
- **Works on other Linux-based distros:** Should work seamlessly on other Linux-based operating systems with similar setups.
  
This tool is open-source 

