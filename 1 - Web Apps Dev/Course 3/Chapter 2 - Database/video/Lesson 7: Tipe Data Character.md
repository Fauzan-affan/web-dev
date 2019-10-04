# Tipe Data Character

## NTH

***instruksi:** pgAdmin 11

Kita akan membahas tentang tipe data *character*. *Character* adalah tipe data yang bisa dimasukan oleh huruf. Jumlah maksimal *value* yang dapat ditampung oleh *character* adalah 255 (ketikin di kolom query). Perlu diketahui juga pada saat membuat tipe data *character*, kita butuh mendefinisikan nilainya juga.

***instruksi:**

1. Tekan tombol petir dibagian kiri atas pojok untuk memunculkan kolom query

2. Buat table baru dengan nama tb_barang, dgn tipe data character, dan execute

    ```sql
    create table tb_barang(
    nama_barang character(30)
    );
    ```

3. Refresh table

4. Masukkan value baru, execute

    ```sql
    insert into tb_barang values ('es krim');
    ```

5. Lihat isi baris barunya, klik tombol table disamping petir buat bikin query
