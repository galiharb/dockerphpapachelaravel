# dockerphpapachelaravel

### Konfigurasi Awal
```
 - Ganti IP Address
 - Ganti Nama Container
 - Ganti Nama Network
```

Selanjutnya jalankan perintah berikut
```
docker-compose up -d --build
```

### Cara Menjalankan Composer
```
docker-compose exec -T web composer update
```

### Jika Aplikasi PHP Native
```
  - Ubah path DocumentRoot /var/www/app/public menjadi /var/www/app pada file default.conf
  - Jalankan kembali docker-compose up -d --build
```
