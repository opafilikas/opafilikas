<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mobile Webseite</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }

        header img {
            max-width: 100px;
            height: auto;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
            padding: 10px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
        }

        .main-content {
            padding: 20px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo.png" alt="Logo">
        <h1>Titel der Seite</h1>
    </header>

    <nav>
        <a href="#login">Login</a>
        <a href="#info">Info</a>
        <a href="#impressum">Impressum</a>
        <a href="#logout">Logout</a>
    </nav>

    <div class="main-content">
        <div id="login">
            <h2>Login</h2>
            <!-- Hier kann der Login-Inhalt hinzugefügt werden -->
        </div>

        <div id="info" style="display: none;">
            <h2>Info</h2>
            <!-- Hier kann der Info-Inhalt hinzugefügt werden -->
        </div>

        <div id="impressum" style="display: none;">
            <h2>Impressum</h2>
            <!-- Hier kann der Impressum-Inhalt hinzugefügt werden -->
        </div>

        <div id="logout" style="display: none;">
            <h2>Logout</h2>
            <!-- Hier kann der Logout-Inhalt hinzugefügt werden -->
        </div>
    </div>

    <footer>
        &copy; 2023 Mobile Webseite | Alle Rechte vorbehalten | <a href="#impressum">Impressum</a>
    </footer>
</body>
</html>
