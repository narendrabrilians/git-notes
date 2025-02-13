# MELIHAT SNAPSHOT SEBELUMNYA

## Berpindah ke Snapshot (Commit) Tertentu

Untuk melihat isi repository pada commit tertentu, gunakan perintah berikut:

```bash
git checkout <hash>
```

> Mode detached HEAD berarti HEAD sedang menunjuk langsung ke commit tertentu, bukan ke branch terbaru.

## Kembali ke Snapshot (Commit) Terbaru di Branch Saat Ini

Jika ingin kembali ke commit terbaru di branch yang sedang digunakan:

```bash
git checkout <nama-branch>
```

## Melihat Nama Branch Saat Ini

Untuk mengetahui branch yang sedang aktif:

```bash
git branch --show-current
```
