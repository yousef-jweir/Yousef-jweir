<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>يوسف جوير للخدمات العامة</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: white;
      text-align: center;
    }
    header {
      padding: 60px 20px;
      background: #222;
      position: relative;
    }
    header h1 {
      font-size: 2.5em;
      margin: 0;
      animation: glow 3s infinite alternate;
    }
    @keyframes glow {
      0% { text-shadow: 0 0 10px #0ff, 0 0 20px #0ff, 0 0 30px #0ff; }
      50% { text-shadow: 0 0 10px #f0f, 0 0 20px #f0f, 0 0 30px #f0f; }
      100% { text-shadow: 0 0 10px #ff0, 0 0 20px #ff0, 0 0 30px #ff0; }
    }
    nav {
      background: #111;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    nav a {
      color: #fff;
      padding: 14px 20px;
      text-decoration: none;
      transition: background 0.3s;
    }
    nav a:hover {
      background: #444;
    }
    .container {
      max-width: 1000px;
      margin: auto;
      padding: 20px;
    }
    section {
      margin-bottom: 40px;
      background: rgba(0,0,0,0.3);
      border-radius: 8px;
      padding: 20px;
      box-shadow: 0 0 20px rgba(0,0,0,0.5);
      transition: transform 0.3s;
    }
    section:hover {
      transform: scale(1.02);
    }
    footer {
      background: #222;
      padding: 20px;
      font-size: 0.9em;
    }
    .contact-buttons a {
      display: inline-block;
      margin: 10px;
      padding: 10px 20px;
      background: #4CAF50;
      color: white;
      border-radius: 5px;
      text-decoration: none;
      transition: background 0.3s;
    }
    .contact-buttons a:hover {
      background: #45a049;
    }
  </style>
</head>
<body>
  <header>
    <h1>يوسف جوير للخدمات العامة</h1>
    <p>خدمات متنوعة بجودة واحترافية عالية</p>
  </header>
  <nav>
    <a href="#about">من نحن</a>
    <a href="#services">خدماتنا</a>
    <a href="#contact">تواصل معنا</a>
  </nav>
  <div class="container">
    <section id="about">
      <h2>من نحن</h2>
      <p>شركة متخصصة تقدم أفضل الخدمات للأفراد والشركات بسرعة ومصداقية عالية.</p>
    </section>
    <section id="services">
      <h2>خدماتنا</h2>
      <p>- خدمات النظافة الشاملة</p>
      <p>- صيانة كهربائية وسباكة وترميم</p>
      <p>- نقل عفش وبضائع داخل وخارج المدينة</p>
    </section>
    <section id="contact">
      <h2>تواصل معنا</h2>
      <div class="contact-buttons">
        <a href="tel:01201540458">📞 اتصل 01201540458</a>
        <a href="tel:01020344404">📞 اتصل 01020344404</a>
        <a href="https://wa.me/201201540458" target="_blank">💬 واتساب</a>
      </div>
      <p>البريد الإلكتروني: info@yousef-jweir.com</p>
      <p>العنوان: جمهورية مصر العربية</p>
    </section>
  </div>
  <footer>
    &copy; 2025 يوسف جوير للخدمات العامة. جميع الحقوق محفوظة.
  </footer>
</body>
</html>
