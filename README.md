
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Site Enseignant</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            margin: 20px;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #4CAF50;
            font-weight: bold;
        }
        .container {
            padding: 20px;
            max-width: 800px;
            margin: 0 auto;
        }
        h2 {
            color: #4CAF50;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Page personnelle de Thomas DESORGERIS</h1>
        <p>Bienvenue </p>
    </header>
    <nav>
        <a href="#lycee">Lycée</a>
        <a href="#projets">Projets</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <!-- Section Lycée -->
        <section id="lycee">
            <h2>Cours</h2>
            <p>Retrouvez ici tous mes cours et travaux dirigés .</p>
            <ul>
                <li><a href="lycee/seconde/cours1.pdf" target="_blank">Cours 1 - Classe 1</a></li>
                <li><a href="lycee/classe2/cours2.pdf" target="_blank">Cours 2 - Classe 2</a></li>
            </ul>
        </section>

        <!-- Section Projets -->
        <section id="projets">
            <h2>Projets</h2>
            <p>Découvrez les projets pédagogiques que je propose.</p>
            <ul>
                <li><a href="projets/projet1.pdf" target="_blank">Projet 1</a></li>
                <li><a href="projets/projet2.pdf" target="_blank">Projet 2</a></li>
            </ul>
        </section>

        <!-- Section Contact -->
        <section id="contact">
            <h2>Contact</h2>
            <p>Vous pouvez me contacter à l'adresse suivante : <a href="mailto:mon-email@exemple.com">mon-email@exemple.com</a>.</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2025 DESORGERIS Thomas</p>
    </footer>
</body>
</html>
