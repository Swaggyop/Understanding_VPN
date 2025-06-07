# 🔐 VPN Setup & Privacy Analysis Lab Report

## 📝 Overview

This project documents a complete hands-on VPN lab activity using **ProtonVPN**, focused on IP masking, encryption testing, traffic verification, speed comparison, and VPN technology research. The aim is to understand how VPNs work, how they protect privacy, and what their strengths and weaknesses are.

---

## 📌 Objectives

- Connect to a secure VPN server
- Verify IP address masking
- Confirm encrypted web traffic
- Measure browsing speed differences
- Analyze VPN encryption and privacy protocols
- Summarize the benefits and limitations of VPNs

---

## 🧭 Step-by-Step Procedure

### 1️⃣ Choose a Reputable Free VPN Service

- Selected: **Proton VPN**
- Why?
  - Strict no-logs policy
  - Swiss jurisdiction (strong privacy laws)
  - Transparent and open-source
  - Trusted by cybersecurity professionals
- Signed up using email via [https://protonvpn.com](https://protonvpn.com)

---

### 2️⃣ Download and Install the VPN Client

- Downloaded ProtonVPN for **Windows**
- Installed from the official site
- Logged in with credentials after installation
- Interface opened with global server list

---

### 3️⃣ Connect to a VPN Server

- Connected to: **Poland Free Server #13** (`PL-FREE#13`)
- Connection Status: ✅ Connected
- Displayed:
  - Real-time traffic graphs
  - Server info (IP, location, uptime)
  - Secure tunnel confirmation

---

### 4️⃣ Verify IP Address Change

- Tool Used: [https://whatismyipaddress.com](https://whatismyipaddress.com)
- **Before VPN**:  
  - IP: `103.177.174.127`  
  - Location: India  
- **After VPN**:  
  - IP: `149.102.244.113`  
  - Location: Warsaw, Mazowieckie, Poland  
  - Hostname: `pl-free-13.protonvpn.net`  
  - ISP: **DataCamp Limited**  
✅ IP successfully masked and routed through Poland.

---

### 5️⃣ Confirm Encrypted Web Traffic

- Visited: [https://www.wikipedia.org](https://www.wikipedia.org)
- Checked browser lock icon
- Verified details:
  - HTTPS enabled
  - TLS Version: **1.3**
  - Certificate Issuer: **GlobalSign**

✅ Encrypted end-to-end communication verified.

---

### 6️⃣ Disconnect VPN & Compare Speed/IP

#### IP Status:
- **Before VPN**: `103.177.174.127` (India)
- **During VPN**: `149.102.244.113` (Poland)
- **After VPN Disconnect**: Indian IP returned

#### Speed Comparison:
| Status            | Download Speed (Mbps) | Upload Speed (Mbps) |
|-------------------|------------------------|-----------------------|
| Before VPN        | 93.52                  | 69.38                 |
| During VPN (Poland)| 80.05                 | 68.09                 |

- Speed dropped due to:
  - Geographic distance from Poland
  - Free server congestion

✅ Browsing was slower while on VPN but functional. Restored to high speed after disconnect.

---

## 🔐 Research on VPN Encryption & Privacy Features

### 🔸 **Encryption Techniques**

- **AES-256 Bit Encryption**  
  - Industry-standard, military-grade
  - Impossible to brute-force

- **RSA Encryption (2048–4096-bit)**  
  - Secures key exchanges between your device and the VPN

- **Perfect Forward Secrecy (PFS)**  
  - Generates a new encryption key per session
  - Prevents past/future data compromise

---

### 🔸 **VPN Protocols Used**

| Protocol     | Description |
|--------------|-------------|
| **OpenVPN**  | Secure and flexible (used by ProtonVPN) |
| **WireGuard**| Modern, fast, lightweight protocol |
| **IKEv2/IPSec** | Great for mobile connections and roaming |

---

### 🔸 **Privacy Features in ProtonVPN**

- ✅ **IP Address Masking**
- ✅ **No Logs Policy**
- ✅ **DNS Leak Protection**
- ✅ **Kill Switch**
- ✅ **Split Tunneling**

---

## ✅ Benefits of VPNs

1. **Anonymous Browsing**
2. **Encrypted Web Traffic**
3. **Public Wi-Fi Protection**
4. **Bypass Geo-blocks & Firewalls**
5. **Prevent ISP Tracking**
6. **Use of Advanced Security Protocols**

---

## ⚠️ Limitations of VPNs

1. **Slight Speed Reduction**
2. **Limited Access in Free Plans**
3. **May Be Blocked by Some Websites**
4. **Cannot Prevent Phishing or Malware**
5. **Illegal in Some Countries**

---

## 📸 Screenshots Folder Includes:

- VPN Client UI (before & after connection)
- IP Change Verification via WhatIsMyIPAddress
- Browser TLS/HTTPS Confirmation
- Speed test before/after VPN

---

## 🙋 Author

**Saswat**  
Student of BCA – Cybersecurity & Forensics  
🛡️ Passionate about network security & ethical hacking  
🎯 Goal: To become a cybersecurity analyst skilled in encryption, privacy, and threat management

---

