<!DOCTYPE html>
<html lang="az">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Erna Handmade</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #f7f7f7;
            color: #333;
        }
        header {
            background: #444;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 20px auto;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .product {
            background: white;
            border-radius: 10px;
            padding: 15px;
            text-align: center;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }
        .product img {
            width: 100%;
            border-radius: 10px;
        }
        .product h3 {
            margin: 10px 0 5px;
        }
        .price {
            font-size: 18px;
            color: #e91e63;
            font-weight: bold;
        }
        .btn {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 15px;
            background: #25d366;
            color: white;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
        }
        .btn:hover {
            background: #1ebe5d;
        }
        footer {
            background: #444;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }
        footer a {
            color: #ffcc00;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Erna Handmade</h1>
        <nav>
            <a href="#home">Ana Səhifə</a>
            <a href="#products">Məhsullar</a>
            <a href="#contact">Əlaqə</a>
        </nav>
    </header>

    <section id="home" class="container">
        <h2>Xoş Gəldiniz</h2>
        <p>Seçilmiş əl işləri – hədiyyəlik və dekorativ məhsullar.</p>
    </section>

    <section id="products" class="container">
        <h2>Məhsullar</h2>
        <div class="products">
            <div class="product">
                <img src="mehsul1.jpg" alt="Məhsul 1">
                <h3>Novruz Yumurtası</h3>
                <p class="price">25 AZN</p>
                <a class="btn" href="https://wa.me/994501234567" target="_blank">WhatsApp ilə əlaqə</a>
            </div>
            <div class="product">
                <img src="mehsul2.jpg" alt="Məhsul 2">
                <h3>Dekorativ Səbət</h3>
                <p class="price">40 AZN</p>
                <a class="btn" href="https://wa.me/994501234567" target="_blank">WhatsApp ilə əlaqə</a>
            </div>
            <div class="product">
                <img src="mehsul3.jpg" alt="Məhsul 3">
                <h3>Səməni Qutusu</h3>
                <p class="price">35 AZN</p>
                <a class="btn" href="https://wa.me/994501234567" target="_blank">WhatsApp ilə əlaqə</a>
            </div>
        </div>
    </section>

    <footer id="contact">
        <p>Bizimlə əlaqə: <a href="https://instagram.com/Erna__handmade" target="_blank">Instagram səhifəmiz</a></p>
    </footer>
</body>
</html>
