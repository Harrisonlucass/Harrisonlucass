<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coracao Especial</title>
    <style>
        body {
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
        }

        #coracao {
            cursor: pointer;
        }
    </style>
</head>
<body>

    <div id="coracao" onclick="mostrarMensagem()">
        &#x2665; <!-- Código Unicode para o símbolo de coração -->
    </div>

    <script>
        function mostrarMensagem() {
            alert("Você é muito especial! Eu te amo.");
        }
    </script>

</body>
</html>

