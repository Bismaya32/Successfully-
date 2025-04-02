# Successfully-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>I Love You</title>
    <style>
        body {
            background-color: pink;
            text-align: center;
            font-family: Arial, sans-serif;
        }
        h1 {
            font-size: 3em;
            color: red;
        }
        .heart {
            font-size: 5em;
            animation: heartbeat 1s infinite;
            color: red;
        }
        @keyframes heartbeat {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }
        .btn {
            background-color: red;
            color: white;
            padding: 10px 20px;
            font-size: 1.5em;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h1>I Love You ❤️</h1>
    <p class="heart">❤️</p>
    <button class="btn" onclick="showMessage()">Click Me</button>
    <p id="message" style="display:none; font-size: 2em; color: darkred;">Will You Be Mine? 💖</p>

    <script>
        function showMessage() {
            document.getElementById('message').style.display = 'block';
        }
    </script>
</body>
</html>
