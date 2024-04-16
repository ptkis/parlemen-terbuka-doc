# RFC001 Usulan Desain Sistem Parlemen Terbuka

## A Latar Belakang

1. Ada negara/daerah yang menggunakan open parliament. Contoh di [Estonia](https://x.com/oomdamar/status/1779761008925716732), [Washington DC](https://x.com/thomaskatalis/status/1779498298514284771).
2. [Pembuatan UU 4 tahun belakang berubah banyak. Prosesnya banyak tertutup.](https://x.com/oomdamar/status/1779753598186123587)

## B Tujuan

1. Masyarakat dapat menerima kabar apabila ada isu yang terkait.
2. Mengawasi kinerja parlemen.

## C Usulan

1. Buat organisasi baru di github untuk host repo
2. RUU disimpan menggunakan markdown
3. Convert ke pdf/html/ebook menggunakan pandoc dengan CI/CD github actions sehingga bisa otomatis setiap PR.
4. Publish ke github pages dan ke openparliament.id
5. Ada notifikasi melalui telegram/email bagi yang subscribe 
5. Ada project roadmap untuk timeline RUU
6. Open issues/discussion supaya masyarakat bisa diskusi
7. Pelibatan media/jurnalis yang peduli
8. Teknologi dibuat open source

![Gambar 1 Desain Sistem Parlemen Terbuka](desain/desain-sistem-parlemen-terbuka.svg)
