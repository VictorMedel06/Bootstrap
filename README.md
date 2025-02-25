# Bootstrap
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bienvenidos a Nuestra Web</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background: linear-gradient(to right, #ff7e5f, #feb47b);
            color: white;
            margin: 0;
            padding: 0;
        }
        .container {
            padding: 50px;
        }
        h1 {
            font-size: 3em;
            animation: fadeIn 2s;
        }
        .points {
            margin-top: 30px;
            font-size: 1.5em;
            list-style: none;
            padding: 0;
        }
        .points li {
            background: rgba(255, 255, 255, 0.2);
            padding: 15px;
            margin: 10px auto;
            width: 60%;
            border-radius: 10px;
            transition: transform 0.3s;
        }
        .points li:hover {
            transform: scale(1.1);
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Bienvenidos a Nuestra Web</h1>
        <p>Conoce los puntos clave a tener en cuenta:</p>
        <ul class="points">
            <li>1.- [Explicación del primer punto]</li>
            <li>2.- [Explicación del segundo punto]</li>
            <li>3.- [Explicación del tercer punto]</li>
        </ul>
    </div>
</body>
</html>
