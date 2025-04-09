<h1>Serverweb termux APACHE, PHP, MYSQL, COMPOSER dan PHPmyadmin.</h1>

**Pertama** : <br>
install git terlebih dahulu dengan command
```text
pkg install git
```


**kedua** :<br>
jalankan command berikut
```text
git clone https://github.com/zhux01/serverwebphp-termux.git
```

**ketiga** :<br>
Lalu lihat isi file dulu dengan command <br>
```text
ls
```
masuk ke folder serverwebphp-termux dengan command 
```text
cd serverwebphp-termux
```

**keempat** :<br>
jalankan perintah ini copas text yang ada di bawah.
```text
chmod +x installserver setupserver startserver stopserver mysqld
```

**kelima** : <br>
jalankan perintah ini
```text
bash installserver
```

**keenam**: <br>
jalankan perintah ini
```text
bash setupserver
```

**ketujuh** :<br>
izinkan akses storage dengan command berikut
```text
termux-setup-storage
```

**lalu buat folder htdocs di penyimpanan internal hp kalian dan buat projek php kalian disitu**

<h4>PENTING :</h4>
untuk mengatasi phpmyadmin yang sudah deprecated harap melakukan langkah-langkah dibawah ini<br>
masuk ke folder phpmyadmin dengan menjalankan perintah dibawah ini:
```text
cd $PREFIX/share/phpmyadmin
```

<h4>Jalankan ketiga perintah dibawah</h4>

First :
```text
composer update slim/psr7
```
Second :
```text
composer require web-auth/webauthn-lib:^5.2.2 --dev --with-all-dependencies
```
Thirth :
```text
composer require thecodingmachine/safe:^3.0.2 --dev --with-all-dependencies
```



lalu untuk menjalankan servernya jalankan dengan perintah berikut :

For Start :
```text
startserver
```
For Stop :
```text
stopserver
```

**ingat❗ huruf kecil semua perintahnya 😊**

untuk mengakses phpmyadmin gunakan url berikut :
```text
http://localhost:8080/phpmyadmin
```
username dan password PHPmyadmin
user: root
password kosongkan

<h3>GOODLUCK 😎</h3>
