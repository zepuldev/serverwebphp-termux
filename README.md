Serverweb termux PHP, MYSQL, COMPOSER dan PHPmyadmin.

Pertama:
install git terlebih dahulu dengan comman 
pkg install git

kedua: 
jalankan command berikut
git clone https://github.com/zhux01/serverwebphp-termux.git

ketiga:
masuk ke folder serverwebphp-termux dengan perintah 
cd serverwebphp-termux

keempat:
jalankan perintah ini copas text yang ada di bawah.

chmod +x installserver setupserver startserver stopserver mysqld

kelima: 
jalankan perintah ini
bash installserver

keenam: 
jalankan perintah ini
bash setupserver

ketujuh:
izinkan akses storage dengan perintah berikut
termux-setup-storage

lalu buat folder htdocs di storage hp kalian dan buat projek php kalian disitu

lalu untuk menjalankan servernya jalankan dengan perintah berikut :

startserver untuk menjalankan
stopserver untuk menghentikan

ingat❗ huruf kecil semua perintahnya 😊

untuk mengakses phpmyadmin gunakan url berikut

http://localhost:8080/phpmyadmin

username dan password PHPmyadmin
user: root
password kosongkan

goodluck 👍
