# 🕵️‍♂️ Ghostfox‑CloudIP Toolkit

![GitHub repo size](https://img.shields.io/github/repo-size/ghostfox121/GHOST-TECH)
![GitHub](https://img.shields.io/github/license/ghostfox121/GHOST-TECH)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20Kali%20%7C%20Ubuntu-informational)
![Made by](https://img.shields.io/badge/Made%20by-Ghostfox-ff69b4)

> An anonymity and recon toolkit to detect real IPs behind Cloudflare, rotate identities with Tor, spoof MAC addresses, and automate private threat recon.

---

## ⚙️ Features

- 🌐 Reveal real IP behind Cloudflare using multiple techniques
- 🧅 Auto-start Tor and verify connection
- 🛡️ MAC address spoofing
- 🧰 Recon Tools (Shodan lookup, DNS, etc.)
- 🖥️ GUI and CLI versions
- 📦 .deb Installer for easy Linux deployment
- 🖼️ Custom icon and branded GUI
- 📄 Output folder for logs and report files

---

## 🚀 Installation

### 📥 Using .deb (Debian/Kali/Ubuntu):
`bash
sudo dpkg -i ghostfox-cloudip_1.0_all.deb
sudo apt-get install -f

## 🐍 From Source:

## git clone https://github.com/ghostfox121/GHOST-TECH.git 
## cd GHOST-TECH/ghostfox-cloudip 
## pip install -r requirements.txt

---

## 🧪 Usage
## 🖥️ Launch GUI
## ghostfox-cloudip

## 🔧 CLI
## python3 ghostfox_main.py

---

## 🔍 Example Screenshot


---

## 🧠 Notes

## Ensure Tor is installed:
## sudo apt install tor 
## You can test if Tor is running:
## service tor status 

---

## 🔐 Shodan API Setup
## Edit the config.json file:
## { "shodan_api_key": "YOUR_API_KEY_HERE" } 
## Register for an API key here: https://account.shodan.io/

---

## 📁 Output
## All reports are saved to:
## ghostfox-cloudip/output/ 
## To delete:
## rm -rf ghostfox-cloudip/output/ 
---
## 🧑‍💻 Author
## Made by Ghostfox
## Telegram: @ghostfoxx

---
## 🪪 License
## MIT License
--- 
### ✅ To Add It: 
#### Option A — Web Interface: 
## 1. Go to your GitHub repo 
## 2. Click `ghostfox-cloudip/` 
## 3. Click `Add File` → `Create new file` 
## 4. Name it `README.md` 
## 5. Paste the content above 
## 6. Click **Commit** 

#### Option B — Local Git: 
## Replace your `README.md` with the above, then: 
## git add README.md git commit -m "Add full project 
## README" git push origin main
