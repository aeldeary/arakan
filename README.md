<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <title>جمعية أراكان الخيرية</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: 'Cairo', sans-serif;
      margin: 0;
      background-color: #f4f6f9;
      color: #333;
    }

    /* === Header === */
    header {
      background-color: #003366;
      color: white;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    header nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    /* === Hero Section === */
    .hero {
      background: url('https://arakan.org.tr/ar/uploads/slide1.jpg') center/cover no-repeat;
      padding: 120px 40px;
      color: white;
      text-align: center;
      background-blend-mode: overlay;
      background-color: #003366a0;
    }
    .hero h1 {
      font-size: 42px;
      margin-bottom: 15px;
    }
    .hero p {
      font-size: 20px;
      margin-bottom: 30px;
    }
    .hero button {
      background-color: #ffd700;
      border: none;
      padding: 15px 30px;
      font-size: 18px;
      cursor: pointer;
      border-radius: 5px;
    }

    /* === Sections === */
    .section {
      padding: 60px 40px;
      text-align: center;
    }
    .section h2 {
      color: #003366;
      margin-bottom: 30px;
    }

    /* === Cards === */
    .projects, .news {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .card {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      width: 300px;
      padding: 20px;
      text-align: right;
    }
    .card img {
      width: 100%;
      border-radius: 10px;
      margin-bottom: 15px;
    }
    .card button {
      background-color: #003366;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
    }

    /* === Footer === */
    footer {
      background-color: #003366;
      color: white;
      padding: 40px;
      text-align: center;
    }
  </style>
</head>
<body>

<!-- Header -->
<header>
  <div><strong>جمعية أراكان</strong></div>
  <nav>
    <a href="#">الرئيسية</a>
    <a href="#">عن أراكان</a>
    <a href="#">مشاريعنا</a>
    <a href="#">الأخبار</a>
    <a href="#" style="color: #ffd700;">تبرع الآن</a>
  </nav>
</header>

<!-- Hero Section -->
<section class="hero">
  <h1>معًا نمنحهم الأمل</h1>
  <p>ساهم في دعم الروهينجا وكن جزءًا من الحل</p>
  <button>تبرع الآن</button>
</section>

<!-- About Section -->
<section class="section">
  <h2>من هم الروهينجا؟</h2>
  <p>الروهينجا أقلية مضطهدة في ميانمار، يعانون من التشريد والحرمان من الحقوق. تعمل جمعيتنا على تقديم الدعم الإنساني لهم منذ سنوات.</p>
</section>

<!-- Projects Section -->
<section class="section">
  <h2>مشاريعنا الحالية</h2>
  <div class="projects">
    <div class="card">
      <img src="https://via.placeholder.com/300x200" alt="مشروع غذاء">
      <h3>سلة غذائية للأسرة</h3>
      <p>ساهم بـ 10 د.ك لتوفير الطعام لعائلة لاجئة.</p>
      <button>ساهم الآن</button>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/300x200" alt="مشروع التعليم">
      <h3>رعاية طالب علم</h3>
      <p>بـ 15 د.ك شهريًا، تضمن تعليم طفل لاجئ.</p>
      <button>تبرع الآن</button>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/300x200" alt="مشروع سكن">
      <h3>مأوى آمن</h3>
      <p>ساهم في بناء غرفة سكن لعائلة نازحة.</p>
      <button>شارك بالخير</button>
    </div>
  </div>
</section>

<!-- News Section -->
<section class="section">
  <h2>آخر الأخبار</h2>
  <div class="news">
    <div class="card">
      <img src="https://via.placeholder.com/300x200" alt="خبر 1">
      <h3>قافلة الإغاثة تصل للمخيمات</h3>
      <p>فريقنا وزع مساعدات عاجلة على مئات الأسر</p>
      <button>اقرأ المزيد</button>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/300x200" alt="خبر 2">
      <h3>افتتاح مدرسة جديدة</h3>
      <p>بفضل تبرعاتكم، افتتحنا مدرسة تضم 200 طالب</p>
      <button>شاهد التفاصيل</button>
    </div>
  </div>
</section>

<!-- Footer -->
<footer>
  <p>© 2025 جمعية أراكان الخيرية - جميع الحقوق محفوظة</p>
  <p>تابعنا على: فيسبوك | تويتر | إنستغرام</p>
</footer>

</body>
</html>
