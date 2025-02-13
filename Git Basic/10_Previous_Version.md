# MELIHAT VERSI SEBELUMNYA

## Melihat Versi File Pada Commit Tertentu

Jika ingin melihat kembali isi file1.txt pada commit tertentu, gunakan perintah berikut:

```bash
git checkout <hash> -- file1.txt
```

> **Catatan:** Isi `file1.txt` akan berubah sesuai dengan commit `<hash>` yang dipilih dan akan masuk ke **staging area**.

## Jika Ingin Membatalkan Perubahan

Jika ingin membatalkan perubahan dan mengembalikan file1.txt ke kondisi sebelumnya, lakukan dua langkah ini:

- ### Mengembalikan dari staging area ke working directory

  ```bash
  git restore --staged file1.txt
  ```

- ### Mengembalikan isi file ke kondisi sebelum diubah

  ```bash
  git restore file1.txt
  ```
