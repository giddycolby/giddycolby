<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>個人網站</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #007BFF;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        .container {
            width: 80%;
            margin: 20px auto;
            overflow: hidden;
        }
        section {
            margin-bottom: 20px;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .profile-pic {
            display: block;
            margin: 0 auto 10px;
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        form input, form textarea {
            margin-bottom: 10px;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        form button {
            padding: 10px;
            border: none;
            background-color: #007BFF;
            color: white;
            cursor: pointer;
            border-radius: 5px;
        }
        form button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <header>
        <h1>我的個人網站</h1>
    </header>
    <div class="container">
        <section id="home">
            <h2>首頁</h2>
            <img src="profile.jpg" alt="個人照片" class="profile-pic">
            <p>你好，我是[你的名字]。歡迎來到我的個人網站！</p>
        </section>
        <section id="about">
            <h2>關於我</h2>
            <p>這裡是我的詳細自我介紹和背景信息。我是一名[你的職業或專長]，擁有多年的經驗。</p>
        </section>
        <section id="portfolio">
            <h2>作品集</h2>
            <p>以下是一些我的代表性作品：</p>
            <ul>
                <li>作品 1</li>
                <li>作品 2</li>
                <li>作品 3</li>
            </ul>
        </section>
        <section id="contact">
            <h2>聯絡方式</h2>
            <form action="mailto:your-email@example.com" method="post" enctype="text/plain">
                <input type="text" name="name" placeholder="你的名字" required>
                <input type="email" name="email" placeholder="你的電子郵件" required>
                <textarea name="message" rows="5" placeholder="你的訊息" required></textarea>
                <button type="submit">送出</button>
            </form>
            <p>或通過以下方式聯繫我：</p>
            <ul>
                <li>Email: your-email@example.com</li>
                <li><a href="https://www.linkedin.com" target="_blank">LinkedIn</a></li>
                <li><a href="https://www.twitter.com" target="_blank">Twitter</a></li>
            </ul>
        </section>
    </div>
</body>
</html>
