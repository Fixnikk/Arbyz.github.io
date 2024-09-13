
<!DOCTYPE html>
<html lang="ru" content="width=device-width, initial-scale=1.0" >
  <head>
<link rel="stylesheet" href="https://github.com/Fixnikk/Arbyz.github.io/blob/main/style.css">
 <script src="https://github.com/Fixnikk/Arbyz.github.io/blob/main/css-js/script.js"> </script>

  <div class="container">
        <h1 class="title">Добро пожаловать в Киберпанк</h1>
        <button class="neon-button" id="neonButton">Нажми на меня</button>
        <div class="background"></div>
    </div>
   

<meta charset="utf-8"/>
<title>Арбуз</title>
<h4>Укажите свои данные для дальнейшей связи</h4>
<input type="email" placeholder="Введите свою электронную почту" size=50px>
</form>
<fieldset>
<h1>Добро пожаловать на тест по криптовалютам!</h1>

<p>Вопрос 1: Что такое Биткойн?</p>
<button onclick="incorrect()">Цифровая монета</button>
<button onclick="correct()">Криптовалюта</button>
<button onclick="incorrect()">Торговая платформа</button>

<p>Вопрос 2: кто создал биткоин?</p>
<button onclick="incorrect()">Илон маск</button>
<button onclick="correct()">Сатоши Накамото</button>
<button onclick="incorrect()">Виталик Бутерин </button>

<p>Вопрос 3: Что такое блокчейн?</p>
<button onclick="correct()">Технология хранения данных</button>
<button onclick="incorrect()">Валюта</button>
<button onclick="incorrect()">Программное обеспечение</button>

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
<button onclick="correct()">Майнинг</button>
<button onclick="incorrect()">криптография</button>
</fieldset>
<a href="https://t.me/arbyzfrog">Telegram</a>
<br>
<a href="https://youtube.com/@fixnik?si=yZ6FFkVijMRZ7x8W">YouTube</a>
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
<?php
$num = 0;
if (isset($_POST['but'])){
  if (isset($_COOKIE['count'])){
    $num = $_COOKIE['count'] + 1;
  }
  setcookie('count', $num);
}
echo 'Вы нажали на кнопку '.$num. ' раз';

?>
<form action="registration.php" method="post">
    <input type="submit" name="but" value="<?php echo $num;?>">
