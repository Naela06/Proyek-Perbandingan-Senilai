
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Media Pembelajaran</title>

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">

    <style>
        /* Tambahkan latar belakang di body dengan animasi */
        body {
            background-image: url('021.jpg');
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            background-attachment: fixed;
            animation: moveBackground 20s infinite alternate; /* Animasi latar belakang */
            color: #0c0b0b;
        }

        /* Animasi untuk latar belakang */
        @keyframes moveBackground {
            0% {
                background-size: 100%;
                background-position: center;
            }
            100% {
                background-size: 110%;
                background-position: top;
            }
        }

        /* Atur tampilan teks agar tetap terlihat jelas */
        .jumbotron, .card, .navbar, footer {
            background-color: rgba(193, 214, 216, 0.9);
            border-radius: 10px;
        }

        /* Tambahan styling untuk card */
        .card {
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0 4px 20px rgba(26, 25, 25, 0.2);
        }

        /* Animasi pulse untuk tombol */
        @keyframes pulse {
            0%, 100% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.05);
            }
        }

        /* Styling untuk tombol */
        .btn-primary {
            background-color: #216580;
            border: none;
            transition: background-color 0.3s;
        }

        .btn-primary:hover {
            background-color: #387c8d;
        }

        .pulse {
            animation: pulse 2s infinite; /* Tambahkan animasi pulse */
        }

        /* Footer styling */
        footer {
            background-color: rgba(0, 0, 0, 0.8);
            border-top: 5px solid #1a6464;
        }
    </style>

</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-secondary">
    <div class="container-fluid">
        <a class="navbar-brand" href="#">NAELA MAGFIROH</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
                <li class="nav-item">
                    <a class="nav-link" href="kelas7.html">Beranda</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="perbandingan_senilai.html">Materi</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="Quiz.html">Kuis</a>
                </li>
                <!-- Dropdown Pembelajaran Media -->
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMedia" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                        Media Pembelajaran
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdownMedia">
                        <li><a class="dropdown-item" href="video.html">Video</a></li>
                        <li><a class="dropdown-item" href="grafikgeogebra.html">Latihan 1</a></li>
                        <li><a class="dropdown-item" href="Lembar Kerja.html">Latihan 2</a></li>
                    </ul>
                </li>
                <!-- Dropdown Tentang Kami -->
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownAbout" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                        Tentang Kami
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
                        <li><a class="dropdown-item" href="biodata.html">Biodata</a></li>
                        <li><a class="dropdown-item" href="kontak.html">Kontak Saya</a></li>
                    </ul>
                </li>
            </ul>
        </div>
    </div>
</nav>

<!-- Jumbotron -->
<div class="jumbotron text-center p-5" style="background-color: rgba(211, 186, 205, 0.7);">
    <h1 class="display-4" style="font-family: 'Poppins', sans-serif; font-weight: 600;">SELAMAT DATANG</h1>
    <p class="lead" style="font-family: 'Roboto', sans-serif; font-size: 1.2rem;">Website Ini Berisi Tentang Materi Perbandingan Senilai</p>
    <a class="btn btn-primary btn-lg pulse" href="video.html" role="button" style="font-family: 'Roboto', sans-serif;">KLIK UNTUK MULAI</a>
</div>

<!-- Content Section -->
<div class="container my-5">
    <div class="row">
        <!-- Materi Pembelajaran Card -->
        <div class="col-lg-4 mb-4">
            <div class="card h-100">
                <img src="009.jpg" class="card-img-top" alt="Materi Image" style="width: 100%; height: 200px; object-fit: cover;">
                <div class="card-body">
                    <h5 class="card-title">Materi Perbandingan Senilai</h5>
                    <ul class="card-text">
                        <li>Pengertian Perbandingan Senilai</li>
                        <li>Syarat Perbandingan Senilai</li>
                        <li>Cara Perhitungan Perbandingan Senilai</li>
                        <li>Grafik Perbandingan Senilai</li>
                    </ul>
                    <a href="perbandingan_senilai.html" class="btn btn-primary pulse">Lihat Materi</a>
                </div>
            </div>
        </div>
        
        <!-- Quiz Interaktif Card -->
        <div class="col-lg-4 mb-4">
            <div class="card h-100">
                <img src="010.jpg" class="card-img-top" alt="Quiz Image" style="width: 100%; height: 200px; object-fit: cover;">
                <div class="card-body">
                    <h5 class="card-title">Quiz</h5>
                    <p class="card-text">Uji kemampuanmu dengan serangkaian kuis interaktif yang seru dan menantang! Setiap pertanyaan dirancang khusus untuk membantumu semakin jago dan percaya diri dalam memahami materi.</p>
                    <a href="Quiz.html" class="btn btn-primary pulse">Mulai Kuis</a>
                </div>
            </div>
        </div>

        <!-- Fitur Lain Card -->
        <div class="col-lg-4 mb-4">
            <div class="card h-100">
                <img src="011.jpg" class="card-img-top" alt="Fitur Image" style="width: 100%; height: 200px; object-fit: cover;">
                <div class="card-body">
                    <h5 class="card-title">Media Pemebelajaran</h5>
                    <p class="card-text">Kami menyediakan fitur-fitur tambahan seperti video tutorial, diskusi online, dan banyak lagi untuk mendukung proses belajar Anda.</p>
                    <div class="dropdown mb-3">
                        <br><button class="btn btn-primary dropdown-toggle pulse" type="button" id="dropdownMenuButton" data-bs-toggle="dropdown" aria-expanded="false">
                            Mulai Jelajahi
                        </button>
                        <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton">
                            <li><a class="dropdown-item" href="video.html">Video Pembelajaran</a></li>
                            <li><a class="dropdown-item" href="grafikgeogebra.html">Latihan 1</a></li>
                            <li><a class="dropdown-item" href="Lembar Kerja.html">Latihan 2</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>

        <br><div class="card text-center">
            <div class="card-header">Matematika Kelas 7</div>
            <div class="card-body">
                <h5 class="card-title">Pendidikan Matematika</h5>
                <p class="card-text">Kami berkomitmen untuk memberikan yang terbaik dalam pembelajaran matematika.</p>
            </div>
        </div>
    </div>
</div>

<!-- Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
