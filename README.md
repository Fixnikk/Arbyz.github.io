# Arbyz.github.io

<!DOCTYPE HTML>
<html lang="ru" content="width=device-width, initial-scale=1.0" >>
  <head>
  <!-- Подключаемые файлы, метатеги, название страницы -->

  <!-- Кодировка страницы-->
  <meta charset="utf-8"/>
  <title>Арбуз</title>
    <style>
    ### CSS (styles.css)
```css
body {
    margin: 0;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
    color: #fff;
    font-family: 'Courier New', Courier, monospace;
    overflow: hidden;
}

.container {
    text-align: center;
    position: relative;
    z-index: 1;
}

.title {
    font-size: 3rem;
    text-shadow: 0 0 20px #00ff99, 0 0 30px #00ff99, 0 0 40px #00ff99;
    animation: flicker 1.5s infinite alternate;
}

.neon-button {
    background-color: transparent;
    border: 2px solid #00ff99;
    color: #00ff99;
    padding: 10px 20px;
    font-size: 1.5rem;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s, transform 0.3s;
}

.neon-button:hover {
    background-color: rgba(0, 255, 153, 0.2);
    transform: scale(1.05);
}

.background {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-image: url('https://example.com/your-cyberpunk-image.jpg');
    background-size: cover;
    filter: blur(8px);
    z-index: 0;
    opacity: 0.5;
    animation: pulsate 5s infinite;
}

@keyframes flicker {
    0% { opacity: 1; }
    50% { opacity: 0.6; }
    100% { opacity: 1; }
}

@keyframes pulsate {
    0% { opacity: 0.5; }
    50% { opacity: 0.7; }
    100% { opacity: 0.5; }
}


### JavaScript (script.js)
javascript
document.getElementById('neonButton').addEventListener('click', function() {
    alert('Вы нажали на кнопку в стиле киберпанк!');
});

    body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }
        .question {
            background: #fff;
            border: 1px solid #ccc;
            border-radius: 5px;
            padding: 15px;
            margin-bottom: 20px;
        }
        .question h2 {
            font-size: 18px;
        }
        .button {
            display: inline-block;
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            margin: 5px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .button:hover {
            background-color: #45a049;
        }
    </style>    

<h1>Добро пожаловать на тест по криптовалютам!</h1>

< p>Вопрос 1: Что такое Биткойн?< /p>
<button onclick="incorrect()">Цифровая монета</button>
<button onclick="correct()">Криптовалюта</button>
<button onclick="incorrect()">Торговая платформа</button>

<p>Вопрос 2: кто создал биткоин?</p>
<button onclick="incorrect()">Илон маск</button>
<button onclick="correct()">Сатоши Накамото</button>
<button onclick="incorrect()">Виталик Бутерин </button>

<p>Вопрос 3: Что такое блокчейн?</p>-->
<button onclick="correct()">Технология хранения данных</button>
<button onclick="incorrect()">Валюта</button>
<button onclick=incorrect()">Программное обеспечение</button>

<p>Вопрос 4: Какая технология обеспечивает анонимность транзакций в криптовалютах?</p>
<button onclick="incorrect()">Blockchain</button>
<button onclick="correct()">Криптография</button>
<button onclick="incorrect()">Майнинг</button>

   <p>Вопрос 5: Что такое альткойн?</p>
<button onclick="correct()">Криптовалюта, которая была созданна в качестве обхода ограничений биткоина</button>
<button onclick="incorrect()">Монета биткойн</button>
<button onclick="incorrect()">Фиатная валюта</button>

<p>Вопрос 6: Что такое ефир? </p>
<button onclick="correct()">Криптовалюта сети Ethereum</button>
<button onclick="incorrect()">Программное обеспечение для обмена</button>
<button onclick="incorrect()">Фиатная валюта</button>


<p>Вопрос 7: Каким образом добываеться некоторая криптотвалюта?</p>
<button onclick="incorrect()">Blockchain</button>
<button onclick="correct()">Криптография</button>
<button onclick="incorrect()">Майнинг</button>

<script>
function correct() {
  alert('Верно! Поздравляем!');
}

function incorrect() {
  alert('Неверно. Попробуйте еще раз.');
}
</script>
</head>
<body>
  <!-- Тело сайта, отвечает за вывод на страницу-->
  <header>
  <!-- Шапка сайта-->
  </header>
  <nav>
  <!-- Навигация -->
  </nav>
  <footer>
  <!-- Подвал сайта-->
  </footer>
</body>
</html>







<!DOCTYPE HTML>
<html lang="ru" content="width=device-width, initial-scale=1.0" >>
  <head>
  <!-- Подключаемые файлы, метатеги, название страницы -->

  <!-- Кодировка страницы-->
  <meta charset="utf-8"/>
  <title>Арбуз</title>
    <style>
    ### CSS (styles.css)
```css
body {
    margin: 0;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
    color: #fff;
    font-family: 'Courier New', Courier, monospace;
    overflow: hidden;
}

