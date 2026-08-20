# Portfolio — Ángel

Index of cybersecurity, development, and automation projects. Each entry links to its own repository with code, README, and (where applicable) full technical documentation.

---

## 🔐 Offensive security / cryptography

### [pki-tfg](https://github.com/aop24/pki-tfg)
Design and implementation of a custom Public Key Infrastructure (PKI) and three client-server secure communication models: automated X.509 certificate provisioning (C/OpenSSL), a hybrid TLS+UDP model, and end-to-end encrypted communication with DTLS 1.2 (wolfSSL).

**Stack:** C, Python, OpenSSL, wolfSSL, TCP/UDP sockets.

### [mobile-sec-toolkit](https://github.com/aop24/mobile-sec-toolkit)
Python toolkit for static, MASTG-aligned APK analysis and Frida-based dynamic bypass — automates common checks from the OWASP Mobile Application Security Testing Guide (permissions, hardcoded secrets, insecure storage, root/SSL-pinning bypass scripting).

**Stack:** Python, JADX, Frida, ADB.

### [linpeas](https://github.com/aop24/linpeas)
Modular Linux post-exploitation enumeration framework built from scratch — not a clone of linPEAS, but a deliberate reimplementation of its most representative checks (SUID/SGID, cron, capabilities, sudo, Docker, kernel CVEs, NFS, LD_PRELOAD) with GTFOBins cross-referencing, severity scoring, and an `--explain` mode documenting the technical reasoning behind each finding.

**Stack:** Bash, GTFOBins.

### [nmap-vuln-scanner](https://github.com/aop24/nmap-vuln-scanner)
Nmap automation tool: port discovery + version detection, then vulnerability matching across three layers — a hand-curated CVE database with exploitability context, live queries to the official NVD API by CPE (with local caching and rate-limiting), and optional Exploit-DB lookups via searchsploit. Includes a banner-only decoy lab for testing detections end-to-end without installing real vulnerable software.

**Stack:** Python (stdlib only), nmap, NVD API.

---

## 💻 Development / own tools

### [bot-gasolina](https://github.com/aop24/bot-gasolina)
Telegram bot that tracks fuel prices in real time via Spain's public MINCOTUR API, with MySQL storage, scheduled tasks, and systemd deployment.

**Stack:** Python, python-telegram-bot, MySQL, APScheduler.

---

## 🎓 Master's Thesis

**Design of a hybrid post-quantum PKI infrastructure** — two-plane architecture (WireGuard VPN management plane + direct mTLS data plane), C/OpenSSL client application supporting messaging, file transfer, and challenge-response modes.

*(Repo/documentation to be published after the thesis defense.)*

---

## 🧰 General stack

`C` `Python` `Kotlin` `Bash` `OpenSSL` `wolfSSL` `Frida` `Volatility 3` `Docker` `Burp Suite` `Nmap`

## 📫 Contact

[LinkedIn](https://www.linkedin.com/in/%C3%A1ngel-olivares-perona-516681253/) · [Email](mailto:angelolivares305@gmail.com) · [GitHub profile](https://github.com/aop24)
