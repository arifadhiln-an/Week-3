☕ 1️⃣ Sistem Kasir Cafe Arifadhil
📌 Deskripsi

Sistem kasir berbasis web yang terintegrasi langsung dengan Google Spreadsheet sebagai database, dirancang untuk membantu pengelolaan transaksi dan monitoring performa cafe secara real-time.

✅ Progress Minggu ke-3

Penyempurnaan tampilan Dashboard

Ringkasan Pendapatan Hari Ini

Total Transaksi Hari Ini

Total Menu Aktif

Stok Perlu Perhatian

Menu Terlaris Hari Ini

Riwayat Transaksi Terbaru

Perapihan struktur kode

🛠 Teknologi

HTML & CSS

JavaScript

Google Apps Script

Google Spreadsheet (Database)

🔗 Akses Project

🌐 Live App (Google Apps Script):
👉 https://script.google.com/macros/s/AKfycbzxXqeWiCFIUARRiLL6pbRcKR-LHgciH0hCJ-Fb05I/dev

🌐 Live App (Google Apps Sheets):
👉 

📝 Blog Breakdown (Medium):
👉 https://medium.com/@arifadhiln/from-spreadsheet-to-smart-dashboard-membangun-sistem-kasir-cafe-arifadhil-yang-terintegrasi-9b51718d3548

--------------------------------------------------------------------------

📅 2️⃣ Website Jadwal Dosen
📌 Deskripsi

Website jadwal dosen berbasis Google Apps Script yang menampilkan jadwal secara dinamis dari Google Spreadsheet.

✅ Progress Minggu ke-3

Integrasi Spreadsheet sebagai database

Dynamic rendering data jadwal

Penyempurnaan UI

Deployment & testing

Struktur modularisasi kode

🛠 Teknologi

HTML

CSS

JavaScript

Google Apps Script

Spreadsheet API

🔗 Akses Project

🌐 Live App:
👉 https://script.google.com/macros/s/AKfycbxm_oQDFPqoR5mWz5pp_wjGxC0IS0NQg0XXBD3gcsI/dev

📝 Blog Breakdown (Medium):
👉 https://medium.com/@arifadhiln/membangun-aplikasi-jadwal-kuliah-berbasis-spreadsheet-google-apps-script-dan-ai-96276746df8a

--------------------------------------------------------------------------

🧠 3️⃣ Data Cleaning Retail Store Sales (Python)

📌 Deskripsi

Proyek data cleaning menggunakan Python dan Pandas untuk membersihkan dataset penjualan retail sebelum digunakan dalam analisis lebih lanjut.

Fokus utama proyek ini adalah memastikan:

Standarisasi nama kolom

Normalisasi nilai string tidak valid

Pembersihan kolom numerik

Validasi logika transaksi

Penghapusan duplikasi

Dataset siap untuk Exploratory Data Analysis (EDA)

Proses cleaning dilakukan secara sistematis dan berbasis logika bisnis, bukan sekadar menghapus missing values.

✅ Progress

Normalisasi nama kolom (lowercase, underscore, hapus karakter khusus)

Konversi string tidak valid menjadi NaN

Pembersihan kolom numerik (hapus simbol & karakter non-angka)

Validasi ulang total transaksi (quantity × price_per_unit)

Konversi format tanggal ke datetime

Penghapusan transaksi tidak valid

Penghapusan duplikasi berdasarkan transaction_id

Final type enforcement (int & float)

Export dataset bersih

🛠 Teknologi

Python

Pandas

NumPy

Matplotlib (untuk deteksi outlier)

CSV Dataset

🔗 Akses Project

📝 Blog Breakdown (Medium):
👉 https://medium.com/@arifadhiln/data-cleaning-with-python-retail-store-sales-dataset-3a0435bd6aad

📸 4️⃣ Sistem Absensi 4 Mode (Camera & Auto Location)

📌 Deskripsi

Aplikasi absensi berbasis web yang terintegrasi langsung dengan Google Spreadsheet sebagai database real-time.

Sistem ini dirancang untuk meningkatkan validitas kehadiran dengan fitur:

Timestamp otomatis

Deteksi lokasi (GPS browser)

Foto langsung dari kamera (bukan upload file)

Penyimpanan data ke sheet berbeda sesuai jenis absensi

Mode absensi yang tersedia:

✅ Absen Masuk

🍽️ Absen Ishoma

🔄 Absen Selesai Ishoma

🏁 Absen Pulang

Setiap mode memiliki sheet terpisah dalam satu file Google Spreadsheet.

✅ Fitur Utama

Auto Timestamp (tidak bisa dimanipulasi user)

Auto Geolocation (latitude & longitude)

Kamera real-time menggunakan getUserMedia()

Routing data ke sheet berbeda

Penyimpanan foto sebagai bukti kehadiran

Real-time update ke Google Spreadsheet

🛠 Teknologi

HTML

CSS

JavaScript

Google Apps Script

Google Spreadsheet (Database)

Geolocation API

MediaDevices API (Camera)

🔗 Akses Project

🌐 Live App (Google Apps Script):
👉 https://script.google.com/macros/s/AKfycbybCKz0Rbf-cD0FOC71D7jLM7SxBJzwHOJ81VGalHA/dev

📝 Blog Breakdown (Medium):
👉 https://medium.com/@arifadhiln/membangun-aplikasi-absensi-4-mode-dengan-kamera-auto-location-menggunakan-google-spreadsheet-54d4769d99af?postPublishedType=initial
