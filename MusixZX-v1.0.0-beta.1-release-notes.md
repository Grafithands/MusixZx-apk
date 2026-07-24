# MusixZX v1.0.0-beta.1

Selamat datang di rilis Beta pertama MusixZX! Versi ini membawa perubahan besar pada arsitektur aplikasi, performa pemindaian lagu, dan pengalaman visualisasi musik yang lebih imersif.

## Fitur Utama

- **Visualizer Studio**: Buat dan terapkan preset visualizer kustom kamu sendiri secara langsung di dalam aplikasi.
- **Milkdrop Visualizer**: Engine visualisasi musik berbasis Milkdrop yang responsif terhadap audio secara real-time.
- **Database Library (Room)**: Pemindaian lagu kini jauh lebih cepat dan efisien menggunakan Room Database dengan dukungan Flow untuk pembaruan UI yang reaktif.
- **Now Playing Experience**: Tab "Now Playing" yang didesain ulang dengan kontrol penuh, dukungan lirik tertanam (embedded lyrics), dan daftar "Up Next".
- **Manajemen Library Fleksibel**: Pilih folder musik kustom, lakukan incremental scan otomatis, atau full rescan manual untuk memperbarui metadata.
- **Sistem Favorit**: Tandai lagu favoritmu dan simpan secara persisten.

## Perbaikan & Peningkatan (Changelog)

- **FIX**: Memperbaiki crash (NullPointerException) saat menerapkan konfigurasi dari Visualizer Studio.
- **PERF**: Migrasi dari sistem cache lama ke Room Database untuk stabilitas data library.
- **UI**: Navigasi baru menggunakan Bottom Navigation untuk perpindahan tab yang lebih lancar antara Visualizer, Now Playing, Library, dan Settings.
- **UI**: Implementasi Edge-to-Edge untuk tampilan yang lebih modern dan luas.
- **AUDIO**: Integrasi ExoPlayer yang lebih stabil untuk pemutaran musik di background.

## Catatan Versi Beta

Karena ini adalah versi Beta, mungkin masih terdapat beberapa bug. Kami sangat menghargai masukan Anda melalui menu "Log" atau dengan membuka Issue di repositori ini.

## Cara Instalasi

1. Unduh file `app-release.apk` di bawah.
2. Izinkan instalasi dari sumber tidak dikenal di perangkat Android Anda.
3. Buka aplikasi dan pilih folder musik Anda melalui tab Settings.

**Full Changelog**: [Link ke perbandingan commit jika ada]
