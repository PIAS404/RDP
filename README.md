# RDP Setup Toolkit 🖥️🔐

A lightweight toolkit to help you **set up and manage a Remote Desktop (RDP) environment** for **development/testing** purposes.  
Includes setup notes, automation scripts (optional), and basic security hardening tips.

> ⚠️ **Disclaimer:** Use only on systems you own or have explicit permission to manage.  
> This repo is for **legitimate** remote access, administration, and learning.

----

## ✨ Features

- ✅ Quick RDP environment setup guide  
- ✅ Optional automation scripts (PowerShell/Bash)  
- ✅ Firewall + port configuration notes  
- ✅ Basic security hardening checklist  
- ✅ Troubleshooting tips for common RDP issues  

---

## 📌 Requirements

- A Windows machine / VM (recommended for RDP server side)
- Admin access (local or cloud VM)
- Stable internet connection

---

## 🚀 Quick Start

### 1) Enable Remote Desktop (Windows)
1. Open **Settings**
2. Go to **System → Remote Desktop**
3. Turn **Remote Desktop ON**
4. Add allowed users if needed

### 2) Allow RDP in Firewall
Make sure **Remote Desktop** rule is allowed in Windows Firewall.

### 3) Connect from Client
Use:
- Windows: **Remote Desktop Connection (mstsc)**
- macOS: **Microsoft Remote Desktop**
- Android: **Microsoft Remote Desktop**

---

## 🔒 Security Tips (Highly Recommended)

- ✅ Use a **strong password**
- ✅ Enable **Network Level Authentication (NLA)**
- ✅ Use **VPN** or restrict IPs if possible
- ✅ Keep Windows updated
- ✅ Change default port only if you understand implications
- ✅ Disable unnecessary accounts / services

---

## 🧰 Scripts (Optional)

If this repo includes scripts, run them carefully:

### PowerShell
```powershell
# Example
# Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
# .\scripts\setup-rdp.ps1
