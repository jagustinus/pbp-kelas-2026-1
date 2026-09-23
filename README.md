# Studio PBP 2026.1

Repositori studio mata kuliah **IF24502 Pemrograman Berbasis Platform**, Program Studi Ilmu
Informatika, Universitas Katolik Darma Cendika. Semester Ganjil 2026/2027.

Satu repositori untuk seluruh studio satu semester. Berisi kode yang dikerjakan bersama di
kelas, beserta kunci yang ditambahkan setelah pertemuan selesai.

## Susunan folder

| Folder | Pertemuan | Isi |
|---|---|---|
| `p02-dart/` | P02 | Dart dasar: tipe, null safety, fungsi, koleksi |
| `p03-dart-lanjut/` | P03 | Kelas, asinkron, dan GitHub |
| `docs/` | - | Catatan pendek yang dirujuk dari kelas |

Folder pertemuan berikutnya ditambahkan saat pertemuannya tiba, bukan dibuat kosong lebih dulu.

## Aturan penamaan repositori mata kuliah ini

| Untuk | Pola nama | Contoh |
|---|---|---|
| Studio, milik dosen | `pbp-studio-<tahun>-<semester>` | `pbp-studio-2026-1` |
| Studio, milik mahasiswa, **satu untuk satu semester** | `pbp-studio-<nim>` | `pbp-studio-2024001` |
| Proyek, milik kelompok | `pbp-proyek-<kode kelompok>` | `pbp-proyek-k1` |
| Proyek, milik mahasiswa yang mengerjakan sendiri | `pbp-proyek-<nim>` | `pbp-proyek-2024001` |

Huruf kecil semua, dipisah tanda hubung, tanpa spasi, tanpa huruf kapital, tanpa nama panggilan.
Alasannya: nama repositori muncul di URL, dan URL berhuruf campur menyusahkan saat disalin.

## Aturan commit

Pesan commit menyebut **apa yang berubah**, bukan "update" atau "fix". Contoh yang diterima:
`Menambah latihan 3 rata-rata dengan penjagaan daftar kosong`.

## Menjalankan

Seluruh berkas `.dart` di folder `p02-dart/` bisa dijalankan tanpa Flutter:

```bash
dart run p02-dart/latihan1.dart
```

Atau ditempel ke `dartpad.dev` kalau Dart belum terpasang.
