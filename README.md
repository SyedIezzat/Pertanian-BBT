# 🌾 Plant Pest Monitoring System

**Versi**: 1.0.0  
**Dibangunkan oleh**: [Nama Anda / Organisasi Anda]

## 📌 Pengenalan

Sistem ini direka untuk memudahkan pemantauan serangan perosak tanaman di lapangan secara sistematik dan seragam. Fokus utama adalah pada tanaman padi, namun sistem ini boleh disesuaikan untuk tanaman lain. Sistem ini menyokong penilaian keterukan serangan, kawasan terjejas, tindakan kawalan, serta kehadiran musuh semula jadi.

## 🎯 Objektif

- Menyeragamkan pengumpulan data serangan perosak di lapangan.
- Memudahkan pemantauan, pelaporan dan analisis data secara berkala.
- Menyokong keputusan tindakan kawalan berdasarkan data terkini.
- Meminimumkan kebergantungan kepada sistem manual berbentuk kertas.

## 📷 Ciri-ciri Utama

- ✅ Borang pemantauan digital (boleh digunakan atas talian & luar talian).
- ✅ Skor keterukan serangan perosak (berdasarkan skala standard).
- ✅ Rekod keluasan kawasan terjejas.
- ✅ Catatan tindakan kawalan yang telah diambil.
- ✅ Pemerhatian kehadiran musuh semula jadi.
- ✅ Fungsi laporan & analisis ringkas.
- ✅ Sesuai untuk pelbagai jenis peranti (mudah alih/desktop).

## 🏗️ Teknologi Digunakan

- `Frontend`: [contoh: React / Vue / Google Forms / AppSheet]
- `Backend`: [contoh: Firebase / Node.js / Google Sheets sebagai DB]
- `Visualisasi`: [contoh: Data Studio / Graf dalam Dashboard dalaman]
- `Hosting`: [contoh: GitHub Pages / Firebase Hosting / Google Drive]

## 📝 Panduan Penggunaan

1. **Log masuk** ke sistem menggunakan akaun organisasi anda.
2. **Pilih lokasi plot pemantauan** atau tambah lokasi baru.
3. **Isi borang pemantauan** mengikut pemerhatian di lapangan:
   - Pilih jenis perosak.
   - Masukkan skor keterukan.
   - Nyatakan keluasan kawasan terjejas.
   - Catat sebarang tindakan atau kehadiran musuh semula jadi.
4. **Hantar data** – sistem akan simpan secara automatik ke dalam pangkalan data.
5. **Lihat laporan ringkas** dalam dashboard atau eksport ke Excel/PDF.

## 📊 Skala Penilaian Keterukan (Contoh)

| Skor | Penerangan                      |
|------|----------------------------------|
| 0    | Tiada serangan                  |
| 1    | Serangan ringan (<10% kawasan) |
| 2    | Sederhana (10–25%)              |
| 3    | Serangan tinggi (26–50%)        |
| 4    | Sangat tinggi (>50%)            |

> *Nota: Skala boleh disesuaikan mengikut jenis tanaman dan perosak.*

## 📁 Struktur Projek

```plaintext
/
├── frontend/               # Antaramuka pengguna
├── backend/                # Kod backend / API
├── docs/                   # Dokumentasi
├── data-sample/            # Contoh data & format
└── README.md               # Fail ini

