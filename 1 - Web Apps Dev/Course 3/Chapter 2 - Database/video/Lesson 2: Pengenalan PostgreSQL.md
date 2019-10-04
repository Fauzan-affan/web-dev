# Perkenalan PostgreSQL

## TH / animation

Apa itu PostgreSQL? PostgreSQL atau (Post-gress-SQL) adalah sebuah *relational database manajemen system* (RDBMS) yang dikembangkan oleh tim relawan yang ada di seluruh dunia yang bersifat *open source*, artinya siapa saja bisa mengembangkannya. PostgreSQL tidak dikelola oleh perusahaan atau badan swasta lainnya, sehingga *source code* (kode programn) yang tersedia bisa di dapatkan secara gratis.

Perbedaan yang paling mendasar antara postgres (sebutan untuk postgreSQL) dengan sistem relasional standar adalah, kemampuan postgres yang memungkinkan *user* untuk mendefinisikan SQL-nya sendiri, terutama untuk pembuatan *function*.

Hal ini dimungkinkan karena informasi yang tersimpan pada postgres tidak hanya tabel dan kolom saja, melainkan tipe, fungsi, dan informasi lainnya.

Kesemuanya itu disatukan dalam bentuk *class* yang memungkinkan *user* untuk merubahnya. Dengan model *class* ini postgres lebih mudah dikembangkan oleh *user* dan bisa mendefinisikan sebuah tabel sebagai turunan (mewariskan semua sifatnya) dari tabel lain *(inheritance)*. Di mana pada *database* konvensional hal seperti itu hanya bisa dilakukan dengan mengganti *source code* nya atau menggunakan modul tambahan.

Kelebihan lain dari postgres adalah dukungan antar muka (GUI) dari berbagai bahasa pemrograman seperti *Perl, PHP, C++, Phyton, Java,* dan masih banyak lagi. Postgres juga mempunyai kemampuan untuk membuat konektifitas dengan *database* lain seperti *pgdump, Interbase, pgaccess,* dan hampir semua *database* pada *Linux*. Karena kemampuan itulah wajar bila orang yang telah mencoba postgres menjadi kecanduan dan sulit untuk pindah ke *database* lain.

Saat ini postgres telah banyak digunakan oleh berbagai perusahaan besar, salah satu contoh pengguna postgres di indonesia adalah Rumah Sakit Pertamina.
