# SetQuad9DNS
# Quad9 DNS Setter

This repository contains a Windows batch script that automatically configures your system's DNS settings to use Quad9 DNS servers. Quad9 is a free, recursive, anycast DNS platform that provides robust security protections, high performance, and privacy [1](https://quad9.com/about/).

## Features

- Automatically detects the active network interface
- Sets primary DNS to Quad9's main server (9.9.9.9)
- Sets secondary DNS to Quad9's alternate server (149.112.112.112)
- Flushes DNS cache to ensure immediate effect of new settings
- Provides user-friendly output and instructions

## Benefits of Quad9 DNS

1. **Enhanced Security**: Quad9 blocks known malicious domains, preventing your devices from connecting to malware or phishing sites [1](https://quad9.com/about/).

2. **Privacy Protection**: Quad9 does not collect or store personal data, ensuring your browsing habits remain private [2](https://quad9.net/service/service-addresses-and-features/).

3. **High Performance**: With servers located worldwide, Quad9 offers low-latency DNS resolution for faster browsing [3](https://techreviewadvisor.com/what-is-quad9-dns/).

4. **No Cost**: Quad9 is a free service, making it accessible to all users [1](https://quad9.com/about/).

5. **Threat Intelligence**: Quad9 uses data from multiple cyber threat intelligence providers to proactively protect against emerging threats [3](https://techreviewadvisor.com/what-is-quad9-dns/).

## Usage

1. Download the `SetQuad9DNS.bat` file from this repository.
2. Right-click on the file and select "Run as administrator".
3. Follow the on-screen instructions.

**Note**: Changing DNS settings requires administrative privileges. Please ensure you run the script as an administrator.

## Requirements

- Windows operating system
- Administrative privileges

## Disclaimer

This script modifies system network settings. While it's designed to be safe and reversible, please ensure you understand the implications of changing your DNS settings. If you experience any issues, you can always revert to your original settings by setting your DNS to "Obtain DNS server address automatically" in your network settings.

## Author

MrNotepad85

---

Remember to stay safe online and happy browsing with Quad9 DNS!
