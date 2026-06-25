# NiagaraSFTP-SSHClient 🔐

[![Niagara 4.14+](https://img.shields.io/badge/Niagara-4.14%2B-blue)](https://www.tridium.com)
[![License: Trial](https://img.shields.io/badge/License-Trial%20%7C%20Commercial-orange)](LICENSE)
[![Contact](https://img.shields.io/badge/Contact-WhatsApp-brightgreen)](https://wa.me/8613801909968)

> **SFTP & SSH client for Niagara 4 — securely transfer files and execute remote commands from your station.**

---

## What Is It?

A native Niagara 4 module that adds **SFTP file transfer** and **SSH command execution** capabilities to your station. No external tools, no scripting — just drag, drop, and configure.

### Use Cases

- **Upload** alarm logs, trend data, or reports to a remote server
- **Download** configuration files or firmware to your station
- **SSH** into Linux-based controllers to run diagnostics
- **Automate** file synchronization between JACE and NAS

---

## Quick Start

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
| [User Manual](docs/User%20Manual%20Niagara%20SFTP%20%26%20SSH%20Client.pdf) | Complete setup and usage guide |

---

## Support & Contact

- **Email**: [jason.zhang@gline-net.com](mailto:jason.zhang@gline-net.com)
- **WhatsApp**: [+86 138 0199 0968](https://wa.me/8613801909968)

**Shanghai Gline Net Co., Ltd.** — Your Partner in Smarter Automation

---

© 2026 Shanghai Gline Net Co., Ltd. All rights reserved.
