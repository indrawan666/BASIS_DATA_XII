
Isi dari video yang ada di Youtobe 

# 1. Permasalahan

- **Duplikasi data**: pelanggan dan produk dalam spreadsheat(tabel) dan produk dalam spreadsheat(tabel) menyebabkan kebingungan, seperti beberapa pelanggan dengan nama yang sama
  **Misal:** tiga pelanggan bernama Mary Johnson, yang menyebabkan kebingungan

- **Kesalahan Pengiriman:** produk yang salah bisa dikirim karena informasi pelanggan tidak terorganisir dengan baik 

# 2. Solusi

- Memisahkan informasi ke dalam tabel terpisah untuk setiap entitas,seperti tabel Pelanggan(Customers),product,pesanan(Order)

- Menggunakan ERD(Diagram Hubungan Entitas)untuk memvisualikasikan dan mendokumentasikan struktur database,memudahkan pengelolaan dan pembaruan data.

# 3. Konsep ERD

 **ERD** digunakan untuk mendefinisikan entitas(tabel) dan atribut(kolom) serta hubungan antara entitas setiap tabel seperti pelanggan,produk, dan pesanan.
setiap entitas memiliki atribut, misalnya:
  - Tabel Pelanggan: ID Pelanggan, Nama, Alamat, Email.![[Pasted image 20241024100307.png]]
   Tabel Produk: ID Produk, Nama Produk, Jumlah Stok, Harga.
  ![[Pasted image 20241024100342.png]]
  - Tabel Pesanan: ID Pesanan, Tanggal, ID Pelanggan, ID Produk, Alamat Pengiriman.
  ![[Pasted image 20241024100634.png]]
**Hubungan**: Menghubungkan tabel dengan kunci primer (misalnya, ID Pelanggan di tabel Pelanggan) dan kunci asing (misalnya, ID Pelanggan di tabel Pesanan).

# 4. 3 Bentuk Pernyataan dalam Video

1. *I**dentifikasi Entitas dan Atribut*:** Tabel Pelanggan menyimpan informasi dasar pelanggan, dan tabel Produk menyimpan detail produk yang dijual.

2. *V**isualisasi Hubungan*:** Diagram ERD menunjukkan bagaimana tabel Pelanggan terhubung dengan tabel Pesanan melalui ID Pelanggan.

3. *P**engelolaan Data yang Efisien***: Dengan tabel terpisah, perubahan seperti pembaruan alamat pelanggan dapat dilakukan di satu tempat, mengurangi kesalahan dan duplikasi.



