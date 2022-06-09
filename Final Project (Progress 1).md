NAMA  : Gilang Maulana

NIM   : 1202190011


1. Langkah pertama dalam install Laravel adalah masuk Command Prompt. Caranya adalah klik Win+R lalu ketik cmd dan klik **OK**

![1](https://user-images.githubusercontent.com/26424175/172338215-659b4b98-3172-4e50-be9a-d66dc1e340e0.JPG)

2. Sebelum melakukan instalasi Laravel, arahkan Command Prompt atau terminal menuju direktori file server. Lokasi file server pada XAMPP secara default berada pada direktori xampp/htdocs. Masukan perintah ini pada jendela Command Prompt untuk masuk ke direktori htdocs.

   ```markdown
   cd \xampp\htdocs
   ```

![2](https://user-images.githubusercontent.com/26424175/172338222-94e69ba9-3ea9-49b3-9593-5868f41b77c3.JPG)


3. Selanjutnya jika sudah masuk direktori htdocs, Anda harus membuat request untuk mengambil (serta menginstall) file Laravel yang telah disediakan dalam repositori Github. Gunakan perintah ini untuk melakukan request:

   ```markdown
   composer create-project --prefer-dist laravel/laravel nama_projectmu
   ```

   Jika perintah telah berhasil dimasukkan, Composer akan mulai melakukan proses pengambilan data serta instalasi Laravel ke dalam direktori yang telah Anda tentukan. Pastikan bahwa koneksi internet dalam keadaan stabil agar tidak terjadi gangguan pada saat proses pengambilan data Laravel.

![3](https://user-images.githubusercontent.com/26424175/172338198-dcc2e0fc-8e49-4ebd-9bfa-995cf2a60b27.JPG)

4. ​	Setelah proses download file Laravel selesai, nantinya akan ada folder baru pada direktori file server dengan nama sesuai nama project yang telah Anda tentukan sebelumnya pada folder /xampp/htdocs.

   ​	Untuk memastikan bahwa Laravel sukses terinstall dan siap untuk digunakan, arahkan Command Prompt atau Terminal menuju direktori yang telah Anda buat sebelumnya. Lalu, masukkan perintah berikut ke dalam Command Prompt atau Terminal:

   ```markdown
   Php artisan serve
   ```
![4](https://user-images.githubusercontent.com/26424175/172338205-e6d0f404-c6ab-49e4-a3be-34ccdcd693e8.JPG)

5. Jika muncul tulisan `Laravel development server started` pada Command Prompt atau Terminal, langkah selanjutnya adalah membuka link yang telah disediakan oleh Laravel. Secara default, Anda akan diarahkan menuju alamat server,yaitu 127.0.0.1:8000. Nantinya, akan muncul tampilan homepage dengan tulisan Laravel di bagian tengah seperti pada gambar di bawah ini:

   ![5](https://user-images.githubusercontent.com/26424175/172338210-53d45a38-2a7c-4825-b9e2-a59bc06f7015.JPG)
