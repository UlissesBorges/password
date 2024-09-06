<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="keywords" content="Gerador de senhas, create password">
    <title>Create Password</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>
    <img class="logo" src="./assets/logo.png" alt="Create password" />    
    <img class="logo" src="./assets/cat-ado.png" alt="Create password" />

    <main class="container-input">
        <span>Tamanho <span id="valor"></span> caracteres</span>
        <input id="slider" class="slider" type="range" min="8" max="25">
        <button id="button" class="button-cta" onclick="generatePassword()">Gerar senha</button>
    </main>

    <div id="container-password" onclick="copyPassword()" class="container-password hide">
        <span class="tittle">Sua senha gerada foi:</span>
        <span id="password" class="password"></span>
        <span id="tooltip" class="tooltip">Clique na senha para copiar. 📝</span>
    </div>
    <script src="script.js"></script>
</body>

</html>
