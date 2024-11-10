<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>شركة مستحضرات تجميل</title>
  <style>
    /* تنسيقات عامة */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
      color: #333;
    }

    header {
      background-color: #ff8ba7;
      color: #fff;
      padding: 15px;
      text-align: center;
    }

    nav ul {
      list-style-type: none;
      padding: 0;
    }

    nav ul li {
      display: inline;
      margin: 0 15px;
    }

    nav ul li a {
      color: #fff;
      text-decoration: none;
    }

    section {
      padding: 20px;
      margin: 10px;
    }

    h2 {
      color: #ff8ba7;
    }

    .product {
      background-color: #fff;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ddd;
      border-radius: 5px;
    }

    form {
      display: flex;
      flex-direction: column;
    }

    form label, form input, form textarea, form button {
      margin: 5px 0;
    }

    button {
      background-color: #ff8ba7;
      color: white;
      border: none;
      padding: 10px;
      cursor: pointer;
      border-radius: 5px;
    }

    button:hover {
      background-color: #ff5f7f;
    }
  </style>
</head>
<body>

  <!-- رأس الموقع -->
  <header>
    <h1>شركة مستحضرات التجميل</h1>
    <nav>
      <ul>
        <li><a href="#home">الرئيسية</a></li>
        <li><a href="#products">منتجاتنا</a></li>
        <li><a href="#about">من نحن</a></li>
        <li><a href="#contact">اتصل بنا</a></li>
      </ul>
    </nav>
  </header>

  <!-- الصفحة الرئيسية -->
  <section id="home">
    <h2>مرحباً بكم في شركة مستحضرات التجميل</h2>
    <p>نقدم أفضل مستحضرات التجميل الطبيعية لإبراز جمالك.</p>
    <button onclick="exploreProducts()">استكشفي المنتجات</button>
  </section>

  <!-- المنتجات -->
  <section id="products">
    <h2>منتجاتنا</h2>
    <div class="product">
      <h3>كريم الوجه الطبيعي</h3>
      <p>مصنوع من مكونات طبيعية 100%.</p>
    </div>
    <div class="product">
      <h3>أحمر الشفاه العضوي</h3>
      <p>تركيبة لطيفة تمنحك لونًا طبيعيًا جذابًا.</p>
    </div>
  </section>

  <!-- من نحن -->
  <section id="about">
    <h2>من نحن</h2>
    <p>شركة مستحضرات التجميل تأسست لتوفير منتجات تجميل طبيعية وآمنة لجميع أنواع البشرة.</p>
  </section>

  <!-- اتصل بنا -->
  <section id="contact">
    <h2>اتصل بنا</h2>
    <form>
      <label for="name">الاسم:</label>
      <input type="text" id="name" name="name" required>
      
      <label for="email">البريد الإلكتروني:</label>
      <input type="email" id="email" name="email" required>
      
      <label for="message">رسالتك:</label>
      <textarea id="message" name="message" required></textarea>
      
      <button type="submit">أرسل</button>
    </form>
  </section>

  <script>
    function exploreProducts() {
      document.getElementById('products').scrollIntoView({ behavior: 'smooth' });
    }
  </script>
</body>
</html>
