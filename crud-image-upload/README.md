# CRUD API Upload Gambar + Validasi + Simpan Path

Contoh implementasi unggah file gambar lewat API, menyimpannya di storage Laravel, dan menyimpan path-nya ke database.

## 📦 Endpoint

| Method | Endpoint          | Deskripsi                |
| ------ | ----------------- | ------------------------ |
| GET    | /post-images      | List semua post gambar   |
| POST   | /post-images      | Tambah post + upload img |
| GET    | /post-images/{id} | Lihat detail             |
| PUT    | /post-images/{id} | Edit data & gambar       |
| DELETE | /post-images/{id} | Hapus data & file        |

---

## 🔧 Teknologi

- Laravel 10
- Storage (public)
- Form Request Validation
- JSON Resource

## 📂 File disimpan di:

`storage/app/public/uploads/`

Akses publik: `http://your-app.test/storage/uploads/filename.jpg`

## 📝 Catatan

- Jalankan `php artisan storage:link` untuk symlink storage ke public.
- Pastikan folder `storage/app/public/uploads` memiliki permission tulis.
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

```

```
