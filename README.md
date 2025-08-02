<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>IRMA SMAN1T</title>
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0; padding: 0; box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Outfit', sans-serif;
      background: linear-gradient(135deg, #e0f2f1, #ffffff);
      color: #2e7d32;
      line-height: 1.6;
    }

    header {
      background: url('https://files.catbox.moe/k39krh.jpg') no-repeat center/cover;
      height: 320px;
      position: relative;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 2rem;
    }

    header::after {
      content: '';
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: rgba(0, 0, 0, 0.55);
      z-index: 1;
    }

    header h1, header p {
      position: relative;
      z-index: 2;
    }

    header h1 {
      font-size: 3rem;
      font-weight: bold;
      margin-bottom: 0.5rem;
      color: #ffffff;
    }

    header p {
      font-size: 1.2rem;
      color: #c8e6c9;
    }

    nav {
      background: #00796b;
      text-align: center;
      padding: 0.8rem 0;
      position: sticky;
      top: 0;
      z-index: 999;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 1rem;
      font-weight: bold;
      transition: all 0.3s ease;
      padding: 0.5rem 1rem;
      border-radius: 8px;
    }

    nav a:hover,
    nav a.active {
      background: #004d40;
      color: #ffffff;
    }

    .hero {
      padding: 4rem 2rem;
      text-align: center;
      background: url('https://images.unsplash.com/photo-1581092160606-4a91d647b588?ixlib=rb-4.0.3&auto=format&fit=crop&w=1600&q=80') no-repeat center/cover;
      color: #fff;
      position: relative;
    }

    .hero::after {
      content: '';
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background-color: rgba(0, 77, 64, 0.6);
      z-index: 1;
    }

    .hero-content {
      position: relative;
      z-index: 2;
    }

    .hero h2 {
      font-size: 2.8rem;
      margin-bottom: 1rem;
    }

    .hero p {
      font-size: 1.2rem;
      max-width: 600px;
      margin: auto;
    }

    .section {
      padding: 3rem 2rem;
      max-width: 1000px;
      margin: auto;
    }

    .section h3 {
      font-size: 2rem;
      margin-bottom: 1rem;
      color: #00695c;
    }

    .section p {
      font-size: 1.1rem;
      color: #444;
    }

    .card-container {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      margin-top: 2rem;
      justify-content: center;
    }

    .card {
      background: #ffffff;
      border-radius: 12px;
      padding: 1.5rem;
      box-shadow: 0 8px 16px rgba(0,0,0,0.1);
      max-width: 300px;
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card h4 {
      color: #00796b;
      margin-bottom: 0.5rem;
    }

    footer {
      background: #004d40;
      color: #fff;
      text-align: center;
      padding: 1.5rem 1rem;
      margin-top: 3rem;
    }

    #scrollTopBtn {
      position: fixed;
      bottom: 30px;
      right: 30px;
      z-index: 999;
      background: #00796b;
      color: #fff;
      border: none;
      padding: 0.8rem 1rem;
      border-radius: 50%;
      font-size: 1.2rem;
      cursor: pointer;
      display: none;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      transition: background 0.3s;
    }

    #scrollTopBtn:hover {
      background: #004d40;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 2.2rem;
      }

      nav a {
        display: inline-block;
        margin: 0.5rem;
      }

      .card-container {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>IRMA SMA NEGRI 1 TAMANSARI</h1>
    <p>Ikatan Remaja Masjid - Bersatu Dalam Iman dan Ilmu</p>
  </header>

  <nav>
    <a href="#beranda" class="nav-link active">Beranda</a>
    <a href="#tentang" class="nav-link">Tentang</a>
    <a href="#kegiatan" class="nav-link">Kegiatan</a>
    <a href="#divisi" class="nav-link">Divisi</a>
    <a href="#kontak" class="nav-link">Kontak</a>
  </nav>

  <section class="hero" id="beranda">
    <div class="hero-content">
      <h2>Remaja Masjid yang Aktif dan Inspiratif</h2>
      <p>Mengembangkan semangat keislaman, kreativitas, dan kepedulian sosial di lingkungan sekolah dan masyarakat.</p>
    </div>
  </section>

  <section class="section" id="tentang">
    <h3>Tentang IRMA</h3>
    <p>IRMA (Ikatan Remaja Masjid) SMA NEGRI 1 Tamansari adalah organisasi kerohanian Islam yang berperan aktif dalam pembinaan akhlak dan keislaman di kalangan siswa. Melalui kegiatan positif dan edukatif, IRMA menjadi wadah bagi siswa untuk belajar, berkarya, dan mendekatkan diri kepada Allah SWT.</p>
  </section>

  <section class="section" id="kegiatan">
    <h3>Kegiatan Utama</h3>
    <div class="card-container">
      <div class="card">
        <h4>Kumpul Rutin Hari Senin (WAJIB)</h4>
        <p>Kumpul ini akan membahas materi-materi atau kajian Islam mingguan bersama untuk meningkatkan pemahaman agama, dan juga kumpul rutin ini akan membahas acara yang akan mendatang di IRMA.</p>
      </div>
    </div>
  </section>

  <section class="section" id="divisi">
    <h3>IRMA SMAN1T</h3>
    <p>Divisi Yang Ada di IRMA SMAN1T Yaitu:</p>
    <p>Divisi Senior, Divisi Tahfidz, Divisi Kaderisasi, Divisi Marketing, Divisi Medkom, Divisi Syiar Dakwah</p>
    <div class="card-container">
      <div class="card">
        <h4>Divisi Senior</h4>
        <p>Mengembangkan minat dan bakat anggota IRMA dalam bidang seni dan olahraga. Contoh nya belajar bermain hadroh.
        <p><strong>Hari:</strong> Setiap Hari Rabu</p>
      </div>
      <div class="card">
        <h4>Divisi Tahfidz</h4>
        <p>Kita akan belajar Alquran bersama. di divisi ini ada kegiatan seperti mengaji, menghafal, imla, dan mentadaburi Al-Qur'an yang menjadi kegiatan rutin IRMA di setiap minggunya.</p>
        <p><strong>Hari:</strong> Setiap Hari Kamis</p>
      </div>
      <div class="card">
        <h4>Divisi Kaderisasi</h4>
        <p>Merekrut anggota IRMA untuk memepertahankan anggota IRMA juga mengajak sisa/siswi untuk bergabung masuk IRMA, membuat jadwal piket dan gs3, dan juga membuat database anggota IRMA.</p>
      </div>
      <div class="card">
        <h4>Divisi Marketing</h4>
        <p>Mengembangkan minat dan bakat anggota IRMA dalam bidang usaha, bisa jualan makanan ataupun barang yang nantinya hasil jualan nya itu bakal dimadukan ke kas nya IRMA.</p>
      </div>
      <div class="card">
        <h4>Divisi Medkom</h4>
        <p>Kita akan mengembangkan minat dan bakat anggota IRMA dalam bidang desain grafis seperti membuat poster, pamflet, banner, dan lain sebagainya. Divisi ini akan bekerja sama dengan Divisi Syiar Dakwah via sosial media.</p>
      </div>
      <div class="card">
        <h4>Divisi Syiar Dakwah</h4>
        <p>Mensyiarkan dakwah baik secara langsung ataupun tidak. Seperti membuat poster-poster islami untuk di shsre di saluran IRMA, dan nantinya Divisi ini akan bekerja sama dengan Divisi Medkom.</p>
      </div>
    </div>
  </section>

  <section class="section" id="kontak">
    <h3>Kontak</h3>
    <p>📍 SMA NEGRI 1 Tamansari, Kabupaten Bogor</p>
    <p>📱 Instagram: <a href="https://www.instagram.com/irma_sman1t" target="_blank">@irma_sman1t</a></p>
  </section>

  <footer>
    <p>&copy; 2025 IRMA SMA NEGRI 1 Tamansari. All Rights Reserved.</p>
  </footer>

  <button id="scrollTopBtn" title="Kembali ke atas">↑</button>

  <script>
    // Navigasi aktif saat diklik
    const links = document.querySelectorAll('.nav-link');
    links.forEach(link => {
      link.addEventListener('click', () => {
        links.forEach(l => l.classList.remove('active'));
        link.classList.add('active');
      });
    });

    // Tombol scroll ke atas
    const scrollBtn = document.getElementById('scrollTopBtn');
    window.addEventListener('scroll', () => {
      scrollBtn.style.display = (window.scrollY > 300) ? 'block' : 'none';
    });
    scrollBtn.addEventListener('click', () => {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    });
  </script>
</body>
</html>
