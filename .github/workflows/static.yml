<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Бесконечные сердечки</title>
    <style>
        body {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }
        .heart {
            width: 50px;
            height: 50px;
            background-color: red;
            clip-path: polygon(50% 0%, 100% 50%, 50% 100%, 0% 50%);
            margin: 10px;
        }
    </style>
</head>
<body>
    <script>
        setInterval(() => {
            const heart = document.createElement('div');
            heart.className = 'heart';
            document.body.appendChild(heart);
        }, 200);
    </script>
</body>
</html>
