# TeknoBicara

Aplikasi Android sederhana untuk mengubah teks menjadi suara menggunakan fitur Speech Synthesis pada WebView Android.

## Membuat APK melalui GitHub

1. Buat repository GitHub bernama `TeknoBicara`.
2. Unggah seluruh isi folder proyek ini ke repository (termasuk folder tersembunyi `.github/workflows`).
3. Pastikan branch bernama `main`.
4. Buka tab **Actions**. Jika diminta, izinkan GitHub Actions.
5. Pilih workflow **Build TeknoBicara APK**, lalu tekan **Run workflow**. Workflow juga berjalan otomatis ketika ada commit ke branch `main`.
6. Setelah selesai dengan status hijau, buka run terbaru, lalu unduh artifact **TeknoBicara-APK**.
7. Ekstrak ZIP artifact dan pasang `app-debug.apk` di HP Android.

Catatan: APK debug cocok untuk uji coba dan pemasangan manual. Untuk menerbitkan ke Google Play, dibutuhkan proses signing/release tersendiri. Fitur suara memakai dukungan text-to-speech yang tersedia di perangkat; pastikan mesin TTS bahasa Indonesia tersedia di pengaturan Android.
