# Perkenalan REST API

## TH / animation

Dalam pembuatan aplikasi atau *web modern*, kita pasti tidak akan terlepas dari penggunaan REST API. Tapi apakah REST API itu?

REST merupakan singkatan dari *REpresentational State Transfer*. Secara singkat REST adalah cara kita untuk menggunakan *resource* (fungsi/*method*) yang ada di sebuah *server* dengan mengakses *url* yang telah disediakan.

Cara mengaksesnya tentu dengan menggunakan HTTP *(Hyper Text Transfer Protocol)* dengan *method* *(http verb)* yang umum digunakan yaitu:

1. `GET`, untuk membaca *resource* (data).
2. `POST`, untuk membuat *resource* baru (data baru).
3. `DELETE`, tentu untuk menghapus *resource* (data).
4. `PUT`, untuk merubah *resource* (data).

Dan yang perlu diingat, bahwa REST ini adalah *stateless*, artinya tidak ada *state* di dalamnya. Misalnya tidak ada penggunaan *session*. Karena sifatnya, klien hanya meminta ke *server* dan *server* akan memberikan *response*-nya. **titik**. Hanya sampai situ saja. Sehingga untuk proses otentikasinya, kita tidak dapat menggunakan *session*.
