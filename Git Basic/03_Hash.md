# SNAPSHOT

Pada Git, snapshot adalah rekaman kondisi seluruh repository pada saat commit dilakukan. Jika kita membuat perubahan pada beberapa file, Git akan menyimpan snapshot yang mencakup semua perubahan tersebut. Setiap snapshot merepresentasikan isi dari commit dan diidentifikasi dengan hash unik.

# HASH

Setiap snapshot yang dibuat akan memiliki hash unik sebagai identitasnya. Hash ini dihitung menggunakan algoritma SHA-1 sebagai checksum untuk memastikan integritas data.

# HEAD

Pada Git, HEAD adalah pointer yang menunjuk ke commit terakhir dalam branch yang sedang aktif.

Detached HEAD terjadi ketika HEAD tidak lagi menunjuk ke branch mana pun, melainkan langsung ke suatu commit tertentu. Hal ini biasanya terjadi saat kita checkout ke commit tertentu.

> Istilah seperti branch dan checkout dapat dipelajari lebih lanjut di pembahasan lain.
