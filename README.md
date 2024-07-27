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
    background-image: url('[https://example.com/your-cyberpunk-image.jpg](https://steamuserimages-a.akamaihd.net/ugc/2128572644671681546/BD73DBA26E7370AF49D30721256C850170BC3C9A/?imw=512&amp;imh=288&amp;ima=fit&amp;impolicy=Letterbox&amp;imcolor=%23000000&amp;letterbox=true)');
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













