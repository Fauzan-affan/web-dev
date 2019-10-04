# Tipe Data Integer

## NTH

***instruksi:** pgAdmin 11

Ada banyak sekali tipe data yang disedikan oleh postgres, oleh karena itu kita tidak akan mencontohkan semuanya.

Kita akan membahas tentang tipe data yang akan sangat sering digunakan nanti yaitu *integer*. *Integer* adalah tipe data yang hanya bisa dimasukan oleh angka bilangan bulat. Jumlah maksimal *value* yang dapat ditampung oleh integer adalah 2147483647 (ketikin di kolom query).

***instruksi:**

1. Tekan tombol petir dibagian kiri atas pojok untuk memunculkan kolom query

2. Buat table baru dengan nama tb_test, dgn tipe data integer, dan execute

    ```sql
    create table tb_test(
    testing integer
    );
    ```

3. Refresh table

4. Masukkan value baru

    ```sql
    insert into tb_test values (2147483647);
    ```

5. Lihat isi baris barunya, klik tombol table disamping petir buat bikin query

6. Contohin kalo lebih besar dari value yang ada 2147483648 dan jelasin error
