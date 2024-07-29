# Arbyz.github.io
<!DOCTYPE HTML>
<html lang="ru" content="width=device-width, initial-scale=1.0" >>
  <head>
  <!-- Подключаемые файлы, метатеги, название страницы -->

  <!-- Кодировка страницы-->
  <meta charset="utf-8"/>
  <title>Арбуз</title>
    <style>
<!DOCTYPE html>
<html>
<head>
    <title>Криптовалютные опросы</title>
</head>
<body>

<h1>Пройдите наш опрос про криптовалюты:</h1>

<p>Какую криптовалюту вы предпочитаете?</p>
<button onclick="vote('bitcoin')">Bitcoin</button>
<button onclick="vote('ethereum')">Ethereum</button>
<button onclick="vote('ripple')">Ripple</button>

<p>Сколько раз в неделю вы следите за курсами криптовалют?</p>
<button onclick="vote('daily')">Ежедневно</button>
<button onclick="vote('weekly')">Раз в неделю</button>
<button onclick="vote('monthly')">Раз в месяц</button>

<p>Как долго вы уже занимаетесь инвестированием в криптовалюты?</p>
<button onclick="vote('less1year')">Менее года</button>
<button onclick="vote('1-3years')">1-3 года</button>
<button onclick="vote('more3years')">Более 3 лет</button>

<p>Спасибо за участие в опросе!</p>

<script>
    function vote(choice) {
        console.log('Вы проголосовали за: ' + choice);
        // Добавьте здесь код для отправки результатов голосования на сервер или сохранения их локально
    }
</script>

</body>
</html>
