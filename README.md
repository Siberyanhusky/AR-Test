# 🕌 AR Candi Borobudur - Pembelajaran Sejarah Interaktif

Web-based Augmented Reality (AR) untuk pembelajaran sejarah Candi Borobudur menggunakan teknologi AR.js dan A-Frame. Dirancang khusus untuk siswa SMA agar dapat belajar sejarah dengan cara yang lebih interaktif dan menyenangkan.

## ✨ Fitur

- 📱 **Web-based AR** - Tidak perlu install aplikasi, buka langsung di browser
- 🎯 **Marker-based** - Menggunakan Hiro marker untuk tracking
- 🏛️ **Model 3D Candi Borobudur** - Visualisasi 3D yang detail
- 🔄 **Auto Rotate** - Model bisa diputar otomatis
- 📖 **Informasi Lengkap** - Panel informasi edukatif tentang sejarah Candi Borobudur
- 📲 **Mobile-Friendly** - Responsif untuk smartphone dan tablet
- ⚡ **Interaktif** - Info muncul otomatis saat marker terdeteksi

## 🚀 Cara Menggunakan

### 1. Download Marker
Download dan print **Hiro Marker** dari link ini:
[Download Hiro Marker](https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/hiro.png)

Atau bisa juga buka marker di layar perangkat lain (tablet/laptop).

### 2. Akses Web AR
Buka link berikut di smartphone/tablet:
```
https://[username-github-anda].github.io/[nama-repo]/
```

### 3. Izinkan Akses Kamera
Ketika diminta, klik **"Allow"** untuk mengizinkan browser mengakses kamera.

### 4. Scan Marker
Arahkan kamera ke Hiro Marker yang sudah di-print/dibuka. Model 3D Candi Borobudur akan muncul di layar beserta informasi edukatifnya!

### 5. Interaksi
- **Panel Info**: Akan muncul otomatis saat marker terdeteksi
- **Tombol Auto Rotate**: Klik untuk memutar model secara otomatis
- **Tombol Info Lengkap**: Klik untuk membuka kembali panel informasi jika tertutup

## 🛠️ Teknologi yang Digunakan

- **[AR.js](https://ar-js-org.github.io/AR.js-Docs/)** - Library AR untuk web
- **[A-Frame](https://aframe.io/)** - Framework WebVR/WebXR
- **WebGL** - Rendering 3D di browser
- **WebRTC** - Akses kamera perangkat

## 📁 Struktur File

```
ar-borobudur/
├── index.html       # File utama aplikasi AR
├── Borobudur.glb    # Model 3D Candi Borobudur
└── README.md        # Dokumentasi (file ini)
```

## 📋 Persyaratan

- Browser modern yang support WebRTC dan WebGL:
  - ✅ Chrome (Android/Desktop)
  - ✅ Safari (iOS/macOS)
  - ✅ Firefox (Android/Desktop)
  - ✅ Edge (Desktop)
- Koneksi HTTPS (otomatis di GitHub Pages)
- Kamera perangkat yang berfungsi
- Pencahayaan yang cukup untuk deteksi marker

## 🎓 Materi Pembelajaran

Aplikasi ini mencakup informasi lengkap tentang:

- **Sejarah Candi Borobudur**
  - Periode pembangunan (780-830 M)
  - Dinasti Syailendra
  - Raja Samaratungga dan arsitek Gunadharma

- **Latar Belakang Pembangunan**
  - Fungsi sebagai tempat pemujaan
  - Simbol legitimasi kekuasaan

- **Struktur dan Arsitektur**
  - Kamadhatu (dunia nafsu)
  - Rupadhatu (dunia bentuk)
  - Arupadhatu (dunia tanpa bentuk)

- **Makna Filosofis**
  - Konsep kosmologi Buddhis
  - Perjalanan spiritual menuju nirwana
  - Relief sebagai media pengajaran

## 🔧 Instalasi untuk Development

Jika ingin menjalankan di local:

1. Clone repository
```bash
git clone https://github.com/[username]/[nama-repo].git
cd [nama-repo]
```

2. Jalankan local server (pilih salah satu):

**Menggunakan Python:**
```bash
python -m http.server 8000
```

**Menggunakan Node.js:**
```bash
npm install -g http-server
http-server -p 8000
```

3. Buka browser dan akses: `http://localhost:8000`

## 🐛 Troubleshooting

### Kamera tidak bisa diakses
- Pastikan mengakses via HTTPS atau localhost
- Periksa permission kamera di browser settings
- Pastikan tidak ada aplikasi lain yang menggunakan kamera

### Marker tidak terdeteksi
- Pastikan pencahayaan cukup terang
- Jaga jarak kamera 20-50cm dari marker
- Pastikan marker tidak terlipat atau rusak
- Marker harus terlihat penuh di layar kamera

### Model 3D tidak muncul
- Periksa koneksi internet
- Pastikan file `Borobudur.glb` sudah terupload dengan benar
- Cek console browser untuk error (F12)

## 📝 Lisensi

Project ini dibuat untuk keperluan edukasi.

## 👨‍💻 Pengembang

Dikembangkan untuk pembelajaran sejarah siswa SMA.

## 🙏 Credit

- Model 3D Candi Borobudur
- AR.js by AR.js Organization
- A-Frame by Mozilla
- Materi sejarah dari berbagai sumber edukatif

---

**📧 Kontak & Support**

Jika ada pertanyaan atau masalah, silakan buat issue di repository ini.

**⭐ Jangan lupa kasih star jika project ini bermanfaat!**
