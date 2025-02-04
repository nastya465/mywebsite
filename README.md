<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Прикольный сайт</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');

        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            color: white;
            text-align: center;
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .container {
            background: rgba(255, 255, 255, 0.2);
            padding: 20px;
            border-radius: 15px;
            backdrop-filter: blur(10px);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }

        h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        button {
            background: #ff6f61;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 1.2em;
            cursor: pointer;
            border-radius: 10px;
            transition: 0.3s;
        }

        button:hover {
            background: #ff3b2e;
            transform: scale(1.1);
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Привет, мир! 🌍</h1>
        <p>Это мой прикольный сайт с плавной анимацией!</p>
        <button onclick="magicFunction()">Нажми меня 🚀</button>
    </div>

    <script>
        function magicFunction() {
            alert("Ты нажал на кнопку! 🔥");
        }
    </script>

</body>
</html>
