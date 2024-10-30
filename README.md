<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modelos de Breakpoint</title>
    <link href="https://maxcdn.bootstrapcdn.com/bootstrap/5.3.0/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background-color: #555;
            color: #ddd;
            font-family: Arial, sans-serif;
        }

        .container-custom {
            padding: 20px;
            max-width: 800px;
            margin: auto;
            border: 2px solid black;
            background-color: #666;
        }

        .highlight {
            background-color: #f9e79f;
            color: blue;
            font-weight: bold;
            padding: 5px;
        }
    </style>
</head>

<body>
    <div class="container container-custom">
        <h1 class="mb-4">Modelos de Breakpoint</h1>
        
        <div class="row">
            <div class="col-12 mb-2">X-Small - Ativado quando resolução for menor que 576px</div>
            <div class="col-12 mb-2">Small - Ativado quando resolução for maior que 576px e menor que 768px</div>
            <div class="col-12 mb-2">Medium - Ativado quando resolução for maior que 768px e menor que 992px</div>
            <div class="col-12 mb-2 highlight">Large - Ativado quando resolução for maior que 992px e menor que 1200px</div>
            <div class="col-12 mb-2">Extra Large - Ativado quando resolução for maior que 1200px e menor que 1400px</div>
            <div class="col-12 mb-2">Extra extra Large - Ativado quando resolução for maior que 1400px</div>
        </div>
    </div>
</body>
</html>
