# Ushakov-Linux

https://disk.yandex.ru/d/z4_fz592vbbA_g

<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Отчёт по установке Ubuntu в VirtualBox</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 40px 20px;
            color: #333;
        }

        .report-container {
            max-width: 1000px;
            margin: 0 auto;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.3);
            overflow: hidden;
        }

        .header {
            background: linear-gradient(135deg, #6B73FF 0%, #000DFF 100%);
            color: white;
            padding: 40px;
            text-align: center;
        }

        .header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
        }

        .header p {
            font-size: 1.2em;
            opacity: 0.95;
        }

        .steps {
            padding: 40px;
        }

        .step {
            margin-bottom: 60px;
            background: #f8f9fa;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .step:hover {
            transform: translateY(-5px);
        }

        .step-header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 15px 25px;
            font-size: 1.3em;
            font-weight: bold;
        }

        .step-content {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 30px;
        }

        .photo-container {
            width: 100%;
            max-width: 800px;
            margin: 20px 0;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }

        .photo-container img {
            width: 100%;
            height: auto;
            display: block;
            transition: transform 0.3s ease;
        }

        .photo-container:hover img {
            transform: scale(1.02);
        }

        .photo-caption {
            background: white;
            padding: 15px;
            text-align: center;
            font-size: 1.1em;
            color: #555;
            border-top: 1px solid #eee;
        }

        .step-description {
            text-align: center;
            margin: 20px 0;
            padding: 0 20px;
            font-size: 1.1em;
            color: #444;
        }

        .badge {
            display: inline-block;
            background: #28a745;
            color: white;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9em;
            margin-top: 10px;
        }

        .footer {
            background: #2d3748;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 0.9em;
        }

        .footer a {
            color: #90cdf4;
            text-decoration: none;
        }

        .footer a:hover {
            text-decoration: underline;
        }

        @media (max-width: 768px) {
            .header h1 {
                font-size: 1.8em;
            }
            
            .steps {
                padding: 20px;
            }
            
            .step-header {
                font-size: 1.1em;
            }
        }
    </style>
</head>
<body>
    <div class="report-container">
        <div class="header">
            <h1>🖥️ Установка Ubuntu на VirtualBox</h1>
            <p>Пошаговое руководство с фотоотчётом</p>
        </div>

        <div class="steps">
            <!-- Шаг 1: Включение OS -->
            <div class="step" id="step1">
                <div class="step-header">
                    Шаг 1: Запуск виртуальной машины
                </div>
                <div class="step-content">
                    <div class="photo-container">
                        <!-- Фото 1 из PDF (страница 4 - номер 1) -->
                        <img src="https://via.placeholder.com/800x450/f0f0f0/333333?text=VirtualBox+Startup+Screen" 
                             alt="Запуск виртуальной машины">
                        <div class="photo-caption">
                            Рисунок 1: Запуск VirtualBox и включение виртуальной машины с Ubuntu
                        </div>
                    </div>
                    <div class="step-description">
                        <p>Запускаем Oracle VM VirtualBox и выбираем созданную виртуальную машину с Ubuntu. Нажимаем "Запустить" для начала установки операционной системы.</p>
                        <span class="badge">✓ Начало установки</span>
                    </div>
                </div>
            </div>

            <!-- Шаг 2: Проверка сети -->
            <div class="step" id="step2">
                <div class="step-header">
                    Шаг 2: Проверка сетевых подключений
                </div>
                <div class="step-content">
                    <div class="photo-container">
                        <!-- Фото 2 из PDF (страница 2 - Проверка Сети) -->
                        <img src="https://via.placeholder.com/800x450/f0f0f0/333333?text=Network+Configuration" 
                             alt="Проверка сети">
                        <div class="photo-caption">
                            Рисунок 2: Настройка и проверка сетевого подключения
                        </div>
                    </div>
                    <div class="step-description">
                        <p>Настраиваем сетевой адаптер виртуальной машины. Выбираем тип подключения "NAT" или "Сетевой мост" для доступа в интернет.</p>
                        <span class="badge">✓ Сеть настроена</span>
                    </div>
                </div>
            </div>

            <!-- Шаг 3: Продолжение установки -->
            <div class="step" id="step3">
                <div class="step-header">
                    Шаг 3: Процесс установки Ubuntu
                </div>
                <div class="step-content">
                    <div class="photo-container">
                        <!-- Фото 3 из PDF (страница 3 - номер 2) -->
                        <img src="https://via.placeholder.com/800x450/f0f0f0/333333?text=Ubuntu+Installation+Process" 
                             alt="Установка Ubuntu">
                        <div class="photo-caption">
                            Рисунок 3: Продолжение установки, выбор параметров
                        </div>
                    </div>
                    <div class="step-description">
                        <p>Следуем инструкциям установщика Ubuntu. Выбираем язык, раскладку клавиатуры и параметры установки.</p>
                        <span class="badge">✓ Установка продолжается</span>
                    </div>
                </div>
            </div>

            <!-- Шаг 4: Завершение -->
            <div class="step" id="step4">
                <div class="step-header">
                    Шаг 4: Завершение установки
                </div>
                <div class="step-content">
                    <div class="photo-container">
                        <!-- Фото 4 из PDF (страница 4 - номер 1, дублируется) -->
                        <img src="https://via.placeholder.com/800x450/f0f0f0/333333?text=Installation+Complete" 
                             alt="Установка завершена">
                        <div class="photo-caption">
                            Рисунок 4: Успешная установка Ubuntu на VirtualBox
                        </div>
                    </div>
                    <div class="step-description">
                        <p>Установка завершена! Перезагружаем виртуальную машину и входим в новую систему Ubuntu.</p>
                        <span class="badge">✓ Установка завершена</span>
                    </div>
                </div>
            </div>
        </div>

        <div class="footer">
            <p>📸 Отчёт по установке Ubuntu в VirtualBox | Последовательность фото в соответствии с PDF</p>
            <p>🔧 Для замены изображений: замените URL в атрибутах src на ссылки ваших фотографий</p>
            <p>📅 Дата создания отчёта: Март 2026</p>
        </div>
    </div>
</body>
</html>
