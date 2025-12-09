# Cyber Security Reconnaissance Project

> **Laporan Tugas Besar Mata Kuliah Keamanan Siber** > Studi kasus penerapan teknik *Passive Reconnaissance* pada target nyata dan *Active Reconnaissance* pada lingkungan laboratorium.

---

## 👨‍💻 Identitas Mahasiswa

| Informasi | Detail |
| :--- | :--- |
| **Nama** | **Eko Prasetyo Adi Nugroho** |
| **NIM** | **105841114223** |
| **Kelas** | **5 JK-A** |
| **Mata Kuliah** | Keamanan Siber (Cyber Security) |

---

## 📝 Deskripsi Proyek

Repositori ini berisi dokumentasi lengkap dan laporan teknis mengenai tahapan **Information Gathering (Reconnaissance)** dalam siklus *Penetration Testing*. Proyek ini dibagi menjadi dua fase utama:

1.  **Passive Reconnaissance (Non-Intrusive):**
    * Mengumpulkan informasi publik sebanyak mungkin tanpa berinteraksi langsung dengan sistem target.
    * **Target:** `growtopiagame.com` (Produk Ubisoft Entertainment).
    * **Fokus:** Enumerasi subdomain, infrastruktur DNS, teknologi web, dan OSINT karyawan.

2.  **Active Reconnaissance (Intrusive):**
    * Melakukan pemindaian jaringan secara langsung untuk memetakan port dan layanan yang berjalan.
    * **Target:** `VulnOSv2` (Virtual Machine di VirtualBox).
    * **Fokus:** Host discovery, port scanning, service versioning, dan OS fingerprinting.

---

## 🛠️ Tools yang Digunakan

Berikut adalah daftar perangkat lunak dan layanan yang digunakan dalam pengerjaan tugas ini:

### 🔍 Passive Recon Tools
* **Whois:** Identifikasi kepemilikan domain dan registrar.
* **Dig:** Analisis DNS Record (A, NS, MX, TXT).
* **Subfinder & Amass:** Enumerasi subdomain dan pemetaan infrastruktur.
* **crt.sh:** Pencarian log transparansi sertifikat SSL/TLS.
* **Censys:** Mesin pencari perangkat IoT dan server.
* **Wappalyzer:** Identifikasi teknologi website (*tech stack*).
* **Wayback Machine:** Analisis riwayat digital website.
* **Google Dorks & GitHub:** Pencarian kebocoran data (*information disclosure*).
* **RocketReach/LinkedIn:** OSINT untuk identifikasi karyawan.

### ⚔️ Active Recon Tools
* **Netdiscover:** Penemuan host dalam jaringan lokal (ARP Scan).
* **Nmap:** Pemindaian port (TCP/UDP), deteksi versi layanan, dan OS fingerprinting.
* **Wireshark:** Analisis trafik jaringan untuk memvalidasi proses scanning.

---

## 📂 Struktur Repositori

* `/Laporan`: Berisi file laporan akhir dalam format PDF.
* `/Dokumentasi`: Kumpulan *screenshot* bukti pengerjaan.
* `README.md`: File informasi proyek ini.

---

## 📺 Video Dokumentasi

Berikut adalah video demonstrasi langkah-langkah pengerjaan tugas besar ini:

[![Video Dokumentasi](https://img.youtube.com/vi/ID_VIDEO_KAMU/0.jpg)](LINK_VIDEO_YOUTUBE_KAMU_DISINI)

> *Klik gambar di atas atau tautan ini untuk menonton video: [Link Video YouTube]*

*(Catatan: Jangan lupa ganti link di atas dengan link video YouTube kamu yang asli)*

---

## ⚠️ Disclaimer

Proyek ini dibuat semata-mata untuk **tujuan pendidikan dan pembelajaran**.
* **Passive Recon** dilakukan pada data publik yang tersedia secara legal.
* **Active Recon** dilakukan pada lingkungan laboratorium tertutup (*VulnOS*) milik pribadi, bukan pada server publik tanpa izin.

Penulis tidak bertanggung jawab atas penyalahgunaan informasi yang terdapat dalam repositori ini.

---
Copyright © 2025 Eko Prasetyo Adi Nugroho.
