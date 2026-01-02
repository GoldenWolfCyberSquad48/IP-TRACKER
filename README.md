# kali-linux-hacker-setup-scripts

A comprehensive guide to setting up and optimizing **Kali Linux** for **ethical hacking, CTFs, and cybersecurity**.  
This repository includes essential commands, scripts, tools, and configurations for a smooth and professional hacking environment.

---

![my_kali_linux_setup](https://github.com/user-attachments/assets/a64bcd44-2c84-4044-8dad-43ea24e3fd6a)

# Kali Linux Setup and Optimization Guide

<div align="center" style="border: 2px solid #444; padding: 12px; margin: 15px 0; background-color: #111;">
  <strong>Estimated Setup Time:</strong> ~2 hours
</div>

Welcome to the **Kali Linux Setup and Optimization Guide**.  
This guide is designed for **beginners and advanced users** who want a clean, fast, and efficient Kali Linux setup for hacking, penetration testing, and CTF challenges.

---

## 📚 Table of Contents

1. [System Update & Upgrade](#1-system-update--upgrade)
2. [Change Hostname](#2-change-hostname)
3. [Configure Kali Repositories](#3-configure-kali-repositories)
4. [Essential Tweaks for Hackers](#4-essential-tweaks-for-hackers)
   - [Remove Default Home Directories](#41-remove-default-home-directories)
   - [CTF Workspace Setup](#42-ctf-workspace-setup)
   - [Disable Lock Screen](#43-disable-lock-screen)
   - [Regenerate SSH Keys](#44-regenerate-ssh-keys)
   - [Configure DNS Servers](#45-configure-dns-servers)
   - [Enable Autologin](#46-enable-autologin)
5. [Essential Packages Installation](#5-essential-packages-installation)
6. [Aliases & Productivity Shortcuts](#6-aliases--productivity-shortcuts)
7. [Conclusion](#conclusion)

---

## 1. System Update & Upgrade

Always start with an updated system.

```bash
sudo apt update && sudo apt upgrade -y