.container {
    text-align: center;
    position: relative;
    z-index: 1;
}

.title {
    font-size: 3rem;
    text-shadow: 0 0 20px #00ff99, 0 0 30px #00ff99, 0 0 40px #00ff99;
    animation: flicker 1.5s infinite alternate;
}

.neon-button {
    background-color: transparent;
    border: 2px solid #00ff99;
    color: #00ff99;
    padding: 10px 20px;
    font-size: 1.5rem;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s, transform 0.3s;
}

.neon-button:hover {
    background-color: rgba(0, 255, 153, 0.2);
    transform: scale(1.05);
}

.background {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-image: url('https://example.com/your-cyberpunk-image.jpg');
    background-size: cover;
    filter: blur(8px);
    z-index: 0;
    opacity: 0.5;
    animation: pulsate 5s infinite;
}

@keyframes flicker {
    0% { opacity: 1; }
    50% { opacity: 0.6; }
    100% { opacity: 1; }
}

@keyframes pulsate {
    0% { opacity: 0.5; }
    50% { opacity: 0.7; }
    100% { opacity: 0.5; }
}


### JavaScript (script.js)
javascript
document.getElementById('neonButton').addEventListener('click', function() {
    alert('Вы нажали на кнопку в стиле киберпанк!');
});

    body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }
        .question {
            background: #fff;
            border: 1px solid #ccc;
            border-radius: 5px;
            padding: 15px;
            margin-bottom: 20px;
        }
        .question h2 {
            font-size: 18px;
        }
        .button {
            display: inline-block;
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            margin: 5px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .button:hover {
            background-color: #45a049;
        }
    </style>    

<h1>Добро пожаловать на тест по криптовалютам!</h1>

< p>Вопрос 1: Что такое Биткойн?< /p>
<button onclick="incorrect()">Цифровая монета</button>
<button onclick="correct()">Криптовалюта</button>
<button onclick="incorrect()">Торговая платформа</button>

<p>Вопрос 2: кто создал биткоин?</p>
<button onclick="incorrect()">Илон маск</button>
<button onclick="correct()">Сатоши Накамото</button>
<button onclick="incorrect()">Виталик Бутерин </button>

<p>Вопрос 3: Что такое блокчейн?</p>-->
<button onclick="correct()">Технология хранения данных</button>
<button onclick="incorrect()">Валюта</button>
<button onclick=incorrect()">Программное обеспечение</button>

<p>Вопрос 4: Какая технология обеспечивает анонимность транзакций в криптовалютах?</p>
<button onclick="incorrect()">Blockchain</button>
<button onclick="correct()">Криптография</button>
<button onclick="incorrect()">Майнинг</button>

   <p>Вопрос 5: Что такое альткойн?</p>
<button onclick="correct()">Криптовалюта, которая была созданна в качестве обхода ограничений биткоина</button>
<button onclick="incorrect()">Монета биткойн</button>
<button onclick="incorrect()">Фиатная валюта</button>

<p>Вопрос 6: Что такое ефир? </p>
<button onclick="correct()">Криптовалюта сети Ethereum</button>
<button onclick="incorrect()">Программное обеспечение для обмена</button>
<button onclick="incorrect()">Фиатная валюта</button>


<p>Вопрос 7: Каким образом добываеться некоторая криптотвалюта?</p>
<button onclick="incorrect()">Blockchain</button>
<button onclick="correct()">Криптография</button>
<button onclick="incorrect()">Майнинг</button>

<script>
function correct() {
  alert('Верно! Поздравляем!');
}

function incorrect() {
  alert('Неверно. Попробуйте еще раз.');
}
</script>
</head>
<body>
  <!-- Тело сайта, отвечает за вывод на страницу-->
  <header>
  <!-- Шапка сайта-->
  </header>
  <nav>
  <!-- Навигация -->
  </nav>
  <footer>
  <!-- Подвал сайта-->
  </footer>
</body>
</html>










