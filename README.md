# Portfolio — Ángel

Index of cybersecurity, development, and automation projects. Each entry links to its own repository with code, README, and (where applicable) full technical documentation.

> 🚧 Work in progress — some links point to repos that are still being uploaded.

---

## 🔐 Offensive security / cryptography

### [pki-tfg](https://github.com/aop24/pki-tfg)
Design and implementation of a custom Public Key Infrastructure (PKI) and three client-server secure communication models: automated X.509 certificate provisioning (C/OpenSSL), a hybrid TLS+UDP model, and end-to-end encrypted communication with DTLS 1.2 (wolfSSL).

**Stack:** C, Python, OpenSSL, wolfSSL, TCP/UDP sockets.

### [mastg-writeups](https://github.com/aop24/mastg-writeups)
Mobile security assessments following the **OWASP MASTG** methodology on public practice applications (InsecureShop, UnCrackable). Includes root detection bypass and encryption hooking with Frida.

**Stack:** JADX, Frida, ADB, Burp Suite, Android.

### [pentesting-labs](https://github.com/aop24/pentesting-labs)
Binary exploitation labs (stack canary bypass, ret2libc, NX, PIE, ASLR on 32/64-bit) and memory forensics analysis with Volatility 3 (Meterpreter detection, reflective DLL injection, registry persistence).

**Stack:** Kali Linux, GDB, pwntools, Volatility 3.

### [linpeas-casero](https://github.com/aop24/linpeas-casero)
Modular Linux post-exploitation enumeration framework built from scratch — not a clone of linPEAS, but a deliberate reimplementation of its most representative checks (SUID/SGID, cron, capabilities, sudo, Docker, kernel CVEs, NFS, LD_PRELOAD) with GTFOBins cross-referencing, severity scoring, and an `--explain` mode documenting the technical reasoning behind each finding.

**Stack:** Bash, GTFOBins.

---

## 💻 Development / own tools

### [aopgasobot](https://github.com/aop24/aopgasobot)
Telegram bot that tracks fuel prices in real time via Spain's public MINCOTUR API, with MySQL storage, scheduled tasks, and systemd deployment.

**Stack:** Python, python-telegram-bot, MySQL, APScheduler.

### [restaurant-pos](https://github.com/aop24/restaurant-pos)
LAN-based point-of-sale (POS) system for a restaurant: real-time order, table, and kitchen management.

**Stack:** FastAPI, PostgreSQL, React, Tailwind CSS.

---

## 🎓 Master's Thesis

**Design of a hybrid post-quantum PKI infrastructure** — two-plane architecture (WireGuard VPN management plane + direct mTLS data plane), C/OpenSSL client application supporting messaging, file transfer, and challenge-response modes.

*(Repo/documentation to be published after the thesis defense.)*

---

## 🧰 General stack

`C` `Python` `Kotlin` `Bash` `OpenSSL` `wolfSSL` `Frida` `Volatility 3` `FastAPI` `React` `Docker` `Burp Suite` `Metasploit`

## 📫 Contact

[LinkedIn](#) · [Email](#) · [GitHub profile](https://github.com/aop24)
