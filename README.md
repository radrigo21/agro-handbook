<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Справочник по выращиванию</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background-color: #f5f5f5;
        }

        /* Шапка */
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }

        /* Навигация */
        nav {
            background-color: #333;
            padding: 15px;
            position: sticky;
            top: 0;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 30px;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 10px;
            transition: 0.3s;
        }

        nav a:hover {
            background-color: #4CAF50;
        }

        /* Основной контент */
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
        }

        .section {
            background: white;
            border-radius: 10px;
            padding: 30px;
            margin-bottom: 30px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        h2 {
            color: #4CAF50;
            margin-bottom: 20px;
        }

        /* Адаптивность */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                text-align: center;
                gap: 10px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Справочник агронома</h1>
        <p>Все о выращивании зелени, чеснока и грибов</p>
    </header>

    <nav>
        <ul>
            <li><a href="#greens">Зелень</a></li>
            <li><a href="#garlic">Чеснок</a></li>
            <li><a href="#mushrooms">Грибы</a></li>
            <li><a href="#tools">Инструменты</a></li>
        </ul>
    </nav>

    <div class="container">
        <section id="greens" class="section">
            <h2>Выращивание зелени</h2>
            <p>Секреты культивации петрушки, укропа и микрозелени...</p>
            <!-- Добавьте контент -->
        </section>

        <section id="garlic" class="section">
            <h2>Технологии выращивания чеснока</h2>
            <p>От посадки до сбора урожая...</p>
        </section>

        <section id="mushrooms" class="section">
            <h2>Грибоводство</h2>
            <p>Лесные и культивируемые виды...</p>
        </section>

        <section id="tools" class="section">
            <h2>Оборудование и инструменты</h2>
            <p>Обзор теплиц и систем полива...</p>
        </section>
    </div>
</body>
</html>
