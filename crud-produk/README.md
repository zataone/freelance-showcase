# CRUD Produk API dengan Laravel

Contoh implementasi API CRUD untuk produk menggunakan Laravel. Ini adalah salah satu task yang sering diminta dalam proyek backend maupun fullstack.

## 🔧 Teknologi

- Laravel 10
- MySQL
- Laravel Resource & Form Request

## 📦 Fitur

- Tambah Produk
- Lihat Daftar Produk
- Update Produk
- Hapus Produk
- Validasi Input
- Resource Response JSON

## 📸 Cuplikan Kode

**ProductController.php**

```php
public function store(StoreProductRequest $request)
{
    $product = Product::create($request->validated());
    return new ProductResource($product);
}

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
```
