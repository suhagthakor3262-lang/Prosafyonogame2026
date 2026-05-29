<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    
    <!-- Aapka Official Website Logo (Favicon Icon) -->
    <link rel="icon" type="image/png" href="https://i.ibb.co/SXrcFVvz/file-000000002aa872089a44603a2278ac14.png">
    <link rel="apple-touch-icon" href="https://i.ibb.co/SXrcFVvz/file-000000002aa872089a44603a2278ac14.png">

    <!-- SEO Meta Tags -->
    <meta name="description" content="Download best Rummy, Slots, and Casino games at ProSafe Bet. Latest APKs available.">
    <meta name="keywords" content="Rummy 77, EVER 777, Slots Spin, Jaiho Arcade, Yono Rummy, Spin 101, ProSafe Bet, Online Casino Games India, Best Rummy APK">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ProSafe Bet - Expert Recommended Games</title>
    
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
        body { background-color: #f5f5f5; color: #333; display: flex; flex-direction: column; min-height: 100vh; }
        
        .wrapper { width: 100%; max-width: 600px; margin: 0 auto; display: flex; flex-direction: column; flex: 1; position: relative; }

        /* Header Layout Styling */
        header { 
            background-color: #1a2229; 
            padding: 12px 15px; 
            display: flex; 
            justify-content: space-between; 
            align-items: center; 
            position: sticky; 
            top: 0; 
            z-index: 100;
            width: 100%;
        }
        
        .logo-container { display: flex; align-items: center; gap: 8px; }
        .logo-img { width: 35px; height: 35px; object-fit: contain; border-radius: 50%; background: #fff; padding: 2px; }
        .logo-text { font-size: 20px; font-weight: bold; letter-spacing: 0.5px; }
        .logo-text .wht { color: #ffffff; }
        .logo-text .grn { color: #4caf50; }
        .logo-text .ylw { color: #ffeb3b; }

        .three-dots { color: white; font-size: 24px; cursor: pointer; padding: 0 5px; user-select: none; }

        /* Sidebar Floating Buttons Area (As per Image 1000165499.png) */
        .floating-sidebar {
            position: fixed;
            right: calc(50% - 290px); /* Centers right offset precisely to wrapper boundary */
            bottom: 80px;
            display: flex;
            flex-direction: column;
            gap: 12px;
            z-index: 150;
        }
        
        @media (max-width: 620px) {
            .floating-sidebar { right: 15px; }
        }

        .float-btn {
            width: 44px;
            height: 44px;
            border-radius: 8px;
            display: flex;
            justify-content: center;
            align-items: center;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
            cursor: pointer;
            transition: transform 0.2s ease, opacity 0.3s ease;
            text-decoration: none;
        }
        
        .float-tg { background-color: #0088cc; }
        .float-top { background-color: #72a0c1; display: none; border: none; font-size: 11px; font-weight: bold; color: white; flex-direction: column; line-height: 1.1; }
        .float-btn:active { transform: scale(0.9); }
        .float-btn img { width: 26px; height: 26px; object-fit: contain; }

        /* Dropdown Modal Container Layout */
        .menu-overlay { position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0, 0, 0, 0.5); display: none; z-index: 200; justify-content: center; align-items: center; }
        .menu-content { background: white; width: 85%; max-width: 340px; border-radius: 12px; padding: 20px; box-shadow: 0 5px 15px rgba(0,0,0,0.3); position: relative; animation: fadeIn 0.3s ease; }
        @keyframes fadeIn { from { opacity: 0; transform: scale(0.9); } to { opacity: 1; transform: scale(1); } }
        .menu-header { display: flex; justify-content: space-between; align-items: center; border-bottom: 1px solid #eee; padding-bottom: 10px; margin-bottom: 15px; }
        .close-btn { font-size: 22px; cursor: pointer; color: #888; }
        .menu-item { margin-bottom: 15px; }
        .menu-link-btn { display: inline-block; text-decoration: none; color: #1e88e5; font-weight: bold; font-size: 16px; margin-bottom: 5px; }
        .menu-text { font-size: 13px; color: #555; line-height: 1.4; }
        .warning-text { color: #d32f2f; font-weight: 500; }

        /* Search Module Elements */
        .search-container { padding: 15px 15px 5px 15px; width: 100%; }
        .search-box { width: 100%; padding: 12px 18px; border: 1px solid #ccc; border-radius: 8px; font-size: 15px; outline: none; }
        
        /* Telegram Header Banner Ticker */
        .telegram-ticker { background-color: #0088cc; color: white; padding: 9px 0; overflow: hidden; white-space: nowrap; font-size: 13px; font-weight: bold; margin: 10px 15px; border-radius: 6px; }
        .telegram-ticker marquee a { color: white; text-decoration: none; }

        /* Horizontal Custom Slider Section (As per Image 1000165500.jpg) */
        .slider-section-heading { font-size: 20px; font-weight: 600; color: #222; padding: 15px 15px 5px 15px; text-align: left; }
        .horizontal-slider { display: flex; gap: 14px; overflow-x: auto; padding: 5px 15px 20px 15px; scroll-behavior: smooth; width: 100%; -webkit-overflow-scrolling: touch; }
        .horizontal-slider::-webkit-scrollbar { display: none; } /* Hide track lines */
        
        .slider-card { flex: 0 0 145px; background: white; border-radius: 12px; padding: 15px 10px; text-align: center; box-shadow: 0 3px 8px rgba(0,0,0,0.06); position: relative; display: flex; flex-direction: column; align-items: center; }
        .slider-card .badge { position: absolute; top: -5px; right: -5px; background: #ff3d00; color: white; font-size: 10px; font-weight: bold; padding: 2px 6px; border-radius: 10px; box-shadow: 0 2px 4px rgba(0,0,0,0.15); }
        .slider-img-wrapper { width: 80px; height: 80px; margin-bottom: 8px; }
        .slider-img { width: 100%; height: 100%; object-fit: cover; border-radius: 50%; }
        .slider-card .rating { color: #4caf50; font-size: 13px; font-weight: bold; margin-bottom: 5px; }
        .slider-name { font-size: 13px; font-weight: 600; color: #333; text-transform: uppercase; margin-bottom: 10px; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; width: 100%; }
        .slider-btn { display: block; width: 100%; padding: 7px 0; background-color: #0084ff; color: white; text-decoration: none; font-weight: bold; border-radius: 6px; font-size: 13px; text-align: center; }

        /* Vertical Sections Architecture */
        .section-title { text-align: center; margin-top: 15px; font-size: 24px; color: #222; font-weight: 500; }
        .section-subtitle { text-align: center; color: #666; font-size: 13px; margin-top: 8px; margin-bottom: 20px; padding: 0 20px; line-height: 1.4; }

        /* Filter Selector Controls - Only 2 Buttons Option Fixed */
        .tabs-container { display: flex; justify-content: center; gap: 12px; margin-bottom: 20px; padding: 0 15px; width: 100%; }
        .tab-btn { flex: 1; max-width: 150px; padding: 11px 0; background-color: #e0e0e0; border-radius: 8px; color: #444; font-weight: bold; font-size: 15px; border: none; cursor: pointer; text-align: center; }
        .tab-btn.active { background-color: white; color: #1a2229; box-shadow: 0 3px 6px rgba(0,0,0,0.1); }
        
        /* Main Grid Architecture */
        .games-grid { display: grid; grid-template-columns: repeat(2, 1fr); gap: 14px; padding: 0 15px 30px 15px; width: 100%; }
        .game-card { background: white; border-radius: 12px; padding: 18px 12px; text-align: center; box-shadow: 0 3px 6px rgba(0,0,0,0.04); display: flex; flex-direction: column; align-items: center; }
        
        .hot-badge { background-color: #ff3d00; color: white; font-size: 10px; font-weight: bold; padding: 2px 7px; border-radius: 20px; margin-bottom: 8px; text-transform: uppercase; }
        .game-image-wrapper { width: 100px; height: 100px; margin-bottom: 10px; display: flex; justify-content: center; align-items: center; }
        .game-img { width: 100%; height: 100%; object-fit: cover; border-radius: 50%; }
        .rating { color: #4caf50; font-size: 13px; font-weight: bold; margin-bottom: 6px; display: flex; align-items: center; gap: 3px; }
        .game-name { font-size: 13px; font-weight: 600; color: #222; margin-bottom: 12px; height: 18px; overflow: hidden; text-transform: uppercase; }
        
        .play-btn { display: block; width: 100%; padding: 9px 0; background-color: #e3f2fd; color: #1e88e5; text-decoration: none; font-weight: bold; border-radius: 6px; font-size: 13px; text-align: center; }
        
        footer { background-color: #1a2229; color: #999; text-align: center; padding: 15px; font-size: 13px; border-top: 2px solid #2e3942; width: 100%; }

        @media (max-width: 360px) {
            .games-grid { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>

    <div class="wrapper" id="topContainer">

        <!-- Sidebar Components Container Layout -->
        <div class="floating-sidebar">
            <!-- Telegram Floating Icon -->
            <a href="https://t.me/invitnew" target="_blank" class="float-btn float-tg" title="Join Telegram">
                <img src="https://upload.wikimedia.org/wikipedia/commons/8/82/Telegram_logo.svg" alt="Telegram">
            </a>
            <!-- Back To Top Element -->
            <button class="float-btn float-top" id="scrollTopBtn" onclick="scrollToTop()">
                <span style="font-size:16px;">▲</span>TOP
            </button>
        </div>

        <!-- Header Wrapper with Official Logo Link -->
        <header>
            <div class="logo-container">
                <img src="https://i.ibb.co/SXrcFVvz/file-000000002aa872089a44603a2278ac14.png" alt="ProSafe Logo" class="logo-img">
                <div class="logo-text">
                    <span class="wht">Pro</span><span class="grn">Safe</span><span class="ylw">Bet</span>
                </div>
            </div>
            <div class="three-dots" onclick="toggleMenu(true)">&#8942;</div>
        </header>

        <!-- Dropdown Dialog Navigation Overlay -->
        <div class="menu-overlay" id="menuOverlay" onclick="toggleMenu(false)">
            <div class="menu-content" onclick="event.stopPropagation()">
                <div class="menu-header">
                    <h3 style="font-size: 18px; color: #1a2229;">Menu Options</h3>
                    <span class="close-btn" onclick="toggleMenu(false)">&times;</span>
                </div>
                <div class="menu-item">
                    <a href="#" class="menu-link-btn" onclick="goHome()">🏠 Home</a>
                    <p class="menu-text">Go back to the main gaming area.</p>
                </div>
                <div class="menu-item">
                    <a href="https://t.me/invitnew" target="_blank" class="menu-link-btn">📞 Contact (Telegram)</a>
                    <p class="menu-text">Latest update or free promo code join telegram channel.</p>
                </div>
                <div class="menu-item">
                    <span class="menu-link-btn" style="color:#222; cursor:default;">ℹ About Us</span>
                    <p class="menu-text warning-text">Warning ⚠️: This game involves financial risk. Restricted for 18+ players only. Please play responsibly.</p>
                </div>
            </div>
        </div>

        <!-- Search Container Context Input -->
        <div class="search-container">
            <input type="text" id="searchBox" class="search-box" placeholder="What you want to search ?" oninput="filterGames()">
        </div>

        <!-- Marquee Notification Banner Link -->
        <div class="telegram-ticker">
            <marquee behavior="scroll" direction="left" scrollamount="5">
                <a href="https://t.me/invitnew" target="_blank">📢 Join Our Official Telegram Channel For Daily Updates! Click Here: https://t.me/invitnew 🚀</a>
            </marquee>
        </div>

        <!-- Horizontal Scroll Section (As per Image 1000165500.jpg) -->
        <div class="slider-section-heading">Recommended by our experts</div>
        <div class="horizontal-slider">
            <!-- Game 1 -->
            <div class="slider-card"><div class="badge">HOT</div><div class="slider-img-wrapper"><img src="https://i.ibb.co/G4xVYT3V/IMG-20260529-085328-640.jpg" class="slider-img"></div><div class="rating">★ 10</div><div class="slider-name">Rummy 77</div><a href="https://rummy77a.vip/?code=F3VYLW5Y4BJ&t=1777381755" class="slider-btn">Play</a></div>
            <!-- Game 2 -->
            <div class="slider-card"><div class="badge">HOT</div><div class="slider-img-wrapper"><img src="https://i.ibb.co/Q3C16fb8/IMG-20260529-085225-981.jpg" class="slider-img"></div><div class="rating">★ 10</div><div class="slider-name">EVER 777</div><a href="https://EVER777A4.COM/?code=Y9AW9K3UAJ7&t=1777382555" class="slider-btn">Play</a></div>
            <!-- Game 3 -->
            <div class="slider-card"><div class="badge">HOT</div><div class="slider-img-wrapper"><img src="https://i.ibb.co/Sw5jz8d4/IMG-20260529-085855-118.jpg" class="slider-img"></div><div class="rating">★ 10</div><div class="slider-name">slots spin</div><a href="https://slotsspinp.com/?code=XJBS8FF579V&t=1777383614" class="slider-btn">Play</a></div>
            <!-- Game 4 -->
            <div class="slider-card"><div class="badge">HOT</div><div class="slider-img-wrapper"><img src="https://i.ibb.co/zT56hbGh/IMG-20260528-170118-181.jpg" class="slider-img"></div><div class="rating">★ 10</div><div class="slider-name">jaiho arcade</div><a href="https://jaihoarcade22.com/?code=AZD2DHWRSRG&t=1779962766" class="slider-btn">Play</a></div>
            <!-- Game 5 -->
            <div class="slider-card"><div class="badge">HOT</div><div class="slider-img-wrapper"><img src="https://i.ibb.co/mFtZ60Ft/IMG-20260528-170044-119.jpg" class="slider-img"></div><div class="rating">★ 10</div><div class="slider-name">jaiho spin</div><a href="https://dwjaihospin.com/?code=LDXRA3KF&t=1779962638" class="slider-btn">Play</a></div>
            <!-- Game 6 -->
            <div class="slider-card"><div class="badge">HOT</div><div class="slider-img-wrapper"><img src="https://i.ibb.co/gMxqcQCG/IMG-20260528-165950-648.jpg" class="slider-img"></div><div class="rating">★ 10</div><div class="slider-name">Rummy Ludo</div><a href="https://rummyludoapk10.com/?code=UWPFGX7U741&t=1779962548" class="slider-btn">Play</a></div>
            <!-- Game 7 -->
            <div class="slider-card"><div class="badge">HOT</div><div class="slider-img-wrapper"><img src="https://i.ibb.co/kVhqgcBS/IMG-20260528-165912-402.jpg" class="slider-img"></div><div class="rating">★ 10</div><div class="slider-name">Maha game</div><a href="https://in-mahagames.com/?code=S3MA7YM89KY&t=1779962492" class="slider-btn">Play</a></div>
            <!-- Game 8 -->
            <div class="slider-card"><div class="badge">HOT</div><div class="slider-img-wrapper"><img src="https://i.ibb.co/HpGCKDhf/IMG-20260528-165827-292.jpg" class="slider-img"></div><div class="rating">★ 10</div><div class="slider-name">Yes spin</div><a href="https://www.yesspinkkk.com/?code=47TB7555QVT&t=1779962440" class="slider-btn">Play</a></div>
            <!-- Game 9 -->
            <div class="slider-card"><div class="badge">HOT</div><div class="slider-img-wrapper"><img src="https://i.ibb.co/W4RkkgnW/IMG-20260528-165717-352.jpg" class="slider-img"></div><div class="rating">★ 10</div><div class="slider-name">Yono Slots</div><a href="https://www.uonoslots.com/?code=PJBD7UBTP3U&t=1779962287" class="slider-btn">Play</a></div>
            <!-- Game 10 -->
            <div class="slider-card"><div class="badge">HOT</div><div class="slider-img-wrapper"><img src="https://i.ibb.co/wF6g121J/IMG-20260528-165432-914.jpg" class="slider-img"></div><div class="rating">★ 10</div><div class="slider-name">Rummy 888</div><a href="https://rummy888vip34.com/?code=TPUC9F7DFYH&t=1779962155" class="slider-btn">Play</a></div>
        </div>

        <!-- Headline Titles Text Blocks -->
        <h2 class="section-title">New on Game</h2>
        <p class="section-subtitle">Discover what's new on Game and enjoy the best new game.</p>

        <!-- Toggle Controls Tabs Grid Container Layout -->
        <div class="tabs-container">
            <button class="tab-btn active" id="btn-casino" onclick="changeTab('casino')">Casinos</button>
            <button class="tab-btn" id="btn-hot" onclick="changeTab('hot')">Hot Game 🔥</button>
        </div>

        <!-- Main Content Core Layout Area Grid -->
        <div class="games-grid">

            <!-- ================= CASINO SECTIONS (Remaining 6 New + Old Ones) ================= -->
            <div class="game-card" data-category="casino"><div class="game-image-wrapper"><img src="https://i.ibb.co/wZBnk9sF/IMG-20260528-165407-231.jpg" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">jaiho slots</div><a href="https://www.jaihoslots22.com/?code=EGPEAZTSMVU&t=1779962073" class="play-btn">Play</a></div>
            <div class="game-card" data-category="casino"><div class="game-image-wrapper"><img src="https://i.ibb.co/GQ6GP2LS/Screenshot-2026-0528-165315.png" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">Yono games</div><a href="https://yonogames8.com/?code=GK1JRVZD9K5&t=1779961990" class="play-btn">Play</a></div>
            <div class="game-card" data-category="casino"><div class="game-image-wrapper"><img src="https://i.ibb.co/RGtvj6Dd/IMG-20260528-165052-353.jpg" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">Top Rummy</div><a href="https://toprummy07.vip/?code=7K96EQ5AKMP&t=1779961780" class="play-btn">Play</a></div>
            <div class="game-card" data-category="casino"><div class="game-image-wrapper"><img src="https://i.ibb.co/chcCTzLS/IMG-20260528-165212-428.jpg" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">Spin winner</div><a href="https://mspinwinner.com/?code=SDNWPZMAS3V&t=1779961842" class="play-btn">Play</a></div>
            <div class="game-card" data-category="casino"><div class="game-image-wrapper"><img src="https://i.ibb.co/xKNsWwb0/IMG-20260528-165017-074.jpg" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">joy Rummy</div><a href="https://joyrummyagent.net/?code=J5KTM4A8CBF&t=1779961723" class="play-btn">Play</a></div>
            <div class="game-card" data-category="casino"><div class="game-image-wrapper"><img src="https://i.ibb.co/fVc44frd/IMG-20260528-164912-649.jpg" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">love rummy</div><a href="https://www.8loverummy.com/?code=AFCVA33P3UL&t=1779961580" class="play-btn">Play</a></div>
            
            <!-- Old Casino Units Portfolio -->
            <div class="game-card" data-category="casino"><div class="game-image-wrapper"><img src="https://i.ibb.co/XxTS3tdZ/Screenshot-2026-0524-121950.png" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">Yono rummy</div><a href="https://dp92t0mhjbqu9.cloudfront.net/yonorummyagent.apk" class="play-btn">Play</a></div>
            <div class="game-card" data-category="casino"><div class="game-image-wrapper"><img src="https://i.ibb.co/m5xd7qpZ/Screenshot-2026-0524-122312.png" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">Spin 777</div><a href="https://spin777ff.com/?code=7V9FYWPMDEW&t=1779605799" class="play-btn">Play</a></div>
            <div class="game-card" data-category="casino"><div class="game-image-wrapper"><img src="https://i.ibb.co/mF600568/Screenshot-2026-0524-122402.png" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">Spin Crush</div><a href="https://bkfadsegtgs.sa
