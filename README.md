<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jalangkote Mama Dewi - Nikmatnya Rasa Tradisional</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #ff6b35;
            color: white;
            text-align: center;
            padding: 50px 20px;
        }
        header h1 {
            font-size: 3em;
            margin: 0;
        }
        header p {
            font-size: 1.2em;
        }
        section {
            padding: 40px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .produk {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .produk-item {
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            margin: 20px;
            padding: 20px;
            width: 300px;
            text-align: center;
            transition: transform 0.3s;
        }
        .produk-item:hover {
            transform: scale(1.05);
        }
        .produk-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
        }
        .testimonial {
            background-color: #fff;
            text-align: center;
            padding: 40px;
        }
        .testimonial blockquote {
            font-style: italic;
            font-size: 1.2em;
        }
        .cta {
            background-color: #ff6b35;
            color: white;
            text-align: center;
            padding: 40px;
        }
        .cta button {
            background-color: white;
            color: #ff6b35;
            border: none;
            padding: 15px 30px;
            font-size: 1.2em;
            cursor: pointer;
            border-radius: 5px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Selamat Datang di Jalangkote Mama Dewi</h1>
        <p>Nikmati kelezatan Jalangkote gurih buatan tangan, dengan bahan segar dan rasa autentik. Cocok untuk cemilan sehari-hari atau acara spesial!</p>
    </header>

    <section class="produk">
        <div class="produk-item">
            <img src="1.jpg" alt="Jalangkote Klasik">
            <h3>Jalangkote Gurih Klasik</h3>
            <p>Isian bihun, kentang.</p>
            <p>Harga: Rp 5.000/4 pcs.</p>
        </div>
        <div class="produk-item">
            <img src="2.jpg" alt="Jalangkote Telur">
            <h3>Jalangkote Gurih Telur</h3>
            <p>Isian telur, bihun, kentang.</p>
            <p>Harga: Rp 10.000/5 pcs.</p>
        </div>
    </section>

    <section class="testimonial">
        <h2>Apa Kata Pelanggan Kami?</h2>
        <blockquote>"Jalangkotegit gurihnya enak banget, kulitnya renyah dan isinya gurih. Sudah jadi favorit keluarga!"</blockquote>
        <blockquote>"Pesan untuk acara ulang tahun anak, semua suka. Recomended!"</blockquote>
    </section>

    <section class="cta">
        <h2>Pesan Sekarang!</h2>
        <p>Jangan lewatkan kesempatan untuk mencoba. Hubungi kami untuk pemesanan grosir atau retail.</p>
        <h3>Dusun Borong Bilalang, Depan Masjid Baitul Iman Julubori,Samping Mitra Swalayan 2, Kec Pallangga, Kab Gowa, Sulawesi Selatan</h3>
        <h4><a href="https://wa.me/62895341606016" class="btn btn-custom">Pesan via WhatsApp</a></h4>
    </section>

    <footer>
        <p>Jalangkote Gurih Dan Enak. Kontak: +62 895-3416-06016 | Email: jalangkotemamadewi@gmail.com</p>
    </footer>

    <script>
        // Efek sederhana: Scroll ke atas saat klik header
        document.querySelector('header').addEventListener('click', () => {
            window.scrollTo({ top: 0, behavior: 'smooth' });
        });
    </script>
</body>
</html>
