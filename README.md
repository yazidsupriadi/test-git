# Belajar Git

Apa itu Git.? Git adalah salah satu sistem pengontrol versi (Version Control System) pada proyek perangkat lunak yang diciptakan oleh Linus Torvalds.(sumber : https://www.petanikode.com/git-untuk-pemula/)

### Bagaimana cara memakai Git.?

pertama kali kita harus install Git Terlebih Dahulu

setelah git diinstal lalu login dengan konfigurasi dengan memasukan username dan email dengan perintah sebagai berikut 

    git config --global user.name "Saya"
    git config --global user.email saya@gmail.com

lalu bisa dicek konfigurasinya dengan menggunakan perintah berikut 

    git config --list

lalu buat repo dengan perintah 
    git init .
    
lalu bisa cek status dengan perintah 
    git status

lalu bisa menambahkan file file dengan contoh sebagai berikut
1. untuk menambahkan file tertentu
    git add READ.md
2. untuk menambahkan semua file
    git add .
     
lalu melakukan commit dengan perintah
    git commit -m "keterangan commit"
  
 lalu bisa melakukan push kode dengan perintah
     git push -u origin master
