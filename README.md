<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¡Las Mejores Donas en la Ciudad!</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fdf4e3;
            color: #333;
        }

        header {
            background-color: #ff6b6b;
            padding: 20px;
            text-align: center;
            color: white;
        }

        header h1 {
            margin: 0;
            font-size: 3em;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .intro {
            text-align: center;
            margin-bottom: 40px;
        }

        .intro p {
            font-size: 1.2em;
            line-height: 1.5;
        }

        .donut-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .donut {
            background-color: #fff;
            border: 2px solid #ff6b6b;
            border-radius: 15px;
            overflow: hidden;
            text-align: center;
            transition: transform 0.3s ease;
        }

        .donut:hover {
            transform: scale(1.05);
        }

        .donut img {
            width: 100%;
            height: auto;
            display: block;
        }

        .donut h2 {
            font-size: 1.5em;
            margin: 15px 0;
        }

        .donut p {
            padding: 0 15px 15px;
        }

        footer {
            background-color: #ff6b6b;
            color: white;
            text-align: center;
            padding: 20px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>¡Deliciosas Donas!</h1>
</header>

<div class="container">
    <div class="intro">
        <p>¡Descubre la variedad más deliciosa de donas artesanales! Perfectas para cualquier ocasión, nuestras donas son esponjosas, suaves y llenas de sabor.</p>
    </div>

    <div class="donut-grid">
        <div class="donut">
            <img src="https://images.unsplash.com/photo-1599785209707-e4e5e15c2479" alt="Dona de chocolate">
            <h2>Dona de Chocolate</h2>
            <p>Sumérgete en la riqueza del chocolate con nuestra dona más popular, cubierta con una capa suave de chocolate.</p>
        </div>
        <div class="donut">
            <img src="https://images.unsplash.com/photo-1599785210099-c6d5c95a2d30" alt="Dona de fresa">
            <h2>Dona de Fresa</h2>
            <p>Fresca y afrutada, nuestra dona de fresa es perfecta para los amantes del sabor dulce y natural.</p>
        </div>
        <div class="donut">
            <img src="https://images.unsplash.com/photo-1599785209671-fbffb2e645b1" alt="Dona glaseada">
            <h2>Dona Glaseada</h2>
            <p>La clásica dona glaseada, perfecta en su simplicidad, con una cobertura que se derrite en tu boca.</p>
        </div>
        <div class="donut">
            <img src="https://images.unsplash.com/photo-1599785209828-13d8a55c4bfb" alt="Dona de caramelo">
            <h2>Dona de Caramelo</h2>
            <p>Para los más golosos, nuestra dona de caramelo es una experiencia indulgente llena de sabor.</p>
        </div>
    </div>
</div>

<footer>
    <p>Visítanos hoy y prueba nuestras deliciosas donas. ¡No te arrepentirás!</p>
</footer>

</body>
</html>
