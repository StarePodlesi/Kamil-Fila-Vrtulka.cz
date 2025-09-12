<!DOCTYPE html>
<html lang="cs">
<head>
    <meta charset="UTF-8">
    <title>Můj plyšový krtek</title>
    <style>
        /* Celá stránka */
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            /* Červeno-modrý gradient */
            background: linear-gradient(135deg, #ff4d4d, #4d79ff);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        /* Hlavní blok s textem a obrázky */
        .container {
            background: rgba(255, 255, 255, 0.85); /* mírně průhledný blok */
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
            max-width: 700px;
            text-align: center;
        }

        h1 {
            color: #ff1a1a; /* červená pro nadpis */
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        p {
            font-size: 1.2em;
            color: #333;
            line-height: 1.6;
        }

        img {
            margin-top: 20px;
            max-width: 100%;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Můj plyšový krtek</h1>
        <p>Tady je můj malý kamarád! Přináší mi radost každý den. 🐾</p>
        <img src="krtek.jpg" alt="Můj plyšový krtek">
        <p>Občas s ním píšu příběhy a vyprávím si o jeho dobrodružstvích.</p>
    </div>
</body>
</html>
