 <!DOCTYPE html>
<html>
<head>
    <title>firli</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="kartu-profil">
        <img src="foto-profil.jpg" alt="Foto profil saya">
        <h1>Nama Lengkap Anda</h1>
        <p>Siswa SMA yang tertarik dengan teknologi dan desain. Selamat datang di website pertama saya!</p>
        <a href="https://www.instagram.com/usernameanda">Kunjungi Instagram Saya</a>
    </div>
</body>
</html>
[13.37, 21/10/2026] Rifat: // 1. Pilih tombol berdasarkan ID-nya
const tombolSapa = document.getElementById('sapaButton');
// 2. Tambahkan 'event listener' untuk aksi 'click'
tombolSapa.addEventListener('click', function() {
    // 3. Jalankan kode ini ketika tombol di-klik
    alert('Halo! Terima kasih sudah berkunjung!');
});
