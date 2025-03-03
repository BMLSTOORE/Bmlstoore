<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BMLSTOORE - Catálogo de Ropa Deportiva</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }
        body {
            background-color: #121212;
            color: #fff;
        }
        header {
            background: linear-gradient(90deg, #ffcc00, #ff8800);
            padding: 20px;
            text-align: center;
            font-size: 28px;
            font-weight: 600;
            text-transform: uppercase;
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 40px auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .product {
            background: #1e1e1e;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            transition: transform 0.3s ease-in-out;
        }
        .product:hover {
            transform: scale(1.05);
        }
        .product img {
            width: 100%;
            max-width: 220px;
            border-radius: 10px;
        }
        .product h3 {
            margin: 15px 0 10px;
            font-size: 20px;
            color: #ffcc00;
        }
        .product p {
            font-size: 18px;
            font-weight: bold;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #222;
            color: #ffcc00;
            margin-top: 40px;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <header>BMLSTOORE - Catálogo de Ropa Deportiva</header>
    <div class="container">
        <div class="product">
            <img src="https://via.placeholder.com/220" alt="Camiseta Deportiva">
            <h3>Camiseta Deportiva</h3>
            <p>Precio: $29.99</p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/220" alt="Chándal Completo">
            <h3>Chándal Completo</h3>
            <p>Precio: $59.99</p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/220" alt="Short Deportivo">
            <h3>Short Deportivo</h3>
            <p>Precio: $24.99</p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/220" alt="Sudadera Deportiva">
            <h3>Sudadera Deportiva</h3>
            <p>Precio: $39.99</p>
        </div>
    </div>
    <footer>
        &copy; 2025 BMLSTOORE - Todos los derechos reservados
    </footer>
</body>
</html>
