# 🛡️ Cyber Security Portfolio

## 📚 1. Dasar Cyber Security: CIA Triad

Memahami prinsip dasar keamanan informasi yang menjadi fondasi dalam dunia cyber security, yaitu:
- 🔒 **Confidentiality** – Menjaga kerahasiaan data
- ✅ **Integrity** – Menjamin keutuhan dan keakuratan data
- 🕒 **Availability** – Memastikan data dan sistem tersedia saat dibutuhkan
- 
Studi ini menjadi dasar saya dalam memahami pentingnya setiap aspek pengamanan dalam praktik nyata seperti web security, network monitoring, dan forensik log.

📁 Folder: `pemahaman_dasar_cyber_security`

## 💥 2. Web Exploitation & Payload Testing
Melakukan eksplorasi dan percobaan payload terhadap aplikasi web lokal untuk memahami jenis-jenis serangan umum dan dampaknya.
### 🔍 Fokus Eksperimen:
- 🔓 **SQL Injection**
- 🧬 **Cross-Site Scripting (XSS)**
- ⚠️ **WordPress Vulnerabilities** (melalui `wpscan`)

### 📄 Dokumentasi:
- Payload yang digunakan
- Tangkapan layar hasil eksploitasi
- Dampak dan saran mitigasi

📁 Folder: `web-exploitation/`

## 🛡️ 3. Penetration Testing (Localhost)
Melakukan penetration testing terhadap aplikasi web lokal dengan pendekatan sistematis: dari informasi awal, scanning, eksploitasi, hingga pelaporan.
### 🧪 Proses:
- Pengumpulan informasi (fingerprinting)
- Identifikasi celah
- Eksploitasi
- Penyusunan laporan

📄 Hasil:
- Laporan PDF & Markdown
- Bukti eksploitasi (screenshot)
- Rekomendasi keamanan

📁 Folder: `penetration-testing/`

## 🛠️ 4. Kali Linux Tools Exploration
Menggunakan berbagai tools dalam Kali Linux untuk kegiatan offensive security:
### ⚙️ Tools yang Digunakan:
- `nmap` – Network scanning
- `nikto` – Web server scanner
- `whatweb` – Web technology fingerprinting
- `wpscan` – WordPress vulnerability scanner
- `sqlmap` – SQL injection automation
- `hydra` – Brute-force attack tool
- Tools tambahan: `dirb`, `dnsenum`, `theHarvester`, `gobuster`, dll.

📁 Folder: `kali-tools/`

## 🌐 5. Network Traffic Analysis
Melakukan pemantauan dan analisis lalu lintas jaringan untuk mendeteksi anomali dan potensi serangan.
### 🧰 Tools:
- `Wireshark` – Analisis paket secara mendalam
- `OWASP ZAP` – Proxy & scanner untuk aplikasi web

### 📄 Studi Kasus:
- Pemantauan login brute force
- Deteksi payload mencurigakan dalam HTTP request
- Visualisasi trafik yang tidak wajar

📁 Folder: `network-analysis/`


## 📊 6. Log Analysis & Automation
Analisis data log sistem dan jaringan untuk mendeteksi pola berbahaya, dengan bantuan query SQL dan pemrograman Python.
### 🧰 Tools:
- **Microsoft Log Parser** – Menjalankan query terhadap file log Windows dan IIS
- **Python** – Untuk mem-parsing dan mencari anomali log secara otomatis

### 📄 Proyek:
- Analisis log HTTP (404, 500, brute force, SQL injection pattern)
- Parsing otomatis file `.log` & `.csv`
- Export hasil analisis ke CSV & visualisasi dasar

📁 Folder: `log-analysis/`

## 🎯 Tujuan Pembelajaran

- Menguasai dasar-dasar cyber security dan prinsip CIA
- Menerapkan pengujian keamanan web secara langsung
- Menggunakan berbagai tools offensive & defensive di Kali Linux
- Melakukan analisis jaringan dan log untuk mendeteksi potensi serangan
- Mendokumentasikan hasil kerja dalam format yang dapat dibagikan secara profesional.