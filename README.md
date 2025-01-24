# Nlphotographie
Photos
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Photographe</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Mon Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">À propos</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>À propos</h2>
        <p>Bienvenue ! Je suis un photographe passionné spécialisé dans les paysages et les portraits. Découvrez mes travaux ci-dessous.</p>
    </section>

    <section id="portfolio">
        <h2>Portfolio</h2>
        <div class="gallery">
            <img src="photo1.jpg" alt="Photo 1">
            <img src="photo2.jpg" alt="Photo 2">
            <img src="photo3.jpg" alt="Photo 3">
        </div>
    </section>

    <section id="services">
        <h2>Services</h2>
        <ul>
            <li>Séances photo portrait</li>
            <li>Photographie de paysage</li>
            <li>Retouches et impressions</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Envoyez-moi un message pour réserver une séance !</p>
        <form action="mailto:tonemail@example.com" method="post" enctype="text/plain">
            <label for="name">Nom :</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email :</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message :</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Envoyer</button>
        </form>
    </section>

    <footer>
        <p>© 2025 Mon Portfolio. Tous droits réservés.</p>
    </footer>
</body>
</html>
