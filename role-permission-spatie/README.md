# Role & Permission Dasar dengan Laravel Spatie

Contoh penggunaan package [Spatie Laravel Permission](https://spatie.be/docs/laravel-permission) untuk implementasi sistem peran dan hak akses sederhana.

## 🔧 Teknologi

- Laravel 10
- Spatie Laravel Permission
- Seeder + Middleware

## 📦 Fitur

- Tambah role dan permission via seeder
- Assign role ke user
- Middleware berbasis role/permission
- Cek akses di controller

## 🛠️ Instalasi

````bash
composer require spatie/laravel-permission
php artisan vendor:publish --provider="Spatie\Permission\PermissionServiceProvider"
php artisan migrate



## 📸 Cuplikan Kode

Seeder Contoh
```php
Role::create(['name' => 'admin']);
Permission::create(['name' => 'manage-users']);

Assign Role ke User
```php
$user->assignRole('admin');

Middleware
Tambahkan ke route:
Route::middleware(['role:admin'])->group(function () {
    Route::get('/admin-only', fn() => 'Halo Admin');
});

## 📝 Catatan

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
