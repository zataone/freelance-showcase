# API Authentication dengan Laravel Sanctum

Contoh implementasi login, register, logout, dan profil ("me") berbasis token API menggunakan Laravel Sanctum. Sangat cocok untuk backend aplikasi mobile & frontend SPA (React, Vue).

## 🔧 Teknologi

- Laravel 10
- Laravel Sanctum
- Token Authentication

## 📦 Endpoint

| Method | Endpoint  | Deskripsi           |
| ------ | --------- | ------------------- |
| POST   | /register | Register user baru  |
| POST   | /login    | Login & ambil token |
| POST   | /logout   | Revoke token aktif  |
| GET    | /me       | Data user login     |

## 🛠️ Instalasi Sanctum

````bash
composer require laravel/sanctum
php artisan vendor:publish --provider="Laravel\Sanctum\SanctumServiceProvider"
php artisan migrate

Tambahkan middleware ke api di Kernel.php:
```php
'api' => [
    \Laravel\Sanctum\Http\Middleware\EnsureFrontendRequestsAreStateful::class,
    'throttle:api',
    \Illuminate\Routing\Middleware\SubstituteBindings::class,
],


## 📝 Catatan
- Gunakan Authorization: Bearer <token> pada setiap request setelah login.
- Logout akan menghapus token aktif user.
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
````
