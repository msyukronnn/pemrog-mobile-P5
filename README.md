# Keamanan Data & HTTP Dasar

Proyek ini mempelajari penggunaan flutter_secure_storage untuk menyimpan data sensitif terenkripsi dan pengambilan data REST API menggunakan http dengan penanganan error yang aman.
---
# Topik Utama Praktikum

Secure Storage (flutter_secure_storage): Menyimpan data sensitif (token auth & PIN) secara terenkripsi (AES-256 di Android / Keychain di iOS), berbeda dengan SharedPreferences yang menyimpan plaintext.

HTTP GET Request (http): Mengambil data JSON dari REST API publik (JSONPlaceholder) dan menampilkannya di ListView.

Penanganan Error: Mengantisipasi kegagalan jaringan menggunakan try-catch, TimeoutException, dan SocketException.

Secure Logging: Memastikan data sensitif (seperti token atau password) tidak pernah dicetak ke console log (print).
---
# Cara Menjalankan

```bash
# Get dependencies
flutter pub get

# Run app
flutter run
```
