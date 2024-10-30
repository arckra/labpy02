**Soal**
Latihan 3: Buat program python untuk kasus berikut:

Kasus 1: Program Pemesanan Tiket Bioskop
Buat program yang menghitung harga tiket bioskop. Tiket reguler berharga Rp50.000,
sedangkan tiket VIP berharga Rp100.000. Jika user memiliki kartu member, mereka
mendapatkan diskon 20% dari harga tiket. Program ini harus meminta tipe tiket dan status
member dari user, lalu menghitung total harga yang harus dibayar.
Petunjuk:
● Gunakan if else dan operator ternary.

**Jawaban**
Berikut ini adalah flowchart dari kasus 1 dan langkah-langkahnya
![Bioskop](https://github.com/user-attachments/assets/8be8f816-7cdd-4820-bdc0-1458de1284aa)


**Soal**
Kasus 2: Program Kalkulator Sederhana
Buat program kalkulator yang menerima dua angka dan satu operator aritmatika dari
pengguna (penjumlahan, pengurangan, perkalian, atau pembagian). Program akan
menghitung hasil sesuai dengan operator yang dipilih.
Petunjuk:
● Gunakan if elif else untuk menentukan operasi aritmatika.

**Jawaban**
Berikut ini adalah flowchart dari kasus 1 dan langkah-langkahnya
![kalkulator](https://github.com/user-attachments/assets/673b6f26-0764-47d5-a241-24db4459b708)

1. **Start**: Flowchart dimulai dari titik "Start".

2. **Tampilkan Judul Kalkulator**: Program menampilkan judul kalkulator, misalnya "Kalkulator Sederhana".

3. **Tampilkan Operator yang Tersedia**: Program menampilkan operator yang bisa dipilih, seperti `+`, `-`, `*`, dan `/`.

4. **Input Angka Pertama**: Pengguna memasukkan angka pertama untuk perhitungan.

5. **Validasi Input Angka Pertama**:
   - Program mengecek apakah input angka pertama valid (misalnya, apakah benar-benar angka).
   - Jika **tidak valid**, pengguna diminta memasukkan angka pertama lagi.
   - Jika **valid**, lanjut ke langkah berikutnya.

6. **Input Operator**: Pengguna memilih operator untuk operasi (misalnya, `+`, `-`, `*`, atau `/`).

7. **Input Angka Kedua**: Pengguna memasukkan angka kedua.

8. **Validasi Input Angka Kedua**:
   - Program mengecek apakah input angka kedua valid.
   - Jika **tidak valid**, pengguna diminta memasukkan angka kedua lagi.
   - Jika **valid**, lanjut ke langkah berikutnya.

9. **Cek Operator**: Program mengecek operator yang dipilih untuk menentukan jenis operasi yang akan dilakukan (penjumlahan, pengurangan, perkalian, atau pembagian).

10. **Perhitungan Berdasarkan Operator**:
    - Jika operator adalah **+**: Program menghitung penjumlahan `a + b`.
    - Jika operator adalah **-**: Program menghitung pengurangan `a - b`.
    - Jika operator adalah **\***: Program menghitung perkalian `a * b`.
    - Jika operator adalah **/**: Program mengecek apakah angka kedua (`b`) sama dengan 0:
      - Jika **`b = 0`** (pembagian dengan nol), program menampilkan pesan **"Error: Pembagian dengan nol!"** karena pembagian dengan nol tidak bisa dilakukan.
      - Jika **`b != 0`**, program menghitung hasil pembagian `a / b`.
    - Jika operator tidak sesuai dengan salah satu dari `+`, `-`, `*`, atau `/`, program menampilkan pesan **"Error: Operator tidak valid!"**.

11. **Tampilkan Hasil Perhitungan**: Setelah perhitungan selesai, program menampilkan hasil perhitungan kepada pengguna.

12. **Finish**: Program selesai dan flowchart berakhir.
