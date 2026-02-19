# Gaga.-Github.Io
Blablsbla
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Красочное приветствие</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', sans-serif;
        }

        body {
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(-45deg, #ff6b6b, #feca57, #48dbfb, #5f27cd);
            background-size: 400% 400%;
            animation: gradientBG 10s ease infinite;
            overflow: hidden;
        }

        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .container {
            text-align: center;
            color: white;
        }

        h1 {
            font-size: 60px;
            animation: fadeInDown 1.5s ease forwards;
            opacity: 0;
        }

        p {
            font-size: 22px;
            margin-top: 20px;
            animation: fadeInUp 2s ease forwards;
            opacity: 0;
        }

        button {
            margin-top: 30px;
            padding: 15px 40px;
            font-size: 18px;
            border: none;
            border-radius: 30px;
            background: white;
            color: #5f27cd;
            cursor: pointer;
            transition: 0.4s;
            animation: fadeIn 3s ease forwards;
            opacity: 0;
        }

        button:hover {
            background: #5f27cd;
            color: white;
            transform: scale(1.1);
        }

        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-50px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(50px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>

<body>

<div class="container">
    <h1>Добро пожаловать ✨</h1>
    <p>Этот сайт создан с любовью и анимацией 💖</p>
    <button onclick="alert('Ты самая лучшая! 💕')">Нажми меня</button>
</div>

</body>
</html>
