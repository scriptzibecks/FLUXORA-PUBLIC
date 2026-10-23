# Fluxora
### Creator Workspace

Fluxora adalah aplikasi desktop untuk membantu fotografer mengelola karya, mengunggah foto dan video ke FotoYu, serta memantau aktivitas dalam satu workspace.

[Unduh versi terbaru](https://github.com/scriptzibecks/FLUXORA-PUBLIC/releases/latest) · [Catatan rilis](https://github.com/scriptzibecks/FLUXORA-PUBLIC/releases) · [Laporkan masalah](https://github.com/scriptzibecks/FLUXORA-PUBLIC/issues)

## Unduh

Buka halaman **Releases**, lalu pilih installer yang sesuai dengan perangkat:

| Perangkat | File installer |
| --- | --- |
| Windows 64-bit | `Fluxora-<versi>-Windows-x64.exe` |
| Mac Apple Silicon, termasuk M1 Pro | `Fluxora-<versi>-macOS-arm64.dmg` |
| Mac Intel | `Fluxora-<versi>-macOS-x64.dmg` |

**Versi macOS masih dalam tahap pengujian.**

Unduh file `.exe` atau `.dmg` pada bagian **Assets**. File **Source code (zip)** dan **Source code (tar.gz)** bukan installer aplikasi.

## Fitur

- Upload foto dan video dengan pengaturan publikasi dan metadata.
- Pemantauan progres, kecepatan upload, serta riwayat sesi dan batch.
- Galeri upload dengan preview, status file, dan filter.
- Analisis FotoYu dengan hasil pencocokan per foto.
- Pengolahan gambar, LUT Creator, dan watermark.
- Ringkasan penjualan, relasi pembeli, dan pengiriman Hi-res.

Ketersediaan fitur mengikuti lisensi dan dukungan akun FotoYu.

## Pemasangan Windows

1. Unduh installer **Windows x64** melalui halaman Releases.
2. Jalankan file `.exe` dan ikuti petunjuk pemasangan.
3. Buka Fluxora.
4. Aktifkan menggunakan lisensi Fluxora, lalu masuk dengan akun FotoYu.

Installer Windows ditandatangani digital menggunakan sertifikat **self-signed** Fluxora. Sertifikat ini belum otomatis dipercaya oleh Windows sehingga peringatan keamanan dapat muncul. Pastikan installer berasal dari halaman Releases resmi repositori ini.

## Pemasangan macOS

1. Unduh DMG sesuai jenis prosesor Mac: **arm64** untuk Apple Silicon atau **x64** untuk Intel.
2. Buka file `.dmg`.
3. Geser **Fluxora.app** ke folder **Applications** dan tunggu penyalinan selesai.
4. Jalankan Fluxora dari Applications.
5. Aktifkan menggunakan lisensi Fluxora, lalu masuk dengan akun FotoYu.

Paket macOS menggunakan tanda tangan **ad-hoc** dan belum menggunakan Apple Developer ID atau notarization.

Jika aplikasi diblokir karena pengembang belum terverifikasi:

1. Coba buka Fluxora sekali, lalu tutup pesan peringatannya.
2. Buka **System Settings → Privacy & Security**.
3. Pada bagian Security, temukan keterangan pemblokiran Fluxora.
4. Klik **Open Anyway**, lalu konfirmasi dengan password atau Touch ID.
5. Pilih **Open** untuk menjalankan aplikasi.

Gunakan langkah tersebut hanya untuk paket resmi yang kamu unduh dari repositori ini.

[Pelajari pemeriksaan keamanan aplikasi macOS melalui Apple Support](https://support.apple.com/en-au/102445)

## Pembaruan aplikasi

### Windows

Ketersediaan versi baru diperiksa secara otomatis. Unduhan dimulai setelah pengguna memilih:

**Pengaturan → Pembaruan Aplikasi → Cek update**

Setelah pembaruan siap, pilih **Restart & pasang** ketika pekerjaan sudah selesai. Restart aplikasi memerlukan konfirmasi pengguna.

### macOS

Pembaruan masih dilakukan secara manual melalui halaman Releases. Unduh DMG terbaru sesuai prosesor Mac, tutup Fluxora, lalu salin aplikasi terbaru ke folder Applications untuk menggantikan versi sebelumnya.

## File sumber

File asli tetap berada di folder sumber setelah diproses. Fluxora menampilkan status file dan menyimpan catatan untuk membantu mencegah pengiriman ulang file yang sudah tercatat berhasil diupload.

## Laporan masalah

Laporkan kendala melalui [GitHub Issues](https://github.com/scriptzibecks/FLUXORA-PUBLIC/issues) dengan menyertakan:

- Versi Fluxora.
- Sistem operasi dan jenis prosesor.
- Langkah untuk mengulangi masalah.
- Pesan error atau screenshot yang relevan.

Jangan sertakan kata sandi, kode autentikator, kode lisensi, atau informasi pribadi dalam laporan publik.

## Tentang repositori

Repositori ini menyediakan installer, panduan penggunaan, dan catatan rilis Fluxora. Source code aplikasi bersifat privat. Repositori publik ini bukan distribusi source code terbuka.

Penggunaan aplikasi memerlukan lisensi Fluxora yang valid.

---

Copyright (c) 2026 Fluxora. All rights reserved.  
Dikembangkan oleh **scriptzibecks**.
