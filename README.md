<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Массажист Тимур Зарбеев</title>

  <!-- Иконки Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #f0f2f5;
      color: #333;
    }

    header {
      background: linear-gradient(135deg, #00a686, #007a73);
      color: white;
      padding: 40px 20px;
      text-align: center;
      position: relative;
      overflow: hidden;
    }

    header::after {
      content: '';
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: url('https://www.transparenttextures.com/patterns/cubes.png');
      opacity: 0.05;
      z-index: 0;
    }

    header h1 {
      position: relative;
      z-index: 1;
      font-size: 2.5rem;
      margin: 0;
    }

    nav {
      margin-top: 20px;
      position: relative;
      z-index: 1;
    }

    nav a {
      margin: 0 15px;
      color: white;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #ffe267;
    }

    section {
      background: white;
      margin: 40px auto;
      max-width: 900px;
      border-radius: 12px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.08);
      padding: 40px;
      animation: fadeIn 0.8s ease;
    }

    h2 {
      color: #00a686;
      margin-top: 0;
    }

    button {
      background-color: #00a686;
      color: white;
      border: none;
      padding: 12px 25px;
      font-size: 1rem;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s;
    }

    button:hover {
      background-color: #007a73;
    }

    iframe {
      width: 100%;
      height: 315px;
      border-radius: 8px;
      margin-bottom: 25px;
      border: none;
    }

    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 1rem;
    }

    footer {
      text-align: center;
      padding: 30px 20px;
      background: #eaeaea;
      font-size: 0.9rem;
    }

    .social-icons a {
      margin: 0 10px;
      color: #555;
      transition: color 0.3s;
    }

    .social-icons a:hover {
      color: #00a686;
    }

    @keyframes fadeIn {
      from {opacity: 0; transform: translateY(20px);}
      to {opacity: 1; transform: translateY(0);}
    }
  </style>
</head>
<body>

<header>
  <h1>Массажист Тимур Зарбеев</h1>
  <nav>
    <a href="#about">Обо мне</a>
    <a href="#services">Услуги</a>
    <a href="#videos">Видео</a>
    <a href="#exercises">Упражнения</a>
    <a href="#map">Адрес</a>
    <a href="#contact">Контакты</a>
  </nav>
</header>

<section id="about">
  <h2>Обо мне</h2>
  <p>Я сертифицированный массажист с более 10 лет опыта и автор YouTube-канала и TikTok-блога о здоровье. Провожу приём в Москве и онлайн.</p>
</section>

<section id="services">
  <h2>Услуги</h2>
  <ul>
    <li>Классический массаж тела</li>
    <li>Коррекция осанки</li>
    <li>Физкультура при грыже</li>
    <li>Личное сопровождение по восстановлению</li>
  </ul>
</section>

<section id="videos">
  <h2>Видео</h2>
  <iframe src="https://www.youtube.com/embed/PfaKW1oPaDs" allowfullscreen></iframe>
  <iframe src="https://www.youtube.com/embed/LZjP6L8a4-M" allowfullscreen></iframe>
  <iframe src="https://www.youtube.com/embed/kXcG9cEVi2I" allowfullscreen></iframe>
  <p><a href="https://www.tiktok.com/@timurzarbeev" target="_blank">Смотреть TikTok Тимура Зарбеева</a></p>
</section>

<section id="exercises">
  <h2>Домашние упражнения</h2>
  <ul>
    <li>Наклоны головы — 3 подхода по 10 повторений</li>
    <li>Ротация шеи сидя — 15 секунд в каждую сторону</li>
    <li>Потягивание рук вверх с дыханием — 5 глубоких повторений</li>
  </ul>
</section>

<section id="map">
  <h2>Где я принимаю</h2>
  <p>Москва, центр. Предварительная запись обязательна.</p>
  <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2244.0045301064326!2d37.6173!3d55.7558!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x46b54a5aaf2b1c4f%3A0x9f3e3b3e3e3e3e3e!5e0!3m2!1sru!2sru!4v1680000000000" loading="lazy"></iframe>
</section>

<section id="contact">
  <h2>Связаться со мной</h2>
  <form>
    <input type="text" placeholder="Ваше имя" required />
    <input type="email" placeholder="Ваш email" required />
    <textarea rows="5" placeholder="Ваше сообщение" required></textarea>
    <button type="submit">Отправить</button>
  </form>
</section>

<footer>
  <div class="social-icons">
    <a href="https://www.youtube.com/@timurzarbeev" target="_blank" title="YouTube"><i class="fab fa-youtube fa-2x" style="color:#c4302b;"></i></a>
    <a href="https://www.tiktok.com/@timurzarbeev" target="_blank" title="TikTok"><i class="fab fa-tiktok fa-2x"></i></a>
    <a href="https://www.instagram.com/timur.zarbeev" target="_blank" title="Instagram"><i class="fab fa-instagram fa-2x" style="color:#E1306C;"></i></a>
    <a href="https://wa.me/79000000000" target="_blank" title="WhatsApp"><i class="fab fa-whatsapp fa-2x" style="color:#25D366;"></i></a>
  </div>
  <p>© 2025 Тимур Зарбеев. Все права защищены.</p>
</footer>

</body>
</html>
