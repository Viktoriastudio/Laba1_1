<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Город Ошмяны</title>
    <style>
        :root {
          --bg: #f0f8ff;
          --card: #fff;
          --accent: #4da6ff;
          --text: #222;
          --active: #0066cc;
        }
        body {
          font-family: system-ui,-apple-system,Segoe UI,Roboto,'Helvetica Neue',Arial;
          line-height: 1.5;
          background: linear-gradient(120deg,#fff 0%,var(--bg) 100%);
          color: var(--text);
          margin: 0;
          padding: 20px;
        }

        /* Верхняя панель */
        .top-nav {
          display: flex;
          justify-content: center;
          gap: 10px;
          margin-bottom: 20px;
        }
        .nav-btn {
          padding: 10px 20px;
          border-radius: 25px;
          border: none;
          font-weight: bold;
          cursor: pointer;
          background: var(--accent);
          color: #222;
          transition: all 0.3s ease;
          box-shadow: 0 4px 12px rgba(0,0,0,.1);
        }
        .nav-btn:hover {
          background: var(--active);
          color: #fff;
          transform: translateY(-2px);
        }
        .nav-btn.active {
          background: var(--active);
          color: #fff;
          box-shadow: 0 6px 16px rgba(0,0,0,.2);
        }

        h1 {
          text-align: center;
          color: var(--active);
        }
        h2 {
          margin-top: 20px;
          color: #333;
        }
        .card {
          background: var(--card);
          border-radius: 14px;
          padding: 18px;
          box-shadow: 0 8px 30px rgba(0,0,0,.06);
          margin-bottom: 20px;
        }
        img {
          margin: 10px;
          border-radius: 8px;
          box-shadow: 0 4px 12px rgba(0,0,0,.1);
        }
        footer {
          margin-top: 18px;
          color: #666;
          font-size: 13px;
          text-align: center;
        }
    </style>
</head>
<body>

    <!-- Панель навигации -->
    <div class="top-nav">
        <button class="nav-btn" onclick="location.href='cats.html'">Котики</button>
        <button class="nav-btn active" onclick="location.href='city.html'">Мой город</button>
    </div>

    <div class="card">
      <h1>Ошмяны всегда в моем сердце</h1>
      <hr>

      <!-- 1. История города -->
      <h2>История города</h2>
      <p>
          Ошмяны — один из древнейших городов Гродненской области. Первое упоминание относится к 14 веку. 
          Город был важным торговым и культурным центром, неоднократно разрушался во время войн, но каждый раз возрождался.
      </p>
      <hr>

      <!-- 2. Достопримечательности -->
      <h2>Достопримечательности</h2>
      <ul>
          <li>Костёл Святого Михаила Архангела</li>
          <li>Руины замка в Старых Ошмянах</li>
          <li>Воскресенская церковь</li>
          <li>Ошмянский краеведческий музей</li>
          <li>Собственное производство кофе</li>
      </ul>
      <hr>

      <!-- 3. Символы города -->
      <h2>Символы города</h2>
      <p><strong>Герб:</strong> Французский щит с вилообразным делением: рука с весами, золотой щит и красный теленок.</p>
      <img src="img1_6.jpg" alt="Герб Ошмян" width="200">
      <p><strong>Флаг:</strong> Полотнище 1:2, разделённое пополам (голубая и красная части), с гербом в центре.</p>
      <img src="img1_7.jpg" alt="Флаг Ошмян" width="200">
      <hr>

      <!-- 4. Расположение на карте -->
      <h2>Расположение на карте</h2>
      <p>Город Ошмяны находится в северо-восточной части Гродненской области.</p>
      <img src="img1_8.jpg" alt="Карта Ошмян" width="500">
      <hr>

      <!-- 5. Новости -->
      <h2>Новости</h2>
      <ul>
          <li><a href="https://oshmiany.gov.by" target="_blank">Официальный сайт Ошмянского района</a></li>
          <li><a href="https://grodnonews.by" target="_blank">Новости региона</a></li>
      </ul>
      <hr>

      <!-- 6. Город сейчас -->
      <h2>Город сейчас</h2>
      <p>
          Сегодня Ошмяны — это современный город с развивающейся промышленностью и сельским хозяйством. 
          Здесь работают предприятия пищевой, строительной и деревообрабатывающей промышленности, 
          развита сеть образовательных и культурных учреждений.
      </p>
      <center>
       <img src="img1_1.jpg" alt="Вечерний город" height="300" weight="300">
      <img src="img1_2.jpg" alt="Вечерний город" height="300" weight="300">
      <img src="img1_4.jpg" alt="Природа" height="300" weight="300">
      <img src="img1_5.jpg" alt="Природа" height="300" weight="300"> 
      </center>
      <hr>

      <!-- 7. Дополнительная информация -->
      <h2>Интересные факты</h2>
      <ol>
          <li>В 20 км от города стоит Гольшанский замок — теперь величественные руины, о которых ходят легенды.</li>
          <li>На Вербное воскресенье в городе проходит крестный ход на Святую гору — «Ошмянскую Голгофу».</li>
      </ol>
      <p><strong>Я люблю свой город, ведь здесь история переплетается с современностью!</strong></p>
    </div>

    <footer>
        <p>&copy; 2025 Мой сайт про Ошмяны</p>
    </footer>
</body>
</html>
