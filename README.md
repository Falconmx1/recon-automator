# 🔥 recon-automator

[![GitHub Actions](https://github.com/Falconmx1/recon-automator/actions/workflows/recon.yml/badge.svg)](https://github.com/Falconmx1/recon-automator/actions)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## 🎯 Bug Bounty Recon Automator

Herramienta automatizada de reconocimiento para Bug Bounty con GitHub Actions.

### ⚡ Características

- 🔍 **Subdomain Discovery** (Subfinder + Assetfinder + Amass)
- 🏓 **HTTP Probing** (httpx con detección de tecnologías)
- 🔬 **Port Scanning** (Nmap top 100 puertos)
- 💥 **Vulnerability Scan** (Nuclei 4000+ templates)
- 📸 **Screenshots** (gowitness)
- 📊 **Reportes automáticos**
- 📦 **Artifacts descargables**

### 🚀 Cómo usarlo

1. Ve a la pestaña **Actions**
2. Selecciona **"🔥 Bug Bounty AutoRecon"**
3. Haz clic en **"Run workflow"**
4. Ingresa el dominio objetivo (ej: `ejemplo.com`)
5. Espera los resultados (5-15 minutos)

### 📥 Resultados

Después del scan, descarga el artifact:
- `all_subs.txt` - Todos los subdominios
- `alive.txt` - Hosts con HTTP/HTTPS activo
- `nmap_scan.xml` - Puertos abiertos
- `nuclei_results.txt` - Vulnerabilidades encontradas
- `screenshots.zip` - Capturas de pantalla

### 🔧 Configuración avanzada

Para notificaciones a Discord, añade en **Settings → Secrets**:
