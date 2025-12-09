# 🚂 Spirited Away Train Scene - 3D WebGL

Project ini adalah visualisasi 3D interaktif dari scene kereta api ikonik dalam film *Spirited Away*, dibangun menggunakan **Three.js**.

## ⚠️ PENTING: Instruksi Instalasi Aset

Karena ukuran file model 3D yang cukup besar, file aset (model & tekstur) **tidak disertakan** di dalam repository GitHub ini. Anda harus mengunduhnya secara manual agar project dapat berjalan.

### 1. Download Aset
Silakan unduh folder `model` melalui link Google Drive di bawah ini:

👉 https://drive.google.com/drive/folders/1AUXPlij_JAWx_Sif1WpE97XlCPh046bD?usp=drive_link 👈

### 2. Struktur Folder
Setelah diunduh, ekstrak file tersebut. Pastikan struktur folder project Anda terlihat persis seperti di bawah ini agar kode dapat membaca file aset dengan benar:

```text
Nama-Project-Folder/
│
├── model/                  <-- Folder hasil download (berisi file .gltf, .bin, textures)
│   ├── parts_rail_railway_track/
│   ├── spirited_away_train_fanart/
│   ├── low_poly_island/
│   ├── station_wild_west/
│   ├── noface/
│   └── ... (dan file model lainnya)
│
└── index.html              <-- File utama (sudah ada di repo ini)
Catatan: Jangan mengubah nama folder model atau memindahkan isinya, karena kode index.html merujuk ke path model/nama-file.gltf.

```

### 4. Cara Menjalankan
WAJIB Menggunakan Live Server
