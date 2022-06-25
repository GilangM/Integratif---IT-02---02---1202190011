1. Langkah pertama dalam install Laravel adalah masuk Command Prompt. Caranya adalah klik Win+R lalu ketik cmd dan klik **OK**

   ![](E:\PEMROGAMAN INTERGRATIF\Progres 1\1.JPG)

2. Sebelum melakukan instalasi Laravel, arahkan Command Prompt atau terminal menuju direktori file server. Lokasi file server pada XAMPP secara default berada pada direktori xampp/htdocs. Masukan perintah ini pada jendela Command Prompt untuk masuk ke direktori htdocs.

   ```markdown
   cd \xampp\htdocs
   ```

![](E:\PEMROGAMAN INTERGRATIF\Progres 1\2.JPG)

3. Selanjutnya jika sudah masuk direktori htdocs, Anda harus membuat request untuk mengambil (serta menginstall) file Laravel yang telah disediakan dalam repositori Github. Gunakan perintah ini untuk melakukan request:

   ```markdown
   composer create-project --prefer-dist laravel/laravel nama_projectmu
   ```

   Jika perintah telah berhasil dimasukkan, Composer akan mulai melakukan proses pengambilan data serta instalasi Laravel ke dalam direktori yang telah Anda tentukan. Pastikan bahwa koneksi internet dalam keadaan stabil agar tidak terjadi gangguan pada saat proses pengambilan data Laravel.

![](E:\PEMROGAMAN INTERGRATIF\Progres 1\3.JPG)

4. ​	Setelah proses download file Laravel selesai, nantinya akan ada folder baru pada direktori file server dengan nama sesuai nama project yang telah Anda tentukan sebelumnya pada folder /xampp/htdocs.

   ​	Untuk memastikan bahwa Laravel sukses terinstall dan siap untuk digunakan, arahkan Command Prompt atau Terminal menuju direktori yang telah Anda buat sebelumnya. Lalu, masukkan perintah berikut ke dalam Command Prompt atau Terminal:

   ```markdown
   Php artisan serve
   ```

![](E:\PEMROGAMAN INTERGRATIF\Progres 1\4.JPG)

5. Jika muncul tulisan `Laravel development server started` pada Command Prompt atau Terminal, langkah selanjutnya adalah membuka link yang telah disediakan oleh Laravel. Secara default, Anda akan diarahkan menuju alamat server,yaitu 127.0.0.1:8000. Nantinya, akan muncul tampilan homepage dengan tulisan Laravel di bagian tengah seperti pada gambar di bawah ini:

   ![](E:\PEMROGAMAN INTERGRATIF\Progres 1\5.JPG)

**Tahap 2 RSS**

1. Langkah pertama, ubah nama DB_DATABASE di .env sesuai dengan nama database yang sudah dibuat di php my admin

   ![](asset\1.JPG)

   ![](asset\2.JPG)

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

   ![](asset\3.JPG)

5. Jika sudah berhasil menjalankan perintah sebelumnya, tambahkan sebuah Route di web.php

   ![](asset\4.JPG)

6. Cek database di php my admin, untuk melihat apakah sudah terupdate atau belum

   ![](asset\5.JPG)

   ![](asset\6.JPG)

7. Langkah terakhir lakukan pengecekan RSS apakah sudah berhasil atau belum

   ![](asset\7.JPG)