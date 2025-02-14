# ALIAS

Git memiliki fitur Alias, yang memungkinkan kita membuat nama lain untuk perintah Git agar lebih mudah digunakan.

## Cara Menggunakannya

Misalnya, kita ingin membuat alias `logone` untuk menjalankan `git log --oneline`, gunakan perintah berikut:

```bash
git config --global alias.logone "log --oneline"
```

Setelah itu, kita bisa menjalankan:

```bash
git logone
```

Perintah ini akan berfungsi sama seperti:

```bash
git log --oneline
```
