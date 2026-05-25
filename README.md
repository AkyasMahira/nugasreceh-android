# Nugas Receh - Android WebView App

Repository ini berisi kode sumber untuk aplikasi Android WebView resmi **Nugas Receh**. Aplikasi ini dirancang menggunakan Android Studio (Java) dengan fokus pada peningkatan UX agar terasa seperti aplikasi native saat mengakses platform utama.

## 🌐 Informasi Platform
* **Website Resmi:** [nugasreceh.com](https://nugasreceh.com/)
* **Instagram:** [@nugasreceh](https://www.instagram.com/nugasreceh/)

---

## 🚀 Fitur & Peningkatan UX
* **Custom Branding:** Nama dan icon aplikasi disesuaikan penuh dengan branding client.
* **Splash Screen:** Transisi layar pembuka yang *smooth* (fade-out) saat aplikasi pertama kali dijalankan.
* **Loading Indicator:** Progress bar horizontal yang informatif di bagian atas layar saat halaman web sedang dimuat.
* **Fullscreen Mode:** Tampilan bersih tanpa Action Bar bawaan Android untuk memaksimalkan area pandang konten website.
* **Smart Back Navigation:** Navigasi kembali native menggunakan `OnBackPressedDispatcher` AndroidX (kembali ke halaman web sebelumnya, bukan langsung keluar aplikasi).
* **Error Handling Page:** Tampilan halaman khusus yang bersih dilengkapi tombol "Coba Lagi" jika koneksi internet terputus atau website gagal dimuat.

---

## 🛠️ Spesifikasi Teknis
* **Bahasa Pemrograman:** Java
* **Minimum SDK:** API 24 (Android 7.0 Nougat)
* **Target SDK:** API 34+
* **Arsitektur Layout:** XML Multi-layer (RelativeLayout & LinearLayout)

---

## 📦 Output Produksi
Project ini dikonfigurasi untuk menghasilkan file `NugasReceh.apk` (Signed APK) versi Release yang optimal, ringan, dan siap diinstal langsung ke perangkat Android pengguna tanpa melalui Google Play Store (*sideloading*).
