# Good-pharmacist-<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>موقعي الشخصي</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(120deg, #00c6ff, #0072ff);
            color: #fff;
        }
        header {
            background: rgba(0, 0, 0, 0.7);
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
            color: #FFD700;
        }
        nav {
            margin-top: 10px;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #fff;
            font-weight: bold;
        }
        nav a:hover {
            color: #FFD700;
        }
        .container {
            padding: 40px 20px;
            text-align: center;
        }
        .container h2 {
            font-size: 2em;
            margin-bottom: 20px;
        }
        .container p {
            font-size: 1.2em;
            line-height: 1.6;
        }
        .card {
            display: inline-block;
            width: 300px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            padding: 20px;
            margin: 15px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .card img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 15px;
        }
        footer {
            background: rgba(0, 0, 0, 0.7);
            padding: 20px;
            text-align: center;
            margin-top: 20px;
        }
        footer p {
            margin: 0;
            font-size: 1em;
        }
    </style>
</head>
<body>
    <header>
        <h1>موقعي الشخصي</h1>
        <nav>
            <a href="#about">من أنا</a>
            <a href="#services">خدماتي</a>
            <a href="#contact">تواصل معي</a>
        </nav>
    </header>
    <div class="container" id="about">
        <h2>من أنا</h2>
        <p>مرحباً! أنا أحمد جابر حسين، طالب بكلية الصيدلة، وأطمح إلى بناء مسيرة مهنية ناجحة. أهتم بالتعلم المستمر وتطوير مهاراتي.</p>
    </div>
    <div class="container" id="services">
        <h2>خدماتي</h2>
        <div class="card">
            <img src="https://via.placeholder.com/100" alt="خدمة 1">
            <h3>التدريب الطبي</h3>
            <p>تقديم خدمات تدريبية في مجال الصيدلة وقياس العلامات الحيوية.</p>
        </div>
        <div class="card">
            <img src="https://via.placeholder.com/100" alt="خدمة 2">
            <h3>استشارات صيدلانية</h3>
            <p>تقديم النصائح والإرشادات في مجال الأدوية والمستحضرات الطبية.</p>
        </div>
    </div>
    <footer id="contact">
        <p>© 2024 جميع الحقوق محفوظة | أحمد جابر حسين</p>
        <p>البريد الإلكتروني: yourname@example.com</p>
    </footer>
</body>
</html>
