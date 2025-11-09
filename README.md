<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bloomy Garden | Toko Bunga Cantik</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --cream: #fff7f0;
      --pink: #f9dbe0;
      --peach: #ffe5d9;
      --text: #4a3f35;
      --accent: #e38fae;
      --shadow: rgba(0, 0, 0, 0.1);
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: linear-gradient(180deg, var(--cream), #fff);
      color: var(--text);
    }

    header {
      background: var(--pink);
      box-shadow: 0 4px 12px var(--shadow);
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 100;
    }

    header h1 {
      font-size: 24px;
      color: var(--text);
    }

    nav a {
      text-decoration: none;
      color: var(--text);
      margin: 0 12px;
      font-weight: 500;
      transition: color 0.2s;
    }

    nav a:hover {
      color: var(--accent);
    }

    .hero {
      background: url('https://i.pinimg.com/736x/2c/2f/35/2c2f35a21e4bfb4d575493dd1b41c9c9.jpg') center/cover no-repeat;
      color: #fff;
      text-align: center;
      padding: 120px 20px;
    }

    .hero h2 {
      font-size: 42px;
      font-weight: 700;
      margin-bottom: 16px;
    }

    .hero p {
      font-size: 18px;
      max-width: 600px;
      margin: auto;
      line-height: 1.6;
    }

    section {
      padding: 60px 40px;
      max-width: 1200px;
      margin: auto;
    }

    /* Koleksi bunga */
    .flowers {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 20px;
      margin-top: 40px;
    }

    .card {
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 4px 16px var(--shadow);
      overflow: hidden;
      transition: transform 0.2s;
    }

    .card:hover {
      transform: translateY(-6px);
    }

    .card img {
      width: 100%;
      height: 220px;
      object-fit: cover;
    }

    .card h3 {
      padding: 16px;
      color: var(--accent);
      font-size: 18px;
    }

    .card p {
      padding: 0 16px 16px;
      color: var(--text);
      font-size: 14px;
    }

    .about, .contact {
      background: var(--pink);
      border-radius: 16px;
      padding: 40px;
      box-shadow: 0 4px 16px var(--shadow);
      margin-top: 40px;
    }

    footer {
      text-align: center;
      padding: 20px;
      font-size: 14px;
      background: var(--pink);
      margin-top: 40px;
    }

    @media (max-width: 900px) {
      .flowers {
        grid-template-columns: repeat(2, 1fr);
      }
    }

    @media (max-width: 600px) {
      .flowers {
        grid-template-columns: 1fr;
      }

      .hero h2 {
        font-size: 30px;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>🌸 Bloomy Garden</h1>
    <nav>
      <a href="#home">Beranda</a>
      <a href="#flowers">Koleksi</a>
      <a href="#about">Tentang Toko</a>
      <a href="#contact">Kontak</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <h2>Bunga Cantik untuk Setiap Momen</h2>
    <p>Bloomy Garden menghadirkan rangkaian bunga segar yang dirangkai dengan cinta dan sentuhan keindahan alami.</p>
  </section>

  <section id="flowers">
    <h2 style="text-align:center;">💐 Koleksi Bunga</h2>
    <div class="flowers">
      <div class="card">
        <img src="https://i.pinimg.com/1200x/68/a1/48/68a14894f37c6659176c61a20a57bb0d.jpg" alt="Mawar Pink">
        <h3>Mawar Pink</h3>
        <p>Simbol cinta dan kasih sayang. Cocok untuk hadiah spesial yang penuh makna.</p>
      </div>

      <div class="card">
        <img src="https://i.pinimg.com/736x/79/08/08/7908086f2cb921cbcb8c4a65cef9532a.jpg" alt="Tulip Putih">
        <h3>Tulip Biru</h3>
        <p>Melambangkan ketulusan dan keanggunan. Minimalis namun berkesan.</p>
      </div>

      <div class="card">
        <img src="https://i.pinimg.com/736x/8f/86/5d/8f865dbca9294a6c67015d58c67a8a40.jpg" alt="Lily">
        <h3>Lily</h3>
        <p>Bunga yang menawan dengan aroma lembut, sempurna untuk berbagai acara.</p>
      </div>

      <div class="card">
        <img src="https://i.pinimg.com/736x/68/d8/e3/68d8e360a977793fbf013be1151c6aea.jpg" alt="Buket Campuran">
        <h3>Buket Campuran</h3>
        <p>Perpaduan warna dan jenis bunga yang ceria dan menawan.</p>
      </div>
    </div>
  </section>

  <section class="about" id="about">
    <h2>🌷 Tentang Toko</h2>
    <p><strong>Bloomy Garden</strong> adalah toko bunga yang menghadirkan keindahan alami dalam setiap rangkaian. Kami percaya setiap bunga memiliki cerita — dari mawar yang melambangkan cinta hingga lily yang menenangkan hati.</p>
    <p>Toko kami menyediakan berbagai pilihan bunga segar untuk berbagai acara: ulang tahun, pernikahan, ucapan selamat, hingga dekorasi ruangan. Dengan layanan yang ramah dan desain buket yang elegan, kami ingin setiap pelanggan merasakan kebahagiaan lewat keindahan bunga Bloomy Garden.</p>
  </section>

  <section class="contact" id="contact">
    <h2>📩 Kontak Kami</h2>
    <p>Ingin memesan bunga atau menanyakan koleksi terbaru? Hubungi kami di:</p>
    <p><strong>Email:</strong> <a href="mailto:info@bloomygarden.com">info@bloomygarden.com</a></p>
    <p><strong>Alamat:</strong> Jl. Melati No. 7, Malang, Jawa Timur</p>
  </section>

  <footer>
    © 2025 Bloomy Garden | Toko Bunga Cantik by Nova Rinda
  </footer>
</body>
</html>
