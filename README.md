<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yudi Kurniawan</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #f06, #4a90e2);
            color: white;
            text-align: center;
            margin: 0;
            padding: 0;
            overflow: hidden;
        }
        .container {
            padding: 20px;
            margin-top: 50px;
        }
        h1 {
            font-size: 3em;
            margin-bottom: 0;
        }
        .bio {
            font-size: 1.5em;
            margin-top: 0;
        }
        .anim-text {
            font-size: 1.2em;
            animation: moveText 10s linear infinite;
            white-space: nowrap;
            overflow: hidden;
        }
        @keyframes moveText {
            0% { transform: translateX(100%); }
            100% { transform: translateX(-100%); }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Yudi Kurniawan</h1>
        <p class="bio">Nama Lengkap: Yudi Kurniawan</p>
        <p class="bio">Tanggal Lahir: [Masukkan Tanggal Lahir]</p>
        <p class="bio">Nomor Kontak: [Masukkan Nomor Kontak]</p>
        <p class="anim-text">Selamat datang di halaman pribadi saya! Saya Yudi Kurniawan, senang bertemu dengan Anda!</p>
    </div>
</body>
</html>
