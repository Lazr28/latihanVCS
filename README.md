# TUTORIAL PENGGUNAAN GIT

1. Download Git pada Link berikut https://git-scm.com/
2. Install Git
3. Buat Folder baru di lokasi yang di inginkan
4. klik kanan pada area kosong di dalam folder tersebut
5. lalu pilih **Git Bash Here**
![Screenshot 1](https://github.com/Lazr28/latihanVCS/blob/master/screenshot/SS1.png?raw=true)
6. kemudian jalankan perintah ` git init `
    pada saat pertama kali membuat repository git, kita perlu melakukan configurasi username & email pengguna dengan perintah berikut

    `git config --global user.name “nama_user”`
    `git config --global user.email “email_user”`
    ![Screenshot 2](https://github.com/Lazr28/latihanVCS/blob/master/screenshot/SS2.png?raw=true)
7. untuk menambahkan file kita bisa menggunakan perintah berikut
    `echo “# Latihan 1” >> README.md`
         echo "isi file / isi teks" >> namafile.typefile
8.  Menambahkan file baru atau menyimpan perubahan ke staging menggunakan perintah berikut
    `git add README.md`
9. lalu untuk menerapkan ke repository kita bisa menggunakan perintah 
    `git commit -m "komentar"`
    ![Screenshot 3](https://github.com/Lazr28/latihanVCS/blob/master/screenshot/SS3.png?raw=true)
    > hasil komentar pada git commit akan muncul seperti ini

10. lalu kita membuat repository server
    - server yang akan kita gunakan adalah http://github.com
    - anda harus membuat akun terlebih dahulu
    - pada laman github klik start a project lalu klik new Repository
        -   isi nama repositorynya, misalkan LatihanVCS
        -   lalu klik tombol Create Repository

11. Setelah kita selesai membuat repository server, kita akan menambahkan remote repository ke repository lokal kita.
    -   untuk menambahkan remote repository server, gunakan perintah berikut 
        ####git remote add origin [url]####
        `git remote add origin https://github.com/Lazr28/latihanVCS.git`

        ![Screenshot 4](https://github.com/Lazr28/latihanVCS/blob/master/screenshot/SS4.png?raw=true)


12. Untuk mengirim perubahan ke server, kita dapat menjalankan perintah 
        `git push -u origin master`

        > untuk pertama kali akan diminta memasukan username dan password pada akun github.com lalu akan diminta juga izin / authorization

13. Melihat Hasil pada server repository
        > Buka halaman github.com lalu pilih repositorynya atau anda dapat membuka link repository yang anda simpan
        > Maka perubahan akan terlihat pada laman tersebut


