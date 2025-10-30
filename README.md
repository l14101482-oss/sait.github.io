# sait.github.io
[universum.html](https://github.com/user-attachments/files/23246003/universum.html)
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Universum - Энциклопедия знаний о науке, истории и технологиях</title>
    <meta name="description" content="Universum - энциклопедия знаний о науке, истории, технологиях и космосе. Подробные статьи с объяснениями сложных тем простым языком">
    <meta name="keywords" content="энциклопедия, наука, история, технологии, космос, образование, знания, обучение, квантовая физика, искусственный интеллект, древний рим">
    <meta name="description" content="Universum - бесплатная энциклопедия знаний о науке, истории, технологиях и космосе. Подробные статьи с объяснениями сложных тем простым языком">
    <meta name="keywords" content="энциклопедия, наука, история, технологии, космос, образование, знания, обучение, квантовая физика, искусственный интеллект, древний Рим, черные дыры">
    <meta name="author" content="Universum Encyclopedia">
    
    <meta property="og:title" content="Universum - Энциклопедия знаний">
    <meta property="og:description" content="Исследуйте мир через призму знаний">
    <meta property="og:type" content="website">
    
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "WebSite", 
      "name": "Universum",
      "description": "Энциклопедия знаний о науке, истории и технологиях",
      "url": "https://ваш-сайт.com"
    }
    </script>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: #fff;
            min-height: 100vh;
            position: relative;
            overflow-x: hidden;
        }

        .snowflake {
            position: absolute;
            top: -10px;
            color: white;
            font-size: 1em;
            user-select: none;
            pointer-events: none;
            opacity: 0.8;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            position: relative;
            z-index: 10;
        }

        header {
            text-align: center;
            padding: 30px 0;
            margin-bottom: 30px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            backdrop-filter: blur(10px);
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.2);
        }

        h1 {
            font-size: 3.5rem;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }

        .subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
            margin-bottom: 15px;
        }

        .logo {
            font-size: 2rem;
            margin-bottom: 10px;
        }

        .search-container {
            display: flex;
            margin: 30px 0;
        }

        #search-input {
            flex: 1;
            padding: 15px 20px;
            border: none;
            border-radius: 50px 0 0 50px;
            font-size: 1.1rem;
            background: rgba(255, 255, 255, 0.9);
            color: #333;
        }

        #search-btn {
            padding: 15px 30px;
            border: none;
            border-radius: 0 50px 50px 0;
            background: #4a00e0;
            color: white;
            font-size: 1.1rem;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        #search-btn:hover {
            background: #8e2de2;
        }

        .categories {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin-bottom: 30px;
            justify-content: center;
        }

        .category-btn {
            padding: 12px 25px;
            border: none;
            border-radius: 50px;
            background: rgba(255, 255, 255, 0.15);
            color: white;
            font-size: 1rem;
            cursor: pointer;
            transition: all 0.3s ease;
            backdrop-filter: blur(5px);
        }

        .category-btn:hover {
            background: rgba(255, 255, 255, 0.25);
            transform: translateY(-3px);
        }

        .category-btn.active {
            background: rgba(255, 255, 255, 0.3);
            font-weight: bold;
        }

        .content {
            display: grid;
            grid-template-columns: 1fr 3fr;
            gap: 30px;
        }

        .sidebar {
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            padding: 20px;
            backdrop-filter: blur(10px);
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.2);
            height: fit-content;
        }

        .sidebar h2 {
            margin-bottom: 15px;
            font-size: 1.5rem;
            border-bottom: 1px solid rgba(255, 255, 255, 0.3);
            padding-bottom: 10px;
        }

        .article-list {
            list-style-type: none;
            max-height: 500px;
            overflow-y: auto;
        }

        .article-item {
            padding: 12px 15px;
            margin-bottom: 10px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .article-item:hover {
            background: rgba(255, 255, 255, 0.2);
            transform: translateX(5px);
        }

        .article-item.active {
            background: rgba(255, 255, 255, 0.25);
            font-weight: bold;
        }

        .main-content {
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            padding: 30px;
            backdrop-filter: blur(10px);
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.2);
            min-height: 500px;
        }

        .article-title {
            font-size: 2.2rem;
            margin-bottom: 20px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.3);
            padding-bottom: 10px;
        }

        .article-content {
            line-height: 1.7;
            font-size: 1.1rem;
        }

        .article-content p {
            margin-bottom: 15px;
        }

        .article-content img {
            max-width: 100%;
            border-radius: 10px;
            margin: 15px 0;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }

        .article-content h3 {
            margin: 20px 0 15px 0;
            color: #e0c3fc;
        }

        .article-content ul, .article-content ol {
            margin-left: 20px;
            margin-bottom: 15px;
        }

        .article-content li {
            margin-bottom: 8px;
        }

        .article-content blockquote {
            border-left: 4px solid #e0c3fc;
            padding-left: 20px;
            margin: 20px 0;
            font-style: italic;
            opacity: 0.9;
        }

        .tools {
            display: flex;
            justify-content: space-between;
            margin-top: 30px;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.3);
        }

        .tool-btn {
            padding: 10px 20px;
            border: none;
            border-radius: 8px;
            background: rgba(255, 255, 255, 0.15);
            color: white;
            cursor: pointer;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .tool-btn:hover {
            background: rgba(255, 255, 255, 0.25);
        }

        .bookmark-btn {
            background: rgba(255, 193, 7, 0.2);
        }

        .bookmark-btn:hover {
            background: rgba(255, 193, 7, 0.3);
        }

        .bookmark-btn.active {
            background: rgba(255, 193, 7, 0.4);
        }

        footer {
            text-align: center;
            margin-top: 50px;
            padding: 20px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            backdrop-filter: blur(10px);
        }

        .stats {
            display: flex;
            justify-content: space-around;
            margin: 20px 0;
            padding: 15px;
            background: rgba(255, 255, 255, 0.05);
            border-radius: 10px;
        }

        .stat-item {
            text-align: center;
        }

        .stat-number {
            font-size: 2rem;
            font-weight: bold;
            color: #e0c3fc;
        }

        .stat-label {
            font-size: 0.9rem;
            opacity: 0.8;
        }

        .featured-articles {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }

        .featured-article {
            background: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-radius: 10px;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .featured-article:hover {
            background: rgba(255, 255, 255, 0.2);
            transform: translateY(-5px);
        }

        @media (max-width: 900px) {
            .content {
                grid-template-columns: 1fr;
            }
            
            h1 {
                font-size: 2.5rem;
            }
            
            .stats {
                flex-direction: column;
                gap: 15px;
            }
            
            .tools {
                flex-wrap: wrap;
                gap: 10px;
            }
            
            .tool-btn {
                flex: 1;
                min-width: 120px;
                justify-content: center;
            }
        }

        /* Стили для модального окна */
        .modal {
            display: none;
            position: fixed;
            z-index: 1000;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0,0,0,0.7);
            backdrop-filter: blur(5px);
        }

        .modal-content {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            margin: 5% auto;
            padding: 30px;
            border-radius: 15px;
            width: 80%;
            max-width: 600px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.3);
        }

        .close {
            color: #fff;
            float: right;
            font-size: 28px;
            font-weight: bold;
            cursor: pointer;
        }

        .close:hover {
            color: #e0c3fc;
        }

        .bookmarks-list {
            max-height: 400px;
            overflow-y: auto;
            margin-top: 20px;
        }

        .bookmark-item {
            padding: 15px;
            margin: 10px 0;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .bookmark-item:hover {
            background: rgba(255, 255, 255, 0.2);
        }

        .search-results {
            margin-top: 20px;
        }

        .search-result-item {
            padding: 15px;
            margin: 10px 0;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 8px;
            cursor: pointer;
        }

        .search-result-item:hover {
            background: rgba(255, 255, 255, 0.2);
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="logo">🌌</div>
            <h1>Universum</h1>
            <p class="subtitle">Энциклопедия знаний о Вселенной, науке и технологиях</p>
            <p>Исследуйте мир через призму знаний</p>
        </header>

        <div class="stats">
            <div class="stat-item">
                <div class="stat-number" id="articles-count">0</div>
                <div class="stat-label">Статей</div>
            </div>
            <div class="stat-item">
                <div class="stat-number" id="categories-count">0</div>
                <div class="stat-label">Категорий</div>
            </div>
            <div class="stat-item">
                <div class="stat-number" id="bookmarks-count">0</div>
                <div class="stat-label">Закладок</div>
            </div>
        </div>

        <div class="search-container">
            <input type="text" id="search-input" placeholder="Введите запрос для поиска по энциклопедии...">
            <button id="search-btn">Найти</button>
        </div>

        <div class="categories">
            <button class="category-btn active" data-category="all">Все категории</button>
            <button class="category-btn" data-category="science">Наука</button>
            <button class="category-btn" data-category="history">История</button>
            <button class="category-btn" data-category="art">Искусство</button>
            <button class="category-btn" data-category="technology">Технологии</button>
            <button class="category-btn" data-category="nature">Природа</button>
            <button class="category-btn" data-category="space">Космос</button>
        </div>

        <div class="content">
            <div class="sidebar">
                <h2>Статьи</h2>
                <ul class="article-list" id="article-list">
                    <!-- Статьи будут загружены через JavaScript -->
                </ul>
            </div>

            <div class="main-content">
                <h2 class="article-title" id="article-title">Загрузка...</h2>
                <div class="article-content" id="article-content">
                    <p>Выберите статью из списка слева для просмотра</p>
                </div>

                <div class="tools">
                    <button class="tool-btn" id="prev-btn">
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" viewBox="0 0 16 16">
                            <path fill-rule="evenodd" d="M11.354 1.646a.5.5 0 0 1 0 .708L5.707 8l5.647 5.646a.5.5 0 0 1-.708.708l-6-6a.5.5 0 0 1 0-.708l6-6a.5.5 0 0 1 .708 0z"/>
                        </svg>
                        Назад
                    </button>
                    <button class="tool-btn bookmark-btn" id="bookmark-btn">
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" viewBox="0 0 16 16">
                            <path d="M2 2a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v13.5a.5.5 0 0 1-.777.416L8 13.101l-5.223 2.815A.5.5 0 0 1 2 15.5V2zm2-1a1 1 0 0 0-1 1v12.566l4.723-2.482a.5.5 0 0 1 .554 0L13 14.566V2a1 1 0 0 0-1-1H4z"/>
                        </svg>
                        В закладки
                    </button>
                    <button class="tool-btn" id="print-btn">
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" viewBox="0 0 16 16">
                            <path d="M2.5 8a.5.5 0 1 0 0-1 .5.5 0 0 0 0 1z"/>
                            <path d="M5 1a2 2 0 0 0-2 2v2H2a2 2 0 0 0-2 2v3a2 2 0 0 0 2 2h1v1a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2v-1h1a2 2 0 0 0 2-2V7a2 2 0 0 0-2-2h-1V3a2 2 0 0 0-2-2H5zM4 3a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v2H4V3zm1 5a2 2 0 0 0-2 2v1H2a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1h-1v-1a2 2 0 0 0-2-2H5zm7 2v3a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1z"/>
                        </svg>
                        Печать
                    </button>
                    <button class="tool-btn" id="share-btn">
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" viewBox="0 0 16 16">
                            <path d="M11 2.5a2.5 2.5 0 1 1 .603 1.628l-6.718 3.12a2.499 2.499 0 0 1 0 1.504l6.718 3.12a2.5 2.5 0 1 1-.488.876l-6.718-3.12a2.5 2.5 0 1 1 0-3.256l6.718-3.12A2.5 2.5 0 0 1 11 2.5z"/>
                        </svg>
                        Поделиться
                    </button>
                    <button class="tool-btn" id="bookmarks-modal-btn">
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" viewBox="0 0 16 16">
                            <path d="M2 2a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v13.5a.5.5 0 0 1-.777.416L8 13.101l-5.223 2.815A.5.5 0 0 1 2 15.5V2zm2-1a1 1 0 0 0-1 1v12.566l4.723-2.482a.5.5 0 0 1 .554 0L13 14.566V2a1 1 0 0 0-1-1H4z"/>
                        </svg>
                        Закладки
                    </button>
                    <button class="tool-btn" id="next-btn">
                        Вперед
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" viewBox="0 0 16 16">
                            <path fill-rule="evenodd" d="M4.646 1.646a.5.5 0 0 1 .708 0l6 6a.5.5 0 0 1 0 .708l-6 6a.5.5 0 0 1-.708-.708L10.293 8 4.646 2.354a.5.5 0 0 1 0-.708z"/>
                        </svg>
                    </button>
                </div>
            </div>
        </div>

        <footer>
            <p>Universum - Энциклопедия знаний © 2024 | Все права защищены</p>
            <p>Энциклопедия постоянно пополняется новыми статьями</p>
        </footer>
    </div>

    <!-- Модальное окно закладок -->
    <div id="bookmarks-modal" class="modal">
        <div class="modal-content">
            <span class="close">&times;</span>
            <h2>Мои закладки</h2>
            <div class="bookmarks-list" id="bookmarks-list">
                <!-- Закладки будут добавляться сюда -->
            </div>
        </div>
    </div>

    <script>
        // Полная база данных статей
        const articles = {
            'quantum-physics': {
                title: 'Квантовая физика',
                category: 'science',
                content: `
                    <p><strong>Квантовая физика</strong> — это раздел теоретической физики, изучающий квантово-механические и квантово-полевые системы и законы их движения.</p>
                    
                    <h3>История развития</h3>
                    <p>Квантовая теория зародилась в начале XX века, когда классическая физика не могла объяснить некоторые явления: излучение абсолютно чёрного тела, фотоэффект, стабильность атомов.</p>
                    
                    <h3>Основные принципы</h3>
                    <ul>
                        <li><strong>Квантование</strong> — физические величины принимают дискретные значения</li>
                        <li><strong>Волновая функция</strong> — математическое описание квантового состояния</li>
                        <li><strong>Принцип неопределённости</strong> — невозможно одновременно точно измерить координату и импульс</li>
                        <li><strong>Корпускулярно-волновой дуализм</strong> — объекты проявляют волновые и корпускулярные свойства</li>
                    </ul>
                    
                    <blockquote>"Если квантовая механика вас не потрясла, значит вы ее еще не поняли." — Нильс Бор</blockquote>
                `
            },
            'ancient-rome': {
                title: 'Древний Рим',
                category: 'history',
                content: `
                    <p><strong>Древний Рим</strong> — одна из величайших цивилизаций древнего мира, существовавшая на протяжении более 12 веков.</p>
                    
                    <h3>Основные периоды</h3>
                    <ul>
                        <li><strong>Царский период (753–509 до н.э.)</strong> — основание Рима</li>
                        <li><strong>Римская республика (509–27 до н.э.)</strong> — расцвет республиканских институтов</li>
                        <li><strong>Римская империя (27 до н.э.–476 н.э.)</strong> — императорское правление</li>
                    </ul>
                    
                    <h3>Наследие</h3>
                    <p>Римляне создали обширную сеть дорог, акведуки, развитую правовую систему и распространили латинский язык.</p>
                `
            },
            'renaissance': {
                title: 'Эпоха Возрождения',
                category: 'history',
                content: `
                    <p><strong>Эпоха Возрождения (Ренессанс)</strong> — период в истории европейской культуры, XIV–XVI века.</p>
                    
                    <h3>Характерные черты</h3>
                    <ul>
                        <li><strong>Гуманизм</strong> — ценность человеческой личности</li>
                        <li><strong>Интерес к античности</strong> — возрождение классических образцов</li>
                        <li><strong>Развитие наук</strong> — достижения в астрономии, физике, медицине</li>
                    </ul>
                    
                    <p>Среди известных деятелей: Леонардо да Винчи, Микеланджело, Рафаэль, Данте Алигьери.</p>
                `
            },
            'ai': {
                title: 'Искусственный интеллект',
                category: 'technology',
                content: `
                    <p><strong>Искусственный интеллект (ИИ)</strong> — область компьютерных наук, создающая машины, способные выполнять задачи, требующие человеческого интеллекта.</p>
                    
                    <h3>Основные направления</h3>
                    <ul>
                        <li><strong>Машинное обучение</strong> — алгоритмы, улучшающие производительность через опыт</li>
                        <li><strong>Глубокое обучение</strong> — нейронные сети с множеством слоев</li>
                        <li><strong>Обработка естественного языка</strong> — понимание человеческой речи</li>
                    </ul>
                    
                    <h3>Применение</h3>
                    <p>ИИ используется в медицине, финансах, транспорте, образовании и многих других областях.</p>
                `
            },
            'space-exploration': {
                title: 'Исследование космоса',
                category: 'space',
                content: `
                    <p><strong>Исследование космоса</strong> — изучение космического пространства и небесных тел с помощью космических аппаратов и телескопов.</p>
                    
                    <h3>История</h3>
                    <ul>
                        <li><strong>1957</strong> — первый искусственный спутник Земли</li>
                        <li><strong>1961</strong> — первый полет человека в космос</li>
                        <li><strong>1969</strong> — первая высадка на Луну</li>
                    </ul>
                    
                    <h3>Будущее</h3>
                    <p>Планы включают возвращение на Луну, полеты на Марс и поиск внеземной жизни.</p>
                `
            },
            'black-holes': {
                title: 'Чёрные дыры',
                category: 'space',
                content: `
                    <p><strong>Чёрные дыры</strong> — области пространства-времени с настолько сильным гравитационным притяжением, что ничто не может их покинуть.</p>
                    
                    <h3>Образование</h3>
                    <p>Чёрные дыры образуются в результате гравитационного коллапса массивных звезд.</p>
                    
                    <h3>Типы</h3>
                    <ul>
                        <li><strong>Звездные</strong> — массой 3-100 масс Солнца</li>
                        <li><strong>Сверхмассивные</strong> — в центрах галактик</li>
                    </ul>
                `
            },
            'climate-change': {
                title: 'Изменение климата',
                category: 'nature',
                content: `
                    <p><strong>Изменение климата</strong> — долгосрочные изменения погодных условий на Земле.</p>
                    
                    <h3>Причины</h3>
                    <ul>
                        <li>Парниковый эффект</li>
                        <li>Выбросы CO2</li>
                        <li>Вырубка лесов</li>
                    </ul>
                    
                    <h3>Последствия</h3>
                    <p>Таяние ледников, повышение уровня моря, экстремальные погодные условия.</p>
                `
            },
            'quantum-computing': {
                title: 'Квантовые компьютеры',
                category: 'technology',
                content: `
                    <p><strong>Квантовые компьютеры</strong> — вычислительные устройства, использующие явления квантовой механики.</p>
                    
                    <h3>Принципы работы</h3>
                    <ul>
                        <li><strong>Кубиты</strong> — квантовые биты</li>
                        <li><strong>Суперпозиция</strong> — одновременное нахождение в нескольких состояниях</li>
                        <li><strong>Запутанность</strong> — взаимосвязь кубитов</li>
                    </ul>
                `
            }
        };

        // Создание снежинок
        function createSnowflakes() {
            const snowContainer = document.body;
            const snowflakeCount = 50;
            
            for (let i = 0; i < snowflakeCount; i++) {
                const snowflake = document.createElement('div');
                snowflake.classList.add('snowflake');
                snowflake.innerHTML = '❄';
                
                const size = Math.random() * 15 + 10;
                const startPosition = Math.random() * 100;
                const animationDuration = Math.random() * 10 + 5;
                const opacity = Math.random() * 0.5 + 0.3;
                
                snowflake.style.left = `${startPosition}vw`;
                snowflake.style.fontSize = `${size}px`;
                snowflake.style.opacity = opacity;
                snowflake.style.animation = `fall ${animationDuration}s linear infinite`;
                
                snowContainer.appendChild(snowflake);
            }
        }

        // Добавление CSS анимации
        const style = document.createElement('style');
        style.textContent = `
            @keyframes fall {
                0% { transform: translateY(-10px) rotate(0deg); }
                100% { transform: translateY(100vh) rotate(360deg); }
            }
        `;
        document.head.appendChild(style);

        // Инициализация
        let currentArticle = 'quantum-physics';
        let bookmarks = JSON.parse(localStorage.getItem('encyclopediaBookmarks')) || [];
        let filteredArticles = Object.keys(articles);

        // Инициализация при загрузке
        document.addEventListener('DOMContentLoaded', function() {
            createSnowflakes();
            initializeApp();
        });

        function initializeApp() {
            updateStats();
            loadArticlesList();
            updateArticleContent(currentArticle);
            setupEventListeners();
        }

        function updateStats() {
            document.getElementById('articles-count').textContent = Object.keys(articles).length;
            document.getElementById('categories-count').textContent = new Set(Object.values(articles).map(a => a.category)).size;
            document.getElementById('bookmarks-count').textContent = bookmarks.length;
        }

        function loadArticlesList() {
            const articleList = document.getElementById('article-list');
            articleList.innerHTML = '';
            
            Object.keys(articles).forEach(articleId => {
                const article = articles[articleId];
                const li = document.createElement('li');
                li.className = 'article-item';
                li.setAttribute('data-article', articleId);
                li.textContent = article.title;
                if (articleId === currentArticle) {
                    li.classList.add('active');
                }
                articleList.appendChild(li);
            });
            
            addArticleEventListeners();
        }

        function updateArticleContent(articleId) {
            if (!articles[articleId]) return;
            
            currentArticle = articleId;
            const article = articles[articleId];
            
            document.getElementById('article-title').textContent = article.title;
            document.getElementById('article-content').innerHTML = article.content;
            
            // Обновление активной статьи
            document.querySelectorAll('.article-item').forEach(item => {
                item.classList.remove('active');
                if (item.getAttribute('data-article') === articleId) {
                    item.classList.add('active');
                }
            });
            
            // Обновление кнопки закладки
            updateBookmarkButton();
        }

        function updateBookmarkButton() {
            const bookmarkBtn = document.getElementById('bookmark-btn');
            const isBookmarked = bookmarks.includes(currentArticle);
            bookmarkBtn.classList.toggle('active', isBookmarked);
            bookmarkBtn.innerHTML = isBookmarked ? 
                `<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" viewBox="0 0 16 16">
                    <path d="M2 2v13.5a.5.5 0 0 0 .74.439L8 13.069l5.26 2.87A.5.5 0 0 0 14 15.5V2a2 2 0 0 0-2-2H4a2 2 0 0 0-2 2z"/>
                </svg> В закладках` :
                `<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" viewBox="0 0 16 16">
                    <path d="M2 2a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v13.5a.5.5 0 0 1-.777.416L8 13.101l-5.223 2.815A.5.5 0 0 1 2 15.5V2zm2-1a1 1 0 0 0-1 1v12.566l4.723-2.482a.5.5 0 0 1 .554 0L13 14.566V2a1 1 0 0 0-1-1H4z"/>
                </svg> В закладки`;
        }

        function filterArticles(category) {
            filteredArticles = category === 'all' ? 
                Object.keys(articles) : 
                Object.keys(articles).filter(id => articles[id].category === category);
            
            loadArticlesList();
            
            if (!filteredArticles.includes(currentArticle) && filteredArticles.length > 0) {
                updateArticleContent(filteredArticles[0]);
            }
        }

        function searchArticles(query) {
            const results = Object.keys(articles).filter(id => {
                const article = articles[id];
                return article.title.toLowerCase().includes(query.toLowerCase()) ||
                       article.content.toLowerCase().includes(query.toLowerCase());
            });
            
            if (results.length > 0) {
                filteredArticles = results;
                loadArticlesList();
                updateArticleContent(results[0]);
            } else {
                alert('По вашему запросу ничего не найдено. Попробуйте другой поисковый запрос.');
            }
        }

        function toggleBookmark() {
            const index = bookmarks.indexOf(currentArticle);
            if (index === -1) {
                bookmarks.push(currentArticle);
            } else {
                bookmarks.splice(index, 1);
            }
            localStorage.setItem('encyclopediaBookmarks', JSON.stringify(bookmarks));
            updateBookmarkButton();
            updateStats();
        }

        function showBookmarks() {
            const modal = document.getElementById('bookmarks-modal');
            const list = document.getElementById('bookmarks-list');
            
            list.innerHTML = '';
            
            if (bookmarks.length === 0) {
                list.innerHTML = '<p>У вас пока нет закладок. Добавьте статьи в закладки, нажав на кнопку "В закладки".</p>';
            } else {
                bookmarks.forEach(articleId => {
                    const article = articles[articleId];
                    const div = document.createElement('div');
                    div.className = 'bookmark-item';
                    div.innerHTML = `<strong>${article.title}</strong>`;
                    div.onclick = () => {
                        updateArticleContent(articleId);
                        modal.style.display = 'none';
                    };
                    list.appendChild(div);
                });
            }
            
            modal.style.display = 'block';
        }

        function navigateArticles(direction) {
            const currentIndex = filteredArticles.indexOf(currentArticle);
            let newIndex;
            
            if (direction === 'next') {
                newIndex = (currentIndex + 1) % filteredArticles.length;
            } else {
                newIndex = (currentIndex - 1 + filteredArticles.length) % filteredArticles.length;
            }
            
            updateArticleContent(filteredArticles[newIndex]);
        }

        function printArticle() {
            const printContent = `
                <html>
                    <head>
                        <title>${articles[currentArticle].title} - Universum</title>
                        <style>
                            body { font-family: Arial, sans-serif; line-height: 1.6; margin: 40px; }
                            h1 { color: #333; border-bottom: 2px solid #333; padding-bottom: 10px; }
                            h3 { color: #555; margin-top: 25px; }
                            ul { margin-left: 20px; }
                            blockquote { border-left: 4px solid #ccc; padding-left: 20px; margin: 20px 0; font-style: italic; }
                            @media print { body { margin: 0.5in; } }
                        </style>
                    </head>
                    <body>
                        <h1>${articles[currentArticle].title}</h1>
                        ${articles[currentArticle].content}
                        <hr>
                        <p><em>Источник: Universum - Энциклопедия знаний</em></p>
                    </body>
                </html>
            `;
            
            const printWindow = window.open('', '_blank');
            printWindow.document.write(printContent);
            printWindow.document.close();
            printWindow.focus();
            printWindow.print();
        }

        function shareArticle() {
            if (navigator.share) {
                navigator.share({
                    title: `${articles[currentArticle].title} - Universum`,
                    text: articles[currentArticle].content.substring(0, 100) + '...',
                    url: window.location.href
                });
            } else {
                navigator.clipboard.writeText(`${articles[currentArticle].title}\n\n${window.location.href}`).then(() => {
                    alert('Ссылка на статью скопирована в буфер обмена!');
                });
            }
        }

        function addArticleEventListeners() {
            document.querySelectorAll('.article-item').forEach(item => {
                item.addEventListener('click', function() {
                    updateArticleContent(this.getAttribute('data-article'));
                });
            });
        }

        function setupEventListeners() {
            // Категории
            document.querySelectorAll('.category-btn').forEach(button => {
                button.addEventListener('click', function() {
                    document.querySelectorAll('.category-btn').forEach(btn => btn.classList.remove('active'));
                    this.classList.add('active');
                    filterArticles(this.getAttribute('data-category'));
                });
            });

            // Поиск
            document.getElementById('search-btn').addEventListener('click', () => {
                const searchTerm = document.getElementById('search-input').value;
                if (searchTerm.trim() !== '') {
                    searchArticles(searchTerm);
                }
            });

            document.getElementById('search-input').addEventListener('keypress', function(e) {
                if (e.key === 'Enter') {
                    searchArticles(this.value);
                }
            });

            // Функциональные кнопки
            document.getElementById('bookmark-btn').addEventListener('click', toggleBookmark);
            document.getElementById('bookmarks-modal-btn').addEventListener('click', showBookmarks);
            document.getElementById('prev-btn').addEventListener('click', () => navigateArticles('prev'));
            document.getElementById('next-btn').addEventListener('click', () => navigateArticles('next'));
            document.getElementById('print-btn').addEventListener('click', printArticle);
            document.getElementById('share-btn').addEventListener('click', shareArticle);

            // Модальное окно
            document.querySelector('.close').addEventListener('click', () => {
                document.getElementById('bookmarks-modal').style.display = 'none';
            });

            window.addEventListener('click', (event) => {
                const modal = document.getElementById('bookmarks-modal');
                if (event.target === modal) {
                    modal.style.display = 'none';
                }
            });

            // Статьи
            addArticleEventListeners();
        }
    </script>
</body>
</html>
