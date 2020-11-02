# Step-2-login
Modul untuk login ke server.

![Login-User](https://github.com/rangkaidata/screenshot/blob/main/login.png)
<br>*Gambar 1. Login Untuk User.*

![Home-Menu](https://github.com/rangkaidata/screenshot/blob/main/home.png)
<br>*Gambar 2. User Sudah Berhasil Login ke Folder Home.*

Setelah User sudah membuat Register di modul register (Step-1-register). User baru telah terdaftar di server, kemudian user bisa langsung Login masuk ke folder user di server dengan modul Login seperti gambar 1. Apabila user berhasil login ke server (entri user name dan password tepat) maka user tersebut akan mendapat nomer login (blok) dari server seperti Gambar 2 diatas. 

Nomer Login tersebut menjadi ID disetiap transaksi mengirim data dan menerima data. Untuk membuat form login, langkah pertama adalah membuat form HTML, CSS seperti berikut:

# Step 2.1. Deklarasi Variabel.
# Step 2.2. Periksa Nomer Login.
# Step 2.3. Masuk ke Menu Home.
# Step 2.4. Ketika Tombol Login di Klik.
# Step 2.4.1. Masukkan Nilai Input ke Dalam Konstan obj.
# Step 2.4.2. Deklarasi Variabel XHR dan Parameter Untuk Data.
# Step 2.4.3. Fungsi Ketika Data Menerima Respon dari Server.
# Step 2.4.3.1. Bila Nilai XHR readyState sama dengan 4 (Empat).
# Step 2.4.3.1.1. Konversi Data Dari Server ke Dalam Bentuk Array Javascript
# Step 2.4.3.1.2. Kirim paket data ke Fungsi terimaData (Callback).
# Step 2.4.3.2. Bila Nilai XHR selain 4 (Empat).
# Step 2.4.4. Kirim Input Data ke Server.
# Step 2.5. Fungsi terimaData().
# Step 2.5.1. Cek Panjang Karakter Paket Data.
# Step 2.5.2. Bila Tidak ada Error.
# Step 2.5.3. Kirim Pesan Error ke User. 
