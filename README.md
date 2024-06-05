<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>黑盒子維修中心</title>
    <style>
        body {
            font-family: 'Noto Sans', sans-serif;
            color: #333;
            background-color: #f5f5f5;
            margin: 0;
            padding: 0;
        }
        header, footer {
            background-color: #eee;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 10px;
            background-color: #ddd;
        }
        nav a {
            text-decoration: none;
            color: #333;
        }
        .container {
            padding: 20px;
        }
        .section-title {
            text-align: center;
            margin-bottom: 20px;
        }
        .products, .services, .locations, .activities {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .card {
            background-color: #fff;
            border: 1px solid #ccc;
            padding: 20px;
            width: 300px;
            box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.1);
        }
        iframe {
            width: 100%;
            border: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>黑盒子維修中心</h1>
        <p>專業手機與筆記型電腦維修服務</p>
    </header>
    <nav>
        <a href="#home">首頁</a>
        <a href="#services">服務項目</a>
        <a href="#products">商品販售</a>
        <a href="#locations">服務據點</a>
        <a href="#activities">活動資訊</a>
        <a href="#contact">聯絡我們</a>
        <a href="#about">關於我們</a>
    </nav>
    <div id="home" class="container">
        <h2 class="section-title">歡迎來到黑盒子維修中心</h2>
        <p>我們提供專業的手機與筆記型電腦維修服務，讓您的設備煥然一新。</p>
    </div>
    <div id="services" class="container">
        <h2 class="section-title">服務項目</h2>
        <div class="services">
            <div class="card">
                <h3>手機維修</h3>
                <p>專業的手機維修服務，涵蓋各種品牌和型號。</p>
            </div>
            <div class="card">
                <h3>筆記型電腦維修</h3>
                <p>提供全面的筆記型電腦維修服務，確保您的設備運行順暢。</p>
            </div>
            <div class="card">
                <h3>其他服務</h3>
                <p>包括配件更換和軟體升級等服務，滿足您的多樣需求。</p>
            </div>
        </div>
    </div>
    <div id="products" class="container">
        <h2 class="section-title">商品販售</h2>
        <div class="products">
            <div class="card">
                <h3>產品 1</h3>
                <p>產品 1 的簡短描述和價格。</p>
            </div>
            <div class="card">
                <h3>產品 2</h3>
                <p>產品 2 的簡短描述和價格。</p>
            </div>
            <div class="card">
                <h3>產品 3</h3>
                <p>產品 3 的簡短描述和價格。</p>
            </div>
        </div>
    </div>
    <div id="locations" class="container">
        <h2 class="section-title">服務據點</h2>
        <div class="locations">
            <div class="card">
                <h3>分店位置</h3>
                <iframe src="https://www.google.com/maps/embed?..."></iframe>
                <p>分店的地址和聯絡方式。</p>
            </div>
            <div class="card">
                <h3>即時評論</h3>
                <iframe src="https://www.google.com/maps/embed/reviews?..."></iframe>
            </div>
        </div>
    </div>
    <div id="activities" class="container">
        <h2 class="section-title">活動資訊</h2>
        <div class="activities">
            <div class="card">
                <h3>最新活動</h3>
                <p>介紹近期的促銷活動和特別優惠。</p>
            </div>
            <div class="card">
                <h3>歷史活動</h3>
                <p>過往活動的簡單回顧和圖片展示。</p>
            </div>
        </div>
    </div>
    <div id="contact" class="container">
        <h2 class="section-title">聯絡我們</h2>
        <form>
            <label for="name">姓名：</label>
            <input type="text" id="name" name="name" required><br>
            <label for="email">電郵：</label>
            <input type="email" id="email" name="email" required><br>
            <label for="message">訊息：</label>
            <textarea id="message" name="message" required></textarea><br>
            <button type="submit">送出</button>
        </form>
        <p>社交媒體連結：</p>
        <a href="https://www.facebook.com/BlackBoxRepairCenter">Facebook</a> | 
        <a href="https://line.me/ti/p/BlackBoxRepairCenter">Line</a>
    </div>
    <div id="about" class="container">
        <h2 class="section-title">關於我們</h2>
        <p>公司簡介：介紹公司的歷史、願景和使命。</p>
        <p>團隊介紹：我們
