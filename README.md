# 🔥 recon-automator

[![GitHub Action](https://github.com/Falconmx1/recon-automator/actions/workflows/recon.yml/badge.svg)](https://github.com/Falconmx1/recon-automator/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🎯 Automated Bug Bounty Reconnaissance

**recon-automator** is a powerful, CI/CD-ready reconnaissance framework for Bug Bounty hunters. It automates the entire recon pipeline with GitHub Actions.

### ✨ Features

- 🔍 **Subdomain Discovery** - Subfinder, Assetfinder, Amass
- 🏓 **HTTP Probing** - httpx with tech detection
- 🔬 **Port Scanning** - Nmap with service detection
- 💥 **Vulnerability Scanning** - Nuclei with 4000+ templates
- 📸 **Screenshots** - gowitness for visual inspection
- 📢 **Notifications** - Discord/Slack/Telegram integration
- 📦 **Artifacts** - Automatic result storage

### 🚀 Quick Start

1. Fork this repository
2. Add your target domain in GitHub Actions → Run workflow
3. Get results in the Actions artifacts

### 📋 Manual Usage

```bash
git clone https://github.com/Falconmx1/recon-automator
cd recon-automator
make install
make recon DOMAIN=example.com
