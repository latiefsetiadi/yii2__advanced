Akses website menggunakan url http://localhost/advanced/frontend/web/index.php
Lakukan import database yii2adv ke phpmyadmin

- Lakukan percobaan sign up
- password telah diberikan kondisi dengan syarat minimal 8 karakter dengan kombinasi angka, huruf kecil, dan huruf besar
- Klik tombol sign up maka akan dilakukan verifikasi email
Berhubung terdapat pembatasan permission untuk kirim email, maka untuk melakukan verifikasi email dilakukan secara manual dengan cara
1. cari folder runtime/mail
2. cari file 20240519-151233-5470-1034.eml dengan syarat kalau ingin melakukan verifikasi user terbaru maka cari file dengan tanggal yang terbaru
3. cari link seperti berikut contohnya seperti localhost/advanced/frontend/web/index.php?r=3Dsite%2Fverify-email&token=3D7=CBk58Pr2GOw1h4luVXVSUrwBLtMFM80_1716124353
4. Lakukan perubahan link menjadi localhost/advanced/frontend/web/index.php?r=site/verify-email&token=7CBk58Pr2GOw1h4luVXVSUrwBLtMFM80_1716124353
5. masing masing user memiliki token berbeda beda
6. lalu paste ke browser sehingga email akan terverifikasi
Setelah email terverifikasi akan langsung menuju ke dashboard karena otomatis login

- Percobaan login
Jika gagal akan memunculkan error, Jika berhasil akan diteruskan ke halaman dashboard
