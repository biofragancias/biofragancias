<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfumes Elegantes</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #333;
        }
        header {
            background-color: #343a40;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            margin: 0 auto;
            max-width: 1200px;
            display: flex;
            justify-content: center;
            gap: 1rem;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-size: 1.2rem;
        }
        .hero {
            background-image: url('https://via.placeholder.com/1200x400');
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            padding: 5rem 1rem;
        }
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }
        .products {
            max-width: 1200px;
            margin: 2rem auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
        }
        .product {
            background: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 1rem;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .product img {
            max-width: 100%;
            border-radius: 8px;
        }
        .product h3 {
            font-size: 1.2rem;
            margin: 1rem 0 0.5rem;
        }
        .product p {
            margin-bottom: 0.5rem;
            color: #555;
        }
        footer {
            background-color: #343a40;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Perfumes Elegantes</h1>
        <nav>
            <a href="#inicio">Inicio</a>
            <a href="#productos">Productos</a>
            <a href="#contacto">Contacto</a>
        </nav>
    </header>

    <section class="hero" id="inicio">
        <h1>Descubre tu aroma perfecto</h1>
        <p>Los mejores perfumes para cada ocasión.</p>
    </section>

    <section class="products" id="productos">
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Perfume 1">
            <h3>Perfume Floral</h3>
            <p>Una fragancia dulce y delicada.</p>
            <p><strong>$50.00</strong></p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Perfume 2">
            <h3>Perfume Cítrico</h3>
            <p>Refrescante y vibrante.</p>
            <p><strong>$45.00</strong></p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Perfume 3">
            <h3>Perfume Amaderado</h3>
            <p>Elegante y sofisticado.</p>
            <p><strong>$60.00</strong></p>
        </div>
    </section>

    <footer id="contacto">
        <p>&copy; 2024 Perfumes Elegantes. Todos los derechos reservados.</p>
        <p>Contacto: info@perfumes.com</p>
    </footer>
</body>
</html>
