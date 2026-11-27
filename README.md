# E-CSSD RSUD Ciamis — Proyek Android WebView

Proyek Android Kotlin/Gradle ini membungkus Google Apps Script Web App Anda menjadi aplikasi Android native (`E-CSSD RSUD Ciamis.apk`).

## Konfigurasi
- **Nama Aplikasi**: E-CSSD RSUD Ciamis
- **Nama File APK**: `E-CSSD RSUD Ciamis.apk`
- **Package ID**: `com.rsudciamis.ecssd`
- **Versi**: `1.0.0` (code 1)
- **Target Entry**: `file:///android_asset/index.html`

---

## Cara 1: Build File .APK Otomatis di Cloud (Tanpa Android Studio)

1. Buat repository baru di **GitHub** (bisa private atau public).
2. Ekstrak file `.zip` ini dan unggah seluruh isinya ke repository tersebut (pastikan folder `.github/workflows/build-apk.yml` ikut terunggah).
3. Buka tab **Actions** di repository GitHub Anda, pilih workflow **Build Android APK**, lalu klik **Run workflow** (atau otomatis berjalan saat `push`).
4. Setelah selesai (~2 menit), unduh artifact **`E-CSSD-RSUD-Ciamis-apk`** di bagian **Artifacts** yang berisi file **`E-CSSD RSUD Ciamis.apk`**.

---

## Cara 2: Build File .APK Secara Lokal dengan Android Studio

1. Ekstrak file `.zip` ini ke sebuah folder.
2. Buka **Android Studio** -> **Open** -> pilih folder hasil ekstrak.
3. Tunggu proses **Gradle Sync** selesai.
4. Klik menu **Build** -> **Build Bundle(s) / APK(s)** -> **Build APK(s)**.
5. File APK akan berada di `app/build/outputs/apk/debug/E-CSSD RSUD Ciamis-debug.apk`.
