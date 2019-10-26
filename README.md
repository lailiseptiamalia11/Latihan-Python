LANGKAH-LANGKAH MEMBUAT REPOSITORY LOCAL DAN REPOSITORY PADA GITHUB DAN CARA MEMBUAT FILE README.md

Sebelumnya kalian harus "MEMBUAT AKUN GITHUB" dan "MENGINSTAL SOFTWARE GIT"

1. Membuat akun github di https://github.com
2. Masukkan username, Email aktif dan Password yang akan kalian gunakan untuk mengkses akun github kalian
![1](https://user-images.githubusercontent.com/56987138/67617109-ea407e00-f809-11e9-8f93-837daa85e8fe.png)

3. Kemudian lakukan verifikasi
![2](https://user-images.githubusercontent.com/56987138/67615814-f7a23c00-f7fa-11e9-867d-fccc34ab933a.png)

4. Lalu pilih ""FREE $0 USD"
![3](https://user-images.githubusercontent.com/56987138/67616908-d6941800-f807-11e9-843a-7397deb148ae.png)

5. Pilih "A LITTLE" dan klik "COMPLETE SET UP"
![5](https://user-images.githubusercontent.com/56987138/67616942-2e328380-f808-11e9-9e49-d9d6c83c410b.png)

6. Lalu kalian akan mendapatkan email dan verifikasikan email kalian
![7](https://user-images.githubusercontent.com/56987138/67616953-6e920180-f808-11e9-9de3-195f19b4e3d1.png)

7. Lalu kalian akan dialihkan ke laman github untuk membuat repository baru. Isi repository name lalu klik "CREATE REPOSITORY"
![8](https://user-images.githubusercontent.com/56987138/67617034-4f47a400-f809-11e9-85a5-b89ed93a81e3.png)

8. Seperti inilah tampila repository yang baru
![9](https://user-images.githubusercontent.com/56987138/67616976-b6188d80-f808-11e9-9e9a-f68d77b67ffc.png)

9. Download dan instal software git di https://git-scm.com sesuai dengan spesifikasi laptop kalian, bagi pengguna windows download untuk versi windows.
![10](https://user-images.githubusercontent.com/56987138/67617069-97ff5d00-f809-11e9-9f75-3bfa2ba14270.png)

10. Install software klik dengan mengklik 2 kali pada software yang telah diunduh, setelah itu akan keluar tampilan seperti ini. klik next
![11](https://user-images.githubusercontent.com/56987138/67617142-4c00e800-f80a-11e9-9003-b119f525b426.png)

11. Selanjutya tentukan lokasi folder untuk menginstal git
![12](https://user-images.githubusercontent.com/56987138/67617143-4d321500-f80a-11e9-8c05-ccd96996a5cc.png)

12. Lalu klik terus "NEXT" sampe ada tampilan seperti ini lalu klik "INSTALL"
![21](https://user-images.githubusercontent.com/56987138/67617158-810d3a80-f80a-11e9-80ba-3a5b9ae67bfb.png)

13. Software git sedang diinstal tunggu sampe proes selesai 100%
![22](https://user-images.githubusercontent.com/56987138/67617163-89fe0c00-f80a-11e9-9ce8-aea5407f49db.png)

14. Proses instalasi git selesai dilakukan

![23](https://user-images.githubusercontent.com/56987138/67617421-2de8b700-f80d-11e9-8426-ce89a529dfa0.png)
   Cek untuk memastikan apakah git bisa digunakan dengan cara membuka "COMMAND PROMPT" dan ketik "git version", jika muncul versi git maka git sudah siap digunakan
![24](https://user-images.githubusercontent.com/56987138/67617182-be71c800-f80a-11e9-859d-04a5608b3d13.png)

15. Buatlah folder baru di directory kalian lalu klik kanan pada folder tersebut dan pilih git bash here
![25](https://user-images.githubusercontent.com/56987138/67617366-b31f9c00-f80c-11e9-891a-6ba7f91c40c1.png)

16. Lalu konfigurasi dengan menggunakan perintah "git config --global user.name" dan "git config --global user.email", masukkan user name dan akun email yang kalian gunakan untuk untuk akun github kalian
![26](https://user-images.githubusercontent.com/56987138/67617423-393be280-f80d-11e9-8b44-09eb4db9b52e.png)

17. Buat directory baru dengan menggunakan perintah "mkdir latihan1" lalu "cd latihan1"
![27](https://user-images.githubusercontent.com/56987138/67617424-3a6d0f80-f80d-11e9-9b2a-178cc264cd99.png)

18. Jalankan perintah "git init" untuk membuat file kosong berformat git
![28](https://user-images.githubusercontent.com/56987138/67617425-3b9e3c80-f80d-11e9-98b2-4008c5d1c1ae.png)

19. Lalu buat file bernama readme.md dengan memasukkan perintah "echo "#latihanpython1">>README.md"
![29](https://user-images.githubusercontent.com/56987138/67617427-3c36d300-f80d-11e9-8a1d-7c9b33ea9c18.png)

20. Untuk melihat file ketikkan perintah  "ls -l"
![30](https://user-images.githubusercontent.com/56987138/67617475-c1ba8300-f80d-11e9-8715-837e1b4138e2.png)

20. Ketik perintah "git add" untuk menambahkan file readme.md pada repository local
![31](https://user-images.githubusercontent.com/56987138/67617476-c2531980-f80d-11e9-8a17-77f32b564915.png)

21. Ketik perintah "git commit-m" untuk menyimpan perubahan yang ada dalam database repository
![32](https://user-images.githubusercontent.com/56987138/67617477-c2ebb000-f80d-11e9-8667-75bd223a7e12.png)

22. Masuk lagi ke website git hub lalu masuk ke repository yang sebelumnya di buat. Pada bagian quick setup terdapat url github kita.
![33](https://user-images.githubusercontent.com/56987138/67617478-c3844680-f80d-11e9-9fe4-d7942c0f1df2.png)

23. Lalu ketikkan perintah "git remote add origin [url]" contoh "git remote add origin https://github.com/lailiseptiamalia11/Latihan-Python.git " 

24. Untuk mengirim perubahan local repository ke server gunakan perintah git push "git push -u origin master"

25. Dan untuk melihat hasilnya cek di github dan lihat reepositorinya

Jika ingin melakukan clone repository gunakan perintah "git clone [ url ]" CONTOH " git clone https://github.com/lailiseptiamalia11/Latihan-Python.git " 
