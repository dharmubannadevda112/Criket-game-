# Criket-game-
Criket game 
y<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Cricket Game</title>
    <style>
        body {
            background-color: #e0f7fa;
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 20px;
        }
        header {
            background-color: #00796b;
            padding: 20px;
            color: white;
        }
        h1 {
            margin: 0;
        }
        .cricket-image {
            width: 300px;
            margin: 20px auto;
            display: block;
        }
        .start-button {
            padding: 15px 30px;
            font-size: 1.2em;
            background-color: #00796b;
            color: white;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            margin-top: 30px;
        }
        .start-button:hover {
            background-color: #004d40;
        }
        .game-area {
            margin-top: 40px;
            display: none;
        }
        /* Add more styles as needed for game elements */
    </style>
</head>
<body>
    <header>
        <h1>Welcome to the Cricket Game</h1>
    </header>
    <img src="https://images.unsplash.com/photo-1552611052-0a8be8f7e711?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Cricket" class="cricket-image" />
    <p>Get ready to bat and bowl!</p>
    <button class="start-button" onclick="startGame()">Start Game</button>

    <div class="game-area" id="gameArea">
        <h2>Game Starts Here!</h2>
        <!-- You can add game logic and elements here -->
    </div>

    <script>
        function startGame() {
            document.getElementById('gameArea').style.display = 'block';
            alert('Game is starting!'); // Placeholder for game logic
        }
    </script>
</body>
</html>
