<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Документальная Информация</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --primary-color: #2c3e50;
            --secondary-color: #3498db;
            --accent-color: #e74c3c;
            --text-color: #ecf0f1;
            --background-color: #1a1a2e;
            --card-background: #16213e;
            --hover-color: #0f3460;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, var(--background-color), #162447);
            color: var(--text-color);
            line-height: 1.6;
            padding: 20px;
            min-height: 100vh;
        }

        header {
            text-align: center;
            padding: 2rem 0;
            margin-bottom: 2rem;
            background: rgba(0, 0, 0, 0.3);
            border-radius: 15px;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            background: linear-gradient(to right, var(--secondary-color), var(--accent-color));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
        }

        .tagline {
            font-size: 1.2rem;
            opacity: 0.8;
            max-width: 600px;
            margin: 0 auto;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
        }

        .card {
            background: var(--card-background);
            border-radius: 15px;
            padding: 25px;
            transition: all 0.3s ease;
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
            display: flex;
            flex-direction: column;
            height: 100%;
        }

        .card:hover {
            transform: translateY(-10px);
            background: var(--hover-color);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.4);
        }

        .card-number {
            font-size: 1.5rem;
            font-weight: bold;
            color: var(--secondary-color);
            margin-bottom: 15px;
            display: flex;
            align-items: center;
        }

        .card-number i {
            margin-right: 10px;
            font-size: 1.8rem;
        }

        .card-title {
            font-size: 1.4rem;
            margin-bottom: 20px;
            color: #f39c12;
            flex-grow: 1;
        }

        .card-content {
            margin-bottom: 20px;
            flex-grow: 1;
        }

        .card-content p {
            margin-bottom: 15px;
            font-size: 1.1rem;
        }

        .card-content ul {
            padding-left: 20px;
            margin-bottom: 15px;
        }

        .card-content li {
            margin-bottom: 8px;
        }

        footer {
            text-align: center;
            margin-top: 3rem;
            padding: 2rem;
            background: rgba(0, 0, 0, 0.3);
            border-radius: 15px;
            font-size: 1.1rem;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        .highlight {
            color: var(--accent-color);
            font-weight: bold;
        }

        @media (max-width: 768px) {
            .container {
                grid-template-columns: 1fr;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            .tagline {
                font-size: 1rem;
            }
            
            body {
                padding: 10px;
            }
        }

        @media (max-width: 480px) {
            .card {
                padding: 15px;
            }
            
            .card-title {
                font-size: 1.2rem;
            }
            
            .card-content p {
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Документальная Информация</h1>
        <p class="tagline">Серьезные исследования по самым актуальным вопросам современности</p>
    </header>

    <div class="container">
        <div class="card">
            <div class="card-number">
                <i class="fas fa-feather-alt"></i>
                Тема 1
            </div>
            <div class="card-title">Почему мадагаскарский яйценосный дрозд сильнее скебоба но не сильнее скебоба прайма</div>
            <div class="card-content">
                <p>Детальное исследование показало, что мадагаскарский яйценосный дрозд обладает уникальными физиологическими характеристиками:</p>
                <ul>
                    <li>Сила клюва: 8.7 у.е.</li>
                    <li>Сила клюва скебоба: 7.2 у.е.</li>
                    <li>Сила клюва скебоба прайма: 9.1 у.е.</li>
                </ul>
                <p>Следовательно, дрозд <span class="highlight">сильнее обычного скебоба</span>, но уступает его усовершенствованной версии.</p>
            </div>
        </div>

        <div class="card">
            <div class="card-number">
                <i class="fas fa-robot"></i>
                Тема 2
            </div>
            <div class="card-title">Почему оптимус прайм не может съесть ядерный гриб чтобы Сталин воскрес</div>
            <div classcode-content">
                <p>Исследование проводилось в три этапа:</p>
                <ul>
                    <li>Анализ молекулярной структуры ядерного гриба</li>
                    <li>Оценка пищеварительной системы оптимуса прайма</li>
                    <li>Моделирование процесса воскрешения</li>
                </ul>
                <p>Результаты показали, что оптимус прайм не имеет необходимых ферментов для <span class="highlight">биологической трансмутации</span> исторических личностей через грибную диету.</p>
            </div>
        </div>

        <div class="card">
            <div class="card-number">
                <i class="fas fa-cube"></i>
                Тема 3
            </div>
            <div class="card-title">Почему никто не получил наследие херобрина виде пениса из бедрока</div>
            <div class="card-content">
                <p>Генетический анализ показал:</p>
                <ul>
                    <li>Херобрин имеет мутацию в 13-ом хромосоме</li>
                    <li>Бедрок усиливает фенотипическую экспрессию</li>
                    <li>Сложности с наследственным кодом</li>
                </ul>
                <p>Поскольку сегмент ДНК <span class="highlight">не функционален</span>, наследие не передается.</p>
            </div>
        </div>

        <div class="card">
            <div class="card-number">
                <i class="fas fa-toilet"></i>
                Тема 4
            </div>
            <div class="card-title">Почему дрим может срать поносом а я так же но только слабее</div>
            <div class="card-content">
                <p>Сравнительный анализ пищеварительных систем:</p>
                <ul>
                    <li>Дрим: 98% эффективности поноса</li>
                    <li>Человеческий организм: 73% эффективности</li>
                    <li>Разница: недостаток специализированных ферментов</li>
                </ul>
                <p><span class="highlight">Биологические ограничения</span> не позволяют достичь той же силы воздействия.</p>
            </div>
        </div>

        <div class="card">
            <div class="card-number">
                <i class="fas fa-dragon"></i>
                Тема 5
            </div>
            <div class="card-title">Почему если смешать раптор с комаром получится Печкин</div>
            <div class="card-content">
                <p>Эксперимент проводился при следующих условиях:</p>
                <ul>
                    <li>Температура: 37°C</li>
                    <li>Влажность: 65%</li>
                    <li>Время реакции: 47 секунд</li>
                </ul>
                <p>Печкин является результатом <span class="highlight">случайной мутации</span> генов в процессе эксперимента.</p>
            </div>
        </div>

        <div class="card">
            <div class="card-number">
                <i class="fas fa-cubes"></i>
                Тема 6
            </div>
            <div class="card-title">Почему все кто ломал бедрок те стали микроволновкой</div>
            <div class="card-content">
                <p>Анализ причинно-следственной связи показал:</p>
                <ul>
                    <li>Бедрок обладает трансформирующими свойствами</li>
                    <li>Нарушение целостности вызывает мутацию</li>
                    <li>100% случаев приводят к этому результату</li>
                </ul>
                <p>Все подопытные превратились в <span class="highlight">микроволновки</span> из-за физико-химических свойств бедрока.</p>
            </div>
        </div>

        <div class="card">
            <div class="card-number">
                <i class="fas fa-poop"></i>
                Тема 999
            </div>
            <div class="card-title">Почему пришельцы сделали ананас из поноса верблюда</div>
            <div class="card-content">
                <p>Исследование пищевых технологий пришельцев:</p>
                <ul>
                    <li>Переработка биологических отходов</li>
                    <li>Использование особых ферментов</li>
                    <li>Странное восприятие вкуса</li>
                </ul>
                <p>Инопланетяне обладают <span class="highlight">уникальной способностью</span> трансформации отходов в экзотические фрукты.</p>
            </div>
        </div>

        <div class="card">
            <div class="card-number">
                <i class="fas fa-book-dead"></i>
                Тема 8
            </div>
            <div class="card-title">Что делать если меня записали в книгу смерти</div>
            <div class="card-content">
                <p>Рекомендации по выживанию:</p>
                <ul>
                    <li>Немедленно разорвать все контракты</li>
                    <li>Принять ванну из молока дракона</li>
                    <li>Разучить заклинание защиты судьбы</li>
                </ul>
                <p><span class="highlight">Важно срочно действовать</span> - эффективность 87% при правильном исполнении.</p>
            </div>
        </div>

        <div class="card">
            <div class="card-number">
                <i class="fas fa-fist-raised"></i>
                Тема 9
            </div>
            <div class="card-title">Что делать если на меня напал гопник, владеющий хамоном</div>
            <div class="card-content">
                <p>Тактика самообороны от хамон-гопника:</p>
                <ul>
                    <li>Избегать прямого контакта с энергией хамон</li>
                    <li>Использовать молитву во имя мемов</li>
                    <li>Носить защитную одежду из алюминия</li>
                </ul>
                <p>Гопник, использующий хамон, опаснее обычного - успешность защиты <span class="highlight">составляет 93%</span>.</p>
            </div>
        </div>

        <div class="card">
            <div class="card-number">
                <i class="fas fa-seedling"></i>
                Тема 10
            </div>
            <div class="card-title">Как создать атомный гриб в домашних условиях и как за ним ухаживать</div>
            <div class="card-content">
                <p>Инструкция по выращиванию:</p>
                <ul>
                    <li>Необходимы плутониевые споры</li>
                    <li>Поливать только радиоактивной водой</li>
                    <li>Удобрять углеродом-14</li>
                </ul>
                <p><span class="highlight">Не рекомендуется к употреблению</span> без специального разрешения.</p>
            </div>
        </div>
    </div>

    <footer>
        <p>Всё было изучено благодаря фонда гемороя 228 в 1125 году до нашей эры</p>
        <p><i class="fas fa-heart"></i> Фондовая документация <i class="fas fa-heart"></i></p>
    </footer>
</body>
</html>
