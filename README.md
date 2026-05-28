<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <!-- SEO Meta Tags -->
    <meta name="description" content="Download best Rummy, Slots, and Casino games at ProSafe Bet. Latest APKs available.">
    <meta name="keywords" content="Yono Rummy, Spin 101, Spin 777, Spin Crush, 567 Slots, IND Rummy, Jaiho 91, Bingo 101, 101Z, Rumble Rummy, ProSafe Bet, Online Casino Games India, Best Rummy APK">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ProSafe Bet - All Games</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
        body { background-color: #f5f5f5; color: #333; display: flex; flex-direction: column; min-height: 100vh; }
        
        /* Centralized Container Wrapper Box */
        .wrapper { width: 100%; max-width: 600px; margin: 0 auto; display: flex; flex-direction: column; flex: 1; }

        /* Header Style */
        header { 
            background-color: #1a2229; 
            padding: 15px 20px; 
            display: flex; 
            justify-content: space-between; 
            align-items: center; 
            position: sticky; 
            top: 0; 
            z-index: 100;
            width: 100%;
        }
        
        /* Colorful Logo Setup */
        .logo { font-size: 22px; font-weight: bold; letter-spacing: 0.5px; }
        .logo .wht { color: #ffffff; }
        .logo .grn { color: #4caf50; }
        .logo .ylw { color: #ffeb3b; }

        .three-dots { color: white; font-size: 24px; cursor: pointer; padding: 0 5px; user-select: none; }

        /* Modal Popup Menu Overlay */
        .menu-overlay { position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0, 0, 0, 0.5); display: none; z-index: 200; justify-content: center; align-items: center; }
        .menu-content { background: white; width: 85%; max-width: 340px; border-radius: 12px; padding: 20px; box-shadow: 0 5px 15px rgba(0,0,0,0.3); position: relative; animation: fadeIn 0.3s ease; }
        @keyframes fadeIn { from { opacity: 0; transform: scale(0.9); } to { opacity: 1; transform: scale(1); } }
        .menu-header { display: flex; justify-content: space-between; align-items: center; border-bottom: 1px solid #eee; padding-bottom: 10px; margin-bottom: 15px; }
        .menu-header h3 { font-size: 18px; color: #1a2229; }
        .close-btn { font-size: 22px; cursor: pointer; color: #888; }
        .menu-item { margin-bottom: 15px; }
        .menu-link-btn { display: inline-block; text-decoration: none; color: #1e88e5; font-weight: bold; font-size: 16px; margin-bottom: 5px; }
        .menu-text { font-size: 13px; color: #555; line-height: 1.4; padding-left: 2px; }
        .warning-text { color: #d32f2f; font-weight: 500; }

        /* Main Elements Structure */
        .search-container { padding: 20px 15px 10px 15px; width: 100%; }
        .search-box { width: 100%; padding: 12px 20px; border: 1px solid #ccc; border-radius: 8px; font-size: 16px; outline: none; box-shadow: inset 0 1px 3px rgba(0,0,0,0.05); }
        
        /* Telegram Banner Fix */
        .telegram-ticker { background-color: #0088cc; color: white; padding: 10px 0; overflow: hidden; white-space: nowrap; font-size: 14px; font-weight: bold; margin: 0 15px 15px 15px; border-radius: 6px; }
        .telegram-ticker marquee a { color: white; text-decoration: none; }
        
        /* New on Game Title Styles (Screenshot jaisa exact look) */
        .section-title { text-align: center; margin-top: 15px; font-size: 26px; color: #222; font-weight: 500; }
        .section-subtitle { text-align: center; color: #666; font-size: 14px; margin-top: 15px; margin-bottom: 25px; padding: 0 20px; line-height: 1.5; }

        /* Filter Tabs Options - Sirf 2 Buttons */
        .tabs-container { display: flex; justify-content: center; gap: 12px; margin-bottom: 25px; padding: 0 15px; width: 100%; }
        .tab-btn { flex: 1; max-width: 150px; padding: 11px 0; background-color: #e0e0e0; border-radius: 8px; color: #444; font-weight: bold; font-size: 15px; border: none; cursor: pointer; text-align: center; }
        .tab-btn.active { background-color: white; color: #1a2229; box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
        
        /* Games Grid Container */
        .games-grid { display: grid; grid-template-columns: repeat(2, 1fr); gap: 15px; padding: 0 15px 40px 15px; width: 100%; }
        .game-card { background: white; border-radius: 12px; padding: 20px 12px; text-align: center; box-shadow: 0 4px 6px rgba(0,0,0,0.05); display: flex; flex-direction: column; align-items: center; }
        
        .hot-badge { background-color: #ff3d00; color: white; font-size: 11px; font-weight: bold; padding: 2px 8px; border-radius: 20px; margin-bottom: 8px; text-transform: uppercase; }
        .game-image-wrapper { width: 110px; height: 110px; margin-bottom: 12px; display: flex; justify-content: center; align-items: center; }
        .game-img { width: 100%; height: 100%; object-fit: cover; border-radius: 50%; }
        .rating { color: #4caf50; font-size: 14px; font-weight: bold; margin-bottom: 8px; display: flex; align-items: center; gap: 4px; }
        .game-name { font-size: 14px; font-weight: 600; color: #222; margin-bottom: 15px; height: 20px; overflow: hidden; text-transform: uppercase; }
        
        .play-btn { display: block; width: 100%; padding: 10px 0; background-color: #e3f2fd; color: #1e88e5; text-decoration: none; font-weight: bold; border-radius: 6px; font-size: 14px; text-align: center; }
        
        footer { background-color: #1a2229; color: #999; text-align: center; padding: 15px; font-size: 13px; border-top: 2px solid #2e3942; width: 100%; }

        @media (max-width: 360px) {
            .games-grid { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>

    <!-- Centralized Container Wrapper Box -->
    <div class="wrapper">

        <!-- Header Area -->
        <header>
            <div class="logo">
                <span class="wht">Pro</span><span class="grn">Safe</span><span class="ylw">Bet</span>
            </div>
            <div class="three-dots" onclick="toggleMenu(true)">&#8942;</div>
        </header>

        <!-- Navigation Popup Menu Overlay -->
        <div class="menu-overlay" id="menuOverlay" onclick="toggleMenu(false)">
            <div class="menu-content" onclick="event.stopPropagation()">
                <div class="menu-header">
                    <h3>Menu Options</h3>
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

        <!-- Search Input Area with exact old placeholder string text -->
        <div class="search-container">
            <input type="text" id="searchBox" class="search-box" placeholder="What you want to search ?" oninput="filterGames()">
        </div>

        <!-- Scrolling Telegram Link with Perfect Puraani Width Alignment -->
        <div class="telegram-ticker">
            <marquee behavior="scroll" direction="left" scrollamount="5">
                <a href="https://t.me/invitnew" target="_blank">📢 Join Our Official Telegram Channel For Daily Updates! Click Here: https://t.me/invitnew 🚀</a>
            </marquee>
        </div>

        <!-- Heading Text Section (Screenshot 1000164806_2.jpg jaisa exact) -->
        <h2 class="section-title">New on Game</h2>
        <p class="section-subtitle">Discover what's new on Game and enjoy the best new game.</p>

        <!-- Filter Tabs Options - ONLY 2 BUTTONS (Casinos aur Hot Game) -->
        <div class="tabs-container">
            <button class="tab-btn active" id="btn-casino" onclick="changeTab('casino')">Casinos</button>
            <button class="tab-btn" id="btn-hot" onclick="changeTab('hot')">Hot Game 🔥</button>
        </div>

        <!-- Games Grid Container -->
        <div class="games-grid">

            <!-- ================= 10 HOT GAMES ================= -->
            <div class="game-card" data-category="hot"><div class="hot-badge">Hot</div><div class="game-image-wrapper"><img src="https://i.ibb.co/Tq72gZFq/IMG-20260527-084621-601.jpg" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">Spin 101</div><a href="https://spin101-l.org/?code=P4CKGELNRH7&t=1779851685" class="play-btn">Play</a></div>
            <div class="game-card" data-category="hot"><div class="hot-badge">Hot</div><div class="game-image-wrapper"><img src="https://i.ibb.co/Df1Ckfb6/IMG-20260527-084343-458.jpg" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">ind club</div><a href="https://indclub40.com/?code=34U7Q463L21&t=1779851539" class="play-btn">Play</a></div>
            <div class="game-card" data-category="hot"><div class="hot-badge">Hot</div><div class="game-image-wrapper"><img src="https://i.ibb.co/LXHb3q9r/IMG-20260527-084105-646.jpg" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">789 jackpot</div><a href="https://789jackpotsrefer06.top/?code=J7ZVY7GG8MG&t=1779851510" class="play-btn">Play</a></div>
            <div class="game-card" data-category="hot"><div class="hot-badge">Hot</div><div class="game-image-wrapper"><img src="https://i.ibb.co/S4Lbb73b/IMG-20260527-083816-794.jpg" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">jaiho rummy</div><a href="https://jaihorummycash.com/?code=E743FQGJMGT&t=1779851188" class="play-btn">Play</a></div>
            <div class="game-card" data-category="hot"><div class="hot-badge">Hot</div><div class="game-image-wrapper"><img src="https://i.ibb.co/Y4QjvfRz/IMG-20260527-083518-645.jpg" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">Hi rummy</div><a href="https://hirummyapp.vip/?code=RX3RPAXW9YA&t=1779851078" class="play-btn">Play</a></div>
            <div class="game-card" data-category="hot"><div class="hot-badge">Hot</div><div class="game-image-wrapper"><img src="https://i.ibb.co/5xFTSv8P/IMG-20260527-083320-198.jpg" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">gogo rummy</div><a href="https://www.gogorummyfreecash.com/?code=8FW3R3HE1HT&t=1779850964" class="play-btn">Play</a></div>
            <div class="game-card" data-category="hot"><div class="hot-badge">Hot</div><div class="game-image-wrapper"><img src="https://i.ibb.co/RpFWTsC2/IMG-20260527-083035-119.jpg" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">Boss rummy</div><a href="https://bossrummyyy.com/?code=0T8Y8BSL24N" class="play-btn">Play</a></div>
            <div class="game-card" data-category="hot"><div class="hot-badge">Hot</div><div class="game-image-wrapper"><img src="https://i.ibb.co/mCGfLWTQ/IMG-20260527-082911-954.jpg" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">Club INR</div><a href="https://clubinrvip1.net/?code=9VCFS6TH9QU&t=1779850732" class="play-btn">Play</a></div>
            <div class="game-card" data-category="hot"><div class="hot-badge">Hot</div><div class="game-image-wrapper"><img src="https://i.ibb.co/XfpncM77/IMG-20260527-082804-195.jpg" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">Game Rummy</div><a href="https://gamerummyd.com/?code=JXA44SSTNVW&t=1779850668" class="play-btn">Play</a></div>
            <div class="game-card" data-category="hot"><div class="hot-badge">Hot</div><div class="game-image-wrapper"><img src="https://i.ibb.co/6CWcJ9t/IMG-20260527-082552-806.jpg" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">Rumble Rummy</div><a href="https://www.rumblerummy2.vip/?code=UC02RS4D5NF&t=1779850561" class="play-btn">Play</a></div>

            <!-- ================= 10 CASINO GAMES ================= -->
            <div class="game-card" data-category="casino"><div class="game-image-wrapper"><img src="https://i.ibb.co/XxTS3tdZ/Screenshot-2026-0524-121950.png" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">Yono rummy</div><a href="https://dp92t0mhjbqu9.cloudfront.net/yonorummyagent.apk" class="play-btn">Play</a></div>
            <div class="game-card" data-category="casino"><div class="game-image-wrapper"><img src="https://i.ibb.co/m5xd7qpZ/Screenshot-2026-0524-122312.png" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">Spin 777</div><a href="https://spin777ff.com/?code=7V9FYWPMDEW&t=1779605799" class="play-btn">Play</a></div>
            <div class="game-card" data-category="casino"><div class="game-image-wrapper"><img src="https://i.ibb.co/mF600568/Screenshot-2026-0524-122402.png" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">Spin Crush</div><a href="https://bkfadsegtgs.safelyearnmillionsbysharingonepersonaqfxzqyj8.com/?code=ADEX2NMGVQT&t=1779605852" class="play-btn">Play</a></div>
            <div class="game-card" data-category="casino"><div class="game-image-wrapper"><img src="https://i.ibb.co/tTHRNZNj/Screenshot-2026-0524-122448.png" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">567 slots</div><a href="https://567slotsrefer08.cc/?code=4NY21SD2TVM&t=1779605926" class="play-btn">Play</a></div>
            <div class="game-card" data-category="casino"><div class="game-image-wrapper"><img src="https://i.ibb.co/39KDGPBr/Screenshot-2026-0524-122547.png" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">IND rummy</div><a href="https://indrummym.in/?code=XU7ZAHJBQM3&t=1779605993" class="play-btn">Play</a></div>
            <div class="game-card" data-category="casino"><div class="game-image-wrapper"><img src="https://i.ibb.co/dwJW89jT/IMG-20260526-094057-833.jpg" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">INR rummy</div><a href="https://inrrummy1.com/?code=7P2T88Y19UP&t=1779768631" class="play-btn">Play</a></div>
            <div class="game-card" data-category="casino"><div class="game-image-wrapper"><img src="https://i.ibb.co/N2kGxkGD/IMG-20260526-093823-947.jpg" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">jaiho 91</div><a href="https://jaiho91gaming.com/?code=C42NGHQ518G&t=1779715488" class="play-btn">Play</a></div>
            <div class="game-card" data-category="casino"><div class="game-image-wrapper"><img src="https://i.ibb.co/S46hgCs6/Screenshot-2026-0524-214009.png" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">Bingo 101</div><a href="https://bingo101aa.com/?code=AZTWFC1LN3P&t=1779638894" class="play-btn">Play</a></div>
            <div class="game-card" data-category="casino"><div class="game-image-wrapper"><img src="https://i.ibb.co/QF1qr0Xs/IMG-20260526-095252-042.jpg" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">101Z</div><a href="https://www.101z12.vip/?code=398ZMFCUX85&t=1779709639" class="play-btn">Play</a></div>
            <div class="game-card" data-category="casino"><div class="game-image-wrapper"><img src="https://i.ibb.co/qYX8344d/IMG-20260526-095508-315.jpg" class="game-img"></div><div class="rating">★ 10</div><div class="game-name">IND Slots</div><a href="https://d1bjlwgcobo9al.cloudfront.net/16/43943299/indslots_T2QDFH0P4AA.apk" class="play-btn">Play</a></div>

        </div>

        <!-- Footer Area -->
        <footer>
            &copy; 2026 ProSafe Bet. All Rights Reserved.
        </footer>

    </div>

    <!-- JavaScript Logic Area -->
    <script>
        let currentTab = 'casino';

        function toggleMenu(show) {
            document.getElementById('menuOverlay').style.display = show ? 'flex' : 'none';
        }

        function goHome() {
            toggleMenu(false);
            changeTab('casino');
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        function changeTab(tabName) {
            currentTab = tabName;
            document.getElementById('searchBox').value = "";

            if (tabName === 'casino') {
                document.getElementById('btn-casino').classList.add('active');
                document.getElementById('btn-hot').classList.remove('active');
            } else {
                document.getElementById('btn-hot').classList.add('active');
                document.getElementById('btn-casino').classList.remove('active');
            }
            renderGames();
        }

        function filterGames() {
            renderGames();
        }

        function renderGames() {
            let searchText = document.getElementById('searchBox').value.toLowerCase();
            let cards = document.getElementsByClassName('game-card');

            for (let i = 0; i < cards.length; i++) {
                let cardCategory = cards[i].getAttribute('data-category');
                let gameNameElement = cards[i].getElementsByClassName('game-name')[0];
                let gameName = gameNameElement ? (gameNameElement.textContent || gameNameElement.innerText).toLowerCase() : "";

                if (cardCategory === currentTab && gameName.includes(searchText)) {
                    cards[i].style.display = "";
                } else {
                    cards[i].style.display = "none";
                }
            }
        }

        window.onload = function() {
            changeTab('casino');
        };
    </script>
</body>
</html>
