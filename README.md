En0wn – Windows Privilege Escalation Lab

En0wn is a vulnerable Windows virtual machine created as a free alternative to the Devel machine from Hack The Box.

I built this VM while preparing for the PNPT exam, specifically the Windows Privilege Escalation section, after realizing that the original Devel machine requires a paid subscription.
The goal was to recreate the same learning experience and attack paths and make it available to everyone.

🎯 Purpose

This machine is designed for practicing:

Windows Privilege Escalation

PNPT preparation

OSCP / OCSP-style labs

Windows enumeration & exploitation

Local privilege escalation techniques

🧪 Lab Difficulty

Beginner → Intermediate

🧩 Prerequisites

Before starting, make sure you have:

VMware Workstation / Player or VirtualBox

At least 4 GB RAM available

10 GB of free disk space

Kali Linux or any other pentesting OS

📚 What You’ll Learn

By completing this lab, you will practice:

✅ Network reconnaissance with Nmap

✅ FTP enumeration and exploitation

✅ Web shell upload techniques

✅ Reverse shell handling with Metasploit

✅ Windows privilege escalation using MS10-015 (KiTrap0d)

✅ Post-exploitation and flag hunting

💻 System Specifications
OS:            Windows 7 Ultimate (Build 7600)
Architecture:  32-bit (x86)
Service Pack:  None
Hotfixes:      None
Web Server:    Microsoft IIS 7.5
FTP Server:    Microsoft FTP Service
Network Mode:  NAT / Host-Only (192.168.x.x)
Credentials:   user / password

🖥️ Machine Details

OS: Windows

Entry Point: FTP / Web

Focus: Local Privilege Escalation

Intended for: Practice & education only

⬇️ Download

The VM is hosted externally due to file size limitations.

🔗 Download link (OneDrive):
👉 https://1drv.ms/u/c/0d3c80175fe24837/IQB6335j2UkxQ7FXRW-k-tzvARrv4sUkM3NtLE-fi0TOLfA?e=beEJgi

Import the VM into VirtualBox or VMware.

⚙️ Setup Instructions

Download the VM from the link above

Import it into VirtualBox / VMware

Use NAT or Host-Only networking

Start the machine and begin enumeration

🏁 Flags

There are 2 flags to capture:

🧑 User Flag:
C:\Users\user\Desktop\user.txt

👑 Root Flag:
C:\Users\Administrator\Desktop\root.txt

No spoilers here 😉
Enumeration is key.

⚠️ Disclaimer

This virtual machine is intended for educational purposes only.
Do not use the techniques learned here on systems you do not own or have explicit permission to test.

🤝 Contributions & Feedback

If you find issues, have suggestions, or want to add:

Improvements

Writeups

Fixes

Feel free to open an issue or pull request 🚀

📜 Credits

Inspired by:

Hack The Box – Devel

TCM Security Academy

Created by Enes Ismaili
