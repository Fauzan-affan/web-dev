# Data Binding dengan Vue.js

Sebelumnya, kita sudah belajar mengenai apa itu vue dan bagaimana penggunaan v-model. Buat teman-teman yang belum tau, v-model adalah *two ways data binding* yang disedikan oleh vue. Nah, kali ini kita akan membahas lebih dalam mengenai salah satu fitur di dalam vue yaitu *data binding*.

*Data binding* atau *reactive data binding system*, secara singkat adalah fitur yang dapat menyimpan data seperti *variabel, array, value*, dll ke dalam *property* yang kita punya dan tersinkronisasikan dengan DOM html secara otomatis. Kalau teman-teman perhatikan pada video-video sebelumnya, si *data binding* inilah yang menyebabkan seolah-olah kita bisa meng-*update* data kita secara *live*.

Contoh, semisal kita mengubah nilai pada parameter `message` menjadi `‘Hello’` maka data akan diperbaharui pada tag html sehingga menyimpan *property* dengan *value* yang sudah kita ubah tadi yaitu `‘Hello’`.
