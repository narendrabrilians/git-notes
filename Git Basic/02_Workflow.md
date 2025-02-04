# THE THREE STATES

Ada tiga state dalam Git, yaitu Modified, Staged, dan Committed.

## 1. Modified

Modified berarti kita telah mengubah file, seperti menambahkan, mengedit, atau menghapus isinya.

## 2. Staged

Staged berarti kita telah **menandai** file yang telah dimodifikasi untuk disertakan dalam commit, sehingga siap untuk disimpan ke repository.

## 3. Committed

Committed berarti perubahan telah disimpan secara permanen di dalam repository.

<br>

# THREE SECTIONS

Tiga state yang telah dibahas sebelumnya terjadi di bagian yang berbeda, yaitu Working Directory, Staging Area, dan Repository.

![Three Sections](https://git-scm.com/book/en/v2/images/areas.png)

> Misalnya, kita melakukan perubahan pada file. Perubahan tersebut berada di Working Directory. Kemudian, gunakan `git add` untuk memasukkannya ke Staging Area. Jika sudah yakin, gunakan `git commit` untuk menyimpan perubahan secara permanen di Repository.
