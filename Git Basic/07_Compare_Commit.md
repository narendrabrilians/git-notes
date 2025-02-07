# MEMBANDINGKAN COMMIT

Perbandingan dilakukan berdasarkan hasil akhir dari setiap commit. Misalnya, commit hash1 memiliki daftar file tertentu, dan commit hash2 memiliki daftar file yang berbeda.

## Menggunakan git diff

```bash
git diff hash1 hash2
```

Menampilkan perbedaan antara dua commit dalam bentuk teks.

## Menggunakan git difftool

```bash
git difftool hash1 hash2
```

Menampilkan perbedaan menggunakan alat perbandingan visual (difftool yang sudah dikonfigurasikan).
