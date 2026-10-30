<img width="1366" height="768" alt="Screenshot (120)" src="https://github.com/user-attachments/assets/3f72dcfe-f3c7-44cf-b697-66250c6e6c64" />
file:///C:/Users/ACER/OneDrive/Documents/GitHub/desktop-tutorial/star3/star3/anvayaraksa.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>anvayaraksa.fx</title>
    <style>
        * {
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f4f7fb;
            color: #263445;
        }

        header {
            background-color: #123b70;
            color: white;
            padding: 30px 15px;
            text-align: center;
        }

        header h1 {
            letter-spacing: 3px;
        }

        nav {
            background-color: #1d5b9e;
            padding: 15px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 10px;
            font-weight: bold;
        }

        nav a:hover {
            color: #facc15;
        }

        .hero {
            background-color: #dbeafe;
            text-align: center;
            padding: 65px 20px;
        }

        .hero h2 {
            color: #123b70;
            font-size: 30px;
        }

        button {
            background-color: #123b70;
            color: white;
            border: none;
            padding: 12px 22px;
            border-radius: 6px;
            cursor: pointer;
        }

        section {
            padding: 35px 20px;
            text-align: center;
        }

        section h2 {
            color: #123b70;
            margin-bottom: 25px;
        }

        section p {
            line-height: 1.7;
        }

        .popup {
            display: none;
            position: fixed;
            z-index: 1000;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.6);
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .popup-content {
            background: white;
            padding: 30px;
            border-radius: 15px;
            max-width: 500px;
            width: 100%;
            text-align: center;
            position: relative;
            animation: muncul 0.4s ease;
        }

        .popup-content h2 {
            color: #123b70;
        }

        .popup-content h3 {
            color: #1d5b9e;
        }

        .close {
            position: absolute;
            right: 18px;
            top: 10px;
            font-size: 30px;
            cursor: pointer;
            color: #555;
        }

        @keyframes muncul {
            from {
                transform: translateY(30px);
                opacity: 0;
            }

            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        .card {
            background-color: white;
            padding: 22px;
            margin: 15px auto;
            max-width: 550px;
            border-radius: 10px;
            box-shadow: 0 3px 10px #00000015;
        }

        .card h3 {
            color: #1d5b9e;
        }

        footer {
            background-color: #123b70;
            color: white;
            text-align: center;
            padding: 25px;
        }

        @media (max-width: 600px) {
            nav a {
                display: inline-block;
                margin: 7px;
            }

            .hero h2 {
                font-size: 24px;
            }
        }
    </style>
</head>

<body>
    <header>
        <h1>ANVAYARAKSA</h1>
        <p>Komunitas Mahasiswa Universitas Jenderal Soedirman</p>
        <P>Bersatu, Bertumbuh, dan Berdampak</P>
    </header>

    <nav>
        <a href="#beranda">Beranda</a>
        <a href="#tentang">Tentang</a>
        <a href="#tujuan">Tujuan</a>
        <a href="#kegiatan">Kegiatan</a>
        <a href="#kontak">Kontak</a>
    </nav>

    <div class="hero" id="beranda">
        <h2>Selamat Datang di ANVAYARAKSA</h2>
        <p>Bersama membangun hubungan kekeluargaan,
            mengembangkan potensi, dan menciptakan
            kontribusi positif bagi lingkungan.
        </p>

        <button onclick="bukaProfil()">
            Kenali Komunitas Kami
        </button>
    </div id="profilKomunitas" class="popup">
    <div class="popup-content">

        <span class="close" onclick="tutupProfil()">&times;</span>

        <h2>Halo, Selamat Datang!</h2>

        <h3>ANVAYARAKSA</h3>

        <P>
            Anvayaraksa merupakan wadah bagi
            mahasiswa untuk membangun hubungan
            kekeluargaan, mengembangkan potensi diri,
            memperluas relasi, dan menciptakan
            kegiatan yang bermanfaat.
        </P>

        <h3>Bersatu, Bertumbuh, dan Berdampak</h3>

        <button onclick="tutupProfil()">
            Mulai Mengenal Kami
        </button>
    </div>
    </div>

    <section id="tentang">
        <h2>Tentang Anvayaraksa</h2>

        <p>
            Anvayaraksa merupakan nama komunitas
            mahasiswa yang menjadi wadah bagi mahasiswa
            untuk membangun hubungan kekeluargaan,
            mengembangkan potensi diri, memperluas relasi,
            serta menciptakan berbagai kegiatan
            yang bermanfaat.
        </p>
    </section>

    <section id="tujuan">
        <h2>Tujuan Komunitas</h2>

        <div class="card">
            <h3>01. Mempererat Hubungan</h3>
            <p>Mempererat hubungan antarmahasiswa.</p>
        </div>

        <div class="card">
            <h3>02. Mengembangkan Potensi</h3>
            <p>Mengembangkan kemampuan dan kreativitas anggota.</p>
        </div>

        <div class="card">
            <h3>03. Membangun Solidaritas</h3>
            <p>Membangun solidaritas dan rasa kekeluargaan.</p>
        </div>

        <div class="card">
            <h3>04. Bertukar Pengalaman</h3>
            <p>Menjadi ruang bertukar ide dan pengalaman.</p>
        </div>

        <div class="card">
            <h3>05. Memberikan Kontribusi</h3>
            <p>
                Mendorong kontribusi positif bagi lingkungan
                kampus dan masyarakat.
            </p>
        </div>
    </section>

    <section id="kegiatan">
        <h2>Kegiatan Komunitas</h2>

        <div class="card">
            <h3>Diskusi dan Sharing Session</h3>
            <p>
                Menjadi tempat bertukar pikiran,
                pengetahuan, dan pengalaman.
            </p>
        </div>

        <div class="card">
            <h3>Pengembangan Kemampuan</h3>
            <p>
                Mengembangkan kemampuan dan potensi
                yang dimiliki setiap anggota.
            </p>
        </div>

        <div class="card">
            <h3>Kegiatan Sosial</h3>
            <p>
                Melaksanakan kegiatan sosial dan
                pengabdian kepada masyarakat.
            </p>
        </div>

        <div class="card">
            <h3>Gathering</h3>
            <p>
                Membangun kebersamaan dan
                mempererat hubungan antaranggota.
            </p>
        </div>

        <div class="card">
            <h3>Kolaborasi Komunitas</h3>
            <p>
                Membangun kerja sama dengan
                komunitas mahasiswa lainnya.
            </p>
        </div>
    </section>

    <section id="kontak">
        <h2>Hubungi Kami</h2>

        <p>
            Ingin mengenal lebih dekat
            ANVAYARAKSA?
        </p>

        <p>
            Komunitas Mahasiswa
            Universitas Jenderal Soedirman
        </p>

        <p>Email: anvayar32@gmail.com</p>
        <p>Instagram: @anvayaraksa</p>
    </section>

    <footer>
        <h3>ANVAYARAKSA</h3>
        <p>Bersatu, Bertumbuh, dan Berdampak.</p>
        <p>
            &copy; 2026 ANVAYARAKSA.
            All Rights Reserved.
        </p>
    </footer>
    function bukaProfil() {
    document.getElementById("profilKomunitas")
    .style.display = "flex";
    }

    function tutupProfil() {
    document.getElementById("profilKomunitas")
    .style.display = "none";
    }
</body>

</html>
