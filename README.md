<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website - Numele Prenumele</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: #0073e6;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            background: #ddd;
            padding: 1rem;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #0073e6;
        }
        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
            background: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            background: #0073e6;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            margin-top: 20px;
        }
        img {
            max-width: 100%;
            height: auto;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        form label {
            margin: 10px 0 5px;
        }
        form input, form textarea, form button {
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Website realizat de [Numele Prenumele]</h1>
    </header>
    
    <nav>
        <a href="#home">Acasă</a>
        <a href="#about">Despre</a>
        <a href="#gallery">Galerie</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="home" class="container">
        <h2>Bun venit!</h2>
        <p>Aceasta este o pagină demonstrativă creată pentru a respecta cerințele date.</p>
    </section>

    <section id="about" class="container">
        <h2>Despre autor</h2>
        <p>Sunt [Numele Prenumele], pasionat de tehnologie și dezvoltare web.</p>
    </section>

    <section id="gallery" class="container">
        <h2>Galerie</h2>
        <p>Iată două imagini cu sursele indicate:</p>
        <figure>
            <img src="https://via.placeholder.com/400" alt="Imagine 1">
            <figcaption>Imagine 1 sursa: <a href="https://via.placeholder.com" target="_blank">placeholder.com</a></figcaption>
        </figure>
        <figure>
            <img src="https://via.placeholder.com/400" alt="Imagine 2">
            <figcaption>Imagine 2 sursa: <a href="https://via.placeholder.com" target="_blank">placeholder.com</a></figcaption>
        </figure>
    </section>

    <section id="contact" class="container">
        <h2>Contact</h2>
        <form action="mailto:youremail@example.com" method="post" enctype="text/plain">
            <label for="name">Nume:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Mesaj:</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <button type="submit">Trimite</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 [Numele Prenumele]. Toate drepturile rezervate.</p>
        <p>
            <a href="https://google.com" target="_blank">Google</a> |
            <a href="https://github.com" target="_blank">GitHub</a> |
            <a href="https://wikipedia.org" target="_blank">Wikipedia</a> |
            <a href="https://stackOverflow.com" target="_blank">Stack Overflow</a>
        </p>
    </footer>
</body>
</html>
