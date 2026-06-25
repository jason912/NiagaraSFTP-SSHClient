# NiagaraSFTP-SSHClient 🔐

[![Niagara 4.14+](https://img.shields.io/badge/Niagara-4.14%2B-blue)](https://www.tridium.com)
[![License: Trial](https://img.shields.io/badge/License-Trial%20%7C%20Commercial-orange)](LICENSE)
[![Stars](https://img.shields.io/github/stars/jason912/NiagaraSFTP-SSHClient?style=social)](https://github.com/jason912/NiagaraSFTP-SSHClient)
[![Contact](https://img.shields.io/badge/Contact-WhatsApp-brightgreen)](https://wa.me/8613801909968)
[![Website](https://img.shields.io/badge/Web-glineweb.com-lightgrey)](https://www.glineweb.com)

> **SFTP & SSH client for Niagara 4 — securely transfer files and execute remote commands from your station.**

---

<p align="center">
  <a href="mailto:jason.zhang@gline-net.com?subject=Trial%20License%20Request%20-%20NiagaraSFTP">
    <img src="https://img.shields.io/badge/GET_FREE_TRIAL-0088CC?style=for-the-badge" alt="Get Free Trial">
  </a>
  &nbsp;&nbsp;
  <a href="mailto:jason.zhang@gline-net.com?subject=Purchase%20Inquiry%20-%20NiagaraSFTP">
    <img src="https://img.shields.io/badge/PURCHASE_LICENSE-28A745?style=for-the-badge" alt="Purchase License">
  </a>
  &nbsp;&nbsp;
  <a href="https://wa.me/8613801909968?text=Hi%2C%20I%27m%20interested%20in%20NiagaraSFTP">
    <img src="https://img.shields.io/badge/CHAT_WHATSAPP-25D366?style=for-the-badge" alt="Chat WhatsApp">
  </a>
</p>

---

## What Is It?

A native Niagara 4 module that adds **SFTP file transfer** and **SSH command execution** capabilities to your station. No external tools, no scripting — just drag, drop, and configure.

### Use Cases

- 📤 **Upload** alarm logs, trend data, or reports to a remote server
- 📥 **Download** configuration files or firmware to your station
- 💻 **SSH** into Linux-based controllers to run diagnostics
- 🔄 **Automate** file synchronization between JACE and NAS

### Why SFTP Instead of FTP?

SFTP (SSH File Transfer Protocol) is **encrypted by default** and runs over a single port (22), making it firewall-friendly and secure. No need for separate FTP ports or FTPS certificates.

---

## Quick Start

### Prerequisites
- **Niagara** 4.14 or later
- **gline.pem** certificate (provided with license / trial)
- **Network** access to target SSH/SFTP server (outbound port 22)

### Steps

```bash
# 1. Install gline.pem certificate into your station trust store

# 2. Add glineSSH-rt.jar to your modules/ directory

# 3. Restart station

# 4. Create an SFTP or SSH client in Workbench:
#    - Set host, port, username, password/key
#    - For SFTP: configure local/remote paths
#    - For SSH: enter the command to execute

# 5. Trigger the client — files transfer or command runs
```

---

## Features

| Feature | SFTP Client | SSH Client |
|---------|:-----------:|:----------:|
| File upload | ✅ | — |
| File download | ✅ | — |
| Directory listing | ✅ | — |
| Remote command execution | — | ✅ |
| Key-based auth | ✅ | ✅ |
| Password auth | ✅ | ✅ |
| Retry on failure | ✅ | ✅ |
| Log output to station console | ✅ | ✅ |

---

## Pricing

| Tier | License | Price |
|:----:|---------|:-----:|
| 🆓 | **Trial** | **Free for 30 days** (per station start) |
| 🥇 | **Single Station** | **$99** |
| 🏢 | **Site Pack (5 stations)** | **$399** |

> Trial: 30 days of full functionality after each station restart.  
> Commercial licenses include 12 months of updates and email support.

---

## How to Get Started

1. **Request a Trial License** — [Email your Host ID](mailto:jason.zhang@gline-net.com?subject=Trial%20License%20Request%20-%20NiagaraSFTP) and I'll generate a free 30-day trial within 24 hours.
2. **Evaluate** — Full features, no restrictions.
3. **Buy when ready** — $99/station or $399 for 5 stations. Same-day license delivery.

---

## Requirements

| Component | Requirement |
|-----------|-------------|
| **Niagara** | 4.14 or later |
| **JAR signing** | Requires gline.pem certificate |
| **Network** | Outbound SSH (port 22) / SFTP (port 22) to target server |

---

## Documentation

| Manual | Description |
|--------|-------------|
| 📄 [User Manual](docs/User%20Manual%20Niagara%20SFTP%20%26%20SSH%20Client.pdf) | Complete setup & usage guide (196 KB) |

---

## About the Author

**Shanghai Gline Net Co., Ltd.** — Authorized Tridium Niagara Partner since 2014. We provide remote Niagara engineering, custom module development, and AI-assisted O&M services for multinational clients including **Swiss Re** and **Mitsubishi Heavy Industries**.

🌐 [www.glineweb.com](https://www.glineweb.com)

---

## Support & Contact

| Method | Details |
|--------|---------|
| 📧 **Email** | [jason.zhang@gline-net.com](mailto:jason.zhang@gline-net.com) |
| 💬 **WhatsApp** | [+86 138 0199 0968](https://wa.me/8613801909968) |
| 🌍 **Web** | [www.glineweb.com](https://www.glineweb.com) |

---

© 2026 Shanghai Gline Net Co., Ltd. All rights reserved.