Sebelum membuat Rest Api, pertama unduh terlebih dahulu codeigniter dan library Rest Api server. Setelah itu extrak codeigniter dan library rest server yang telah di download tadi ke dalam forder xampp lalu rubah nama folder. Untuk mengecek apakah sudah berhasil terinstal, buka url http://127.0.0.1/nama_folder/index.php/res_server pada browser,jika telah berhasil di download, buat database lalu sesuaikan nama database dan username di application>config>database.php. Setelah itu barulah kita dapat melakukan metode GET, POST,PUT.

# GET
Buka postman untuk menguji program yang telah dibuat, dengan cara msukkan link http://127.0.0.1/nama_folder/index.php/kontak di aaddress bar , pilih metode GET kemudian klik send. 

# POST 
Untuk mengirimkan data baru dari clien ke server Rest Api. Lakukan cara yang sama seperti di metode GET, klik body pada menu, klik x-www-form-urlencoded, isikan key beserta value nya lalu klik send. Untuk melihat data baru pilih metode GET.

# PUT
PUT untuk memperbarui data atau mengupdate data yang sudah ada di server. Untuk menguji program yang telah dibuat, seperti sebelumnya, buka postman. Pilih metode PUT copy link http://127.0.0.1/nama_forlder/index.php/kontak , klik body, pilih x-www-form-urlencoded, masukkan id dan velue id yang akan dirubah, lalu send. Pilih metode GET untuk melihat hasil data baru.

# DELETE
Ini untuk menghapus data yang telah ada. Uji hasilnya di postman. Pilih metode DELETE, masukkan link seperti sebelumnya, klik body, pilih x-www-form-urlencoded, masukkan velue id dan key id yang akan dihapus, lalu send. Ubah ke metode GET untuk melihat data baru.





