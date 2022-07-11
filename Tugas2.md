<h1>**Tugas 2**</h1>
<h2>**SIAPKAN FILE**</h2>
<h3>**Membuat File Models**</h3>
<blockquote>php artisan make:model Rss</blockquote>
<blockquote>php artisan make:model News</blockquote>

<h3>**Membuat File Controller**</h3>
<blockquote>php artisan make:controller RssController</blockquote>
<blockquote>php artisan make:controller NewsController</blockquote>

<h3>**Membuat File Migration**</h3>
<blockquote>php artisan make:migration create_rss_table</blockquote>
Class untuk memasukkan feed xml file ke db dari suatu web

<h3>**Membuat File Seeders**</h3>
<blockquote>php artisan make:seeder RssSeeder</blockquote>

<h2>**KONFIGURASI FILE**</h2>

<h3>**EDIT FILE .env**</h3>
Buat DB lalu sesuaikan nama DB 
Jika ingin membuat foreign key masukkan script
<blockquote>DB_FOREIGN_KEYS=true</blockquote> 
![Capture](https://user-images.githubusercontent.com/51281505/177594536-ce215a91-851f-4d3f-bc7e-997bb0823a34.PNG)



<h4>**Masukkan url untuk mengambil file xml feed/rss ditaruh ke dalam db kita**</h4>
![rss seed url](https://user-images.githubusercontent.com/51281505/178327240-a2383403-5b7b-4231-b664-ad7669d2a7c2.PNG)

<h4>**Cek file feed/rss harus file xml**</h4>
![isi xml](https://user-images.githubusercontent.com/51281505/178327998-239ed7ab-c03f-44d0-a3b4-a3edec798805.PNG)

<h4>**Masukkan content ke db berita**</h4>
![simple xml](https://user-images.githubusercontent.com/51281505/178328250-ce52924a-a9c5-4237-ac75-8c1fbb350c4c.PNG)

<h4>**Tampilkan content dari db berita**</h4>
![ouput](https://user-images.githubusercontent.com/51281505/178328491-1c286a50-e527-4daa-a623-de10ac342517.PNG)

<h2>**LAUNCH FILE**</h2>
