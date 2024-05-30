<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Osobista Strona</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f3f0ff;
            color: #333;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        h1, h2, h3 {
            color: #5d3fd3;
        }
        .header, .footer {
            text-align: center;
            padding: 20px;
            background-color: #e5d7ff;
        }
        .section {
            margin-bottom: 40px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
        }
        .contact-form button {
            background-color: #5d3fd3;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #4c2bb3;
        }
        .social-links a {
            margin: 0 10px;
            color: #5d3fd3;
            text-decoration: none;
        }
        .social-links a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Imię i Nazwisko</h1>
    </div>
    <div class="container">
        <div class="section">
            <h2>O mnie</h2>
            <p>Krótka biografia...</p>
        </div>
        <div class="section">
            <h2>Zainteresowania</h2>
            <p>Twoje zainteresowania...</p>
        </div>
        <div class="section">
            <h2>Umiejętności</h2>
            <p>Twoje umiejętności...</p>
        </div>
        <div class="section">
            <h2>Wykształcenie</h2>
            <p>Twoje wykształcenie...</p>
        </div>
        <div class="section">
            <h2>Blog</h2>
            <p>Wkrótce...</p>
        </div>
        <div class="section">
            <h2>Kontakt</h2>
            <form class="contact-form">
                <input type="text" name="name" placeholder="Twoje imię">
                <input type="email" name="email" placeholder="Twój email">
                <textarea name="message" placeholder="Twoja wiadomość"></textarea>
                <button type="submit">Wyślij</button>
            </form>
        </div>
    </div>
    <div class="footer">
        <h3>Znajdź mnie w mediach społecznościowych</h3>
        <div class="social-links">
            <a href="#">Facebook</a>
            <a href="#">Twitter</a>
            <a href="#">LinkedIn</a>
        </div>
        <p>Dane kontaktowe: email@example.com</p>
    </div>
</body>
</html>
