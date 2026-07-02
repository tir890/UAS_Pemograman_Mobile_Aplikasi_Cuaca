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
| <img src="screenshots/splash.png" width="180"/> | <img src="screenshots/location.png" width="180"/> | <img src="screenshots/sunny.png" width="180"/> | <img src="screenshots/cloudy.png" width="180"/> |

---

# 🚀 Cara Menjalankan

1. Clone repository
2. Buka project menggunakan Android Studio
3. Sync Gradle
4. Jalankan aplikasi pada Emulator atau Android Device
5. Pastikan perangkat memiliki koneksi internet

---

Mata Kuliah : Pemrograman Mobile

Project UTS
