<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Скачать программы</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #1a2a6c, #b21f1f, #fdbb2d);
            color: #fff;
            line-height: 1.6;
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        header {
            text-align: center;
            padding: 40px 0;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }
        
        .subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        .apps-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        
        .app-card {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border-radius: 15px;
            padding: 30px;
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.2);
        }
        
        .app-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.3);
        }
        
        .app-icon {
            width: 80px;
            height: 80px;
            margin: 0 auto 20px;
            border-radius: 15px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2.5rem;
            background: rgba(255, 255, 255, 0.2);
        }
        
        .app-title {
            font-size: 1.5rem;
            margin-bottom: 15px;
        }
        
        .app-description {
            margin-bottom: 20px;
            opacity: 0.8;
        }
        
        .download-btn {
            display: inline-block;
            background: #4CAF50;
            color: white;
            padding: 12px 25px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            transition: background 0.3s ease;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
        }
        
        .download-btn:hover {
            background: #45a049;
            transform: scale(1.05);
        }
        
        .instructions {
            margin-top: 50px;
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.2);
        }
        
        .instructions h2 {
            margin-bottom: 20px;
            text-align: center;
        }
        
        .instructions ol {
            margin-left: 20px;
        }
        
        .instructions li {
            margin-bottom: 10px;
        }
        
        footer {
            text-align: center;
            margin-top: 50px;
            padding: 20px;
            opacity: 0.7;
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            
            .apps-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Скачать программы</h1>
            <p class="subtitle">Безопасные и проверенные приложения для вашего устройства</p>
        </header>
        
        <div class="apps-grid">
            <div class="app-card">
                <div class="app-icon">🔒</div>
                <h2 class="app-title">Avast VPN</h2>
                <p class="app-description">Защитите свою конфиденциальность и обходите географические ограничения с помощью надежного VPN-сервиса.</p>
                <a href="#" class="download-btn" id="avast-link">Скачать Avast VPN</a>
            </div>
            
            <div class="app-card">
                <div class="app-icon">🎵</div>
                <h2 class="app-title">Media Station</h2>
                <p class="app-description">Мощный медиаплеер для воспроизведения всех популярных аудио и видео форматов.</p>
                <a href="#" class="download-btn" id="media-link">Скачать Media Station</a>
            </div>
            
            <div class="app-card">
                <div class="app-icon">🌐</div>
                <h2 class="app-title">Яндекс Браузер</h2>
                <p class="app-description">Быстрый и безопасный браузер с интегрированными сервисами Яндекс для комфортного веб-сёрфинга.</p>
                <a href="#" class="download-btn" id="yandex-link">Скачать Яндекс Браузер</a>
            </div>
        </div>
        
        <div class="instructions">
            <h2>Как вставить свои ссылки для скачивания</h2>
            <ol>
                <li>Откройте файл HTML в текстовом редакторе</li>
                <li>Найдите строки с комментариями "ЗАМЕНИТЕ ЭТУ ССЫЛКУ"</li>
                <li>Замените символ "#" в атрибуте href на вашу ссылку для скачивания</li>
                <li>Сохраните файл и откройте его в браузере</li>
            </ol>
        </div>
        
        <footer>
            <p>© 2023 Сайт для загрузки программ. Все права защищены.</p>
        </footer>
    </div>

    <script>
        // Замените ссылки ниже на ваши собственные
        document.getElementById('avast-link').href = "https://10b67809-3268-49b1-a858-db24324b66cf.selcdn.net/avoVPN.1.20.tv.apk"; // https://ru.avohub.net/avoVPN.1.7.35.tv.apk
        document.getElementById('media-link').href = "#"; // ЗАМЕНИТЕ ЭТУ ССЫЛКУ на вашу ссылку для Media Station
        document.getElementById('yandex-link').href = "#"; // ЗАМЕНИТЕ ЭТУ ССЫЛКУ на вашу ссылку для Яндекс Браузера
    </script>
</body>
