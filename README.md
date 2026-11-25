# Kelas PBP 2026.1

Kode kelas dan kunci studio mata kuliah **IF24502 Pemrograman Berbasis Platform**, Program Studi Ilmu
Informatika, Universitas Katolik Darma Cendika. Semester Ganjil 2026/2027.

Kunci satu pertemuan ditambahkan **sesudah deadline studio pertemuan itu lewat**.

## Isi

| Folder | Pertemuan | Isi |
|---|---|---|
| `p02-studio/` | P02 | Dart dasar: tipe, null safety, fungsi, koleksi |
| `guyub/` | P06 dan seterusnya | Guyub, proyek studio: aplikasi Flutter di folder ini, backend di `guyub/backend/` mulai P07 |

`guyub/` di sini disusun persis seperti `guyub/` di repositori studio Anda. Bagian A diketik bersama di
kelas; jawaban Bagian B ditambahkan hari **Senin** sesudah batas terlambat, dengan satu tag per pertemuan
mulai `p09`. Tertinggal? Ambil tag pertemuan terakhir untuk ikut pertemuan berikutnya, karena studio selalu
melanjutkan kode pertemuan sebelumnya.

## Repositori Anda

Seluruh semester Anda hanya membuat **dua sampai tiga repositori**.

| Repositori | Pola nama | Isi |
|---|---|---|
| Studio | `pbp-studio-<nim>` | Studio per pertemuan di folder `p<nomor>-studio/`, tugas terstruktur di `ts1/`, `ts2/`, ..., dan Guyub di folder `guyub/` |
| Proyek | `pbp-proyek-<nama kelompok>` | Aplikasi kelompok, dipakai sampai UAS. Sendirian: `pbp-proyek-<nim>` |
| Backend, bila dipisah | `pbp-backend-<nama kelompok>` | Backend buatan sendiri. Boleh digabung ke repositori proyek sebagai folder `backend/` |

Huruf kecil semua, dipisah tanda hubung, tanpa spasi.

## Pesan commit

| Di mana | Bentuk | Contoh |
|---|---|---|
| Studio | `studio(p<nomor>): <langkah> <apa yang berubah>` | `studio(p06): A1 class dan data` |
| Proyek | `<jenis>: <apa yang berubah> (#<nomor kartu>)` | `feat: form laporan baru (#12)` |

Pesan menyebut **apa yang berubah**, bukan "update", "fix", atau "tugas". Aturan lengkap ada di
**Aturan Main Scrum PBP** (PDF di EdLink).

## Menjalankan

Berkas `.dart` di `p02-studio/` bisa dijalankan tanpa Flutter:

```bash
dart run p02-studio/latihan1.dart
```

Atau ditempel ke `dartpad.dev` bila Dart belum terpasang.
