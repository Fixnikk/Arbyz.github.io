# Arbyz.github.io
<!DOCTYPE HTML>
<html lang="ru">
  <head>
  <!-- Подключаемые файлы, метатеги, название страницы -->

  <!-- Кодировка страницы-->
  <meta charset="utf-8"/>
  <title>Арбуз</title>
      <style>
        body {
            font-family: sans-serif;
        }

        #quiz-container {
            width: 500px;
            margin: 0 auto;
            padding: 20px;
            border: 1px solid #ccc;
        }

        #question {
            font-size: 1.2em;
            margin-bottom: 15px;
        }

        .answer-button {
            display: block;
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }

        .answer-button:hover {
            background-color: #45a049;
        }

        #result {
            display: none;
            font-size: 1.4em;
            margin-top: 20px;
        }
    </style>



    <div id=" quiz-container">
        <h2 id=" question"></h2>

        <button class="answer-button" id= " answer1"></button>
        <button class="answer-button" id= " answer2"></button>
        <button class="answer-button" id= " answer3"></button>
        <button class="answer-button" id= " answer4"></button>

        <div id="result"></div>
    </div>

    <script>
        const questions = [
            {
                question: "Что такое Биткоин?",
                answers: [
                    "Децентрализованная криптовалюта",
                    "Централизованная криптовалюта",
                    "Электронная валюта, выпущенная банком",
                    "Фиатная валюта"
                ],
                correctAnswer: 0
            },
            {
                question: "Что такое майнинг?",
                answers: [
                    "Процесс создания новых блоков в блокчейне",
                    "Процесс покупки криптовалюты",
                    "Процесс продажи криптовалюты",
                    "Процесс хранения криптовалюты"
                ],
                correctAnswer: 0
            },
            // Добавьте больше вопросов
        ];

        let currentQuestion = 0;
        let score = 0;

        function loadQuestion() {
            const questionData = questions[currentQuestion];
            document.getElementById("question").textContent = questionData.question;

            for (let i = 0; i < 4; i++) {
                document.getElementById(`answer${i + 1}`).textContent = questionData.answers[i];
                document.getElementById(`answer${i + 1}`).onclick = () => checkAnswer(i);
            }
        }

        function checkAnswer(selectedAnswer) {
            if (selectedAnswer === questions[currentQuestion].correctAnswer) {
                score++;
                alert("Правильно!");
            } else {
                alert("Неправильно!");
            }

            currentQuestion++;

            if (currentQuestion < questions.length) {
                loadQuestion();
            } else {
                showResult();
            }
        }

        function showResult() {
            document.getElementById("result").textContent = `Ваш результат: ${score} из ${questions.length}`;
            document.getElementById("result").style.display = "block";
        }

        loadQuestion();
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





