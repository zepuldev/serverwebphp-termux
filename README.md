Serverweb termux APACHE, PHP, MYSQL, COMPOSER dan PHPmyadmin.

Pertama:
```markdown
install git terlebih dahulu dengan command  
```text
pkg install git
```


kedua: 
jalankan command berikut
```text
git clone https://github.com/zhux01/serverwebphp-termux.git
```

ketiga:
masuk ke folder serverwebphp-termux dengan command 
```text
cd serverwebphp-termux
```

keempat:
jalankan perintah ini copas text yang ada di bawah.
```text
chmod +x installserver setupserver startserver stopserver mysqld
```

kelima: 
jalankan perintah ini
```text
bash installserver
```

keenam: 
jalankan perintah ini
```text
bash setupserver
```

ketujuh:
izinkan akses storage dengan command berikut
```text
termux-setup-storage
```

lalu buat folder htdocs di penyimpanan internal hp kalian dan buat projek php kalian disitu

lalu untuk menjalankan servernya jalankan dengan perintah berikut :

For Start :
```text
startserver
```
For Stop :
```text
stopserver
```

ingat❗ huruf kecil semua perintahnya 😊

untuk mengakses phpmyadmin gunakan url berikut

http://localhost:8080/phpmyadmin

username dan password PHPmyadmin
user: root
password kosongkan

goodluck 👍
