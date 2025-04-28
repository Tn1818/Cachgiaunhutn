<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="google-site-verification" content="AUSsFethPERa13ZSx3quBLi9cAgEXBwlE6_JC0u9bCA" />
    <title>Trang Web Nhấp Nháy</title>

    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f4f4f4;
        }

        .blinking-text {
            font-size: 3em;
            font-weight: bold;
            color: #333;
            animation: blink-animation 1s steps(5, start) infinite;
        }

        @keyframes blink-animation {
            0%, 100% {
                opacity: 1;
            }
            50% {
                opacity: 0;
            }
        }
    </style>
</head>
<body>

    <div class="blinking-text">Có cái nịt mà seach</div>

</body>
</html>
