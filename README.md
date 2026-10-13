<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>自転車 右折ウィンカー</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>自転車 右折ウィンカー</title>
    <style>
        /* 画面全体を黒背景にしてスクロールや拡大を禁止 */
        body, html {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            background-color: #000000;
            overflow: hidden;
            position: fixed;
        }

        /* アニメーション全体のコンテナ（横に広く配置） */
        .marquee-container {
            display: flex;
            width: 200%;
            height: 100%;
            position: absolute;
            top: 0;
            left: 0;
            align-items: center;
            animation: scrollLoop 3s linear infinite;
        }

        /* トラック（画像を等間隔に並べる） */
        .marquee-track {
            display: flex;
            align-items: center;
            justify-content: space-around;
            width: 50%;
            height: 100%;
        }

        /* 指の画像のサイズと見栄えの調整 */
        .item img {
            height: 35vh; /* 画面の高さの35%に大きく表示 */
            width: auto;
            object-fit: contain;
        }

        /* 右方向へ途切れなく流すループアニメーション */
        @keyframes scrollLoop {
            0% {
                transform: translateX(-50%);
            }
            100% {
                transform: translateX(0%);
            }
        }
    </style>
</head>
<body>

    <div class="marquee-container">
        <!-- 1つ目のグループ -->
        <div class="marquee-track">
            <div class="item">
                <img src="finger.png" alt="Finger">
            </div>
            <div class="item">
                <img src="finger.png" alt="Finger">
            </div>
        </div>
        <!-- 継ぎ目をなくすための複製グループ -->
        <div class="marquee-track">
            <div class="item">
                <img src="finger.png" alt="Finger">
            </div>
            <div class="item">
                <img src="finger.png" alt="Finger">
            </div>
        </div>
    </div>

</body>
</html>
            width: 100%;<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>自転車 右折ウィンカー</title>
    <style>
        /* 画面全体を黒背景にしてスクロールを禁止 */
        body, html {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            background-color: #000000;
            overflow: hidden;
            position: fixed;
        }

        /* アニメーション全体のコンテナ */
        .marquee-container {
            display: flex;
            width: 200%;
            height: 100%;
            position: absolute;
            top: 0;
            left: 0;
            animation: scrollLoop 4s linear infinite;
        }

        /* 各レーン（行）のスタイル */
        .marquee-track {
            display: flex;
            align-items: center;
            justify-content: space-around;
            width: 50%;
            height: 100%;
        }

        /* アイテム（画像と矢印）のスタイル */
        .item {
            display: flex;
            align-items: center;
            gap: 20px;
        }

        /* finger.png のサイズ調整（スマホ画面に合わせて大きく表示） */
        .item img {
            height: 25vh; /* 画面の高さの25%に調整 */
            width: auto;
            object-fit: contain;
        }

        /* ➡ 矢印のスタイル */
        .arrow {
            font-size: 20vh; /* 画像とバランスを取る大きさ */
            color: #00bfff;  /* 夜間に視認性の高い鮮やかなシアン/青系 */
            font-weight: bold;
        }

        /* 右方向へ滑らかに流すループアニメーション */
        @keyframes scrollLoop {
            0% {
                transform: translateX(-50%);
            }
            100% {
                transform: translateX(0%);
            }
        }
    </style>
</head>
<body>

    <div class="marquee-container">
        <!-- 1つ目のトラック -->
        <div class="marquee-track">
            <div class="item">
                <img src="finger.png" alt="Finger">
                <span class="arrow">➡</span>
            </div>
            <div class="item">
                <img src="finger.png" alt="Finger">
                <span class="arrow">➡</span>
            </div>
        </div>
        <!-- ループを途切れさせないための複製トラック -->
        <div class="marquee-track">
            <div class="item">
                <img src="finger.png" alt="Finger">
                <span class="arrow">➡</span>
            </div>
            <div class="item">
                <img src="finger.png" alt="Finger">
                <span class="arrow">➡</span>
            </div>
        </div>
    </div>

</body>
</html>
            height: 100%;
            background-color: #000000;
            overflow: hidden;
            position: fixed;
        }
        .marquee-container {
            display: flex;
            width: 200%;
            height: 100%;
            position: absolute;
            top: 0;
            left: 0;
            animation: scrollLoop 4s linear infinite;
        }
        .marquee-track {
            display: flex;
            align-items: center;
            justify-content: space-around;
            width: 50%;
            height: 100%;
        }
        .item {
            display: flex;
            align-items: center;
        }
        .item img {
            height: 30vh;
            width: auto;
            object-fit: contain;
        }
        @keyframes scrollLoop {
            0% { transform: translateX(-50%); }
            100% { transform: translateX(0%); }
        }
    </style>
</head>
<body>
    <div class="marquee-container">
        <div class="marquee-track">
            <div class="item">
                <img src="IMG_6774.jpeg" alt="Finger">
            </div>
            <div class="item">
                <img src="IMG_6774.jpeg" alt="Finger">
            </div>
        </div>
        <div class="marquee-track">
            <div class="item">
                <img src="IMG_6774.jpeg" alt="Finger">
            </div>
            <div class="item">
                <img src="IMG_6774.jpeg" alt="Finger">
            </div>
        </div>
    </div>
</body>
</html>
