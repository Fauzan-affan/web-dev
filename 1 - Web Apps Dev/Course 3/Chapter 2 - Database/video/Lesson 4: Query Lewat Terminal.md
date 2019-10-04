# Query Lewat Terminal

## NTH

***instruksi:** Buka postgreSQL 11

Kita bisa menjalankan query lewat console atau terminal, seperti masuk ke database tertentu, melihat semua daftar database yang ada, membuat database baru, dll.

Jangan lupa nyalakan postgresnya terlebih dahulu.

***instruksi:**

1. Masuk sebagai postgres

    ```sql
    psql postgres
    ```

2. Melihat semua database yang ada

    ```sql
    \l
    ```

3. Membuat database baru

    ```sql
    create database nama_db;
    ```

4. Connect database

    ```sql
    \c nama_db;
    ```

5. Melihat semua table yang ada

    ```sql
    \dt
    ```

6. Menghapus database

    ```sql
    drop database nama_db;
    ```

7. Keluar dari console postgre

    ```sql
    \q
    ```
