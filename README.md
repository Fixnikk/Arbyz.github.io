
<!DOCTYPE html> 
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Болдино - Уголок Пушкина</title>
    <link rel=stylesheet href="123.css">
</head>
<body>
    <header>
        <h1 class=texth>Болдино - Уголок Пушкина</h1>
        <nav>
            <ul type=disk class=a>
                <li><a class=o href="#about">О Болдино</a></li>
                <li><a class=o href="#pushkin">Пушкин в Болдине</a></li>
                <li><a class=o href="#gallery">Галерея</a></li>
               <li><a class=o href="#genitba">Женитьба</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>О Болдино</h2>
        <p>Болдино — это живописное село в России, расположенное на берегу реки Оки в Нижегородской области. Это место славится своей красивой природой, историческими памятниками и, что особенно важно, связью с жизнью и творчеством великого русского поэта Александра Пушкина. Болдино стало для Пушкина не только домом, но и источником вдохновения, где он создал множество своих шедевров.</p>
        <p>В Болдине сохранились памятники, связанные с жизнью поэта, а также его усадьба, которая привлекает туристов и почитателей его творчества. Природа этого края — леса, поля и реки — стала фоном для многих его произведений.</p>
    </section>

      <section id="pushkin">
        <h2>Пушкин в Болдине</h2>
         <p>Александр Пушкин впервые посетил Болдино в 1831 году, когда находился в ссылке после дуэли. Этот период стал одним из самых продуктивных в его творческой жизни. Поэт провел здесь осень и зиму, и именно в Болдине он создал множество произведений, которые впоследствии стали классикой русской литературы.</p>
        
        <p>В Болдине Пушкин работал над своим знаменитым романом "Евгений Онегин". Здесь он завершил работу над вторым томом и написал несколько новых глав, которые стали важными для развития сюжета. Кроме того, поэт создал множество стихотворений, в том числе:</p>
        <ul >
            <li class=q><strong>"Осень"</strong>: Стихотворение, которое отражает печаль и глубину чувств Пушкина, связанные с уходом лета и приближением зимы.</li>
            <li class=q><strong>"На холмах Грузии лежит ночная мгла"</strong>: Это стихотворение стало символом любви и тоски по родине, передавая атмосферу глубокой эмоциональной связи с природой.</li>
            <li class=q><strong>"Бесы"</strong>: "Мчатся тучи, вьются тучи..."</li>
        </ul>

        <p>Помимо поэзии, Пушкин также работал над прозой и написал несколько сказок, включая "Сказку о рыбаке и рыбке". В этом произведении, как и во многих других, проявилась его способность сочетать народные мотивы с глубокими философскими темами.</p>

        <p>Село Болдино и его природа стали не только местом вдохновения для Пушкина, но и символом русской культуры и литературы. После его смерти Болдино стало памятным местом, где почитают память великого поэта, и ежегодно сюда приезжают туристы и любители его творчества.</p>
    </section>
  <section id="genitba">
        <h2>Женитьба</h2>
     <p>
Женитьба Александра Пушкина на Наталье Гончаровой состоялась 18 февраля 1831 года и стала важным событием в его жизни. Пушкин влюбился в Наталью в 1828 году, и их отношения были полны страсти и волнений. Свадьба прошла в церкви Святой Троицы в Москве, окруженная родными и близкими. Это событие символизировало не только личное счастье поэта, но и новый этап в его творческой деятельности. После свадьбы Пушкин продолжил писать, и Болдино стало местом его вдохновения, где он создал множество произведений, включая главы "Евгения Онегина".
</p>





    <section id="gallery">
        <h2>Галерея</h2>
        <img src="" alt=""" ">
        <img src="https://avatars.mds.yandex.net/i?id=842aadf1a83089c14f0d0efb9495f7f516f75215-5583685-images-thumbs&n=13" alt=""" ">
		<img src="https://avatars.mds.yandex.net/i?id=3b2cf12f942ad434b3d4d7809c715eea63a99c35-8145720-images-thumbs&n=13" alt=""" ">
		<img src="https://avatars.mds.yandex.net/i?id=25c8ff7568c236f3b336ef8f12c52b3d44458baa-10551030-images-thumbs&n=13" alt=""" ">
		<img src="https://avatars.mds.yandex.net/i?id=02185cc2d80cccbf5ae09d0bd94f468fccabe0d4-4219741-images-thumbs&n=13" alt=""" ">
		<img src="" alt=""" ">
		<img src="" alt=""" ">
		<img src="" alt=""" ">
		<img src="" alt=""" ">
		<img src="" alt=""" ">
		<img src="" alt=""" ">
		<img src="" alt=""" ">
		
		
    </section>

    <button id="backToTop">Наверх</button>

    <script>
        // Получаем кнопку
        const backToTopButton = document.getElementById('backToTop');

        // Показываем кнопку при скролле вниз
        window.addEventListener('scroll', () => {
            if (window.scrollY > 300) {
                backToTopButton.style.display = 'block';
            } else {
                backToTopButton.style.display = 'none';
            }
        });

        // Прокручиваем страницу к началу при нажатии на кнопку
        backToTopButton.addEventListener('click', () => {
            window.scrollTo({
                top: 0,
                behavior: 'smooth' // Плавный скролл
            });
        });
    </script>
    <footer>
        <p class=foot>&copy; 2024 Болдино. Все права защищены.</p>
    </footer>
    <style>

    body{
	
	background-image:url('100.jfif');  
	background-repeat: no-repeat;
    background-attachment: fixed;
	background-size: cover;
}



img.q {
	
	width:50px;
	height:50px;
	border-radius:50px 0px  15px 10px;
	border:solid 2px green;   ;
}

img.r {
	
	width:500px;
	height:500px;
	border-radius:25%;
border:solid 2px black;
opacity:0.0001;
margin:0 0 0 50%;	
text-transform:translateX(-250px);

}


img.r:hover{
	opacity:1;
	background-image:url('флаг.png'); 	
	
}	





 .texth{
	 color:white;
	 text-align:center;
	 
 }
 
 h2{
	 font-size:35pt;
	 color:#d1e0b1;
	 
	 
 }
 

h1  {
	
	
	font-size:40pt;
	
}

.o{
		font-size:15pt;
	
	
	
	
}
ul.a{
	color:#d1e0b1	
	
	
}
li.q {
	color:white;
	font-size:20pt;
	
	
	
	
}




p  {
	
	text-align:center;
	color:white;
	font-size:30pt;
	font-style:italic;
	font-weight:normal;
}
.foot{
	font-size:10pt;
	
	
	
}

}
.divs{
	width:300px;
	height:300px;
    border-radius:100%;
	background-size:250px 250px;
	position:absolute;
}

 
.div1{
	background-color:;
	background:url('hhh.jpg');
	left:400px;
	top:400px;
}
.div2{
	background-color:red;
	left:700px;
	top:100000px;
}
.div1:hover{
	background:url('флаг.png');
		
}






.divimg{
	width:100%;
	
}









       #backToTop {
            position: fixed;
            bottom: 20px;
            right: 20px;
            display: none; /* Скрыть кнопку по умолчанию */
            background-color: #dbca2e;
            color: white;
            border: none;
            border-radius: 20px;
            padding: 10px 15px;
            cursor: pointer;
            font-size: 16px;
        }

        #backToTop:hover {
            background-color: #0056b3;
        }
</style>
</body>
</html>





