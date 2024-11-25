<!DOCTYPE html>
<html>
<head>
    <title>Casa Assombrada</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="quarto">
        <img src="quarto_escuro.jpg" alt="Quarto escuro">
        <p>Você está em um quarto escuro. Uma porta range no final do corredor. O que você faz?</p>
        <button onclick="explorarCorredor()">Explorar o corredor</button>
    </div>

    <script src="script.js"></script>
</body>
</html>/* style.css */
body {
    background-color: black;
    color: white;
    font-family: 'Times New Roman', serif;
}

.quarto {
    text-align: center;
}// script.js
function explorarCorredor() {
    // Aqui você pode adicionar sons, animações e mostrar uma nova imagem
    alert("Um grito ecoa pelos corredores. Você está sozinho?");
}
