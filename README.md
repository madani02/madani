<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Interface Web</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 40px;
            background: #f5f5f5;
        }
        .container {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            max-width: 450px;
            margin: auto;
        }
        h1 { color: #333; }
        button {
            padding: 15px 25px;
            background: #007bff;
            border: none;
            color: white;
            border-radius: 6px;
            font-size: 16px;
            cursor: pointer;
        }
        button:hover { background: #0056b3; }
    </style>
</head>
<body>

<div class="container">
    <h1>Bienvenue !</h1>
    <p>Ceci est mon interface accessible au monde entier.</p>
    <button onclick="alert('Bonjour !')">Clique ici</button>
</div>

</body>
</html>
