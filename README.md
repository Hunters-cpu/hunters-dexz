<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HUNTERS COMMUNITY | Pusat Turnamen FF & MLBB</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Arial, sans-serif;
        }

        body {
            background-color: #000;
            color: #fff;
            line-height: 1.7;
            padding: 20px;
            padding-bottom: 140px;
            min-height: 100vh;
        }

        header {
            text-align: center;
            padding: 20px 15px;
            border-bottom: 2px solid #25d366;
            margin-bottom: 25px;
        }

        header h1 {
            color: #25d366;
            font-size: 26px;
            margin-bottom: 6px;
        }

        header p {
            color: #aaa;
            font-size: 14px;
        }

        .beranda {
            background-color: #111;
            padding: 22px;
            border-radius: 10px;
            margin-bottom: 25px;
        }

        .beranda h2 {
            color: #25d366;
            margin-bottom: 12px;
            font-size: 19px;
        }

        .beranda p {
            color: #ddd;
            margin-bottom: 20px;
            font-size: 15px;
        }

        .tombol-game {
            display: flex;
            flex-direction: column;
            gap: 12px;
            margin-bottom: 30px;
        }

        .tombol-ff {
            background: linear-gradient(135deg, #ff5500, #ff2200);
            color: #fff;
            padding: 14px;
            border-radius: 8px;
            text-align: center;
            text-decoration: none;
            font-weight: bold;
            font-size: 16px;
        }

        .tombol-mlbb {
            background: linear-gradient(135deg, #2266ff, #8822ff);
            color: #fff;
            padding: 14px;
            border-radius: 8px;
            text-align: center;
            text-decoration: none;
            font-weight: bold;
            font-size: 16px;
        }

        /* === BAGIAN TENTANG KAMI === */
        .tentang {
            background-color: #111;
            padding: 25px;
            border-radius: 10px;
            margin-bottom: 25px;
            border-left: 4px solid #25d366;
        }

        .tentang h2 {
            color: #25d366;
            font-size: 20px;
            margin-bottom: 20px;
            text-align: center;
        }

        .tentang h3 {
            color: #fff;
            font-size: 17px;
            margin: 20px 0 10px 0;
            padding-bottom: 5px;
            border-bottom: 1px solid #333;
        }

        .tentang p {
            color: #ccc;
            font-size: 15px;
            margin-bottom: 12px;
            text-align: justify;
        }

        .tentang ul {
            color: #ccc;
            padding-left: 25px;
            margin-bottom: 15px;
        }

        .tentang li {
            margin-bottom: 8px;
            color: #ddd;
        }

        .kesimpulan {
            background-color: #1a1a1a;
            padding: 18px;
            border-radius: 8px;
            margin-top: 20px;
            border: 1px solid #25d366;
        }

        .kesimpulan p {
            color: #fff;
            font-weight: 500;
            text-align: center;
            margin: 0;
        }

        /* === NAVIGASI BULAT === */
        nav {
            position: fixed;
            bottom: 0;
            left: 0;
            right: 0;
            background-color: #111;
            border-top: 2px solid #25d366;
            padding: 12px 10px;
            box-shadow: 0 -3px 10px rgba(0,0,0,0.5);
        }

        .nav-baris {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px 8px;
        }

        .nav-baris a {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            width: 65px;
            height: 65px;
            background-color: #1a1a1a;
            color: #fff;
            border-radius: 50%;
            text-decoration: none;
            font-size: 11px;
            text-align: center;
            border: 2px solid #25d366;
            transition: 0.2s;
        }

        .nav-baris a:hover {
            background-color: #25d366;
            color: #000;
            transform: scale(1.05);
        }

        .nav-baris a span {
            font-size: 18px;
            margin-bottom: 2px;
        }

        footer {
            text-align: center;
            margin-top: 20px;
            padding: 10px;
            color: #777;
            font-size: 13px;
        }
    </style>
</head>
<body>

    <header>
        <h1>HUNTERS COMMUNITY</h1>
        <p>Dikelola: DEXZ STORE | Pusat Turnamen FF & MLBB</p>
    </header>

    <section class="beranda">
        <h2>Selamat Datang!</h2>
        <p>Tempat resmi pendaftaran & kompetisi game terpercaya.<br>Pilih tombol di bawah untuk melihat detail turnamen, aturan, atau bergabung.</p>

        <div class="tombol-game">
            <a href="#" class="tombol-ff">🔥 Lihat Turnamen Free Fire</a>
            <a href="#" class="tombol-mlbb">⚔️ Lihat Turnamen Mobile Legends</a>
        </div>
    </section>

    <!-- === BAGIAN TENTANG KAMI (SUDAH DITAMBAHKAN) === -->
    <section class="tentang">
        <h2>🏠 TENTANG KAMI</h2>

        <h3>🤝 HUNTERS COMMUNITY</h3>
        <p>HUNTERS COMMUNITY adalah wadah berkumpulnya para pemain Free Fire dan Mobile Legends yang ingin mengasah kemampuan, bertanding secara adil, serta menjalin pertemanan yang positif dan sportif. Kami berdiri sebagai komunitas yang terbuka, rapi, dan terpercaya, tempat berkumpulnya pemain dari berbagai tingkatan untuk berkompetisi dan berkembang bersama.</p>
        <p>Kami hadir agar setiap anggota bisa bertanding tanpa rasa takut ditipu, dicurangi, atau dipandang sebelah mata. Di sini, semua tim diperlakukan sama, tanpa memandang nama besar atau latar belakang.</p>

        <h3>🏪 DEXZ STORE</h3>
        <p>DEXZ STORE adalah pendiri sekaligus penyelenggara resmi HUNTERS COMMUNITY. Seluruh kegiatan, mulai dari pembukaan pendaftaran, pengelolaan dana, pelaksanaan pertandingan, hingga pembagian hadiah — sepenuhnya dikelola dan dipertanggungjawabkan oleh DEXZ STORE.</p>
        <p>Kami menjunjung tinggi:</p>
        <ul>
            <li>✅ Kejujuran — Dana dikelola terbuka, tidak ada yang disembunyikan</li>
            <li>✅ Keadilan — Satu aturan berlaku untuk semua tim</li>
            <li>✅ Tanggung Jawab — Hadiah pasti dibayarkan tepat waktu</li>
            <li>✅ Pelayanan — Siap membantu dan menjawab pertanyaan dengan sopan dan cepat</li>
        </ul>
        <p><strong>DEXZ STORE = Penyelenggara Resmi • Terpercaya • Siap Melayani</strong></p>

        <h3>🎯 TUJUAN TURNAMEN ONLINE YANG KAMI SELENGGARAKAN</h3>
        <p><strong>🏆 Tujuan Utama</strong></p>
        <p>Kami menyelenggarakan turnamen bukan sekadar untuk bertanding, melainkan dengan tujuan yang jelas:</p>
        <ul>
            <li>📈 Meningkatkan kemampuan bermain setiap anggota melalui pengalaman bertanding yang sesungguhnya</li>
            <li>⚖️ Mewujudkan kompetisi yang ADIL dan TERPERCAYA — bebas dari kecurangan, bebas dari pengelolaan yang tidak transparan</li>
            <li>🤝 Mempererat persaudaraan antar anggota — menjadikan permainan sebagai sarana berteman, bukan saling bermusuhan</li>
            <li>💰 Memberikan keuntungan yang nyata — hadiah yang dijanjikan adalah nyata dan akan diserahkan sepenuhnya kepada pemenang tanpa alasan tertunda</li>
            <li>📋 Membiasakan kedisiplinan — mengikuti aturan, menghargai waktu, dan menghormati sesama pemain</li>
        </ul>

        <p><strong>🎮 Turnamen yang Kami Selenggarakan</strong></p>
        <ul>
            <li>🔥 <strong>Free Fire</strong> — Aturan lengkap dan ketat, karakter terbatas, bebas kecurangan, sistem langsung gugur</li>
            <li>⚔️ <strong>Mobile Legends</strong> — Mengikuti standar kompetisi resmi, tepat waktu, tertib, dan sportif</li>
        </ul>
        <p>Setiap turnamen yang kami buka, selalu dengan aturan yang jelas, biaya yang terbuka, dan jadwal yang pasti. Tidak ada biaya tersembunyi, tidak ada alasan yang berbelit-belit.</p>

        <div class="kesimpulan">
            <p>✨ KESIMPULAN SINGKAT<br>
            HUNTERS COMMUNITY adalah tempat berkumpulnya pemain yang ingin bertanding dengan jujur. DEXZ STORE adalah pihak yang menjamin semuanya berjalan benar-benar terpercaya. Dan turnamen yang kami selenggarakan bertujuan agar semua orang bisa berkompetisi secara adil, berkembang menjadi lebih baik, dan pulang dengan kepuasan hati.</p>
        </div>
    </section>

    <footer>
        DEXZ STORE • Penyelenggara Resmi • Terpercaya
    </footer>

    <!-- === NAVIGASI BULAT DI BAWAH === -->
    <nav>
        <div class="nav-baris">
            <a href="#"><span>🏠</span>Beranda</a>
            <a href="#"><span>🔥</span>FF</a>
            <a href="#"><span>⚔️</span>MLBB</a>
            <a href="#"><span>📝</span>Daftar</a>
            <a href="#"><span>📜</span>Aturan</a>
            <a href="#"><span>👥</span>Tim</a>
            <a href="#"><span>📊</span>Jadwal</a>
            <a href="#"><span>🔗</span>Grup</a>
            <a href="#"><span>📱</span>Sosmed</a>
            <a href="#"><span>📂</span>Data</a>
            <a href="#"><span>📞</span>Kontak</a>
        </div>
    </nav>

</body>
</html>
