# 🔍 Scan-Proxy-Ip

A powerful and efficient Python-based proxy scanner and validator that collects and checks proxies from multiple public sources. Built with a user-friendly GUI using Tkinter, it supports multi-threaded scanning for high performance.

![Python](https://img.shields.io/badge/Python-3.6%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![GUI](https://img.shields.io/badge/GUI-Tkinter-orange)

## ✨ Features

- **Multi-Source Proxy Collection**: Fetches proxies from 30+ reliable GitHub repositories
- **Multiple Protocol Support**: HTTP, HTTPS, SOCKS4, and SOCKS5 proxies
- **Multi-Threaded Scanning**: Uses concurrent threads for fast proxy validation
- **Intelligent Validation**: Checks proxy functionality against target websites
- **FreeProxy Integration**: Additional proxy discovery using FreeProxy library
- **User-Friendly GUI**: Easy-to-use interface with real-time logging
- **Customizable Settings**: Adjustable timeouts and target URLs
- **Real-time Results**: Live updates of working proxies during scanning

## 📦 Installation

### Prerequisites
- Python 3.6 or higher
- pip (Python package manager)

### Install Dependencies

```bash
pip install requests fake-useragent fp
