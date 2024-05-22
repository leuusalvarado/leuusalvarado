- 👋 Hi, I’m @leuusalvarado
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
leuusalvarado/leuusalvarado is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Leuis Alvarado Payano - Videos de Partidos de Basket</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: #fff;
            padding: 1em;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #555;
        }
        .container {
            padding: 2em;
        }
        h1, h2 {
            text-align: center;
        }
        .video-section, .shop-section {
            margin: 2em 0;
        }
        .video-list, .product-list {
            display: flex;
            flex-wrap: wrap;
            gap: 1em;
            justify-content: center;
        }
        .video-item, .product-item {
            background-color: #fff;
            border: 1px solid #ddd;
            padding: 1em;
            width: 300px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Leuis Alvarado Payano</h1>
        <p>Videos de Partidos de Basket</p>
    </header>
    <nav>
        <a href="#videos">Videos</a>
        <a href="#shop">Tienda</a>
    </nav>
    <div class="container">
        <section id="videos" class="video-section">
            <h2>Videos de Partidos</h2>
            <div class="video-list">
                <div class="video-item">
                    <h3>Partido 1</h3>
                    <video width="100%" controls>
                        <source src="video1.mp4" type="video/mp4">
                        Tu navegador no soporta la etiqueta de video.
                    </video>
                    <p><a href="video1.mp4" download>Descargar Video</a></p>
                </div>
                <div class="video-item">
                    <h3>Partido 2</h3>
                    <video width="100%" controls>
                        <source src="video2.mp4" type="video/mp4">
                        Tu navegador no soporta la etiqueta de video.
                    </video>
                    <p><a href="video2.mp4" download>Descargar Video</a></p>
                </div>
            </div>
        </section>
        <section id="shop" class="shop-section">
            <h2>Tienda de Ropa</h2>
            <div class="product-list">
                <div class="product-item">
                    <h3>Camiseta de Basket</h3>
                    <img src="camiseta.jpg" alt="Camiseta de Basket" width="100%">
                    <p>Precio: $20</p>
                    <button>Comprar Ahora</button>
                </div>
                <div class="product-item">
                    <h3>Pantalones Deportivos</h3>
                    <img src="pantalones.jpg" alt="Pantalones Deportivos" width="100%">
                    <p>Precio: $25</p>
                    <button>Comprar Ahora</button>
                </div>
            </div>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Leuis Alvarado Payano. Todos los derechos reservados.</p>
    </footer>
</body>
</html>

