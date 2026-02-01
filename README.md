<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Valentine’s Day Baby ❤️</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background: linear-gradient(to bottom right, #ff9a9e, #fad0c4);
            color: white;
            text-align: center;
        }
        .container {
            padding: 80px 20px;
        }
        h1 {
            font-size: 48px;
        }
        p {
            font-size: 20px;
            max-width: 600px;
            margin: 20px auto;
        }
        button {
            background: white;
            color: #ff4d6d;
            border: none;
            padding: 14px 26px;
            border-radius: 30px;
            font-size: 16px;
            cursor: pointer;
            margin-top: 20px;
        }
        button:hover {
            background: #ffe6eb;
        }
        .heart {
            font-size: 40px;
            animation: pulse 1.5s infinite;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body>

<div class="container">
    <div class="heart">❤️</div>
    <h1>Happy Valentine’s Day</h1>
    <p>
        You make my ordinary days brighter and my best days unforgettable.
        This little page is just a reminder of how special you are to me 💕
    </p>
    <button onclick="revealLove()">Click for a surprise 💌</button>
    <p id="message"></p>
</div>

<script>
    function revealLove() {
        document.getElementById("message").innerText =
        "I choose you. Today. Tomorrow. Always ❤️";
    }
</script>

</body>
</html>
