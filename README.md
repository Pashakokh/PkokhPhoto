<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Інтернет Провайдер VECHIR</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #0078d4;
            color: #ffffff;
            padding: 20px;
            text-align: center;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            color: #ffffff;
            text-decoration: none;
        }
        .content {
            padding: 20px;
        }
        footer {
            background: #0078d4;
            color: #ffffff;
            text-align: center;
            padding: 10px 0;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
        .contact-form {
            background: #ffffff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <header>
        <h1>Вітаємо в VECHIR!</h1>
        <nav>
            <a href="#services">Послуги</a>
            <a href="#about">Про нас</a>
            <a href="#contact">Контакт</a>
        </nav>
    </header>

    <div class="content">
        <section id="services">
            <h2>Наші Послуги</h2>
            <ul>
                <li>Швидкий доступ до Інтернету</li>
                <li>Безкоштовна установка</li>
                <li>24/7 технічна підтримка</li>
                <li>Гнучкі тарифні плани</li>
            </ul>
        </section>

        <section id="about">
            <h2>Про нас</h2>
            <p>VECHIR - ваш надійний партнер у світі Інтернету. Ми пропонуємо високошвидкісний доступ до Інтернету та якісне обслуговування клієнтів.</p>
        </section>

        <section id="contact">
            <h2>Зв'яжіться з нами</h2>
            <div class="contact-form">
                <form>
                    <label for="name">Ім'я:</label><br>
                    <input type="text" id="name" name="name" required><br><br>
                    <label for="email">Електронна пошта:</label><br>
                    <input type="email" id="email" name="email" required><br><br>
                    <label for="message">Повідомлення:</label><br>
                    <textarea id="message" name="message" rows="4" required></textarea><br><br>
                    <input type="submit" value="Відправити">
                </form>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 VECHIR. Усі права захищені.</p>
    </footer>
</body>
</html>
