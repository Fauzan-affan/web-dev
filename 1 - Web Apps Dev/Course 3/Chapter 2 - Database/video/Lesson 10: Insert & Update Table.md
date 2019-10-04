# Insert & Update Table

## NTH

***instruksi:** pgAdmin 11

Sebenernya kita sudah pernah membuat *insert*. Sekarang kita akan coba gimana caranya mengisikan *table* dan memperbarui *table* yang sudah ada.

***instruksi:** insert table

1. Insert table company

    ```sql
    insert into company values (1,'fauzan',17,'jakarta',2000);
    ```

2. Lihat valuenya

***instruksi:** update table

1. Update table db_test

    ```sql
    UPDATE company SET name = 'mantul' WHERE id = 1;
    ```

2. Refresh database
