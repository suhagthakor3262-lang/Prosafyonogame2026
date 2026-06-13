<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Download the official ProSafe Yono Game app for 2026. Access all top Yono games, mega bonuses, and 100% secure direct download links in one place.">
    <title>ProSafe Yono Game</title>
    <style>
        * { box-sizing: border-box; margin: 0; padding: 0; font-family: sans-serif; }
        body { background-color: #f4f6f9; color: #333; }
        
        /* 🔵 ORIGINAL HEADER THEME */
        .header { background: #fff; padding: 12px 15px; display: flex; align-items: center; justify-content: space-between; border-bottom: 1px solid #e0e0e0; box-shadow: 0 2px 4px rgba(0,0,0,0.05); }
        .header-left { display: flex; align-items: center; gap: 10px; }
        .logo-img { width: 35px; height: 35px; border-radius: 50%; }
        .site-title { font-size: 18px; font-weight: bold; color: #1e3a8a; }
        .menu-icon { font-size: 24px; color: #333; cursor: pointer; }

        /* 📋 PERFECT LIVE COUNTING STRIP (AS REQUESTED) */
        .live-ticker-container { padding: 10px 15px; background-color: #f4f6f9; }
        .live-ticker { background: #fff; padding: 8px 15px; border-radius: 6px; display: flex; align-items: center; justify-content: center; gap: 10px; border: 1px solid #e2e8f0; box-shadow: 0 1px 3px rgba(0,0,0,0.05); }
        .live-badge { background: #ff0000; color: #fff; padding: 2px 6px; font-size: 11px; font-weight: bold; border-radius: 4px; animation: blink 1s infinite; display: inline-block; }
        @keyframes blink { 0% { opacity: 1; } 50% { opacity: 0.3; } 100% { opacity: 1; } }
        .ticker-text { color: #475569; font-size: 13px; font-weight: 500; text-align: center; }

        /* 🔍 ORIGINAL SEARCH BAR */
        .search-box { padding: 5px 15px 15px 15px; background-color: #f4f6f9; position: relative; }
        .search-input { width: 100%; padding: 12px 40px 12px 15px; border: 1px solid #cbd5e1; border-radius: 25px; font-size: 15px; outline: none; background: #fff; color: #333; }
        .search-icon { position: absolute; right: 30px; top: 22px; width: 18px; height: 18px; opacity: 0.5; }

        /* 🔥 HIGHLIGHT APPS (HORIZONTAL SCROLL) */
        .section-title { padding: 10px 15px 5px 15px; font-size: 16px; font-weight: bold; color: #334155; display: flex; align-items: center; gap: 5px; }
        .highlight-scroll { display: flex; gap: 12px; padding: 10px 15px; overflow-x: auto; white-space: nowrap; scrollbar-width: none; }
        .highlight-scroll::-webkit-scrollbar { display: none; }
        .highlight-card { background: #fff; border: 1px solid #e2e8f0; border-radius: 12px; padding: 10px; display: flex; align-items: center; gap: 10px; min-width: 210px; box-shadow: 0 1px 3px rgba(0,0,0,0.02); }
        .scroll-img { width: 45px; height: 45px; border-radius: 10px; }
        .scroll-info { display: flex; flex-direction: column; }
        .scroll-title { font-size: 14px; font-weight: bold; color: #1e293b; }
        .scroll-bonus { font-size: 11px; color: #10b981; font-weight: 500; }
        .mini-play-btn { background: #f59e0b; color: white; padding: 4px 10px; border-radius: 6px; font-size: 12px; font-weight: bold; text-decoration: none; margin-left: auto; }

        /* 📱 ORIGINAL VERTICAL GAME LIST */
        .game-list { padding: 10px 15px; display: flex; flex-direction: column; gap: 12px; }
        .game-row { background: #fff; border-radius: 14px; padding: 12px; display: flex; align-items: center; border: 1px solid #e2e8f0; box-shadow: 0 1px 3px rgba(0,0,0,0.02); position: relative; }
        .rank-tag { position: absolute; top: -6px; left: 8px; font-size: 9px; font-weight: bold; padding: 1px 5px; border-radius: 4px; color: #fff; text-transform: uppercase; }
        .rank-1 { background: #ef4444; } .rank-2 { background: #f59e0b; } .rank-3 { background: #f59e0b; }
        .row-img { width: 60px; height: 60px; border-radius: 12px; object-fit: cover; margin-right: 12px; }
        .row-details { display: flex; flex-direction: column; flex-grow: 1; }
        .row-title-container { display: flex; align-items: center; gap: 6px; margin-bottom: 2px; }
        .row-title { font-size: 14px; font-weight: bold; color: #1e293b; }
        .badge-new { background: #10b981; color: white; padding: 1px 5px; font-size: 9px; font-weight: bold; border-radius: 3px; }
        .badge-hot { background: #ef4444; color: white; padding: 1px 5px; font-size: 9px; font-weight: bold; border-radius: 3px; }
        .row-meta { font-size: 11px; color: #f59e0b; font-weight: bold; margin-bottom: 3px; }
        .row-sub { font-size: 12px; color: #64748b; font-weight: 500; width: 150px; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
        
        /* 🔵 ORIGINAL BLUE PLAY BUTTON */
        .blue-play-btn { background: #2563eb; color: white; padding: 8px 16px; border-radius: 6px; font-size: 13px; font-weight: bold; text-decoration: none; box-shadow: 0 2px 4px rgba(37,99,235,0.2); }
        .blue-play-btn:hover { background: #1d4ed8; }

        /* 📝 FOOTER CONTENT & DISCLAIMER */
        .footer-content { padding: 20px 15px; color: #333; line-height: 1.6; }
        .footer-content h2 { font-size: 18px; color: #1e3a8a; margin-bottom: 8px; font-weight: bold; }
        .footer-content p { font-size: 13px; color: #475569; text-align: justify; }
        .disclaimer-box { background: #fff; padding: 15px; border-radius: 10px; font-size: 12px; color: #64748b; border: 1px solid #e2e8f0; text-align: justify; margin-top: 15px; line-height: 1.5; }
        .copyright { text-align: center; font-size: 11px; color: #94a3b8; margin-top: 20px; padding-bottom: 10px; }
    </style>
</head>
<body>

    <!-- 🔵 ORIGINAL HEADER -->
    <div class="header">
        <div class="header-left">
            <div class="menu-icon">☰</div>
            <img src="https://i.ibb.co/Df1Ckfb6/IMG-20260527-084343-458.jpg" class="logo-img" alt="ProSafe Yono Logo">
            <span class="site-title">ProSafe Yono Game</span>
        </div>
    </div>

    <!-- 📋 ORIGINAL STRIP WITH NEW BLINKING LIVE BADGE -->
    <div class="live-ticker-container">
        <div class="live-ticker">
            <span class="live-badge">LIVE</span>
            <div class="ticker-text">User12** won ₹1,500 in Spin 777</div>
        </div>
    </div>

    <!-- 🔍 ORIGINAL SEARCH BAR -->
    <div class="search-box">
        <input type="text" id="gameSearch" class="search-input" placeholder="Search game...">
        <svg class="search-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="11" cy="11" r="8"></circle><line x1="21" y1="21" x2="16.65" y2="16.65"></line></svg>
    </div>

    <!-- 🔥 ORIGINAL HORIZONTAL HIGHLIGHT APPS -->
    <div class="section-title">🔥 Highlight Apps (Hot Rewards)</div>
    <div class="highlight-scroll">
        <!-- Card 1 -->
        <div class="highlight-card">
            <img src="https://i.ibb.co/Q7Wr5bhm/IMG-20260604-173703-578.jpg" class="scroll-img" alt="567 Slots Box Mini Icon">
            <div class="scroll-info">
                <span class="scroll-title">567 Slots</span>
                <span class="scroll-bonus">Bonus ₹55 Free</span>
            </div>
            <a href="slots-567.html" class="mini-play-btn">Play</a>
        </div>
        <!-- Card 2 -->
        <div class="highlight-card">
            <img src="https://i.ibb.co/XxTS3tdZ/Screenshot-20260524-121950.png" class="scroll-img" alt="Yono 777 Box Mini Icon">
            <div class="scroll-info">
                <span class="scroll-title">Yono 777</span>
                <span class="scroll-bonus">Bonus ₹51 Free</span>
            </div>
            <a href="yono-777.html" class="mini-play-btn">Play</a>
        </div>
    </div>

    <!-- 📱 ORIGINAL VERTICAL LIST (CONNECTED TO NEW REVIEWS & WORKING LINKS) -->
    <div class="game-list" id="gameList">

        <!-- Rank 1: Yono Rummy -->
        <div class="game-row">
            <span class="rank-tag rank-1">👑 Rank 1</span>
            <img src="https://i.ibb.co/XxTS3tdZ/Screenshot-20260524-121950.png" class="row-img" alt="Yono Rummy App Icon">
            <div class="row-details">
                <div class="row-title-container">
                    <span class="row-title">Yono Rummy</span>
                    <span class="badge-new">NEW</span>
                </div>
                <span class="row-meta">⭐ 10</span>
                <span class="row-sub">Yono rummy Apk Download & Bonus ₹55 Free</span>
            </div>
            <a href="yono-777.html" class="blue-play-btn">PLAY</a>
        </div>

        <!-- Rank 2: Spin 777 -->
        <div class="game-row">
            <span class="rank-tag rank-2">👑 Rank 2</span>
            <img src="https://i.ibb.co/QF1qr0Xs/IMG-20260526-095252-042.jpg" class="row-img" alt="Spin 777 App Icon">
            <div class="row-details">
                <div class="row-title-container">
                    <span class="row-title">Spin 777</span>
                    <span class="badge-new">NEW</span>
                </div>
                <span class="row-meta">⭐ 10</span>
                <span class="row-sub">Spin 777 Apk Download & Bonus ₹55 Free</span>
            </div>
            <a href="spin-777.html" class="blue-play-btn">PLAY</a>
        </div>

        <!-- Rank 3: Spin Crush -->
        <div class="game-row">
            <span class="rank-tag rank-3">👑 Rank 3</span>
            <img src="https://i.ibb.co/N2KgxkGD/IMG-20260526-093823-947.jpg" class="row-img" alt="Spin Crush App Icon">
            <div class="row-details">
                <div class="row-title-container">
                    <span class="row-title">Spin Crush</span>
                    <span class="badge-new">NEW</span>
                </div>
                <span class="row-meta">⭐ 10</span>
                <span class="row-sub">Spin Crush Apk Download & Bonus ₹55 Free</span>
            </div>
            <a href="spin-crush.html" class="blue-play-btn">PLAY</a>
        </div>

        <!-- 567 Slots Row -->
        <div class="game-row">
            <img src="https://i.ibb.co/Q7Wr5bhm/IMG-20260604-173703-578.jpg" class="row-img" alt="567 Slots App Icon">
            <div class="row-details">
                <div class="row-title-container">
                    <span class="row-title">567 Slots</span>
                    <span class="badge-hot">HOT</span>
                </div>
                <span class="row-meta">⭐ 10</span>
                <span class="row-sub">567 slots Apk Download & Bonus ₹55 Free</span>
            </div>
            <a href="slots-567.html" class="blue-play-btn">PLAY</a>
        </div>

        <!-- IND Rummy Row (Review page connecting link) -->
        <div class="game-row">
            <img src="https://i.ibb.co/Df1Ckfb6/IMG-20260527-084343-458.jpg" class="row-img" alt="IND Rummy App Icon">
            <div class="row-details">
                <div class="row-title-container">
                    <span class="row-title">IND Rummy</span>
                    <span class="badge-hot">HOT</span>
                </div>
                <span class="row-meta">⭐ 10</span>
                <span class="row-sub">IND rummy Apk Download & Bonus ₹55 Free</span>
            </div>
            <a href="ind-club.html" class="blue-play-btn">PLAY</a>
        </div>

        <!-- Club INR Row (Special Link Connected Inside Review) -->
        <div class="game-row">
            <img src="https://i.ibb.co/5xFTSv8P/IMG-20260527-083320-198.jpg" class="row-img" alt="Club INR App Icon">
            <div class="row-details">
                <div class="row-title-container">
                    <span class="row-title">Club INR</span>
                    <span class="badge-new">NEW</span>
                </div>
                <span class="row-meta">⭐ 10</span>
                <span class="row-sub">Club INR Official Safe Secure Download Link</span>
            </div>
            <a href="club-inr.html" class="blue-play-btn">PLAY</a>
        </div>

    </div>

    <!-- 📝 ORIGINAL FOOTER STYLE & CONTENT -->
    <div class="footer-content">
        <h2>Welcome to ProSafe Yono Games Portal 2026</h2>
        <p>Your ultimate destination to find verified and secure direct download links for all top-rated Yono gaming applications. We provide the latest updates, legal gaming reviews, and absolute safety features for an enhanced experience.</p>
        
        <div class="disclaimer-box">
            <strong>Responsible Gaming Disclaimer:</strong> This platform only provides verified app links and official descriptions for informational and educational purposes. All gaming applications available on this portal carry financial risks and can be addictive. We strictly encourage players to play responsibly and at their own discretion. This platform is not liable for any losses incurred through these third-party apps.
        </div>

        <div class="copyright">
            © 2026 ProSafe Yono Games. All Rights Reserved. Verified Secure Portal.
        </div>
    </div>

    <!-- Live Counter & Pure Original Search Logic -->
    <script>
        // --- LIVE WINNING TICKER ---
        const names = ["User12**", "Player99**", "Rahul88**", "Arun55**", "Soni44**"];
        const amounts = ["₹1,500", "₹3,200", "₹9,500", "₹700", "₹12,000"];
        const games = ["Spin 777", "Yono Rummy", "567 Slots", "Club INR", "Spin Crush"];
        
        setInterval(() => {
            const randName = names[Math.floor(Math.random() * names.length)];
            const randAmount = amounts[Math.floor(Math.random() * amounts.length)];
            const randGame = games[Math.floor(Math.random() * games.length)];
            document.querySelector('.ticker-text').innerText = `${randName} won ${randAmount} in ${randGame}`;
        }, 4000);

        // --- LIVE SEARCH FILTER ---
        const searchInput = document.getElementById('gameSearch');
        const rows = document.querySelectorAll('.game-row');

        searchInput.addEventListener('input', function() {
            const val = searchInput.value.toLowerCase().trim();
            rows.forEach(row => {
                const title = row.querySelector('.row-title').innerText.toLowerCase();
                if(title.includes(val)) {
                    row.style.display = "flex";
                } else {
                    row.style.display = "none";
                }
            });
        });
    </script>
</body>
</html>
