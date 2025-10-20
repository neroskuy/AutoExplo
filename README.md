<p align="center">
  <img src="https://raw.githubusercontent.com/neroskuy/AutoExplo/refs/heads/main/explo.jpg
" width="800" height="400" alt="auto explo jpg" />
</p>
# 🚀 AUTOEXPLO SCANNER
Tool ini dibuat untuk scanning berbagai **vulnerability** & **misconfiguration** secara otomatis dari daftar target.  
⚠️ Gunakan hanya untuk **edukasi, riset, atau lab pribadi** – bukan untuk tujuan ilegal.

---

## 📌 Fitur Utama
- Multi-scan terhadap target (domain/IP) untuk mencari bug dan konfigurasi rentan.
- Scan cepat dan efisien via multi-threading.
- Hasil scan tersimpan otomatis ke folder `result/`.

---

## 🎯 Target Scan (Vuln/Exploit Modules)

Berikut daftar **modul scanning** yang aktif:
- `sketch` — Check untuk Sketch File exposure  
- `alfa` — CMS Alfa Scan  
- `rsf` — RSF Panel Exposure  
- `upsc` — Upload Shell Checker  
- `rfm` — Responsive File Manager  
- `kcf` — KCFinder Vulnerability  
- `tatsu` — Tatsu Page Builder RCE  
- `sftpc` — FTP Config / File Disclosure  
- `lconfig` — Laravel Config Leak  
- `env` — .env File Disclosure  
- `phpunit` — PHPUnit RCE  
- `lms` — Learning Management System Exposure  
- `bdp` — Backup Database Finder  
- `wpfm` — WP File Manager Exploit  
- `wpins` — WP Install Leak  
- `dzs` — DZS Videogallery Exploit  
- `debug` — Debug Mode Exposure  

---

## 🔧 Cara Install & Setup
### 1. Clone Repository
```bash
git clone https://github.com/username/autoexplo-scanner.git
cd autoexplo-scanner

2. Install Python
Pastikan Python 3.8+ sudah terinstall:
python3 --version

Linux (Ubuntu/Debian)
sudo apt update && sudo apt upgrade -y
sudo apt install python3 python3-pip git -y

🔹 Termux (Android)
pkg update && pkg upgrade -y
pkg install python git -y
pip install --upgrade pip

3. Install Modul Python
pip install requests beautifulsoup4 colorama urllib3
python3 autoexplo.py list.txt
