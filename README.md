# 🎀 Blockchain Simulator - Pastel Edition

Website edukasi interaktif untuk mempelajari konsep dasar **Blockchain** dengan tampilan yang **Cute & Aesthetic** (Tema Pastel). Simulator ini mencakup materi Hashing, Mining Block, Rantai Blockchain, Digital Signature (ECC), hingga Simulasi Konsensus antar user.

## ✨ Fitur Utama

Website ini memiliki 5 modul simulasi utama:

1.  **🍭 Hash Generator:** Mengubah input teks menjadi kode unik SHA-256 secara real-time.
2.  **🧱 Single Block:** Simulasi proses _Mining_ mencari nilai Nonce yang valid agar Hash diawali dengan "0000".
3.  **🔗 Blockchain:** Rantai block yang saling terhubung. Jika data di satu block diubah, seluruh rantai setelahnya akan rusak (Invalid).
4.  **✒️ ECC Signature:** Simulasi Tanda Tangan Digital menggunakan _Elliptic Curve Cryptography_ (ECC). Membuat Key Pair, menandatangani pesan, dan verifikasi.
5.  **🤝 Konsensus Simulator:** Simulasi transaksi antar 3 user (A, B, C) dengan sistem _Mempool_, Mining serentak, dan penyelesaian konflik data (Konsensus).

### 🎨 Fitur Tambahan

- **Responsive Design:** Tampilan rapi di Desktop & Mobile (Menu Hamburger).
- **Pastel UI:** Desain antarmuka yang ramah dan lucu.
- **Tanpa Backend:** Berjalan sepenuhnya di browser (Client-side).

---

## 🛠️ Teknologi yang Digunakan

- **HTML5** - Struktur halaman.
- **CSS3** - Styling (Flexbox, Grid, Animations, Responsive).
- **JavaScript (Vanilla)** - Logika Hash, Mining, dan Blockchain.
- **Elliptic.js** - Library eksternal untuk kriptografi ECC (via CDN).

---

## 🚀 Cara Install & Clone (Step-by-Step)

Ikuti langkah-langkah berikut untuk mengunduh dan menjalankan proyek ini di komputer kamu:

### Prasyarat

Pastikan kamu sudah menginstall **Git** di komputer. Jika belum, download di [git-scm.com](https://git-scm.com/).

### Langkah 1: Clone Repository

Buka terminal (Command Prompt / Git Bash / Terminal VS Code), arahkan ke folder tujuan, lalu ketik:

```bash
git clone [https://github.com/MuhammadDias/Blockchain-simulator-pipit.git](https://github.com/MuhammadDias/Blockchain-simulator-pipit.git)
```

### Langkah : Jalankan Website

Karena website ini statis (hanya HTML/CSS/JS), kamu tidak perlu menginstall node_modules.

Cukup buka file index.html dengan cara:

Cara Manual: Buka folder di File Explorer, klik 2x pada index.html.

VS Code: Install ekstensi "Live Server", klik kanan index.html > "Open with Live Server".

## 📂 Struktur File

```text
/
├── index.html      # File utama (Struktur & Layout)
├── style.css       # File gaya (Warna Pastel & Tata Letak)
├── script.js       # File logika (Hashing, Mining, ECC, Consensus)
├── img/            # (Opsional) Folder gambar profil
│   └── profile.jpg
├── cv.pdf          # (Opsional) File CV untuk didownload
└── README.md       # Dokumentasi proyek ini
```
