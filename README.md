## Hi there 👋

<!--
**BrandoShoes/Brandoshoes** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
body {
    font-family: Arial, sans-serif;
    background-color: #f9f9f9;
    margin: 0;
    padding: 0;
    color: #333;
}

header {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 20px;
}

h1 {
    margin: 0;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 30px;
}

h2 {
    color: #333;
}

a {
    color: #0066cc;
    text-decoration: none;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
}

form {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    width: 100%;
    max-width: 600px;
    margin: 0 auto;
}

input, textarea {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    border-radius: 5px;
    border: 1px solid #ccc;
}

button {
    background-color: #4CAF50;
    color: white;
    padding: 10px 15px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #45a049;
}<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تولیدی صمدزاده</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>تولیدی صمدزاده</h1>
        <p>بهترین کفش‌ها برای شما</p>
    </header>

    <main>
        <section id="about">
            <h2>درباره ما</h2>
            <p>ما یک تولیدی کفش با نام "صمدزاده" هستیم و بهترین کفش‌های روز دنیا را تولید می‌کنیم. هدف ما تولید کفش‌های با کیفیت و متناسب با نیاز مشتریان است.</p>
        </section>

        <section id="contact">
            <h2>تماس با ما</h2>
            <p>شماره تماس: <a href="tel:+989033667146">+989033667146</a></p>
            <p>آدرس: باغ سپهسالار کوچه محسن مظفری پلاک 43 واحد 6</p>
            <p>واتساپ: <a href="https://whatsapp.com/channel/0029VakN4Q1DzgT5guiEMx0n">لینک واتساپ</a></p>
            <p>اینستاگرام: <a href="https://www.instagram.com/brandoshoes2022?igsh=ZGExNHFmb2h0OHQ2">brandoshoes2022</a></p>
            <p>تلگرام: <a href="https://t.me/Brandogallery">Brandogallery</a></p>
        </section>

        <section id="order-form">
            <h2>فرم ثبت سفارش</h2>
            <form action="submit_order.php" method="POST">
                <label for="name">نام و نام خانوادگی:</label>
                <input type="text" id="name" name="name" required><br><br>

                <label for="phone">شماره تماس:</label>
                <input type="tel" id="phone" name="phone" required><br><br>

                <label for="shoe-type">نوع کفش و سایز:</label>
                <input type="text" id="shoe-type" name="shoe-type" required><br><br>

                <label for="address">آدرس تحویل:</label>
                <textarea id="address" name="address" required></textarea><br><br>

                <button type="submit">ثبت سفارش</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 توليدي صمدزاده. تمامی حقوق محفوظ است.</p>
    </footer>
</body>
</html>
