# 🤖 Telegram AI Appointment Assistant  
AI-powered appointment scheduling bot built with **n8n**, **Google Gemini**, and **Telegram Bot API**.

## 📌 Overview
Proyek ini adalah sistem otomatis berbasis n8n yang memungkinkan pengguna untuk mengelola **janji temu (appointment)** melalui **Telegram Bot** menggunakan perintah natural-language.

Bot ini dapat:
- Menambahkan appointment baru  
- Melihat daftar appointment  
- Reschedule appointment  
- Membatalkan appointment  
- Mengelola customer (add / list)
- Menggunakan AI untuk memahami pesan pengguna

Workflow ini memanfaatkan integrasi AI + API internal + Telegram untuk membuat pengalaman scheduling yang mudah dan otomatis.

---

## 🧠 How It Works

```
Telegram Trigger (menerima pesan user)
        ↓
AI Agent (Gemini – memahami perintah user)
        ↓
Memory (Simple Memory – menyimpan konteks percakapan)
        ↓
Logic Nodes:
   - Get Customer List
   - Add Customer
   - Add Appointment
   - Get Appointment List
   - Reschedule Appointment
   - Cancel Appointment
        ↓
Send Message (balasan ke Telegram)
```

---

## 🚀 Features
✔ Menggunakan AI (Gemini) untuk memahami perintah natural  
✔ CRUD Appointment (Add, List, Update, Cancel)  
✔ Manajemen customer  
✔ Memory system untuk mempertahankan konteks percakapan  
✔ Dibangun sepenuhnya di n8n  
✔ Cocok untuk belajar **AI Agent + Chatbot + Automation**  

---

## 🗂 Technologies Used
- **n8n** (workflow automation)
- **Telegram Bot API**
- **Google Gemini Chat Model**
- **n8n AI Agent + Memory**
- JavaScript Expressions
- JSON-based internal API logic

---

## 📁 Repository Structure
```
Appointment - 07.json        → Workflow utama (export dari n8n)
README.md                    → Dokumentasi project
/screenshots (opsional)      → Screenshot workflow & output Telegram
```

---

## 💬 Example User Commands
```
"Tambahkan appointment besok jam 10 dengan Budi"
"Lihat semua appointment saya"
"Reschedule appointment saya ke hari Jumat"
"Hapus appointment hari ini"
"Tambah customer baru"
```

---

## 📬 Example Telegram Output
```
📅 Appointment Created!

Nama: Budi
Tanggal: 2025-02-10
Waktu: 10:00

Appointment berhasil ditambahkan.
```

---

## 🛠 Setup Instructions

### 1. Import Workflow  
Buka n8n → *Import from File* → pilih `Appointment - 07.json`.

### 2. Set Credentials  
- Telegram Bot API  
- API Keys / Credentials internal lain jika diperlukan  

### 3. Jalankan Workflow  
Aktifkan Telegram Trigger dan workflow akan siap digunakan.

---

## 🖼️ Recommended Screenshots
Tambahkan folder `/screenshots` dengan:
- Gambar workflow node  
- Gambar percakapan Telegram  
- Gambar AI Agent memproses pesan  

Ini membuat repo kamu jauh lebih profesional.

---

## 🤝 Contribution  
Pull Request terbuka untuk:
- Penambahan fitur notifikasi otomatis  
- Integrasi Google Calendar  
- Sistem reminder otomatis  

---

## 👤 Author  
**Arfan Fadillah**  
Programmer & Automation Enthusiast  
- Instagram: [@aefjocode](https://www.instagram.com/aefjocode)  
- YouTube: [@AefjoCode](https://www.youtube.com/@AefjoCode)

---

## ⭐ Support  
Jika proyek ini bermanfaat, jangan lupa memberikan ⭐ pada repository GitHub.
