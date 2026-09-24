# Studio PBP 2026.1

Repositori studio mata kuliah **IF24502 Pemrograman Berbasis Platform**, Program Studi Ilmu
Informatika, Universitas Katolik Darma Cendika. Semester Ganjil 2026/2027.

Satu repositori untuk seluruh studio satu semester. Berisi kode yang dikerjakan bersama di
kelas, beserta kunci yang ditambahkan setelah pertemuan selesai.

## Susunan folder

| Folder | Pertemuan | Isi |
|---|---|---|
| `p02-studio/` | P02 | Dart dasar: tipe, null safety, fungsi, koleksi |
| `p03-studio/` | P03 | Kelas, asinkron, dan GitHub |
| `ts1/`, `ts2/`, ... | - | Tugas terstruktur, satu folder per tugas |
| `docs/` | - | Catatan pendek yang dirujuk dari kelas |

Satu folder per pertemuan, berpola `p<nomor>-studio`. Folder pertemuan berikutnya ditambahkan
saat pertemuannya tiba, bukan dibuat kosong lebih dulu.

## Aturan penamaan repositori mata kuliah ini

Seluruh semester ini Anda hanya membuat **dua sampai tiga repositori**, bukan satu per tugas.

| Repositori | Pola nama | Isinya | Dibuat |
|---|---|---|---|
| **Studio** | `pbp-studio-<nim>` | Seluruh studio P02 sampai P15, ditambah tugas terstruktur TS-1 dan seterusnya | P02 |
| **Proyek** | `pbp-proyek-<kode kelompok>` | Aplikasi Flutter kelompok beserta kasus berjalannya, dipakai sampai UAS | P06 |
| **Backend**, bila tim memisahkannya | `pbp-backend-<kode kelompok>` | Backend buatan sendiri. Boleh digabung ke repositori proyek sebagai folder `backend/` | P06 |

Mahasiswa yang mengerjakan proyek sendiri memakai `pbp-proyek-<nim>`. Milik dosen memakai
tahun dan semester, yaitu `pbp-studio-2026-1`.

Huruf kecil semua, dipisah tanda hubung, tanpa spasi, tanpa huruf kapital, tanpa nama panggilan.
Alasannya: nama repositori muncul di URL, dan URL berhuruf campur menyusahkan saat disalin.

## Aturan commit

Pesan commit menyebut **apa yang berubah**, bukan "update" atau "fix". Contoh yang diterima:
`Menambah latihan 3 rata-rata dengan penjagaan daftar kosong`.

## Menjalankan

Seluruh berkas `.dart` di folder `p02-studio/` bisa dijalankan tanpa Flutter:

```bash
dart run p02-studio/latihan1.dart
```

Atau ditempel ke `dartpad.dev` kalau Dart belum terpasang.
