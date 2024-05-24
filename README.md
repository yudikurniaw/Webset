<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yudi Kurniawan - Personal Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #ff7e5f, #feb47b);
            color: #fff;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            overflow: hidden;
        }
        .container {
            text-align: center;
            padding: 20px;
            background: rgba(0, 0, 0, 0.5);
            border-radius: 10px;
        }
        h1, h2 {
            margin: 0.5em 0;
            animation: fadeIn 2s;
        }
        p {
            margin: 0.5em 0;
            animation: slideIn 2s;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes slideIn {
            from { transform: translateY(20px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        .animated-text {
            display: inline-block;
            animation: colorChange 4s infinite alternate;
        }
        @keyframes colorChange {
            0% { color: #ff7e5f; }
            100% { color: #feb47b; }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 class="animated-text">Selamat Datang di Halaman Pribadi</h1>
        <h2>Yudi Kurniawan</h2>
        <div class="bio">
            <p><strong>Nama Lengkap:</strong> Yudi Kurniawan</p>
            <p><strong>Tanggal Lahir:</strong> 15 Mei 1990</p>
            <p><strong>Nomor Kontak:</strong> 0812-3456-7890</p>
        </div>
    </div>
</body>
</html>
