# SkyFlux RF Simulator

SkyFlux RF Simulator adalah aplikasi simulasi sinyal video link FPV 5.8 GHz berbasis web statis. Proyek ini dibuat untuk membantu pengguna memahami konsep RF secara visual dan interaktif tanpa perlu instalasi software tambahan.

## Fitur Utama
- Simulasi link budget FPV 5.8 GHz secara interaktif
- Pengaturan parameter antena TX dan RX (gain, efisiensi, SWR, polarisasi)
- Simulasi kondisi lingkungan dan multipath
- Dukungan mode video populer (Analog, HDZero, Walksnail, DJI)
- Tampilan metrik real-time (RSSI, SINR, status link)
- Tooltip pemula untuk tiap komponen penting
- Dukungan bahasa Indonesia dan English pada aplikasi utama
- Dokumentasi terpisah yang ramah pemula

## Struktur Repo
- `simulator-sinyal-antenna.html` : aplikasi utama simulator
- `dokumentasi.html` : panduan lengkap aplikasi untuk pengguna awam
- `DESCRIPTION.md` : ringkasan deskripsi proyek
- `.gitignore` : pengecualian file tertentu dari version control

## Menjalankan Secara Lokal
1. Clone repo
2. Buka file `simulator-sinyal-antenna.html` langsung di browser
3. Atau buka `dokumentasi.html` untuk panduan lengkap

Tidak membutuhkan build step, package manager, atau server khusus.

## Deploy
Proyek ini cocok untuk static hosting, misalnya Azure Blob Static Website.

## Open Source & Disclaimer
Proyek ini adalah **Open Source Project**. Anda bebas untuk mempelajari, memodifikasi, dan berkontribusi pada *source code* aplikasi ini.

**Disclaimer:** Aplikasi ini disediakan "seadanya" (*as-is*) tanpa garansi dalam bentuk apa pun. Aplikasi ini murni untuk tujuan edukasi dan simulasi. Hasil perhitungan adalah estimasi model RF yang disederhanakan dan dapat sangat berbeda dari kondisi terbang nyata di lapangan. Pengguna bertanggung jawab penuh atas segala risiko yang timbul saat menerbangkan dan mengatur *gear* FPV di dunia nyata.
