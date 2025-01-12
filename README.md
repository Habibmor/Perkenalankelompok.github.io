<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Biodata Kelompok 4</title>
    <style type="text/css">
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            color: whitesmoke;
            position: relative;
            overflow: hidden;
        }

        /* Background with animated gradient */
        body::before {
            content: "";
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(45deg, #1a73e8, #9c27b0, #ff5722, pink, rgb(239, 255, 10));
            background-size: 300% 300%;
            animation: gradientAnimation 8s ease infinite;
            z-index: -1;
        }

        @keyframes gradientAnimation {
            0% {
                background-position: 0% 50%;
            }
            50% {
                background-position: 100% 50%;
            }
            100% {
                background-position: 0% 50%;
            }
        }

        h1 {
            color: #ffdd40;
            text-align: center;
            padding: 20px 0;
            background-color: rgba(0, 0, 0, 0.7);
            margin-bottom: 20px;
            text-shadow: 2px 4px 6px rgba(0, 0, 0, 0.5);
        }

        .biodata-wrapper {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            padding: 20px;
        }

        .biodata-container {
            flex: 1;
            max-width: 390px;
            background-color: rgba(0, 0, 0, 0.8);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .biodata-container:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.7);
        }

        .biodata-container p {
            font-size: 16px;
            line-height: 1.5;
            margin: 10px 0;
        }

        .biodata-container .label {
            font-weight: bold;
        }

        .nav {
            text-align: center;
            margin: 30px 0;
        }

        .nav a {
            display: inline-block;
            padding: 10px 20px;
            background-color: #1a73e8;
            color: white;
            text-decoration: none;
            border-radius: 30px;
            font-size: 18px;
            font-weight: bold;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
            transition: background 0.3s, transform 0.3s;
        }

        .nav a:hover {
            background-color: #155ab2;
            transform: scale(1.1);
        }
    </style>
</head>
<body>

    <h1>Biodata Kelompok 4</h1>

    <div class="biodata-wrapper">
        <!-- Biodata Luthfi Habib Ritonga -->
        <div class="biodata-container">
            <p><span class="label">Nama Lengkap:</span> Luthfi Habib Ritonga</p>
            <p><span class="label">Umur:</span> 15 Tahun</p>
            <p><span class="label">Kelamin:</span> Laki-Laki</p>
            <p><span class="label">Tempat Tinggal:</span> Medan Marelan Pasar 1 Tengah</p>
            <p><span class="label">Sekolah:</span> SMK Tritech Informatika</p>
        </div>

        <!-- Biodata Zahra Almafira -->
        <div class="biodata-container">
            <p><span class="label">Nama Lengkap:</span> Zahra Almafira</p>
            <p><span class="label">Umur:</span> 16 Tahun</p>
            <p><span class="label">Kelamin:</span> Perempuan</p>
            <p><span class="label">Tempat Tinggal:</span> Medan Usman Siddik</p>
            <p><span class="label">Sekolah:</span> SMK Tritech Informatika</p>
        </div>

        <!-- Biodata Rafa Arifin -->
        <div class="biodata-container">
            <p><span class="label">Nama Lengkap:</span> Rafa Arifin</p>
            <p><span class="label">Umur:</span> 15 Tahun</p>
            <p><span class="label">Kelamin:</span> Laki-Laki</p>
            <p><span class="label">Tempat Tinggal:</span> Medan Marelan Pasar 1 Barat</p>
            <p><span class="label">Sekolah:</span> SMK Tritech Informatika</p>
        </div>
    </div>

    <div class="nav">
        <a href="WebsiteHalaman2Galeri.html">Galeri</a>
    </div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galeri</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #1e3c72, #2a5298);
            color: #fff;
            overflow-x: hidden;
        }

        h1 {
            text-align: center;
            margin: 30px 0;
            font-size: 2.8em;
            color: #ffdd40;
            text-shadow: 2px 4px 8px rgba(0, 0, 0, 0.5);
        }

        .gallery-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            padding: 40px;
        }

        .gallery-item {
            width: 300px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .gallery-item:hover {
            transform: translateY(-10px) scale(1.05);
            box-shadow: 0 15px 25px rgba(0, 0, 0, 0.5);
        }

        .gallery-item img {
            width: 100%;
            border-radius: 15px 15px 0 0;
        }

        .gallery-item p {
            padding: 20px;
            font-size: 1.1em;
            line-height: 1.6;
            color: #fff;
            text-align: justify;
        }

        .nav {
            text-align: center;
            margin: 40px 0;
        }

        .nav a {
            display: inline-block;
            padding: 15px 30px;
            background: linear-gradient(135deg, #ffdd40, #ffa940);
            color: #333;
            font-size: 1.2em;
            font-weight: bold;
            text-decoration: none;
            border-radius: 30px;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.3);
            transition: background 0.3s ease, box-shadow 0.3s ease;
        }

        .nav a:hover {
            background: linear-gradient(135deg, #ffa940, #ff6f00);
            box-shadow: 0 12px 20px rgba(0, 0, 0, 0.5);
        }

        /* Add floating particles for a cool effect */
        .particles {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: -1;
        }

        .particles span {
            position: absolute;
            width: 10px;
            height: 10px;
            background: rgba(255, 255, 255, 0.5);
            border-radius: 50%;
            animation: float 6s infinite ease-in-out;
        }

        .particles span:nth-child(odd) {
            animation-duration: 2s;
            background: rgba(255, 221, 64, 0.7);
        }

        @keyframes float {
            0% {
                transform: translateY(0) translateX(0);
                opacity: 1;
            }
            50% {
                transform: translateY(-20px) translateX(10px);
                opacity: 0.8;
            }
            100% {
                transform: translateY(0) translateX(0);
                opacity: 1;
            }
        }
    </style>
</head>
<body>
    <div class="particles">
        <span style="top: 10%; left: 15%;"></span>
        <span style="top: 20%; left: 70%;"></span>
        <span style="top: 50%; left: 30%;"></span>
        <span style="top: 80%; left: 50%;"></span>
        <span style="top: 90%; left: 85%;"></span>
    </div>

    <h1>Halaman Galeri Saya</h1>

    <div class="gallery-container">
        <div class="gallery-item">
            <img src="Poto1.jpg" alt="Gambar 1">
            <p>Ini Foto saya yang menjuarai peringkat 1 Umum Ranking ini Foto terakhir mendapatkannya, dan masih ada lagi sebelumnya.</p>
        </div>
        <div class="gallery-item">
            <img src="Poto2.jpg" alt="Gambar 2">
            <p>Ini Jersey Kelas RPL 1 yang bermotif Bunga Mawar Biru.</p>
        </div>
        <div class="gallery-item">
            <img src="Poto3.jpg" alt="Gambar 3">
            <p>Ini Saya di fotoin oleh om saya di penginapan Parapat.</p>
        </div>
        <div class="gallery-item">
            <img src="Poto4.jpg" alt="Gambar 4">
            <p>Ini Mobil Impian saya, Skyline R34 Twin Turbo. Mobil ini sangat unik, keren, dan cool, dengan suara menggelegar meski dalam kondisi standar.</p>
        </div>
        <div class="gallery-item">
            <img src="Poto5.jpg" alt="Gambar 5">
            <p>Ini adalah Club Favorit saya yang bernama Real Madrid FC.</p>
        </div>
    </div>

    <div class="nav">
        <a href="WebsiteHalaman1Biodata.html">Kembali</a>
    </div>
</body>
</html>

