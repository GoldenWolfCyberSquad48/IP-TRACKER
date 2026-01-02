# 🐺 Golden Wolf Cyber Squad – IP Tracker Tool

Dark Hacker IP Console
Track IP address information directly from the terminal using Kali Linux.

⚠️ Educational Purpose Only
Do not use this tool for illegal or unauthorized activities.

---

<p align="center">
  <img src="image.interface.png" alt="My Kali Linux Setup" width="800">
</p>
<p align="center">
  <img src="image.Rename Screenshot_2026-01-02_21_06_16.png to interface.png" alt="My Kali Linux Setup" width="800">
</p>


# IP-TRACKER Setup  Guide

<div align="center" style="border: 2px solid #444; padding: 12px; margin: 15px 0; background-color: #111;">
  <strong>Estimated Setup Time:</strong> ~5 minute
</div>

---

# ✨ Features

• Fast IP information lookup

• Clean and hacker-style terminal interface

• Uses ipinfo.io API

• Lightweight and easy to use

• Designed for Kali Linux

##🖥️ Supported Operating Systems

• Kali Linux

• Ubuntu

• Debian-based Linux distributions
 

## 🔧 Installation & Usage (Step by Step)
## 📚 Table of Contents

1. [SUpdate & Upgrade Kali Linux](#1-system-update--upgrade)
2. [Install Required Packages](#2-Install-Required-Packages)
3. [Verify Installed Tools](#3-Verify-Installed-Tools)
4. [Clone the Repository](#4-Clone-the-Repository)
   - [Remove Default Home Directories](#41-remove-default-home-directories)
   - [CTF Workspace Setup](#42-ctf-workspace-setup)
   - [Disable Lock Screen](#43-disable-lock-screen)
   - [Regenerate SSH Keys](#44-regenerate-ssh-keys)
   - [Configure DNS Servers](#45-configure-dns-servers)
   - [Enable Autologin](#46-enable-autologin)
5. [Give Execute Permission](#5-Give-Execute-Permission)
6. [Run the Tool](#6-Run-the-Tool)
## 🧑‍💻 Developer
Golden Wolf Cyber Squad
🔐 Ethical Hacking | Cyber Security | OSINT

⚠️ Disclaimer

This tool is created strictly for educational purposes only.
The developer is not responsible for any misuse or illegal activities.

⭐ Support

If you like this project, don’t forget to ⭐ star the repository on GitHub.

---

## 1. SUpdate & Upgrade Kali Linux

Always start with an updated system.

```bash
sudo apt update && sudo apt upgrade -y

## 2. Install Required Packages

Always start with an updated system.

```bash
sudo apt install chafa jq curl whois traceroute -y

## 3. Verify Installed Tools

Always start with an updated system.

```bash
chafa --version
jq --version

## 4. Clone the Repository

Always start with an updated system.

```bash
git clone https://github.com/YOUR-USERNAME/ip-tracker4.git
cd ip-tracker4

## 5. Give Execute Permission

Always start with an updated system.

```bash
chmod +x ip-tracker4.sh

## 6. Run the Tool

Always start with an updated system.

```bash
./ip-tracker4.sh
