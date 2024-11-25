<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Semih'in Yemekleri</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f9fa;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff5722;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .menu {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin: 20px;
        }
        .menu-item {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            margin: 10px;
            width: 300px;
            padding: 15px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .menu-item img {
            width: 100%;
            border-radius: 8px;
        }
        .menu-item h3 {
            margin: 10px 0;
        }
        .menu-item p {
            color: #555;
        }
        .menu-item button {
            background-color: #ff5722;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
        }
        .menu-item button:hover {
            background-color: #e64a19;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Semih'in Yemekleri</h1>
        <p>Lezzetli yemekler burada! Hemen sipariş verin.</p>
    </header>
    <section class="menu">
        <div class="menu-item">
            <img src="https://via.placeholder.com/300x200" alt="Yemek 1">
            <h3>Adana Kebap</h3>
            <p>Lezzetli Adana kebabımızı deneyin.</p>
            <p><strong>₺80</strong></p>
            <button>Sipariş Ver</button>
        </div>
        <div class="menu-item">
            <img src="https://via.placeholder.com/300x200" alt="Yemek 2">
            <h3>Lahmacun</h3>
            <p>Yanında bol yeşillik ile çıtır lahmacun.</p>
            <p><strong>₺25</strong></p>
            <button>Sipariş Ver</button>
        </div>
        <div class="menu-item">
            <img src="https://via.placeholder.com/300x200" alt="Yemek 3">
            <h3>Pide</h3>
            <p>Karışık pide: et, peynir ve sebze.</p>
            <p><strong>₺50</strong></p>
            <button>Sipariş Ver</button>
        </div>
    </section>
    <footer>
        <p>© 2024 Semih'in Yemekleri. Tüm hakları saklıdır.</p>
    </footer>
</body>
</html>
