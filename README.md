## 🌐 Network-Usage - Server Network Monitor
<p align="center">
  <img src="https://img.shields.io/badge/OS-Linux-ff69b4.svg" alt="OS: Linux"/>
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License: MIT"/>
  <img src="https://img.shields.io/github/contributors/pynoxi/Network-Usage.svg" alt="Contributors"/>
  <img src="https://img.shields.io/badge/Language-Bash-lightgrey.svg" alt="Language: Bash"/>
</p>
<p align="center">
  <img src="https://img.shields.io/github/stars/pynoxi/Network-Usage.svg?style=social&label=Stars" alt="GitHub stars"/>
  <img src="https://img.shields.io/github/forks/pynoxi/Network-Usage.svg?style=social&label=Forks" alt="GitHub forks"/>
</p>

## Preview
![Network Usage Preview](https://forum.pynoxi.com/assets/files/2025-10-08/1759945097-693439-image.png)

**Network-Usage** is a lightweight, terminal-based network monitor for Linux VPS, powered by XenDns.  
It displays **real-time download/upload speeds**, **total data usage** in GB, and provides a **stylish live dashboard** with zero flicker.

---

## 🔹 Features

- Auto-detects active network interface (eth0, ens160, enp0s3, etc.)
- Displays:
  - Live download/upload speed (MB/s)
  - Total download/upload (GB)
  - Total usage (GB)
  - Timestamp
- Stylish PyNoxi terminal UI
- Works smoothly without terminal flicker
- Supports **any Linux VPS** terminal (SSH)

---

## 💻 Supported Linux Distributions

- Ubuntu 18.04 / 20.04 / 22.04
- Debian 9 / 10 / 11
- CentOS 7 / 8 / Stream
- Rocky Linux / AlmaLinux
- Any Linux system with:
  - Bash
  - `bc` installed
  - `/sys/class/net/` access for network stats

---

## ⚙️ Installation

### Method 1: One-line installer (no clone needed)

You can run the script directly without downloading or cloning the repo:

```bash
bash <(curl -s https://raw.githubusercontent.com/xendns/Network-Usage/refs/heads/main/Network-Usage)
```
This will fetch and run the latest version from the GitHub repository automatically.

---
### Method 2: Git clone (manual installation)
#### 1. Clone the repository
```bash
git clone https://github.com/xendns/Network-Usage.git && cd Network-Usage
```
#### 2. Make the script executable
```bash
chmod +x Network-Usage
```
#### 3. Run the script
```bash
bash Network-Usage
```
---

## 🚀 Usage
- Press `Ctrl+C` to stop monitoring.
- Script automatically detects the active network interface If none found, it shows a friendly error message with a link to [PyNoxi Forum](https://forum.Xendns.com "XenDns Forum")

## 💡 Manual Steps
- Ensure Bash is installed (`bash --version`)
- Ensure `bc` is installed for floating point calculations.
- Run the script using either Method 1 or Method 2.
- Enjoy real-time network stats on your VPS.

## 📜 License
- MIT License © 2025 PyNoxi
- See [LICENSE](https://github.com/xendns/Network-Usage/blob/main/LICENSE "LICENSE") for details.

## 🔗 Links

Website: [https://xendns.com](https://xendns.com "https://pynoxi.com")

Forum: [https://forum.xendns.com](https://forum.xendns.com "https://forum.xendns.com")

GitHub Repo: [Network-Usage](https://github.com/xendns/Network-Usage "Network-Usage")
