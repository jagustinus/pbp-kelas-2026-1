# Aturan Studio PBP

Ringkas, dan berlaku sampai UAS.

## Satu repositori untuk satu semester

Studio memakai satu repositori, `pbp-studio-<nim>`. Jangan membuat repositori baru tiap
pertemuan. Proyek kelompok memakai repositori terpisah, `pbp-proyek-<kode kelompok>`.

## Satu folder untuk satu pertemuan

`p02-dart/`, `p03-dart-lanjut/`, dan seterusnya. Folder dibuat saat pertemuannya tiba.

## Satu commit untuk satu pekerjaan selesai

Bukan satu commit untuk semua latihan, dan bukan satu commit tiap kali menekan simpan. Pesannya
menyebut apa yang berubah:

- Diterima: `Menambah latihan 3 rata-rata dengan penjagaan daftar kosong`
- Ditolak: `update`, `fix`, `tugas`, `asdf`

## Yang tidak masuk repositori

Berkas hasil build, folder `.dart_tool/`, dan berkas pengaturan editor. Semuanya sudah ada di
`.gitignore`.

## Kalau lupa

Jalankan `git status` dan baca kalimat yang muncul. Git hampir selalu menyebutkan perintah
berikutnya yang Anda butuhkan.
