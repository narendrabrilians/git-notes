# RESET COMMIT

```bash
git reset <mode> <hash>
```

Reset commit berarti menggeser pointer HEAD ke commit tertentu. Setelah reset, commit baru akan dilakukan di posisi HEAD yang baru.

## Mode :

`--soft`

Memindahkan HEAD, commit yang dilewati tetap ada. Perubahan dari commit yang dilewati akan masuk ke staging area.

`--mixed` (default)

Memindahkan HEAD, commit yang dilewati tetap ada. Perubahan dari commit yang dilewati akan masuk ke working directory (tidak di-staging).

`--hard`

Memindahkan HEAD dan menghapus semua perubahan dari commit yang dilewati. Perubahan akan hilang dari staging area dan working directory.
