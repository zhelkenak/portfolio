<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Моё портфолио</title>
    <style>
        /* Сброс отступов и базовые стили */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            width: 90%;
            max-width: 1100px;
            margin: auto;
            padding: 20px 0;
        }
        section {
            margin-bottom: 40px;
        }
        h1, h2 {
            margin-bottom: 15px;
        }
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .project {
            background: #fff;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .project img {
            max-width: 100%;
            border-radius: 5px;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 15px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>Стив Джобс</h1>
    <nav>
        <a href="#about">О Стив Джобсе</a>
        <a href="#projects">Проекты Стива</a>
        <a href="#contact">Контакты Стива</a>
    </nav>
</header>

<div class="container">
    <section id="about">
        <h2>О Стив Джобсе</h2>
        <p>Стивен Пол Джобс – изобретатель, предприниматель, промышленный дизайнер. Стоял у истоков создания компаний Apple и Pixar.</p>
    </section>

    <section id="projects">
        <h2>Проекты Стива</h2>
        <div class="projects">
            <div class="project">
                <img src="apple.jpg" alt="Проект 1">
                <h3>Проект 1</h3>
                <p>Apple Inc — американская технологическая корпорация, известная своими инновационными продуктами и высокой рыночной капитализацией.</p>
            </div>
            <div class="project">
                <img src="pixar.jpg" alt="Проект 2">
                <h3>Проект 2</h3>
                <p>Pixar Animation Studios (наиболее известная как Pixar) — американская студия компьютерной анимации, известная своими рецензентски и коммерчески успешными компьютерными анимационными фильмами. Базируется в Эмеривилле, штат Калифорния. С 2006 года Pixar является дочерней компанией Walt Disney Studios, подразделения Disney Entertainment, которое принадлежит The Walt Disney Company.</p>
            </div>
            <div class="project">
                <img src="next.jpg" alt="Проект 3">
                <h3>Проект 3</h3>
                <p>NeXT Computer (также назывался NeXT Computer System) — персональный компьютер, разработанный компанией NeXT. Выпускался c 1988 по 1990 год с предустановленной UNIX-подобной операционной системой NeXTSTEP. Системная плата была заключена в корпус, представляющий собой идеальный куб со стороной 30,48 см (1 фут)[1]. Изначально продавался напрямую вузам по цене в 6500 долларов США; в 1990 году поступил в розничную продажу по цене 9999 долларов</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Контакты</h2>
        <p>Email: <a href="mailto:example@mail.com">example@mail.com</a></p>
        <p>Телефон: +7 (777) 123‑45‑67</p>
    </section>
</div>

<footer>
    <p>&copy; 2026 Иван Иванов. Все права защищены.</p>
</footer>

</body>
</html>
