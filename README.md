<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <title>المستقبل القادم</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    /* تنسيق عام */
    body {
      font-family: Arial, sans-serif;
      direction: rtl;
      margin: 0;
      padding: 0;
      background-color: #f7f7f7;
    }
    header {
      background-color: #2c3e50;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #34495e;
    }
    nav a {
      color: #fff;
      padding: 14px 20px;
      text-decoration: none;
      display: block;
    }
    nav a:hover {
      background-color: #1abc9c;
    }
    .container {
      max-width: 1200px;
      margin: auto;
      padding: 20px;
    }
    .post {
      background: #fff;
      margin-bottom: 20px;
      padding: 20px;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .pricing {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
    .plan {
      background: #fff;
      margin: 10px;
      padding: 20px;
      border: 1px solid #ddd;
      border-radius: 5px;
      flex: 1 1 300px;
      text-align: center;
    }
    .plan h3 {
      margin-top: 0;
    }
    .plan p {
      font-size: 24px;
      margin: 10px 0;
    }
    .subscribe-btn {
      background-color: #1abc9c;
      color: #fff;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }
    .subscribe-btn:hover {
      background-color: #16a085;
    }
    footer {
      background-color: #2c3e50;
      color: #fff;
      text-align: center;
      padding: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>المستقبل القادم</h1>
    <p>طريق النجاح يبدأ هنا مع المشاركات اليومية والنصائح القيمة</p>
  </header>
  <nav>
    <a href="#home">الرئيسية</a>
    <a href="#posts">المشاركات</a>
    <a href="#tips">النصائح</a>
    <a href="#subscribe">الاشتراكات</a>
    <a href="#contact">اتصل بنا</a>
  </nav>
  
  <!-- قسم المشاركات اليومية -->
  <div class="container" id="home">
    <section>
      <h2>أحدث المشاركات</h2>
      <div class="post">
        <h3>عنوان المشاركة 1</h3>
        <p>هذا نص تجريبي للمشاركة اليومية التي تساعدك على تحقيق النجاح. تابعنا لمزيد من المشاركات الملهمة.</p>
      </div>
      <div class="post">
        <h3>عنوان المشاركة 2</h3>
        <p>نصيحة اليوم: ابحث عن فرص جديدة وكن دائماً مستعداً للتعلم من التجارب اليومية.</p>
      </div>
    </section>
  </div>
  
  <!-- قسم النصائح اليومية -->
  <div class="container" id="tips">
    <section>
      <h2>نصائح النجاح اليومية</h2>
      <div class="post">
        <h3>نصيحة 1</h3>
        <p>ابدأ يومك بتحديد أهداف واضحة وانطلق لتحقيقها.</p>
      </div>
      <div class="post">
        <h3>نصيحة 2</h3>
        <p>تعلم من أخطائك واعتبرها فرصاً للنمو والتطوير.</p>
      </div>
    </section>
  </div>
  
  <!-- قسم الاشتراكات -->
  <div class="container" id="subscribe">
    <section>
      <h2>خطط الاشتراك</h2>
      <div class="pricing">
        <div class="plan">
          <h3>اشتراك شهري</h3>
          <p>$10</p>
          <a href="#" class="subscribe-btn">اشترك الآن</a>
        </div>
        <div class="plan">
          <h3>اشتراك سنوي</h3>
          <p>$100</p>
          <a href="#" class="subscribe-btn">اشترك الآن</a>
        </div>
        <div class="plan">
          <h3>اشتراك مدى الحياة</h3>
          <p>$400</p>
          <a href="#" class="subscribe-btn">اشترك الآن</a>
        </div>
      </div>
      <p>ملحوظة: عند النقر على "اشترك الآن" سيتم تحويلك إلى صفحة الدفع الآمنة. (للتكامل مع بوابات الدفع، ستحتاج إلى إعداد API خاص مثل Stripe أو PayPal)</p>
    </section>
  </div>
  
  <!-- قسم اتصل بنا -->
  <div class="container" id="contact">
    <section>
      <h2>اتصل بنا</h2>
      <p>إذا كان لديك أي استفسار أو ملاحظة، يرجى إرسال رسالة عبر البريد الإلكتروني: <a href="mailto:info@almustaqbalqadem.com">info@almustaqbalqadem.com</a></p>
    </section>
  </div>
  
  <footer>
    <p>&copy; 2025 المستقبل القادم. جميع الحقوق محفوظة.</p>
  </footer>
</body>
</html>
