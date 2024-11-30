<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bouton intéractif</title>
    <link rel="stylesheet" href="mon.css">
</head>
<body>
    <header>
        <h1>Bienvenue sur mon site</h1>
    </header>
    <div id="cookie-banner" style="position: fixed; bottom: 0; background: #333; color: #fff; width: 100%; text-align: center; padding: 10px;">
        <p>Ce site utilise des cookies pour améliorer votre expérience. En poursuivant votre navigation, vous acceptez notre <a href="/politique-de-confidentialité" style="color: #4CAF50;">politique de confidentialité</a>.</p>
        <button onclick="acceptCookies()">Accepter</button>
        <button onclick="declineCookies()">Refuser</button>
    </div>
    <div>
        <button onclick="showMessage()">Clique ici mec</button>
    </div>
    <div>
        <button id="button1" ondblclick="showMessage()">Double click mec</button>
    </div> 
    <div>
        <img src="https://i.pinimg.com/originals/3a/ee/8d/3aee8d3cf15482a8972195ef398a081a.jpg" alt="chevre">
        <p id="commentaire1">Salut toi</p>
    </div>   
    <script>
        function showMessage(){
            alert("Tu n'aurais jamais dû");
        }
    </script>
</body>
</html>
