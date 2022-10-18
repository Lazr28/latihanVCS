# TUTORIAL PENGGUNAAN GIT

1. Download Git pada Link berikut https://git-scm.com/
2. Install Git
3. Buat Folder baru di lokasi yang di inginkan
4. klik kanan pada area kosong di dalam folder tersebut
5. lalu pilih **Git Bash Here**
![Screenshot 1](image/SS1.png)
6. kemudian jalankan perintah ` git init `
    pada saat pertama kali membuat repository git, kita perlu melakukan configurasi username & email pengguna dengan perintah berikut
    `git config --global user.name “nama_user”`
    `git config --global user.email “email_user”`
    ![Screenshot 2](image/SS2.png)
7. untuk menambahkan file kita bisa menggunakan perintah berikut
    `echo “# Latihan 1” >> README.md`
         echo "isi file / isi teks" >> namafile.typefile
8.  Menambahkan file baru atau menyimpan perubahan ke staging menggunakan perintah berikut
    `git add README.md`
9. lalu untuk menerapkan ke repository kita bisa menggunakan perintah 
    `git commit -m "komentar"`