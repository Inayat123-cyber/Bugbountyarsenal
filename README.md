bugarsenal
🔹 Description:

    A modular bug bounty recon and automation framework built in Bash by Inayat Hussain — designed to run efficiently on low-spec systems.

📄 README.md for BugArsenal

# 🛡️ BugArsenal – Bug Bounty Recon Framework

**BugArsenal** is a lightweight, modular, and beginner-friendly bug bounty framework written in Bash by **Inayat Hussain**. Built to run even on low-resource systems like 4GB RAM laptops or free cloud environments such as Replit and Termux.

## 🚀 Features

- Subdomain Enumeration
- Port Scanning
- HTTP Probing
- Active Scanning (XSS, open redirects)
- Dork Generator
- Organized Output
- Tool Integration (httpx, nuclei, dalfox, etc.)

## 📦 Requirements

Install the following tools before running:

```bash
sudo apt install -y curl git jq whois

You may also need:

go install github.com/projectdiscovery/httpx/cmd/httpx@latest
go install github.com/projectdiscovery/nuclei/v2/cmd/nuclei@latest
go install github.com/hahwul/dalfox/v2@latest

🧠 Usage

chmod +x bugarsenal.sh
./bugarsenal.sh

    Enter target domain when prompted

    Choose from available modules (subdomain scan, XSS scan, etc.)

    Results are saved automatically into folders like /output/domain_name/

🛡️ Author

Inayat Hussain (Inayat Raj Chohan)
Bug bounty hunter | Cybersecurity researcher | 60+ certs by age 17
🌐 LinkedIn
📘 Facebook: Inayat Raj Chohan
⚠️ Disclaimer

This tool is for educational and ethical hacking purposes only. Do not use without permission.
❤️ Support My Journey

I'm a self-taught security researcher from a rural village with no electricity and a 4GB laptop. If you find this tool useful, give it a ⭐ on GitHub and help share it with others.


---

## 📁 File Name for Script:
Rename your script file to:

```bash
bugarsenal.sh

