
     roby: /* Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    background: #ffffff;
    color: #4b5563;
    min-height: 100vh;
}

/* Area utama */
.profile-container {
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 30px 16px;
    border: 5px solid #a8dce8;
    margin: 12px;
}

/* Kartu profil */
.profile-card {
    width: 320px;
    max-width: 100%;
    padding: 28px 22px 24px;
    background: #ffffff;
    border-radius: 8px;
    text-align: center;
    box-shadow: 0 4px 18px rgba(0, 0, 0, 0.04);
}

/* Avatar oval merah */
.avatar {
    position: relative;
    width: 145px;
    height: 220px;
    margin: 0 auto 25px;
    overf…
[13.34, 21/10/2026] roby: <!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Profil Saya</title>

    <!-- Menghubungkan file CSS -->
    <link rel="stylesheet" href="./style.css">
</head>
<body>

    <main class="page">
        <article class="profile-card">

            <div class="avatar" aria-label="Ilustrasi avatar profil">
                <div class="hair"></div>
                <div class="face"></div>
                <div class="neck"></div>

                <div class="jacket">
                    <div class="shirt"></div>
                    <div class="tie"></div>
                </div>
            </div>

            <h1>Nama Lengkap<br>Anda</h1>

            <p class="d…
[13.34, 21/10/2026] roby: /* =========================
   RESET DAN DASAR HALAMAN
========================= */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    min-height: 100%;
}

body {
    min-height: 100vh;
    font-family: Arial, Helvetica, sans-serif;
    background: #ffffff;
    color: #555b65;
}

/* =========================
   AREA UTAMA
========================= */
.page {
    min-height: calc(100vh - 24px);
    margin: 12px;
    border: 4px solid #b8e3ed;

    display: flex;
    justify-content: center;
    align-items: center;

    padding: 35px 16px;
}

/* =========================
   KARTU PROFIL
========================= */
.profile-card {
    width: 320px;
    max-width: 100%;
    padding: 22px 20px 25px;

    text-align: center;
    backgro…
