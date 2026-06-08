<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GameHub Léger</title>

<style>
body{
    font-family: Arial, sans-serif;
    background:#121212;
    color:white;
    text-align:center;
    margin:0;
}

header{
    background:#00b894;
    padding:20px;
}

.games{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:20px;
    padding:20px;
}

.card{
    background:#1f1f1f;
    width:300px;
    padding:15px;
    border-radius:10px;
}

a{
    display:inline-block;
    padding:10px 20px;
    background:#00b894;
    color:white;
    text-decoration:none;
    border-radius:5px;
}
</style>
</head>
<body>

<header>
    <h1>🎮 GameHub Léger</h1>
    <p>Des jeux en ligne sans téléchargement</p>
</header>

<div class="games">

    <div class="card">
        <h2>2048</h2>
        <p>Jeu de réflexion.</p>
        <a href="https://play2048.co/" target="_blank">
            Jouer
        </a>
    </div>

    <div class="card">
        <h2>Snake</h2>
        <p>Le classique Snake.</p>
        <a href="https://playsnake.org/" target="_blank">
            Jouer
        </a>
    </div>

    <div class="card">
        <h2>Tetris</h2>
        <p>Empile les blocs.</p>
        <a href="https://tetris.com/play-tetris" target="_blank">
            Jouer
        </a>
    </div>

</div>

</body>
</html>
