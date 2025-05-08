# Upload Gambar dan Simpan Path ke Database (Laravel)

Contoh implementasi upload gambar dari form ke server Laravel, kemudian menyimpan path file-nya ke database.

## 🔧 Teknologi

- Laravel 10
- Storage Filesystem
- Form Request Validation

## 📦 Fitur

- Upload gambar saat membuat produk
- Validasi file gambar (ukuran & format)
- Simpan nama file ke kolom `image`
- Menyimpan file ke `storage/app/public/products`

## 🛠️ Setup Singkat

````bash
php artisan storage:link


## 📸 Cuplikan Kode

Controller
```php
if ($request->hasFile('image')) {
    $file = $request->file('image');
    $filename = time() . '.' . $file->getClientOriginalExtension();
    $file->storeAs('public/products', $filename);
    $data['image'] = 'products/' . $filename;
}

Model
```php
protected $fillable = ['name', 'price', 'image'];

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
