<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hidden Love Website</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f5f5f5;
            color: #333;
            text-align: center;
            padding: 20px;
            margin: 0;
        }
        h1 {
            color: #ff6f61;
            font-size: 36px;
        }
        .hidden-message {
            display: none; /* Hidden initially */
            font-size: 20px;
            color: #555;
            margin-top: 20px;
        }
        button {
            padding: 10px 20px;
            background-color: #ff6f61;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 18px;
            cursor: pointer;
        }
        button:hover {
            background-color: #ff3b3b;
        }
    </style>
</head>
<body>
    <h1>My Secret Love Message</h1>
    <p>There's something special here. Click the button to reveal it!</p>

    <button id="revealBtn">Reveal My Love</button>
    
    <div class="hidden-message" id="loveMessage">
        <p>💖 You are my world, and my heart belongs to you. 💖</p>
    </div>

    <script>
        // JavaScript function to reveal the love message
        document.getElementById('revealBtn').addEventListener('click', function() {
            const message = document.getElementById('loveMessage');
            message.style.display = 'block'; // Show the hidden message
        });
    </script>
</body>
</html>

