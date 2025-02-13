# IGNORE

Terkadang kita tidak ingin Git melacak semua file dalam proyek, misalnya file konfigurasi lingkungan (`.env`) atau file sementara.

## Cara Menggunakan

1. Buat file `.gitignore` di root repository

2. Tambahkan daftar file atau folder yang ingin diabaikan di dalamnya

## Contoh `.gitignore`

### Mengabaikan Folder

Gunakan format berikut untuk mengabaikan folder tertentu:

```gitignore
nama_folder/
```

### Mengabaikan File dengan Ekstensi Tertentu

Gunakan wildcard `*` untuk mengabaikan semua file dengan ekstensi tertentu:

```gitignore
*.backup
```

### Mengabaikan File Tertentu

Tulis nama file langsung untuk mengabaikannya:

```gitignore
nama_file.txt
```
