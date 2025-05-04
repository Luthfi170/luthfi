# luthfi
personal date
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ahmad Luthfi Taqiyyan - Personal Branding</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    /* Dekorasi Batik Samping */
    body::before,
    body::after {
      content: "";
      position: fixed;
      top: 0;
      bottom: 0;
      width: 90px;
      background-repeat: repeat-y;
      background-size: cover;
      z-index: 0;
      opacity: 0.2;
    }

    body::before {
      left: 0;
      background-image: url('https://i.ibb.co/NFkxLmW/batik-gold-left.png'); /* Ganti dengan file batik kamu jika ada */
    }

    body::after {
      right: 0;
      background-image: url('https://i.ibb.co/NFkxLmW/batik-gold-left.png');
      transform: scaleX(-1);
    }

    body > * {
      position: relative;
      z-index: 10;
    }
  </style>
</head>
<body class="bg-[#1e1e2f] text-white font-sans scroll-smooth">

  <!-- Hero -->
  <section class="h-screen flex flex-col items-center justify-center text-center px-4">
    <h1 class="text-5xl md:text-6xl font-serif text-[#ffd700]">Ahmad Luthfi Taqiyyan</h1>
    <p class="mt-4 text-lg md:text-xl text-gray-300">Memanfaatkan teknologi dengan sebaik mungkin</p>
    <a href="#about" class="mt-6 px-6 py-3 border-2 border-[#ffd700] text-[#ffd700] rounded-full hover:bg-[#ffd700] hover:text-[#1e1e2f] transition duration-300">
      Jelajahi Portofolio
    </a>
  </section>

  <!-- Tentang Saya -->
  <section id="about" class="py-16 px-6 max-w-3xl mx-auto text-center">
    <h2 class="text-3xl font-semibold mb-4 text-[#ffd700]">Tentang Saya</h2>
    <p class="text-gray-300">
      Saya Luthfi, mahasiswa Universitas Tazkia dari Program Studi Ekonomi Syariah. Saya memiliki minat besar dalam bidang ekonomi Islam, organisasi, dan pengembangan diri...
    </p>
  </section>

  <!-- Biodata -->
  <section id="biodata" class="py-16 px-6 max-w-4xl mx-auto">
    <h2 class="text-3xl font-semibold mb-6 text-[#ffd700] text-center">Biodata</h2>
    <div class="overflow-x-auto">
      <table class="w-full text-left text-gray-300 border border-gray-600">
        <tbody>
          <tr class="border-b border-gray-600">
            <th class="py-2 px-4 text-[#ffd700] w-1/3">Nama Lengkap</th>
            <td class="py-2 px-4">Ahmad Luthfi Taqiyyan</td>
          </tr>
          <tr class="border-b border-gray-600">
            <th class="py-2 px-4 text-[#ffd700]">Tempat, Tanggal Lahir</th>
            <td class="py-2 px-4">Bulungan 17 April 2006</td>
          </tr>
          <tr class="border-b border-gray-600">
            <th class="py-2 px-4 text-[#ffd700]">Alamat</th>
            <td class="py-2 px-4">JL BUNG TOMO GG. H . SYAHRAN NO 27</td>
          </tr>
          <tr class="border-b border-gray-600">
            <th class="py-2 px-4 text-[#ffd700]">Jenis Kelamin</th>
            <td class="py-2 px-4">Laki-laki</td>
          </tr>
          <tr>
            <th class="py-2 px-4 text-[#ffd700]">Agama</th>
            <td class="py-2 px-4">Islam</td>
          </tr>
        </tbody>
      </table>
    </div>
  </section>
  <!-- Riwayat Pendidikan -->
<section id="pendidikan" class="py-16 px-6 max-w-4xl mx-auto">
    <h2 class="text-3xl font-semibold mb-6 text-[#ffd700] text-center">Riwayat Pendidikan</h2>
    <ul class="space-y-4 text-gray-300 text-lg">
      <li>
        <strong class="text-[#ffd700]">SD:</strong> [SD Muhammadiyah 3] (2012 - 2018)
      </li>
      <li>
        <strong class="text-[#ffd700]">SMP:</strong> [SMP Muhammadiyah 5] (2018 - 2021)
      </li>
      <li>
        <strong class="text-[#ffd700]">SMA:</strong> [SMA Istiqamah Muhammadiyah] (2021 - 2024)
      </li>
      <li>
        <strong class="text-[#ffd700]">Kuliah:</strong> Universitas Islam Tazkia – Ekonomi Syariah (2024 - Sekarang)
      </li>
    </ul>
  </section>
  

  <!-- Keahlian -->
  <section class="py-16 px-6 bg-[#2b2b3c]">
    <h3 class="text-3xl font-semibold mb-8 text-center text-[#ffd700]">Keahlian</h3>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6 max-w-5xl mx-auto">
      <div class="text-center">
        <p>Problem Solving</p>
        <div class="w-full bg-gray-700 h-2 rounded mt-2">
          <div class="h-2 bg-[#ffd700] rounded" style="width: 60%"></div>
        </div>
      </div>
      <div class="text-center">
        <p>Design</p>
        <div class="w-full bg-gray-700 h-2 rounded mt-2">
          <div class="h-2 bg-[#ffd700] rounded" style="width: 90%"></div>
        </div>
      </div>
      <div class="text-center">
        <p>Time Management</p>
        <div class="w-full bg-gray-700 h-2 rounded mt-2">
          <div class="h-2 bg-[#ffd700] rounded" style="width: 80%"></div>
        </div>
      </div>
    </div>
  </section>

  <!-- Kontak -->
  <section class="py-16 px-6 text-center">
    <h2 class="text-3xl font-semibold mb-4 text-[#ffd700]">Hubungi Saya</h2>
    <p class="text-gray-300 mb-6">Tertarik bekerja sama? Kirim pesan melalui email atau media sosial saya.</p>
    
    <div class="flex flex-col items-center space-y-4">
      <a href="mailto:luthfirealitas@gmail.com" class="flex items-center space-x-2 text-[#ffd700] hover:text-white">
        <img src="https://cdn-icons-png.flaticon.com/512/732/732200.png" alt="Email" class="w-6 h-6" />
        <span>luthfirealitas@gmail.com</span>
      </a>
      <a href="https://instagram.com/ahmdfiii_" target="_blank" class="flex items-center space-x-2 text-[#ffd700] hover:text-white">
        <img src="https://cdn-icons-png.flaticon.com/512/2111/2111463.png" alt="Instagram" class="w-6 h-6" />
        <span>@ahmdfiii_</span>
      </a>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-6 text-center text-gray-500 text-sm border-t border-gray-700">
    © 2025 Ahmad Luthfi Taqiyyan. All rights reserved.
  </footer>
</body>
</html>

