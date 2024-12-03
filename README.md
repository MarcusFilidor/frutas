<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Verdulería - Frutas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
        }

        header {
            background-color: #FFD700; /* Amarillo */
            padding: 20px;
            text-align: center;
            font-size: 24px;
            color: #000;
        }

        .content {
            padding: 20px;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .fruit-card {
            background-color: #808080; /* Gris */
            padding: 20px;
            border-radius: 10px;
            width: 200px;
            text-align: center;
            color: #fff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .fruit-card h3 {
            margin: 10px 0;
        }

        .fruit-card p {
            font-size: 18px;
            margin: 5px 0;
        }

        footer {
            background-color: #000; /* Negro */
            color: #fff;
            text-align: center;
            padding: 10px;
        }

        .back-to-home {
            margin-top: 20px;
            background-color: #FFD700;
            color: #000;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }

        .back-to-home:hover {
            background-color: #e6b800;
        }
    </style>
</head>
<body>

<header>
    Verdulería - Frutas
</header>

<div class="content">
    <div class="fruit-card">
        <h3>Manzana</h3>
        <p>Fruta fresca y deliciosa</p>
    </div>
    <div class="fruit-card">
        <h3>Plátano</h3>
        <p>Ideal para el desayuno</p>
    </div>
    <div class="fruit-card">
        <h3>Naranja</h3>
        <p>Rica en vitamina C</p>
    </div>
    <div class="fruit-card">
        <h3>Uvas</h3>
        <p>Perfectas para picar</p>
    </div>
    <div class="fruit-card">
        <h3>Pera</h3>
        <p>Dulce y jugosa</p>
    </div>
</div>

<footer>
    <a href="index.html" class="back-to-home">Volver al Inicio</a>
</footer>

</body>
</html>
