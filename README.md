# Tutorial 8
### What is amqp?
amqp adalah singkatan dari *Advanced Message Queuing Protocol* yang merupakan protokol
lapisan aplikasi klien saat berbicara ke server dan berinteraksi. amqp dibuat sebagai
protokol standar terbuka yang memungkinkan interoperabilitas pengiriman pesan antar
sistem, terlepas dari vendor perantara pesan atau platform yang digunakan

### what it means? guest:guest@localhost:5672 , what is the first quest, and what is the second guest, and what is localhost:5672 is for?
"guest:guest@localhost:5672" merupakan URL koneksi yang umum digunakan dalam aplikasi 
software untuk menentukan detail dari koneksi dalam mengakses server. Sebenarnya "guest:guest" 
berasal dari format "username:password". Namun, disini "guest" digunakan untuk username dan 
password sebagai *default* value. "localhost:5672" menentukan *hostname* dan *port number* dari
layanan yang ingin kita gunakan. "localhost" menandakan bahwa layanan dijalankan pada mesin/device
yang sama dengan aplikasi. sedangkan port "5672" merupakan port yang umumnya digunakan untuk AMQP.
