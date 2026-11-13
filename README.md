# ROVE HUB

Aplikasi kerja internal staf Rove, dibuka di https://nrnholding.github.io/rove-hub/
(link lama `/rove-hub-test/` diteruskan ke sini).

## Pemakaian

1. Buka alamat HUB, lalu **Masuk** dengan akunmu sendiri. Data tersimpan di
   backend berkunci dan tersinkron ke semua perangkat; tanpa akun, data tak bisa
   dibaca.
2. Klik **🔔 Nyalakan notifikasi browser** di kotak jabatan kalau ingin diberi tahu
   saat ada tugas baru.

Jumlah tugas yang menunggumu muncul di judul tab, misalnya `(3) ROVE HUB`, jadi
terlihat walau tabnya di latar belakang.

## Yang tidak boleh masuk repo ini

Repo ini publik dan hanya berisi kode aplikasi (`index.html`) serta penanda versi
(`versi.txt`). Jangan pernah menaruh token, kata sandi, rahasia, atau tanda tangan
asli di sini.

## Memperbarui

Berkas sumbernya ada di folder kerja Rove, bukan di sini. Versi baru diterbitkan
dari salinan admin (`terbitkan.js`), lalu `index.html` dan `versi.txt` di-commit
dan di-push. GitHub Pages menerbitkannya ulang sekitar satu menit kemudian. Jangan
mengedit `index.html` langsung di GitHub.
