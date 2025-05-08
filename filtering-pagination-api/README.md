# Filtering & Pagination API JSON (Laravel)

Contoh endpoint REST API untuk menampilkan data produk dengan fitur filtering (by name, min price) dan pagination menggunakan Laravel.

## 🔧 Teknologi

- Laravel 10
- Resource Collection
- Pagination
- Query Filtering

## 📦 Fitur

- Filter berdasarkan nama produk (like)
- Filter berdasarkan harga minimum
- Pagination respons standar (meta + links)

## 🛠️ Route API

```http
GET /api/products?name=susu&min_price=10000&page=2
```

## 🔁 Response Contoh

{
"data": [
{ "id": 2, "name": "Susu Ultra", "price": 12000 },
...
],
"meta": {
"current_page": 2,
"last_page": 4,
...
},
"links": {
"first": "...",
"last": "...",
...
}
}

## 📝 Catatan

- Bisa dikombinasikan dengan resource/transformer untuk response yang rapi.
- Cocok untuk dipakai di aplikasi mobile & dashboard admin.
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
