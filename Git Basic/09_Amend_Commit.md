# AMEND COMMIT

Jika ada perubahan yang tertinggal setelah melakukan commit, kita bisa menambahkannya ke commit terakhir tanpa membuat commit baru.

Daripada melakukan `git reset` lalu commit ulang, kita bisa menggunakan **amend commit** untuk memperbarui commit terakhir secara otomatis.

```bash
git commit --amend -m "pesan commit baru"
```

> Jika sudah melakukan push, gunakan amend commit dengan hati-hati karena akan mengubah riwayat commit.
