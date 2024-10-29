# labpy02
Nama        : Sayyid Sulthan Abyan <p>

Kelas       : TI.24.A.5 <p>

Nim         : 312410496 <p>

Mata kuliah : Bahasa Pemrograman <p>

## Program pemesanan tiket bioskop
### Flowchart
![gambar 1](screenshot/ft1.png)

### Berikut adalah penjelasan terkait flowchart di atas 

- **Mulai:** Proses dimulai dengan langkah ini, ditandai oleh simbol oval. <p>
![gambar 4](screenshot/ft4.png)

- **Inisialisasi Harga Tiket:** <p>
Tiket Reguler: Rp50.000 <p>
Tiket VIP: Rp100.000 <p>
Diskon Member: 20% <p>
Tentukan harga untuk tiket reguler dan tiket VIP, serta diskon yang diberikan untuk member <p>
![gambar 5](screenshot/ft5.png)

- **Input Tipe Tiket:** Pengguna diminta untuk memasukkan tipe tiket yang ingin dibeli, apakah "reguler" atau "VIP". <p>
![gambar 6](screenshot/ft6.png)

- **Input Status Member:** Pengguna diminta untuk memasukkan status keanggotaan mereka, apakah memiliki kartu member ("ya") atau tidak ("tidak"). <p>
![gambar 7](screenshot/ft7.png)

- **Validasi Tipe Tiket:** Program memeriksa apakah tipe tiket yang diinput adalah "reguler" atau "VIP": <p>
Jika tipe tiket adalah "reguler", lanjutkan ke langkah berikutnya dengan harga tiket diatur ke Rp50.000. <p>
Jika tipe tiket adalah "VIP", lanjutkan ke langkah berikutnya dengan harga tiket diatur ke Rp100.000. <p>
Jika tipe tiket bukan "reguler" atau "VIP", anggap sebagai input yang tidak valid dan minta pengguna untuk memasukkan tipe tiket yang benar. <p>
![gambar 8](screenshot/ft8.png)

- **Periksa Apakah Harga Tidak Nol:** <p>
Program memeriksa apakah harga tiket sudah diatur (tidak nol): <p>
Jika harga sudah diatur, lanjutkan ke langkah berikutnya. <p>
Jika harga belum diatur (nol), kembali ke input tipe tiket. <p>
![gambar 9](screenshot/ft9.png)

- **Cek Status Member dan Hitung Diskon:** <p>
Program memeriksa apakah pengguna memiliki kartu member: <p>
Jika pengguna memiliki kartu member ("ya"), harga akhir dihitung dengan memberikan diskon 20%. <p>
Jika pengguna tidak memiliki kartu member ("tidak"), harga akhir tetap sama dengan harga tiket tanpa diskon. <p>
![gambar 10](screenshot/ft10.png)

- **Tampilkan Harga Akhir:** Program menampilkan total harga tiket yang harus dibayar oleh pengguna. <p>
![gambar 11](screenshot/ft11.png)

- **Selesai:** Proses selesai, ditandai oleh simbol oval. <p>
![gambar 12](screenshot/ft12.png)

### Program python
seperti ini jika algoritma di atas yang di buat dalam bentuk flowchart di jadikan sebuah program dengan bahasa python
![gambar 13](screenshot/ft2.png)

### Hasil eksekusi 
ini hasil eksekusi dari kode program di atas
![gambar 14](screenshot/ft3.png)

## Membuat kalkulator sederhana
### Flowchart
![gambar 13](screenshot/ft3.png)
**penjelasan unutk flowchart di atas**
- **Mulai:** Awal proses.
- **Input Angka Pertama:** Meminta pengguna memasukkan angka pertama.
- **Input Angka Kedua:** Meminta pengguna memasukkan angka kedua.
- **Input Operator Aritmatika:** Meminta pengguna memasukkan operator aritmatika (penjumlahan, pengurangan, perkalian, atau pembagian).
- **Pilih Operator Aritmatika:**
Jika operator adalah +, lakukan penjumlahan.
Jika operator adalah -, lakukan pengurangan.
Jika operator adalah *, lakukan perkalian.
Jika operator adalah /, lakukan pembagian (dengan pengecekan pembagian nol).
Jika operator tidak valid, tampilkan pesan kesalahan.
- **Hitung Hasil:** Hitung hasil operasi aritmatika berdasarkan operator yang dipilih.
- **Tampilkan Hasil:** Tampilkan hasil perhitungan kepada pengguna.
- **Selesai:** Akhir proses.
