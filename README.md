# MP3 Player

Aplikasi pemutar musik Android sederhana yang memindai lagu lokal dan menyediakan kontrol pemutaran dasar.

## Fitur

- Memindai audio lokal melalui MediaStore
- Mendukung izin audio Android 13+ dan Android lama
- Play, pause, lagu berikutnya, dan lagu sebelumnya
- Pencarian lagu
- Indikator durasi dan waktu pemutaran
- Build APK otomatis melalui GitHub Actions

## Build

```bash
./gradlew assembleDebug
```

Hasil debug APK tersedia di:

```text
app/build/outputs/apk/debug/app-debug.apk
```

## Catatan

- Minimum Android: API 24 (Android 7.0)
- GitHub Pages pada proyek ini bersifat opsional untuk dokumentasi/unduhan; aplikasi utama tetap Android APK.
