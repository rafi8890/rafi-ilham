<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Portal berita terkini dan hits di Indonesia">
    <title>Berita Hits Indonesia</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #ff5722;
            color: white;
            padding: 1rem 0;
        }
        header .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        nav ul li {
            margin-left: 1rem;
        }
        nav ul li a {
            text-decoration: none;
            color: white;
            font-weight: bold;
        }
        #hero {
            background: url('hero-bg.jpg') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 4rem 1rem;
        }
        #hero h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        #hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
        }
        #hero button {
            background-color: #ff5722;
            color: white;
            border: none;
            padding: 0.8rem 2rem;
            cursor: pointer;
            font-size: 1rem;
        }
        .content-section {
            padding: 2rem 1rem;
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: auto;
        }
        .news-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
        }
        article {
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            overflow: hidden;
        }
        article img {
            width: 100%;
            height: auto;
        }
        article h3 {
            font-size: 1.5rem;
            margin: 0.5rem;
        }
        article p {
            padding: 0 0.5rem;
            font-size: 1rem;
        }
        article a {
            display: block;
            text-align: center;
            padding: 0.5rem;
            color: white;
            background-color: #ff5722;
            text-decoration: none;
            font-weight: bold;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Berita Hits Indonesia</h1>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#news">Berita</a></li>
                    <li><a href="#lifestyle">Gaya Hidup</a></li>
                    <li><a href="#sports">Olahraga</a></li>
                    <li><a href="#contact">Kontak</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section id="hero">
            <div class="container">
                <h2>Berita Terkini dan Terpopuler</h2>
                <p>Selalu update dengan berita terbaru dari seluruh Indonesia.</p>
                <button>Selengkapnya</button>
            </div>
        </section>

        <section id="news" class="content-section">
            <div class="container">
                <h2>Berita Utama</h2>
                <div class="news-grid">
                    <article>
                        <img src="news1.jpg" alt="Berita 1">
                        <h3>Judul Berita 1</h3>
                        <p>Ringkasan berita singkat tentang kejadian terkini di Indonesia.</p>
                        <a href="#">Baca Selengkapnya</a>
                    </article>
                    <article>
                        <img src="news2.jpg" alt="Berita 2">
                        <h3>Judul Berita 2</h3>
                        <p>Informasi terbaru dari dunia olahraga dan hiburan.</p>
                        <a href="#">Baca Selengkapnya</a>
                    </article>
                    <article>
                        <img src="news3.jpg" alt="Berita 3">
                        <h3>Judul Berita 3</h3>
                        <p>Kabar menarik seputar teknologi dan inovasi terbaru.</p>
                        <a href="#">Baca Selengkapnya</a>
                    </article>
                </div>
            </div>
        </section>

        <section id="lifestyle" class="content-section">
            <div class="container">
                <h2>Gaya Hidup</h2>
                <p>Temukan tips dan inspirasi gaya hidup modern di sini.</p>
            </div>
        </section>

        <section id="sports" class="content-section">
            <div class="container">
                <h2>Olahraga</h2>
                <p>Kabar terbaru dari dunia olahraga Indonesia dan internasional.</p>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2024 Berita Hits Indonesia. Semua hak dilindungi.</p>
        </div>
    </footer>
</body>
</html>
