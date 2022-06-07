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