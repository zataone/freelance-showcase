# Export Data ke Excel (Laravel + Maatwebsite Excel)

Contoh penggunaan package `Maatwebsite Excel` untuk mengekspor data model ke file Excel (.xlsx) secara cepat dan rapi.

## 🔧 Teknologi

- Laravel 10
- Maatwebsite Excel

## 📦 Fitur

- Export semua data produk ke Excel
- Route khusus untuk export
- Bisa disesuaikan untuk export filter/tanggal, dll.

## 🛠️ Instalasi

````bash
composer require maatwebsite/excel
php artisan make:export ProductExport --model=Product


## 🚀 Route Contoh
```php
Route::get('/export/products', [ProductController::class, 'export']);



## 📝 Catatan
- Ekspor berbasis collection dari model.
- File akan otomatis diunduh saat route dipanggil.
- Ekstensi default .xlsx.
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
