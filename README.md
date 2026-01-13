# En0wn – Windows Privilege Escalation Lab

A vulnerable Windows virtual machine created as a **free alternative to the Devel machine from Hack The Box**, focused on Windows privilege escalation practice.

---

## 📖 Overview

**En0wn** is a vulnerable Windows VM built for learning and practicing **Windows enumeration and local privilege escalation** techniques.

I created this machine while preparing for the **PNPT exam**, specifically the **Windows Privilege Escalation** section, after realizing that the original Devel machine from Hack The Box requires a paid subscription.  
The goal was to recreate the **same learning experience and attack paths** and make it freely available to the community.

---

## 🎯 Purpose

This lab is intended for practicing:

- Windows Privilege Escalation  
- PNPT preparation  
- OSCP / OCSP-style labs  
- Windows enumeration & exploitation  
- Local privilege escalation techniques  

---

## 🧪 Difficulty

**Beginner → Intermediate**

---

## 🧩 Prerequisites

Before starting, make sure you have:

- VMware Workstation / Player **or** VirtualBox  
- At least **4 GB RAM** available  
- **10 GB** of free disk space  
- Kali Linux or any other pentesting OS  

---

## 📚 What You’ll Learn

By completing this lab, you will practice:

- ✅ Network reconnaissance with **Nmap**
- ✅ FTP enumeration and exploitation
- ✅ Web shell upload techniques
- ✅ Reverse shell handling with **Metasploit**
- ✅ Windows privilege escalation using **MS10-015 (KiTrap0d)**
- ✅ Post-exploitation and flag hunting

---

## 💻 System Specifications

OS: Windows 7 Ultimate (Build 7600)
Architecture: 32-bit (x86)
Service Pack: None
Hotfixes: None
Web Server: Microsoft IIS 7.5
FTP Server: Microsoft FTP Service
Network Mode: NAT / Host-Only (192.168.x.x)
Credentials: user / password


---

## ⚙️ Setup Instructions

1. Download the VM from the link below  
2. Import it into **VirtualBox** or **VMware**  
3. Configure networking as **NAT** or **Host-Only**  
4. Start the machine and begin enumeration  

---

## ⬇️ Download

Due to file size limitations, the VM is hosted externally.

🔗 **Download link (OneDrive):**  
👉 https://1drv.ms/u/c/0d3c80175fe24837/IQB6335j2UkxQ7FXRW-k-tzvARrv4sUkM3NtLE-fi0TOLfA?e=beEJgi

---

## 🏁 Flags

There are **2 flags** to capture:

- 🧑 **User Flag:**  
  `C:\Users\user\Desktop\user.txt`

- 👑 **Root Flag:**  
  `C:\Users\Administrator\Desktop\root.txt`
---

## ⚠️ Disclaimer

This virtual machine is intended **for educational purposes only**.  
Do **not** use the techniques learned here on systems you do not own or have explicit permission to test.

---

## 🤝 Contributions

Contributions and feedback are welcome!

- Bug reports  
- Improvements  
- Writeups  
- Fixes  

Feel free to open an **issue** or **pull request** 🚀

---

## 📜 Credits

Inspired by:
- Hack The Box – Devel  
- TCM Security Academy  

Created by **Enes Ismaili**
