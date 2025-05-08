# Role Akses Sederhana (User & Admin)

Contoh implementasi kontrol akses berbasis role di Laravel, dengan 2 role utama: User dan Admin. Role ditentukan pada model User, dan middleware memastikan kontrol akses API.

## 📦 Endpoint

| Method | Endpoint     | Deskripsi                 |
| ------ | ------------ | ------------------------- |
| GET    | /admin/users | Lihat semua user (Admin)  |
| GET    | /profile     | Lihat profil (User/Admin) |
| POST   | /register    | Registrasi user           |
| POST   | /login       | Login dan dapatkan token  |

## 🔧 Teknologi

- Laravel 10
- Middleware untuk role
- Token API Auth

## 📝 Catatan

- Role dibedakan menggunakan kolom `role` pada tabel `users`.
- Admin hanya bisa mengakses `/admin/users`, sedangkan user biasa hanya bisa akses `/profile`.
- Cuplikan kode hanya sebagian dari keseluruhan implementasi.
- Tidak untuk penggunaan komersial tanpa izin.
- Kode lengkap hanya ditampilkan setelah ada kesepakatan kerja.
- Untuk review demo, silakan hubungi saya.

---

## 📬 Kontak

📧 email: sayakeren@gmail.com
📱 WhatsApp: +62 812-xxxx-xxxx
🌐 LinkedIn: [linkedin.com/in/sayakeren](https://linkedin.com/in/sayakeren)
📂 Portfolio lainnya: [github.com/username/freelance-showcase](https://github.com/username/freelance-showcase)

```

```
