# Integratif---IT-02---02---1202190011
**Tahap 2 RSS**

1. Langkah pertama, ubah nama DB_DATABASE di .env sesuai dengan nama database yang sudah dibuat di php my admin

   ![](asset/1.JPG)

   ![](asset/2.JPG)

2. Buat file RssController.php dan NewsController.php di app/http/controllers

   ```markdown
   php artisan make:controller RSSController
   php artisan make:controller NewsController
   ```

3. Coba jalankan migration dan seeding dengan perintah berikut :

   ```markdown
   php artisan migrate:fresh
   php artisan migrate --seed
   ```

4. Setelah sukses menjalankan perintah 3, lanjutkan dengan edit file di NewsController.php

   ![](asset/3.JPG)

5. Jika sudah berhasil menjalankan perintah sebelumnya, tambahkan sebuah Route di web.php

   ![](asset/4.JPG)

6. Cek database di php my admin, untuk melihat apakah sudah terupdate atau belum

   ![](asset/5.JPG)

   ![](asset/6.JPG)

7. Langkah terakhir lakukan pengecekan RSS apakah sudah berhasil atau belum

   ![](asset/7.JPG)
   
   **Tahap 3 RSS**
Berikut ditampilkan halaman RSS yang telah dibuat

Berikut Link RSS yang digunakan :

![3_1](https://user-images.githubusercontent.com/26424175/178131881-8d7e3262-02f7-4b1c-8e25-93b3c3940447.JPG)

1. https://www.antaranews.com/rss/ekonomi
2. https://feeds.fireside.fm/bibleinayear/rss
3. https://news.un.org/feed/subscribe/en/news/topic/economic-development/feed/rss.xml
