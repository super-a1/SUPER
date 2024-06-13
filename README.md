<!DOCTYPE html>
<html lang="hr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>blabla</title>
    <style>
        body {
            font-family: Verdana, sans-serif;
            background-color: #fff8b0;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background: linear-gradient(45deg, #ffc107, #ff9800);
            color: #fff;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }
        nav ul li a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 20px;
        }
        .section {
            margin-bottom: 40px;
        }
        h2 {
            border-bottom: 2px solid #ffc107;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }
        .blog-post {
            background-color: #fff;
            border: 2px solid red;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            transition: transform 0.2s;
        }
        .blog-post:hover {
            transform: scale(1.05);
        }
        footer {
            background: linear-gradient(45deg, #ff9800, #ffc107);
            color: #fff;
            text-align: center;
            padding: 20px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
            box-shadow: 0 -4px 8px rgba(0,0,0,0.1);
        }
        a {
            color: #ff9800;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>blabla</h1>
        <nav>
            <ul>
                <li><a href="#meni">Meni</a></li>
                <li><a href="#kontakt">Kontakt</a></li>
                <li><a href="#blog">Blog</a></li>
            </ul>
        </nav>
    </header>
    <div class="container">
        <div id="meni" class="section">
            <h2>O meni</h2>
            <p>Blablabla</p>
        </div>
        <div id="kontakt" class="section">
            <h2>Kontakt</h2>
            <p>blabla <a href="mailto:toni.francic@example.com">blabla</a></p>
        </div>
        <div id="blog" class="section">
            <h2>Blog</h2>
            <div class="blog-post">
                <h3>Naslov Bloga 1</h3>
                <p>Ovo je prvi blog post. Ovdje možete napisati nešto zanimljivo ili podijeliti svoja iskustva.</p>
            </div>
            <div class="blog-post">
                <h3>Naslov Bloga 2</h3>
                <p>Ovo je drugi blog post. Nastavite dijeliti svoja iskustva i zanimljivosti.</p>
            </div>
        </div>
    </div>
    <footer>
        <p>&copy; blbla</p>
    </footer>
</body>
</html>
