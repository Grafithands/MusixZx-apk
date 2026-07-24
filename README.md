# MusixZX 🎵

![Version](https://img.shields.io/badge/version-1.0.0--beta.1-blue)
![Platform](https://img.shields.io/badge/platform-Android-green)
![License](https://img.shields.io/badge/license-MIT-orange)

Aplikasi musik Android modern dengan visualisasi musik yang menakjubkan dan pengalaman pengguna yang luar biasa.

## 📋 Daftar Isi

- [Fitur](#fitur)
- [Persyaratan](#persyaratan)
- [Instalasi](#instalasi)
- [Penggunaan](#penggunaan)
- [Teknologi](#teknologi)
- [Kontribusi](#kontribusi)
- [Lisensi](#lisensi)

## ✨ Fitur

### 🎨 Visualizer Studio
Buat dan terapkan preset visualizer kustom Anda sendiri secara langsung di dalam aplikasi tanpa perlu tools eksternal.

### 🎬 Milkdrop Visualizer
Engine visualisasi musik berbasis Milkdrop yang responsif terhadap audio secara real-time, memberikan pengalaman visual yang imersif.

### 📚 Database Library (Room)
- Pemindaian lagu yang cepat dan efisien
- Dukungan Flow untuk pembaruan UI yang reaktif
- Penyimpanan data yang stabil dan terstruktur

### ▶️ Now Playing Experience
- Tab "Now Playing" yang didesain ulang
- Kontrol penuh atas pemutaran musik
- Dukungan lirik tertanam (embedded lyrics)
- Daftar "Up Next" untuk antrian lagu berikutnya

### 🎯 Manajemen Library Fleksibel
- Pilih folder musik kustom
- Incremental scan otomatis
- Full rescan manual untuk memperbarui metadata

### ❤️ Sistem Favorit
Tandai lagu favoritmu dan simpan secara persisten untuk akses cepat.

## 💻 Persyaratan

- **Android**: API Level 24 (Android 7.0) atau lebih tinggi
- **RAM**: Minimal 2 GB
- **Storage**: Minimal 100 MB untuk instalasi aplikasi

## 🚀 Instalasi

### Dari APK
1. Unduh file `app-release.apk` dari [Releases](https://github.com/Grafithands/MusixZx-apk/releases)
2. Aktifkan "Instalasi dari sumber tidak dikenal" di pengaturan keamanan perangkat Android Anda
3. Buka file APK dan ikuti petunjuk instalasi
4. Jalankan aplikasi dan pilih folder musik Anda di tab Settings

### Dari Source (Developer)
```bash
git clone https://github.com/Grafithands/MusixZx-apk.git
cd MusixZx-apk
./gradlew installDebug
```

## 📖 Penggunaan

### Tab Utama

#### 🎨 Visualizer
- Putar musik dan nikmati visualisasi real-time
- Ketuk menu untuk mengakses Visualizer Studio
- Buat atau pilih preset visualizer yang berbeda

#### ▶️ Now Playing
- Kontrol pemutaran musik (play, pause, skip, previous)
- Lihat lirik tertanam jika tersedia
- Kelola antrian "Up Next"
- Lihat informasi lagu detail

#### 📚 Library
- Jelajahi semua lagu di perangkat Anda
- Filter dan cari lagu berdasarkan judul, artis, atau album
- Tandai sebagai favorit dengan mengklik tombol hati
- Lihat statistik library (total lagu, ukuran, dll)

#### ⚙️ Settings
- Pilih folder musik kustom
- Jalankan incremental scan atau full scan
- Atur preferensi tampilan
- Kelola izin aplikasi

## 🛠️ Teknologi

### Arsitektur
- **Pattern**: MVVM (Model-View-ViewModel)
- **Language**: Kotlin
- **Coroutines**: Untuk operasi asynchronous

### Libraries Utama
- **Room Database**: Penyimpanan data lokal yang efisien
- **Flow**: Reactive programming untuk UI updates
- **ExoPlayer**: Pemutaran audio yang stabil
- **Jetpack Compose** atau **XML Layouts**: UI development
- **Milkdrop Engine**: Visualisasi musik

### Build Tools
- **Gradle**: Build system
- **Android Gradle Plugin**: v7.0+

## 🐛 Catatan Beta

Ini adalah versi beta (v1.0.0-beta.1) dan mungkin masih terdapat beberapa bug. Kami sangat menghargai masukan Anda.

### Pelaporan Bug
Jika menemukan bug, silakan:
1. Buka menu "Log" di aplikasi untuk melihat error messages
2. Buat [Issue](https://github.com/Grafithands/MusixZx-apk/issues) di repositori ini dengan detail lengkap
3. Sertakan: versi Android, langkah reproduksi, screenshot/video jika perlu

## 📝 Changelog

### v1.0.0-beta.1
- ✅ **FIX**: Memperbaiki crash (NullPointerException) saat menerapkan konfigurasi dari Visualizer Studio
- 🚀 **PERF**: Migrasi dari sistem cache lama ke Room Database untuk stabilitas data library
- 🎨 **UI**: Navigasi baru menggunakan Bottom Navigation untuk perpindahan tab yang lebih lancar
- 📱 **UI**: Implementasi Edge-to-Edge untuk tampilan yang lebih modern
- 🔊 **AUDIO**: Integrasi ExoPlayer yang lebih stabil untuk pemutaran musik di background

[Lihat full changelog](./MusixZX-v1.0.0-beta.1-release-notes.md)

## 🤝 Kontribusi

Kami menyambut kontribusi dari komunitas! Untuk berkontribusi:

1. Fork repositori ini
2. Buat branch fitur (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan (`git commit -m 'Add AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buat Pull Request

## 📄 Lisensi

Proyek ini dilisensikan di bawah MIT License - lihat file [LICENSE](LICENSE) untuk detail lengkap.

## 👤 Author

**Grafithands**
- GitHub: [@Grafithands](https://github.com/Grafithands)

## 💬 Dukungan & Feedback

Punya pertanyaan atau saran? Silakan:
- Buka [Issues](https://github.com/Grafithands/MusixZx-apk/issues)
- Diskusikan di [Discussions](https://github.com/Grafithands/MusixZx-apk/discussions)
- Hubungi melalui profil GitHub

---

Dibuat dengan ❤️ oleh Grafithands
