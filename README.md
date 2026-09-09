# Rapi - Daily & Weekly Report

Prototype web app untuk menyusun daily report berbasis catatan bebas dan membangun weekly report dari seluruh daily report tersimpan pada Senin-Jumat di minggu yang dipilih.

## Cara menjalankan

Buka `index.html` langsung di browser. Aplikasi tidak membutuhkan instalasi atau server.

## Perilaku utama

- Input aktivitas memakai satu baris per kegiatan: `[jam] [description]`, misalnya `8-11 prepare sparrow untuk bank j-trust`.
- Kolom Jam dan Description diisi langsung dari input pengguna. Sistem hanya merekomendasikan Detail, organisasi, dan status.
- Semua hasil rekomendasi merupakan draft dan dapat diedit per baris sebelum disimpan atau diunduh sebagai PDF.
- Daily report disimpan di browser (`localStorage`).
- Weekly report otomatis mengambil semua daily report yang tersimpan dalam rentang Senin sampai Jumat.
