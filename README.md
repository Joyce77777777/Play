# Play
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Personal Music Album</title>
    <style>
        a {
            color: Black;
            text-decoration: none;
        }

        a:visited {
            color: Grey;
        }

        body {
            background-color: #f3ebe2;
            font-family: 'Georgia', serif;
            color: #5d5d5a;
            margin: 0;
            padding: 0;
        }

        h1, h2 {
            text-align: center;
        }

        h1 {
            margin-top: 40px;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }

        .category {
            border-bottom: 2px solid #ccc;
            margin-bottom: 20px;
        }

        .song {
            padding: 10px 0;
        }

        img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 20px auto;
            border-radius: 10px;
        }
    </style>
</head>

<body>
    <h1>Your Personal Music Album</h1>
    <div class="container">

        <div class="category">
            <h2>Mandarin/Cantonese</h2>
            <div class="song"><a href="https://www.youtube.com/watch?v=K4i7UfFSr8k" target="_blank">Private Memory</a></div>
            <div class="song"><a href="https://www.youtube.com/watch?v=xHsSWiLsIRY" target="_blank">Betray</a></div>
            <div class="song"><a href="https://www.youtube.com/watch?v=cPKfUWDmNbo" target="_blank">Next Stop, Tianhou</a></div>
            <div class="song"><a href="https://www.youtube.com/watch?v=rT4FqOwn-rs" target="_blank">Turns Out You Want Nothing</a></div>
        </div>

        <img src="hkhk.jpg" alt="HK">

        <div class="category">
            <h2>Japanese</h2>
            <div class="song">Lemon</div>
            <div class="song">The crying face with a smile</div>
        </div>

        <img src="jpjp.jpg" alt="TK">

        <!-- Add more categories and songs as needed -->

    </div>
</body>

</html>
