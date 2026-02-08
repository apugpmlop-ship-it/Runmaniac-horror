<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RunManiac Horror</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-image: url('https://example.com/scary-background.jpg'); /* Замените на реальный URL страшного фона */
            background-size: cover;
            background-position: center;
            color: #fff;
            text-align: center;
            overflow-x: hidden;
        }

        h1 {
            font-size: 4rem;
            margin-bottom: 1rem;
            color: #ff0000;
        }

        p {
            font-size: 1.5rem;
            margin-bottom: 1rem;
        }

        .info button {
            background-color: transparent;
            border: 2px solid #ffffff;
            color: white;
            padding: 10px 20px;
            font-size: 1.2rem;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .info button:hover {
            background-color: rgba(255, 255, 255, 0.1);
        }

        #more-info {
            display: none;
            font-size: 1.2rem;
            line-height: 1.5;
            margin-top: 1rem;
        }

        a button {
            background-color: #000000;
            color: white;
            padding: 10px 20px;
            font-size: 1.2rem;
            margin-top: 2rem;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        a button:hover {
            background-color: rgba(0, 0, 0, 0.8);
        }

        .images {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin-top: 2rem;
        }

        .images img {
            width: 200px;
            height: 150px;
            object-fit: cover;
            border-radius: 10px;
        }

        #download-section {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin-top: 2rem;
        }

        #download-section button {
            background-color: transparent;
            border: 2px solid #ffffff;
            color: white;
            padding: 10px 20px;
            font-size: 1.2rem;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        #download-section button:hover {
            background-color: rgba(255, 255, 255, 0.1);
        }

        .footer {
            margin-top: 2rem;
            font-size: 0.8rem;
            opacity: 0.7;
        }
    </style>
</head>
<body>

<!-- Шапка -->
<h1>RunManiac Horror</h1>
<p>Добро пожаловать в RunManiac Horror!</p>
<p>Погрузитесь в мир ужасов и попробуйте выбраться живым.</p>

<!-- Основная информация -->
<div class="info">
    <p>Цель:</p>
    <p>В игре будет 3 маньяка, и надо будет от них сбежать. Будет 3 этажа.</p>
    <p>На 1 этаже будет 1 маньяк, который плохо слышит. На 2 этаже тоже 1 маньяк, который уже плохо видит. На 3 этаже хорошо слышит и хорошо видит.</p>
    <button onclick="toggleDescription()">Читать далее</button>
    <div id="more-info">
        <p>Чтобы сбежать с 1 этажа, надо найти ключи (3 ключа) и код от замка. Со 2 этажа надо будет найти молоток, ключи (5 ключей) и найти код от замка. С 3 — надо найти ключи (10 ключей), код от замка (2): 1 код, как обычно, 2 код — он будет расположен в начальной комнате на ноутбуке (код разный), молот, отвёртку и ножницы.</p>
        <p>Если вас поймал маньяк, вы будете в какой-то комнате на этаже, где он поймал. На первом этаже 2 комнаты, на 2 этаже 3 комнаты, на 3 этаже 4 комнаты, и в 3 из них расположен ключ, чтоб сбежать с комнаты, а в 2 из них надо ждать маньяка, когда он принесет покушать. Будет написано, когда он идет, и надо спасаться за дверь, а когда он подойдет к дивану — убегать.</p>
        <p>У вас будет 5 попыток. Не забудьте фонарик в главной комнате. Если что-то там забыли, можно вернуться.</p>
    </div>
</div>

<!-- Кнопка "Скачать" -->
<a href="#download-section"><button>Скачать</button></a>

<!-- Изображения игры -->
<div class="images">
    <img src="game-image1.png" alt="Image 1">
    <img src="game-image2.png" alt="Image 2">
    <img src="game-image3.png" alt="Image 3">
</div>

<!-- Загрузка игры -->
<div id="download-section">
    <button>BETA 📱</button>
    <button>ANDROID 📱</button>
    <button>PC 🖥️</button>
</div>

<!-- Нижний колонтитул -->
<div class="footer">
    <span>ooo &lt;&lt;jogil&gt;&gt;</span>
</div>

<script>
    // Скрипт переключения полной версии текста
    function toggleDescription() {
        const moreInfoDiv = document.querySelector('#more-info');
        if (moreInfoDiv.style.display === 'none' || moreInfoDiv.style.display === '') {
            moreInfoDiv.style.display = 'block';
        } else {
            moreInfoDiv.style.display = 'none';
        }
    }
</script>

</body>
</html>
 
