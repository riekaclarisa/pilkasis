Cara Instalasi:
1. Ektrak folder pilkasis ke dalam folder web server (html atau htdocs atau wwww)
2. Buat database baru dan import file database yang ada di folder db/pilkasis.sql (dapat menggunakan PHPMyAdmin) tutor lewat terminal ada di http://muhidin.web.id/backup-and-restore-mysql-database-using-terminal/
3. Sesuaikan isian database pada file sambungan.php, misal menggunakan xampp tanpa password dengan nama database pilkasis, maka settingan-nya menjadi:
<pre>
<?php
$host="localhost";
$userdb="root";
$passdb="";
$namadb="pilkasis";
$koneksi=mysqli_connect($host,$userdb,$passdb,$namadb);
?>
</pre>
4. Jalankan browser http://localhost/pilkasis
