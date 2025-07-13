<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <title>يوسف جوير للخدمات العامة</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f0f0f0;
      margin: 0;
      padding: 0;
      direction: rtl;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #4CAF50, #388E3C);
      color: white;
      padding: 40px 20px;
      text-align: center;
      position: relative;
    }

    header h1 {
      font-size: 2.5em;
      margin: 0;
      text-shadow: 0 0 10px rgba(255,255,255,0.8);
      animation: glow 2s ease-in-out infinite alternate;
    }

    @keyframes glow {
      from {
        text-shadow: 0 0 10px #fff, 0 0 20px #4CAF50, 0 0 30px #4CAF50;
      }
      to {
        text-shadow: 0 0 20px #fff, 0 0 40px #66BB6A, 0 0 60px #81C784;
      }
    }

    header p {
      font-size: 1.2em;
      margin-top: 10px;
    }

    nav {
      background: #333;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }

    nav a {
      display: block;
      color: #f2f2f2;
      padding: 14px 20px;
      text-decoration: none;
      transition: background 0.3s, color 0.3s;
    }

    nav a:hover {
      background: #555;
      color: #fff;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 20px;
      animation: fadeIn 1s ease;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    section {
      margin-bottom: 40px;
    }

    .service {
      background: white;
      margin: 10px 0;
      padding: 20px;
      border-radius: 6px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .service:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }

    footer {
      background: #4CAF50;
      color: white;
      text-align: center;
      padding: 15px;
    }

    a.phone-link {
      color: #4CAF50;
      text-decoration: none;
      font-weight: bold;
    }

    a.phone-link:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

<header>
  <h1>يوسف جوير للخدمات العامة</h1>
  <p>نقدم خدمات متنوعة بجودة عالية واحترافية</p>
</header>

<nav>
  <a href="#contact">اتصل بنا</a>
  <a href="#services">خدماتنا</a>
  <a href="#about">من نحن</a>
</nav>

<div class="container">
  <section id="about">
    <h2>من نحن</h2>
    <p>شركة يوسف جوير للخدمات العامة تقدم حلول متكاملة للأفراد والشركات مع التزام كامل بالجودة والمصداقية والسرعة في الإنجاز.</p>
  </section>

  <section id="services">
    <h2>خدماتنا</h2>
    <div class="service">
      <h3>خدمات النظافة</h3>
      <p>تنظيف شامل للمنازل والمكاتب باستخدام أفضل المواد والمعدات الحديثة.</p>
    </div>
    <div class="service">
      <h3>خدمات الصيانة</h3>
      <p>صيانة كهربائية وسباكة وترميمات مع ضمان الجودة.</p>
    </div>
    <div class="service">
      <h3>خدمات النقل</h3>
      <p>نقل عفش وبضائع بسرعة وأمان داخل وخارج المدينة.</p>
    </div>
  </section>

  <section id="contact">
    <h2>اتصل بنا</h2>
    <p>📞 الهاتف 1: <a href="tel:01201540458" class="phone-link">01201540458</a></p>
    <p>📞 الهاتف 2: <a href="tel:01020344404" class="phone-link">01020344404</a></p>
    <p>📧 البريد الإلكتروني: info@yousef-jweir.com</p>
    <p>📍 العنوان: جمهورية مصر العربية</p>
  </section>
</div>

<footer>
  &copy; 2025 يوسف جوير للخدمات العامة. جميع الحقوق محفوظة.
</footer>

</body>
</html>
