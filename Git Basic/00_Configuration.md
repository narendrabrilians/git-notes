# CONFIGURATION USERNAME & USER EMAIL

Setiap perubahan yang dilakukan akan disisipkan informasi identitas, sehingga terlihat siapa yang melakukan perubahan. Oleh karena itu, kita perlu mengonfigurasi username dan email.

```bash
git config --global user.name "Your Name"
```

```bash
git config --global user.email "youremail@company.com"
```

<br>

# MENGGUNAKAN VISUAL STUDIO CODE

Agar lebih mudah, kita bisa menjadikan Visual Studio Code sebagai editor default untuk Git serta alat perbandingan (diff tool) default.

## Default Editor

Default Editor berarti editor yang akan digunakan Git secara otomatis ketika Git membutuhkan editor teks, seperti saat menulis pesan commit atau mengedit merge commit.

```bash
git config --global core.editor "code --wait"
```

> Menggunakan --wait agar terminal menunggu sampai editor (Visual Studio Code) ditutup.

## Difftool

```bash
git config --global diff.tool "default-difftool"
```

```bash
git config --global difftool.default-difftool.cmd "code --wait --diff \$LOCAL \$REMOTE"
```

<br>

# MELIHAT SELURUH CONFIGURATION

```bash
git config --list --show-origin
```

`Q` atau `q` untuk keluar
