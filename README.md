<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile của Tôi</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .card {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(15px);
            padding: 40px;
            border-radius: 20px;
            width: 350px;
            text-align: center;
            box-shadow: 0 15px 35px rgba(0,0,0,0.2);
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-10px);
        }

        .avatar {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 4px solid white;
            object-fit: cover;
            margin-bottom: 20px;
        }

        h1 {
            font-size: 24px;
            font-weight: 600;
        }

        .title {
            font-size: 14px;
            opacity: 0.8;
            margin-bottom: 20px;
        }

        .bio {
            font-size: 14px;
            margin-bottom: 25px;
            line-height: 1.6;
        }

        .btn {
            display: inline-block;
            padding: 10px 20px;
            margin: 5px;
            border-radius: 30px;
            background: white;
            color: #764ba2;
            text-decoration: none;
            font-size: 14px;
            font-weight: 500;
            transition: 0.3s;
        }

        .btn:hover {
            background: #ddd;
        }

        .socials {
            margin-top: 20px;
        }

        .socials a {
            color: white;
            margin: 0 10px;
            font-size: 18px;
            text-decoration: none;
            transition: 0.3s;
        }

        .socials a:hover {
            color: #ffd369;
        }
    </style>
</head>
<body>

    <div class="card">
        <img src="https://i.pravatar.cc/150" alt="Avatar" class="avatar">
        <h1>Nguyễn Văn A</h1>
        <p class="title">Web Developer | Designer</p>
        <p class="bio">
            Xin chào! Tôi là một lập trình viên yêu thích thiết kế giao diện và phát triển web.
            Tôi thích học công nghệ mới và xây dựng sản phẩm sáng tạo.
        </p>

        <a href="#" class="btn">Liên hệ</a>
        <a href="#" class="btn">Portfolio</a>

        <div class="socials">
            <a href="#">Facebook</a>
            <a href="#">Github</a>
            <a href="#">LinkedIn</a>
        </div>
    </div>

</body>
</html>
