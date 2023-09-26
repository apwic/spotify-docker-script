# Milestone 2 IF3110 Pengembangan Aplikasi Berbasis Web

## Deskripsi Service

Repository ini berisi file `docker-compose.yaml` untuk melakukan build docker pada masing-masing repository lainnya untuk memudahkan.

## Cara Menjalankan Server

1. Pastikan docker desktop sudah dijalankan, disarankan untuk melakukan delete terlebih dahulu pada image MySQL yang sudah dimiliki sebelumnya
2. Clone semua repository lainnya yaitu:
```
https://github.com/apwic/spotify-clone
https://github.com/apwic/spotify-soap-service
https://github.com/apwic/extended-spotify-clone
https://github.com/apwic/extended-spotify-rest-service
```
2. Jalankan perintah `docker-compose up --build`
3. Buka satu-persatu service yang diinginkan.

> Untuk melihat daftar port pada docker, jalankan perintah dapat dilihat pada aplikasi docker desktop sesuai dengan container yang dijalankan
