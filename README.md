# 🔒 ProxyVault

<p align="center">
  <img src="https://img.shields.io/badge/Made%20by-Dark%20Vibez-blueviolet?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Python-3.7%2B-blue?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/Platform-Termux%20%7C%20Linux-black?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Proxies-HTTP%20%7C%20SOCKS4%20%7C%20SOCKS5-cyan?style=for-the-badge"/>
</p>

<p align="center">
  <b>Professional Proxy Scraper & Checker — Fast, Free, No API Key</b>
</p>

---

## ⚡ Features

- 🌐 Scrape HTTP, HTTPS, SOCKS4, SOCKS5 proxies from multiple sources
- ✅ Live proxy checker with latency measurement
- 🗺️ Country detection with flag for every proxy
- 🧵 Multi-threaded — blazing fast
- 💾 Export results to `.txt` file
- 📋 Load proxies from your own file
- 🎨 Clean color terminal UI
- 📱 Works perfectly on **Termux**

---

## 📦 Installation

### Termux
```bash
pkg install python
pip install requests
python proxyvault.py
```

### Linux / Kali
```bash
pip install requests
python3 proxyvault.py
```

---

## 🚀 Usage

```
[1] Scrape & Show Proxies   (no check)
[2] Scrape + Live Check     (verified, slower)
[3] Load from file & Check
[4] Export last results
[0] Exit
```

---

## 📸 Preview

```
██████╗ ██████╗  ██████╗ ██╗  ██╗██╗   ██╗
██╔══██╗██╔══██╗██╔═══██╗╚██╗██╔╝╚██╗ ██╔╝
██████╔╝██████╔╝██║   ██║ ╚███╔╝  ╚████╔╝
...

  #    IP              PORT    TYPE     LATENCY  COUNTRY
  ────────────────────────────────────────────────────
   1   103.xx.xx.xx   8080    HTTP      312ms   🇺🇸 United States
   2   45.xx.xx.xx    1080    SOCKS5    489ms   🇩🇪 Germany
```

---

## ⚙️ Options

| Option | Description |
|--------|-------------|
| Type Filter | HTTP / HTTPS / SOCKS4 / SOCKS5 / All |
| Limit | Max proxies to fetch |
| Threads | Concurrent check threads (default 50) |
| Export | Save to `.txt` |

---

## 📋 Requirements

```
Python 3.7+
requests
```

---

## ⚠️ Disclaimer

> This tool is for **educational purposes only**.  
> Use responsibly and only on networks you have permission to access.  
> The author is not responsible for any misuse.

---

## 👤 Author

**Dark Vibez**  
> *"Stay anonymous, stay safe."*

---

<p align="center">⭐ Star this repo if you like it!</p>

