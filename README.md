# Letras_eternas.es
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Literatura</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 15px 20px;
        }
        nav a:hover {
            background-color: #575757;
        }
        .container {
            text-align: center;
            margin: 50px;
        }
        .option {
            display: inline-block;
            width: 250px;
            margin: 20px;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 10px;
            background-color: white;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .option h2 {
            color: #4CAF50;
        }
        .option button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 5px;
        }
        .option button:hover {
            background-color: #45a049;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Tienda de Literatura</h1>
        <p>Explora nuestra colección de cuentos y poemas</p>
    </header>
    <nav>
        <a href="#cuentos">Cuentos</a>
        <a href="#poemas">Poemas</a>
    </nav>
    <div class="container">
        <div id="cuentos" class="option">
            <h2>Cuentos</h2>
            <p>Descubre fascinantes historias que te transportarán a otros mundos.</p>
            <button onclick="alert('Opción para comprar cuentos próximamente disponible')">Comprar Cuentos</button>
        </div>
        <div id="poemas" class="option">
            <h2>Poemas</h2>
            <p>Sumérgete en versos llenos de emoción e inspiración.</p>
            <button onclick="alert('Opción para comprar poemas próximamente disponible')">Comprar Poemas</button>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Tienda de Literatura. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
