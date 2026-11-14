DESAIN RUMAH - proyek APK (WebView + editor denah 3D)

CARA DAPAT APK DARI HP (tanpa Android Studio):
1. Buat akun GitHub, buat repo baru (kosong).
2. Upload SELURUH isi folder ini (termasuk folder .github) ke repo.
   Jika folder .github tidak ikut ke-upload, buat manual file
   .github/workflows/build-apk.yml dari isi file yang sama.
3. Buka tab Actions -> workflow "Build APK" jalan otomatis (+/- 5 menit).
4. Selesai -> klik run-nya -> Artifacts -> DesainRumah-APK -> download, ekstrak, install app-debug.apk.

PREVIEW CEPAT (tanpa APK): buka app/src/main/assets/index.html di browser HP.

STATUS: editor (index.html) dites di Chromium headless. Build APK / workflow BELUM dites.
Catatan: tombol simpan/ekspor file tidak jalan di WebView; desain tersimpan otomatis di app.
