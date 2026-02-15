# Social-Bracelet-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proverbs 16:3</title>
    <style>
        body {
            background-color: pink;
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 20px;
        }
        p {
            font-size: 20px;
            margin-bottom: 20px;
        }
        #verse-container {
            margin-top: 40px;
            font-size: 18px;
            font-style: italic;
        }
    </style>
</head>
<body>
    <h1>Proverbs 16:3</h1>
    <p>Commit to the Lord whatever you do, and he will establish your plans.</p>
    
    
    <div id="verse-container"></div>
    <script>
        // Array of random Bible verses
        var verses = [
            "God loves you ❤️",
            "Trust in the Lord - Proverbs 3:5",
            "I know the plans I have for you - Jeremiah 29:11",
            "Be strong and courageous - Joshua 1:9",
            "The Lord is my shepherd - Psalm 23:1",
            "Love your neighbor - Matthew 22:39"
        ];

        // Function to get a random verse
        function getRandomVerse() {
            return verses[Math.floor(Math.random() * verses.length)];
        }

        // Set a random verse in the container on page load
        var randomVerse = getRandomVerse();
        document.getElementById('verse-container').textContent = randomVerse;
    </script>
</body>
</html>
