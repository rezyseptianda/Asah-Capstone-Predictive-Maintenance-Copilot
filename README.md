# MaintenX - Predictive Maintenance Copilot 🏭🤖

> **Capstone Project - Dicoding x Accenture ASAH** > **Use Case:** [AC-02] Predictive Maintenance Copilot  
> **Team ID:** A25-CS057

---

## 📖 Tentang Proyek

**MaintenX** adalah sistem _Copilot_ berbasis Agentic AI yang dirancang untuk membantu tim engineer di industri energi. Aplikasi ini berfungsi untuk mendeteksi anomali pada sensor mesin, memberikan prediksi kerusakan, dan merekomendasikan tindakan perawatan secara _real-time_.

---

## 🛠 Tech Stack (Front-End)

- **Framework:** [React.js](https://react.dev/) + [Vite](https://vitejs.dev/)
- **Language:** JavaScript (JSX)
- **Styling:** [CSS / Tailwind CSS - sesuaikan dengan yang kamu pakai]
- **HTTP Client:** Axios / Fetch (untuk koneksi ke Back-End)
- **State Management:** React Context / Redux (Opsional)

---

## 🚀 Cara Menjalankan Project (Local Development)

Ikuti langkah ini untuk menjalankan aplikasi di komputer lokal kalian:

### 1. Prerequisites

Pastikan sudah menginstall **Node.js** (versi LTS disarankan).

### 2. Instalasi

Clone repository ini, lalu masuk ke folder project dan install dependencies:

```bash
# Clone repository (jika belum)
git clone [https://github.com/USERNAME_GITHUB/NAMA_REPO.git](https://github.com/USERNAME_GITHUB/NAMA_REPO.git)

# Masuk ke direktori
cd predictive-maintenance-app

# Install dependencies
npm install
```

---

🤝 Panduan Kolaborasi Git (WAJIB DIBACA TIM) ⚠️
Agar kode tidak bentrok dan tetap rapi, kita menggunakan alur kerja (workflow) berikut. Mohon dipatuhi oleh tim Back-End dan ML saat integrasi.

Struktur Branch
🔴 main: Branch UTAMA. Kode di sini adalah versi final yang siap demo/production. JANGAN PUSH LANGSUNG KE SINI.

🟡 develop: Branch PENGEMBANGAN. Semua fitur baru digabungkan di sini terlebih dahulu sebelum masuk ke main.

🔵 feature/\*: Branch FITUR. Gunakan ini saat kalian sedang mengerjakan tugas spesifik (misal: feature/api-login, feature/chart-sensor).

---

SOP: Bagaimana Cara Mulai Coding?
Pindah ke branch develop dan update kode terbaru: Selalu mulai dengan mengambil kode terbaru dari teman-teman agar tidak konflik.

Bash

git checkout develop
git pull origin develop
Buat Branch Baru untuk Tugas Kalian: Berikan nama branch yang jelas sesuai fitur yang dikerjakan.

Bash

# Contoh: Mengerjakan integrasi API Login

git checkout -b feature/api-login
Lakukan Coding & Commit: Simpan perubahan kalian secara berkala. Gunakan pesan commit yang jelas.

Bash

git add .
git commit -m "feat: integrate login API with backend endpoint"

---

SOP: Bagaimana Jika Kode Sudah Selesai?
Push Branch Kalian ke GitHub:

Bash

git push -u origin feature/nama-fitur-kalian
Buat Pull Request (PR):

Buka halaman repository di GitHub.

Kalian akan melihat tombol "Compare & pull request". Klik tombol itu.

Pastikan arahnya: base: develop <--- compare: feature/nama-fitur-kalian.

Berikan judul dan deskripsi apa yang kalian ubah.

Klik Create Pull Request.

Review & Merge:

Beritahu tim di grup (WhatsApp/Discord) untuk mengecek PR kalian.

Jika sudah oke, Admin/Lead akan melakukan Merge ke develop.
