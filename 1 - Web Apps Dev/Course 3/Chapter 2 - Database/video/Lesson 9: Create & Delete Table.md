# Create & Delete Table

## NTH

***instruksi:** pgAdmin 11

Sebenernya kita sudah pernah membuat table. Sekarang kita akan coba gimana caranya membuat table baru dan menghapusnya menggunakan query.

***instruksi:** membuat table

1. Membuat table company

    ```sql
    CREATE TABLE COMPANY(
        ID INT PRIMARY KEY     NOT NULL,
        NAME           TEXT    NOT NULL,
        AGE            INT     NOT NULL,
        ADDRESS        CHAR(50),
        SALARY         REAL
    );
    ```

2. Refresh database

***instruksi:** menghapus table

1. Hapus table db_test

    ```sql
    drop table test_db;
    ```

2. Refresh database
