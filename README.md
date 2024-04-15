<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guatemala Virtual - Tienda en línea</title>
    <link rel="icon" type="image/png" href="guate.jpeg">
   <style>
        header {
            background-image: url('https://www.wallpapers.net/web/wallpapers/mountains-of-guatemala-hd-wallpaper/3840x2160.jpg');
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            color: #fff;
            padding: 20px;
            position: relative;
            text-align: center;
        }

        header nav {
            position: absolute;
            top: 20px;
            right: 20px;
        }

        header nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        header nav ul li {
            display: inline;
            margin-right: 20px;
        }

        header nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }
        main {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 20px;
        }

        .product {
            background-color: #f4f4f4;
            border-radius: 5px;
            padding: 20px;
            text-align: center;
        }

        .product img {
            max-width: 100%;
        }

        .price {
            font-size: 1.2em;
            font-weight: bold;
        }

        button {
            background-color: #333;
            border: none;
            border-radius: 5px;
            color: #fff;
            cursor: pointer;
            font-size: 1em;
            padding: 10px 20px;
            transition: background-color 0.3s;
        }

        button:hover {
            background-color: #555;
        }

        footer {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        .contact-box {
            border: 2px solid #fff;
            border-radius: 5px;
            display: inline-block;
            padding: 10px 20px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
</head>
<body>
    <header>
        <h1>GUATEMALA VIRTUAL</h1>
        <nav>
            <ul>
                <li><a href="#">Inicio de sesión</a></li>
                <li><a href="#">Registro</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <article class="product">
            <img src="https://i.pinimg.com/736x/26/65/7e/26657e6eab9bfb06c6b1276f03701ee3.jpg" alt="Producto 1">
            <h2>Camisa de la Selección</h2>
            <p class="price">Q.600</p>
            <button>Comprar</button>
        </article>
        <article class="product">
            <img src="https://i.etsystatic.com/28677854/r/il/9db1c2/3058697855/il_1588xN.3058697855_dt4u.jpg" alt="Producto 2">
            <h2>Camisa Tipica</h2>
            <p class="price">Q.300</p>
            <button>Comprar</button>
        </article>
        <article class="product">
            <img src="https://i.ebayimg.com/images/g/C98AAOSwQsNinRXw/s-l500.jpg" alt="Producto 3">
            <h2>Camisa Tipica de la Selección</h2>
            <p class="price">Q.250</p>
            <button>Comprar</button>
        </article>
        <article class="product">
            <img src="https://th.bing.com/th/id/OIP.6N15Qot4PegZGKmMNxwGoQHaG-?rs=1&pid=ImgDetMain" alt="Producto 4">
            <h2>Camisa de Antigua Guatemala</h2>
            <p class="price">Q.275</p>
            <button>Comprar</button>
        </article>
        <article class="product">
            <img src="https://ropastipicas.com/wp-content/uploads/2023/05/Camisas_tipicas_de_hombre_en_Panajachel-600x697.webp" alt="Producto 5">
            <h2>Camisa de Panajachel</h2>
            <p class="price">Q.150</p>
            <button>Comprar</button>
        </article>
        <article class="product">
            <img src="https://th.bing.com/th/id/OIP.VUiv0bP1RHTsuUjLKsv8qwHaI3?rs=1&pid=ImgDetMain" alt="Producto 6">
            <h2>Camisa de Petén</h2>
            <p class="price">Q.200</p>
            <button>Comprar</button>
        </article>
    </main>
    <footer>
        <div class="contact-box">
            <p>Contactanos</p>
        </div>
        <p>&copy; 2024 Guatemala Virtual - Tienda en línea</p>
    </footer>
</body>
</html>
