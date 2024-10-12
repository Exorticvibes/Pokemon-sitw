<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Get Your Pokémon</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f5f5f5;
            color: #333;
        }
        h1 {
            color: #ff4500;
            margin-top: 50px;
            font-size: 36px;
        }
        button {
            padding: 15px 30px;
            font-size: 18px;
            background-color: #ff6347;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        button:hover {
            background-color: #ff4500;
        }
        #loadingText {
            display: none;
            margin-top: 20px;
            font-size: 20px;
            color: #555;
        }
        img {
            display: none;
            margin-top: 20px;
            width: 300px;
            height: auto;
            opacity: 0;
            transition: opacity 1s ease-in-out;
        }
    </style>
</head>
<body>
    <h1>Get Your Pokémon</h1>
    <button onclick="showPokemon()">Get Your Pokémon</button>
    <div id="loadingText">Finding your Pokémon...</div>
    <img id="pokemonImage" src="https://pbs.twimg.com/media/FlttQeHXEAA6pIU?format=jpg&name=small" alt="Pokemon">

    <script>
        function showPokemon() {
            // Show loading text
            document.getElementById('loadingText').style.display = 'block';

            // Hide image initially
            const pokemonImage = document.getElementById('pokemonImage');
            pokemonImage.style.display = 'none';
            pokemonImage.style.opacity = '0';

            // Wait for 3 seconds, then display the image
            setTimeout(function() {
                document.getElementById('loadingText').style.display = 'none';
                pokemonImage.style.display = 'block';
                setTimeout(function() {
                    pokemonImage.style.opacity = '1'; // Smooth fade-in effect
                }, 100);
            }, 3000); // 3 seconds delay
        }
    </script>
</body>
</html>
