<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تصميم موقع حديث</title>
    <style>
        /* --- الألوان الأساسية --- */
        :root {
            --primary-color: #1A535C;
            --secondary-color: #4ECDC4;
            --accent-color: #FF6B6B;
            --text-color: #333;
            --bg-light: #f8f9fa;
        }

        /* --- إعدادات أساسية --- */
        body {
            font-family: Arial, sans-serif;
            color: var(--text-color);
            margin: 0;
            padding: 0;
            background: var(--bg-light);
        }

        /* --- شريط التنقل --- */
        .navbar {
            background: var(--primary-color);
            padding: 1rem;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }

        .navbar a {
            color: white;
            margin: 0 1.5rem;
            text-decoration: none;
            font-weight: 600;
            transition: color 0.3s;
        }

        .navbar a:hover {
            color: var(--secondary-color);
        }

        /* --- قسم الترحيب --- */
        .hero {
            text-align: center;
            padding: 50px 20px;
            background: var(--secondary-color);
            color: white;
        }

        .hero h1 {
            font-size: 2.5rem;
        }

        .hero p {
            font-size: 1.2rem;
        }

        /* --- زر الاتصال --- */
        .cta-button {
            background: var(--accent-color);
            color: white;
            padding: 1rem 2rem;
            border-radius: 30px;
            display: inline-block;
            margin-top: 20px;
            text-decoration: none;
            font-weight: bold;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .cta-button:hover {
            transform: scale(1.05);
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
        }

        /* --- قسم الخدمات --- */
        .services {
            text-align: center;
            padding: 50px 20px;
        }

        .service-box {
            display: inline-block;
            width: 30%;
            margin: 10px;
            padding: 20px;
            background: white;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            transition: transform 0.3s;
        }

        .service-box:hover {
            transform: translateY(-5px);
        }

        .service-box h3 {
            color: var(--primary-color);
        }

        /* --- قسم الفوتر --- */
        .footer {
            text-align: center;
            padding: 20px;
            background: var(--primary-color);
            color: white;
            margin-top: 50px;
        }

    </style>
</head>
<body>

    <!-- شريط التنقل -->
    <nav class="navbar">
        <a href="#">الرئيسية</a>
        <a href="#">الخدمات</a>
        <a href="#">تواصل معنا</a>
    </nav>

    <!-- قسم الترحيب -->
    <section class="hero">
        <h1>مرحبًا بكم في موقعنا</h1>
        <p>نحن نقدم أفضل الحلول لاحتياجاتك</p>
        <a href="#" class="cta-button">تواصل معنا</a>
    </section>

    <!-- قسم الخدمات -->
    <section class="services">
        <h2>خدماتنا</h2>
        <div class="service-box">
            <h3>تصميم حديث</h3>
            <p>نقوم بإنشاء مواقع احترافية وجذابة</p>
        </div>
        <div class="service-box">
            <h3>تطوير متجاوب</h3>
            <p>تصاميم تتكيف مع جميع الأجهزة</p>
        </div>
        <div class="service-box">
            <h3>دعم فني</h3>
            <p>نقدم دعمًا فنيًا على مدار الساعة</p>
        </div>
    </section>

    <!-- الفوتر -->
    <footer class="footer">
        <p>جميع الحقوق محفوظة © 2025</p>
    </footer>

</body>
</html>
