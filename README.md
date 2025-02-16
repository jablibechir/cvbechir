﻿<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon CV</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            text-align: center;
        }
        header {
            background: #615d51;
            color: white;
            padding: 20px;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 10px;
        }
        nav a {
            text-decoration: none;
            color: #615d51;
            font-weight: bold;
        }
        section {
            padding: 20px;
            margin: 20px;
            background: white;
            border-radius: 10px;
        }
        .gallery img {
            width: 200px;
            height: auto;
            margin: 10px;
            border-radius: 10px;
        }
        form {
            display: flex;
            flex-direction: column;
            max-width: 400px;
            margin: auto;
        }
        input, textarea {
            margin: 10px 0;
            padding: 10px;
            border: 1px solid #615d51;
            border-radius: 5px;
        }
        button {
            background: #f5c242;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
            border-radius: 5px;
        }
        footer {
            margin-top: 20px;
            padding: 10px;
            background: #615d51;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bechir Jabli</h1>
        <p>Développeur Web | Marketing Digital</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#cv">Mon CV</a></li>
            <li><a href="#experience">Expérience</a></li>
            <li><a href="#iset">ISET Nabeul</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <section id="cv">
        <h2>Mon CV</h2>
        <embed src="CV.pdf" type="application/pdf" width="100%" height="500px" />
    </section>
    
    <section id="experience">
        <h2>Expérience Professionnelle</h2>
        <p><strong>EchoCome On Multimedia</strong> - Refonte du site Echo Tunisien</p>
    </section>
    
    <section id="iset">
        <h2>ISET Nabeul</h2>
        <div class="gallery">
            <img src="img1.jpg" alt="ISET Nabeul 1">
            <img src="img2.jpg" alt="ISET Nabeul 2">
            <img src="img3.jpg" alt="ISET Nabeul 3">
        </div>
    </section>
    
    <section id="contact">
        <h2>Contactez-moi</h2>
        <form>
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
        <p>&copy; 2025 Bechir Jabli</p>
    </footer>
</body>
</html>
