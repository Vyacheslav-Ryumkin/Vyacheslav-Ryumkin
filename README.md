<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Цветы</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            margin: 0;
            padding: 20px;
        }

        h1 {
            color: #228b22;
        }

        .flower {
            background-color: #fff;
            padding: 10px;
            border: 2px solid #ddd;
            margin: 10px 0;
            border-radius: 5px;
        }

        button {
            padding: 10px;
            background-color: #228b22;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #2e8b57;
        }
    </style>
</head>
<body>

    <h1>Цветы</h1>
    <p>Нажмите на кнопку, чтобы узнать больше о цветах:</p>

    <div class="flower">
        <h2>Роза</h2>
        <p id="rose-info">Роза — это красивый цветок, который символизирует любовь и страсть.</p>
        <button onclick="showRoseInfo()">Узнать больше о розе</button>
    </div>

    <div class="flower">
        <h2>Тюльпан</h2>
        <p id="tulip-info">Тюльпаны — символ весны и возрождения.</p>
        <button onclick="showTulipInfo()">Узнать больше о тюльпане</button>
    </div>

    <div class="flower">
        <h2>Лилия</h2>
        <p id="lily-info">Лилии — это символ чистоты и невинности.</p>
        <button onclick="showLilyInfo()">Узнать больше о лилии</button>
    </div>

    <script>
        function showRoseInfo() {
            document.getElementById("rose-info").innerHTML = "Розы бывают разных цветов, включая красные, белые, желтые и розовые. Их аромат неповторим, и они часто используются в букете.";
        }

        function showTulipInfo() {
            document.getElementById("tulip-info").innerHTML = "Тюльпаны родом из Центральной Азии, и их можно найти в различных цветах, таких как красный, желтый, фиолетовый и белый.";
        }

        function showLilyInfo() {
            document.getElementById("lily-info").innerHTML = "Лилии часто встречаются на свадьбах и похоронах. Они также могут символизировать чистоту, надежду и обновление.";
        }
    </script>

</body>
</html>
