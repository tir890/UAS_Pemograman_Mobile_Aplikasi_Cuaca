# 🌦️ Cuacaku

## Deskripsi Aplikasi

Cuacaku adalah aplikasi mobile berbasis Android yang dikembangkan menggunakan **Kotlin** dan **Jetpack Compose** untuk menampilkan informasi cuaca secara real-time berdasarkan lokasi pengguna.

Aplikasi memanfaatkan **Open-Meteo Weather API** sebagai sumber data cuaca dan mengimplementasikan **Rule-Based AI** sederhana untuk memberikan rekomendasi aktivitas maupun barang yang perlu dipersiapkan sesuai kondisi cuaca saat ini.

Selain menampilkan suhu dan kondisi cuaca, aplikasi juga menghadirkan tampilan antarmuka yang berubah secara dinamis mengikuti kondisi cuaca sehingga memberikan pengalaman pengguna yang lebih menarik.

---

# ✨ Fitur Utama

## 1. Splash Screen
- Menampilkan logo aplikasi saat pertama kali dibuka.
- Sebagai halaman pembuka sebelum masuk ke aplikasi.

---

## 2. Izin Lokasi (Location Permission)
- Meminta izin lokasi kepada pengguna.
- Menggunakan koordinat **Latitude** dan **Longitude** sebagai parameter untuk mengambil data cuaca.
- Pada versi UTS, lokasi masih menggunakan koordinat Jakarta sebagai simulasi.

---

## 3. Dashboard Cuaca
- Menampilkan suhu saat ini.
- Menampilkan kondisi cuaca.
- Menampilkan ikon cuaca.
- Background berubah otomatis sesuai kondisi cuaca:
  - ☀️ Cerah
  - ☁️ Mendung
  - 🌧️ Hujan

---

## 4. AI Recommendation
- Tombol AI berada di pojok kanan bawah.
- Menggunakan pendekatan **Rule-Based AI**.
- Memberikan rekomendasi berdasarkan weather code dari API.

Contoh:
- Cerah → Gunakan sunscreen
- Mendung → Siapkan payung
- Hujan → Bawa payung dan jas hujan

---

# 🛠 Teknologi

- IDE : Android Studio
- Bahasa : Kotlin
- UI : Jetpack Compose
- Networking : Retrofit
- API : Open-Meteo Weather API
- AI : Rule-Based AI (If-Else)

---

# 📂 Struktur Project

```
com.example.cuacaku
│
├── api
│   ├── RetrofitClient.kt
│   └── WeatherApi.kt
│
├── model
│   └── WeatherResponse.kt
│
├── ui
│   ├── screen
│   │   ├── SplashScreen.kt
│   │   ├── LocationScreen.kt
│   │   └── WeatherScreen.kt
│   │
│   └── theme
│
├── utils
│   └── WeatherUtils.kt
│
└── MainActivity.kt
```

---

# 📱 Tangkapan Layar (Screenshots)

# 📱 Tangkapan Layar (Screenshots)

| Splash Screen | Izin Lokasi | Dashboard | AI Recomendation |
|:-------------:|:-----------:|:-----------:|:-------------:|
| ![satu](https://github.com/tir890/UAS_Pemograman_Mobile_Aplikasi_Cuaca/blob/57966e3b1e359b69a4e5323ac1e6f830e4b025b0/splash%20screen.jpeg) | ![dua](https://github.com/tir890/UAS_Pemograman_Mobile_Aplikasi_Cuaca/blob/57966e3b1e359b69a4e5323ac1e6f830e4b025b0/izinkan%20lokasi.jpeg) | ![tiga](https://github.com/tir890/UAS_Pemograman_Mobile_Aplikasi_Cuaca/blob/57966e3b1e359b69a4e5323ac1e6f830e4b025b0/dashboard.jpeg) | ![empat](https://github.com/tir890/UAS_Pemograman_Mobile_Aplikasi_Cuaca/blob/57966e3b1e359b69a4e5323ac1e6f830e4b025b0/ai%20rekomendasi.jpeg) |

---

# 🚀 Cara Menjalankan

1. Clone repository
2. Buka project menggunakan Android Studio
3. Sync Gradle
4. Jalankan aplikasi pada Emulator atau Android Device
5. Pastikan perangkat memiliki koneksi internet

---

Mata Kuliah : Pemrograman Mobile

Project UAS
