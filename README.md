# Generator Prompt Kisi-Kisi dan Naskah Soal

Aplikasi web satu halaman untuk menyusun **master prompt** perangkat asesmen (kisi-kisi, naskah soal, kunci, pembahasan, rubrik, audit) yang siap ditempel ke Claude.

## Fitur
- Formulir identitas asesmen, Tujuan Pembelajaran, dan rincian materi (kode materi TP.Bab.Sub dibuat otomatis).
- Blueprint otomatis: pembagian butir per TP, bentuk soal, level kognitif (LOTS/MOTS/HOTS), butir visual, peta nomor, dan target sebaran kunci.
- Pengaturan skor per bentuk soal atau per level kognitif (manual), lengkap dengan konversi nilai 0–100.
- Pemeriksaan input dan tombol salin prompt.

## Cara pakai
Buka halaman GitHub Pages repositori ini, isi formulir, lalu salin prompt dari tab **Master prompt**.
Isian tersimpan di browser masing-masing pengguna (localStorage), tidak dikirim ke server mana pun.

## Teknis
Satu berkas `index.html` tanpa dependensi build. Font dimuat dari Google Fonts.
