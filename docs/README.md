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

## ⭐ Stellar

**Stellar** is a program built with `Python`, `Bash`, and `Node.js` designed to improve the boring default appearance of **Termux**, giving it a fresh new look while adding new functionality.

Although it includes several command-based tools oriented toward **hacking** and **OSINT**, its primary focus is enhancing the appearance of Termux by providing multiple layers of customization.

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

> **Note:** The appearance does not change based on language.  
> Screenshots are taken from the Stellar system in Spanish.

---

## 🗃️ Documentation

- [English Documentation](https://github.com/Keiji821/Stellar/blob/master/docs/README_English.md)
- [日本語のドキュメント](https://github.com/Keiji821/Stellar/blob/master/docs/README_Japanese.md)
- [中文文檔](https://github.com/Keiji821/Stellar/blob/master/docs/README_Chinese.md)
- [한국어 문서](https://github.com/Keiji821/Stellar/blob/master/docs/README_Korean.md)
- [Portuguese Documentation](https://github.com/Keiji821/Stellar/blob/master/docs/README_Portuguese.md)

---

## 📄 Status Information

⚠️ In-program language support for **Japanese, Chinese, Korean, English, and Portuguese** is coming soon.  

⚠️ Still under active development — bugs may exist.  

📌 If you want to contribute to Stellar or report a bug, contact me on Discord: **`keiji100`**

---

## 📜 Contents

### 📑 Program Details

```text
Program Name: Stellar
Creation Date: 06/01/2024
Version: v0.0.0 (Still in development)
Program Size: 17 MB
Available Languages: Spanish only
Author: Keiji821
```

---

### 📥 Installation Steps

Follow these steps to install Stellar on Termux:

```bash
pkg update && pkg upgrade
pkg install git -y
git clone https://github.com/Keiji821/Stellar
cd Stellar
bash install.sh
```

After running `install.sh`, the Stellar installer will start.

⚠️ Make sure you have a **stable internet connection**.  
⚠️ After installation, your Termux session will restart.  
⚠️ It is recommended to **close and reopen Termux** after installation for proper **TOR** functionality.

---

### 🧩 Features

Stellar pushes `Bash` to its limits **without using Zsh** for Termux customization.

#### Features & Changes

- Customizable banner (colors and background)
- Device information table below the banner
- Security layer using **TOR**
- Custom Termux background colors
- Built-in Stellar system utilities
- Improved `termux-properties`
- Native Stellar `command-not-found`
- Fingerprint screen lock for Termux
- Termux API integration
- Default import of Termux-X11 variables

---

### 📦 APT Dependencies

```text
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

---

### 📦 PIP Dependencies

```text
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

### 🔨 Plugins

**How to use?**  
You can create your own Stellar commands in **any programming language**.  
When Stellar starts, it automatically loads all plugins.

**How to create a plugin?**  
Place your plugin inside:

```text
Stellar/plugins
```

Restart the terminal and Stellar will load it automatically.

Supported by default:
- Bash
- Python
- JavaScript

You may also use other languages by installing their compilers manually.

---

### 📀 Commands

#### SYSTEM

```bash
menu         | Show available Stellar commands
reload       | Reload system banner
user-config  | Customize banner and profile
my           | Show Stellar profile
uninstall    | Completely uninstall Stellar
update       | Update from GitHub
bash         | Restart terminal session
reset        | Reset terminal to default
x11          | Alias for termux-x11 :0 & export DISPLAY=:0
```

#### UTILITIES

```bash
ia           | AI service with free API
ia-image     | AI image generator
translator   | Real-time translation
myip         | Show public IP
passwordgen  | Generate secure passwords
encrypt-file | Encrypt files
ddos         | DDoS attack (IP + port)
```

#### OSINT

```bash
ipinfo         | IP information
urlinfo        | URL analysis
userfinder     | Username search
phoneinfo     | Phone number info
metadatainfo  | File metadata extraction
emailsearch   | Email search
instagraminfo | Instagram profile metadata
```

#### DISCORD

```bash
userinfo             | User info (ID)
serverinfo           | Server info (ID)
searchinvites        | Search invites
inviteinfo           | Analyze invites
role-mapper          | Map roles (Server ID)
mutual-servers       | Mutual servers
webhook-mass-spam    | Webhook spam
mass-delete-channels | Mass delete channels
```

---

### 📄 Usage Guide

Install Stellar and use Termux normally.

Use `user-config` to:
- Change ASCII banner
- Modify colors
- Set background images or colors

You can also switch Termux themes from dark to white or blue.

---

### 🌹 Author

```diff
+ Keiji821 (Developer)
```

For questions or collaboration, contact me on Discord:

<p align="left">
  <a href="https://discord.com/users/983476283491110932">
    <img src="https://img.shields.io/badge/Discord-Keiji-%235865F2?style=for-the-badge&logo=discord&logoColor=white">
  </a>
</p>

---

### ❤️ Donations

If you like this project and find it useful, consider supporting its development.

[![Binance Pay](https://img.shields.io/badge/Binance_Pay-Donate-F0B90B?style=for-the-badge&logo=binance&logoColor=white)](https://pay.binance.com/en)

[![PayPal](https://img.shields.io/badge/PayPal-Donate-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/felixdppdcg69)
