# Chorphilia
<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>斐亞文化藝術 Chorphilia 演出資訊</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            background-color: #fcfcfc;
            color: #333;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 40px 20px;
            margin: 0;
        }
        .container {
            max-width: 600px;
            width: 100%;
        }
        header {
            text-align: center;
            margin-bottom: 40px;
        }
        h1 { font-size: 1.6rem; color: #1a1a1a; margin-bottom: 8px; letter-spacing: 1px; }
        p { color: #666; font-size: 0.95rem; }
        
        /* 活動卡片樣式 */
        .event-card {
            background: white;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 10px 25px rgba(0,0,0,0.05);
            margin-bottom: 35px;
            transition: transform 0.3s ease;
            border: 1px solid #eee;
        }
        .event-card:hover { transform: translateY(-5px); }
        .event-image {
            width: 100%;
            height: auto;
            display: block;
            background-color: #f0f0f0;
        }
        .event-info { padding: 25px; text-align: center; }
        .event-title { font-weight: bold; margin-bottom: 20px; font-size: 1.15rem; line-height: 1.5; color: #222; }
        
        /* 藍綠黃漸層按鈕 */
        .buy-btn {
            display: inline-block;
            /* 漸層顏色：藍綠 -> 亮黃 */
            background: linear-gradient(135deg, #1abc9c 0%, #f1c40f 100%);
            color: #fff;
            text-decoration: none;
            padding: 14px 45px;
            border-radius: 50px;
            font-weight: bold;
            font-size: 1.1rem;
            letter-spacing: 1px;
            box-shadow: 0 4px 15px rgba(26, 188, 156, 0.3);
            transition: all 0.3s ease;
            text-shadow: 0px 1px 2px rgba(0,0,0,0.1);
        }
        
        .buy-btn:hover {
            background: linear-gradient(135deg, #16a085 0%, #d4ac0d 100%);
            box-shadow: 0 6px 20px rgba(26, 188, 156, 0.5);
            transform: scale(1.05);
        }

        footer { margin-top: 50px; font-size: 0.85rem; color: #aaa; text-align: center; padding-bottom: 20px; }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>斐亞文化藝術 Chorphilia</h1>
            <p>最新演出行程與購票資訊</p>
        </header>

        <div class="event-card">
            <img src="https://via.placeholder.com/600x350?text=Twelve+Nights" alt="胡志龍" class="event-image">
            <div class="event-info">
                <div class="event-title">胡志龍的十二夜<br>Twelve Nights – Chih-long HU 2026 Piano Recitals</div>
                <a href="https://www.opentix.life/event/2009557730338074625" target="_blank" class="buy-btn">立即購票</a>
            </div>
        </div>

        <div class="event-card">
            <img src="https://via.placeholder.com/600x350?text=Path+of+Life" alt="林鈺音" class="event-image">
            <div class="event-info">
                <div class="event-title">生命的軌跡Path of Life – 2026 林鈺音鋼琴獨奏會</div>
                <a href="https://www.opentix.life/event/2011269109732937728" target="_blank" class="buy-btn">立即購票</a>
            </div>
        </div>

        <div class="event-card">
            <img src="https://via.placeholder.com/600x350?text=Buddhist+Song" alt="妙法之歌" class="event-image">
            <div class="event-info">
                <div class="event-title">妙法之歌 & 鋼琴協奏之旅</div>
                <a href="https://www.opentix.life/event/2012854119319642113" target="_blank" class="buy-btn">立即購票</a>
            </div>
        </div>

        <div class="event-card">
            <img src="https://via.placeholder.com/600x350?text=Sam+Armstrong" alt="Sam Armstrong" class="event-image">
            <div class="event-info">
                <div class="event-title">音緣際會 Sam Armstrong x Huang Shao Wei 長號音樂會</div>
                <a href="https://www.opentix.life/event/2017506956858097665" target="_blank" class="buy-btn">立即購票</a>
            </div>
        </div>

        <footer>
            &copy; 2026 斐亞文化藝術 Chorphilia
        </footer>
    </div>

</body>
</html>
