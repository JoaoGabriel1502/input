<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mensagem de Bom Dia</title>
</head>
<body>
    <input type="text" id="nome" placeholder="Digite seu nome" />
    <button onclick="Bomdia()">Enviar</button>

    <script>
        function Bomdia() {
            const nome = document.getElementById("nome").value;
            alert("Bom dia, " + nome + "!");
        }
    </script>
</body>
</html>
