<p align="center">
  <kbd>
    <img src="https://i.pinimg.com/originals/02/87/d3/0287d3ba8b3330fca99f69e2001d3168.gif?semt=ais_hybrid&w=740" width="420">
  </kbd>
  <br><br>
</p>

<div align="center">

![Open Source](https://img.shields.io/badge/Open_Source-3DA639?style=for-the-badge&logo=open-source-initiative&logoColor=white)
![Maintained](https://img.shields.io/badge/Maintained-Yes-2ea44f?style=for-the-badge)

### Built With

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)
[![Node.js](https://img.shields.io/badge/JavaScript_Runtime-Node.js-yellow?style=for-the-badge&logo=javascript&logoColor=white&labelColor=000000)](https://nodejs.org/)

</div>

<div align="center">
  <img src="https://img.shields.io/badge/Stellar-6C00FF?style=for-the-badge&logo=stellar&logoColor=white&labelColor=121212">
</div>

---

# ⭐ Stellar (v2)

**Stellar** is a customization and utility framework for **Termux**, built using  
`Python`, `Bash`, and `Node.js`.

It enhances the default Termux environment by improving its appearance, adding layered personalization, and providing built-in system, OSINT, and utility tools.

Although Stellar includes commands oriented toward security and OSINT, its primary goal is to deliver a modern, customizable, and feature-rich Termux experience.

---

## 🚀 Version 2 Notice

This repository represents **Stellar v2**, a major rewrite focused on:

- Full English language support  
- Improved structure and maintainability  
- Better international accessibility  
- Cleaner documentation  

The original version of Stellar was written primarily in Spanish.  
Some sections may still be under translation as v2 development continues.

---

## 📱 In Termux

<table align="center">
  <tr>
    <td><img src="https://github.com/Keiji821/Stellar/blob/master/images/Termux1.jpg" width="500"></td>
    <td><img src="https://github.com/Keiji821/Stellar/blob/master/images/Termux2.jpg" width="500"></td>
  </tr>
</table>

## 💻 In Linux / SSH

<table align="center">
  <tr>
    <td><img src="https://github.com/Keiji821/Stellar/blob/master/images/Linux1.jpg" width="500"></td>
    <td><img src="https://github.com/Keiji821/Stellar/blob/master/images/Linux2.jpg" width="500"></td>
  </tr>
</table>

> Note: Appearance does not change with language.  
> Screenshots shown are from the Spanish interface.

---

## 🗃️ Documentation

- English Documentation  
- Japanese Documentation  
- Chinese Documentation  
- Korean Documentation  
- Portuguese Documentation  

---

## 📄 Status

⚠️ Still under active development — bugs may exist.  
⚠️ Additional language support is planned.  

📌 To report bugs or contribute, contact via Discord: `keiji100`

---

## 📑 Program Details

```
Program Name: Stellar
Version: v2 (in development)
Initial Release: 06/01/2024
Program Size: ~17 MB
Primary Language: English
```

---

## 📥 Installation (Termux)

```
pkg update && pkg upgrade
pkg install git -y
git clone https://github.com/Keiji821/Stellar
cd Stellar
bash install.sh
```

Installation notes:
- Stable internet connection required
- Termux will restart after installation
- Close and reopen Termux for proper TOR functionality

---

## 🧩 Features

Stellar maximizes Bash customization without relying on Zsh.

- Custom banner (ASCII, colors, background)
- Device information panel
- TOR-based security layer
- Custom Termux background themes
- Native Stellar utilities
- Improved termux-properties
- Custom command-not-found handler
- Fingerprint lock support
- Termux API integration
- Termux-X11 variable import

---

## 📦 Dependencies

APT:
```
python
cloudflared
tor
nmap
exiftool
nodejs
termux-api
dnsutils
lsd
x11-repo
termux-x11-nightly
root-repo
```

PIP:
```
beautifulsoup4
pyfiglet
phonenumbers
psutil
PySocks
requests
rich
rich[jupyter]
lolcat
discord
fake_useragent
pycryptodome
```

---

## 🔨 Plugins

Place plugins inside:
```
Stellar/plugins
```

Restart the terminal and Stellar will load them automatically.

Supported languages:
- Bash
- Python
- JavaScript

Other languages are supported if their compiler is installed.

---

## 📀 Commands

SYSTEM:
```
menu         | Show available commands
reload       | Reload banner
user-config  | Customize banner and profile
my           | Show Stellar profile
uninstall    | Uninstall Stellar
update       | Update from GitHub
bash         | Restart terminal
reset        | Reset terminal
x11          | Launch Termux-X11
```

UTILITIES:
```
ia           | AI service (free API)
ia-image     | AI image generator
translator   | Real-time translation
myip         | Show public IP
passwordgen  | Generate passwords
encrypt-file | Encrypt files
ddos         | DDoS attack (IP + port)
```

OSINT:
```
ipinfo
urlinfo
userfinder
phoneinfo
metadatainfo
emailsearch
instagraminfo
```

DISCORD:
```
userinfo
serverinfo
searchinvites
inviteinfo
role-mapper
mutual-servers
webhook-mass-spam
mass-delete-channels
```

---

## 📄 Usage

Install Stellar and use Termux normally.

Use `user-config` to:
- Change ASCII banner
- Adjust colors
- Switch background themes

---

## 👤 Maintainers

Keiji821 — Original Creator  
Dev Malvryx — Maintainer & v2 Rewrite (English Support)

---

## ❤️ Donations

If you find Stellar useful, consider supporting development.

Binance Pay  
PayPal
