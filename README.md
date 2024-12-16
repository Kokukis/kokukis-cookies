<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kokukis - Delicious Cookies</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f3e9;
            color: #444;
        }

        header {
            text-align: center;
            background-color: #fdf5e6;
            padding: 20px;
            border-bottom: 2px solid #e4d7c7;
        }

        header h1 {
            font-size: 2.5rem;
            color: #d49f6f;
        }

        .product-section {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
            gap: 20px;
        }

        .product-card {
            background: #fff;
            border: 1px solid #e4d7c7;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            width: 250px;
            text-align: center;
            padding: 15px;
        }

        .product-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .product-card h3 {
            font-size: 1.2rem;
            color: #d49f6f;
            margin: 10px 0;
        }

        .product-card p {
            font-size: 1rem;
            margin: 5px 0;
        }

        footer {
            text-align: center;
            background-color: #fdf5e6;
            padding: 20px;
            border-top: 2px solid #e4d7c7;
        }

        footer a {
            color: #d49f6f;
            text-decoration: none;
            font-size: 1.2rem;
            margin: 0 10px;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to Kokukis Cookies</h1>
    <p>Freshly Baked Deliciousness</p>
</header>

<section class="product-section">
    <!-- Cookies Original -->
    <div class="product-card">
        <img src="kokukis original.jpg" alt="Cookies Original">
        <h3>Cookies Original</h3>
        <p>Price: Rp4.000</p>
    </div>

    <!-- Cookies Matcha -->
    <div class="product-card">
        <img src="kokukis matcha.jpg" alt="Cookies Matcha">
        <h3>Cookies Matcha</h3>
        <p>Price: Rp4.000</p>
    </div>

    <!-- Cookies Monster -->
    <div class="product-card">
        <img src="kokukis monster.jpg" alt="Cookies Monster">
        <h3>Cookies Monster</h3>
        <p>Price: Rp4.000</p>
    </div>

    <!-- Cookies Coklat -->
    <div class="product-card">
        <img src="kokukis Cookies coklat.jpg" alt="Cookies Coklat">
        <h3>Cookies Coklat</h3>
        <p>Price: Rp4.000</p>
    </div>

    <!-- Cookies Red Velvet -->
    <div class="product-card">
        <img src="kokukis redvelvet.jpg" alt="Cookies redvelvet">
        <h3>Cookies Red Velvet</h3>
        <p>Price: Rp4.000</p>
    </div>

    <!-- Cookies + Keju -->
    <div class="product-card">
        <img src="kokukis +keju.jpg" alt="Cookies + Keju">
        <h3>Cookies + Keju</h3>
        <p>Price: Rp5.000</p>
    </div>
</section>

<footer>
    <p>Contact Us</p>
    <a href="https://wa.me/6285809083352">WhatsApp</a>
    <a href="https://www.instagram.com/kooklla_llg">Instagram</a>
    <a href="https://www.tiktok.com/@kokukis_llg">TikTok</a>
</footer>

</body>
</html>
