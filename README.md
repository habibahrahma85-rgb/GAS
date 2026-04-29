# 🚀 GAS Automatic Result Assessment

## 📌 Overview

GAS (Automatic Result Assessment) adalah sistem otomatis berbasis Google Apps Script yang digunakan untuk melakukan penilaian hasil secara real-time dari data yang dikumpulkan melalui Google Form dan disimpan di Google Spreadsheet.

Project ini dirancang untuk menyederhanakan proses evaluasi data tanpa perlu pengolahan manual, sehingga lebih cepat, akurat, dan efisien.

## 🎯 Objectives

* Mengotomatisasi proses penilaian dari Google Form
* Mengurangi human error dalam evaluasi data
* Mempercepat pengolahan hasil secara real-time
* Menghasilkan output yang konsisten dan terstruktur

## ⚙️ Features

* 📥 Integrasi langsung dengan Google Form sebagai input data
* 📊 Penyimpanan otomatis ke Google Spreadsheet
* ⚡ Pemrosesan data otomatis menggunakan Google Apps Script
* 🧮 Sistem penilaian berdasarkan kriteria tertentu
* 📤 Output hasil evaluasi langsung di spreadsheet
* 📄 FIle siap kirim berupa pdf 

## 🛠️ Tech Stack

* Google Apps Script (GAS)
* Google Forms
* Google Sheets

## 🔄 Workflow

1. User mengisi Google Form
2. Data otomatis masuk ke Google Spreadsheet
3. Google Apps Script berjalan (trigger otomatis / manual)
4. Sistem memproses dan menilai data
5. Hasil penilaian ditampilkan di Spreadsheet

## 📂 Project Structure

```
├── Code.gs           # Script utama GAS
├── Form              # Google Form (external)
├── Spreadsheet       # Database & hasil output
├── README.md         # Dokumentasi project
```

## 🚀 How to Use

1. Buat Google Form sebagai input data 
    klik link ini untuk membuka gform BOS Check buatan saya https://s.id/BOScheck
2. Hubungkan Form ke Google Spreadsheet
    nantinya file jawaban dari link BOS Check akan masuk ke dalam "BOS Check  Skala Linier 5 Bagian (Jawaban)"
3. Buka Apps Script dari Spreadsheet
4. Copy script dari project ini ke editor GAS
5. Setup trigger (misalnya: On Form Submit)
6. Jalankan dan cek hasil di Spreadsheet
    hasil berupa file pdf akan muncul di folder hasil yang sudah disiapkan sebelumnya dalam file tamplate, secara otomatis

## 📊 Example Use Case

* Penilaian kuis / ujian otomatis
* Evaluasi data survey
* Sistem scoring sederhana untuk seleksi
* Monitoring performa berdasarkan input form

## 📈 Future Improvements

* 🌐 Dashboard visualisasi (Google Data Studio / Looker)
* 🔔 Notifikasi otomatis (email / WhatsApp)
* 🤖 Integrasi AI untuk analisis data lanjutan
* 🔗 API integration

## 🤝 Contributing

Kontribusi terbuka untuk pengembangan lebih lanjut. Silakan fork dan pull request.

## 👤 Author

Dibuat oleh Habibah Rahma Hayeti
Sebagai bagian dari portfolio pengembangan sistem berbasis automation
