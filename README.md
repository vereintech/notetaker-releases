# Notetaker: rilis

Notetaker mencatat rapat di Mac **sepenuhnya lokal**: rekam mic + audio rapat, transkrip otomatis,
pisahkan pembicara, lalu buat ringkasan, keputusan, dan action item.

**[⬇ Unduh versi terbaru](https://github.com/vereintech/notetaker-releases/releases/latest)**: pilih file `Notetaker-x.y.z.dmg`.

## Kebutuhan

- macOS **14.4** atau lebih baru, Mac **Apple Silicon** (M1 ke atas)
- ±1 GB ruang kosong untuk model AI lokal (diunduh otomatis saat setup)
- Untuk fitur AI (ringkasan, rapikan transkrip, Tanya AI): **Claude Code** atau **Codex CLI** yang sudah login.
  Belum ada? Notetaker menawarkan tombol **Pasang** saat setup.

## Instalasi

1. Buka file `.dmg`, lalu seret **Notetaker** ke folder **Applications**.
2. Buka Notetaker dari Applications. macOS akan memblokirnya karena app ini belum di-notarize oleh Apple
   (khusus internal tim). Klik **Done**.
3. Buka **System Settings → Privacy & Security**, gulir ke bawah, lalu klik **Open Anyway** di
   bagian "Notetaker was blocked…". Masukkan password Mac, lalu klik **Open Anyway** sekali lagi.
4. Ikuti setup awal: izinkan **Mikrofon**, pilih bahasa, klik **Unduh semua** untuk model lokal (±610 MB),
   lalu pilih Claude atau Codex.

> Langkah 2–3 hanya perlu **sekali**. Di macOS 14, cukup klik kanan Notetaker → **Open** → **Open**.

Saat pertama merekam, macOS juga meminta izin **audio sistem** (agar suara peserta Zoom/Meet ikut terekam).
Pilih **Allow**.

## Pembaruan

Notetaker mengecek pembaruan setiap hari dan memasangnya sendiri, tanpa perlu instal ulang.
Cek manual: menu **Notetaker → Periksa Pembaruan…**

## Data

Semua rekaman, transkrip, dan model tersimpan di Mac Anda:
`~/Library/Application Support/Notetaker`. Tidak ada yang dikirim ke server, kecuali teks transkrip
yang Anda proses lewat Claude/Codex CLI milik Anda sendiri.

---
Repositori ini hanya berisi file rilis dan `appcast.xml` untuk pembaruan otomatis (Sparkle).
