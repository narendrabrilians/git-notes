# REVERT COMMIT

git revert digunakan untuk membatalkan perubahan dari commit tertentu tanpa menghapus riwayat commit.

Perintah ini akan membuat commit baru yang membatalkan efek dari commit yang dipilih.

```bash
git revert <hash>
```

## Contoh:

Jika commit dengan hash `12345` menghapus file `config.js`, maka menjalankan perintah berikut akan membuat commit baru yang mengembalikan `config.js` seperti sebelum commit `12345` dibuat:

```bash
git revert 12345
```

> `12345` adalah hash dari commit yang ingin dibatalkan.

- `git revert` hanya membatalkan perubahan dari commit tertentu, bukan menghapusnya dari riwayat.

- Gunakan ini jika ingin membatalkan commit tanpa merusak histori, terutama jika commit tersebut sudah di-push ke remote repository.
