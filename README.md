<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ProSafe Bet - Games</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f5f5f5;
            color: #333;
        }

        /* Top Header Navigation */
        header {
            background-color: #1a2229;
            color: white;
            padding: 15px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .logo {
            font-size: 22px;
            font-weight: bold;
        }

        .logo span {
            color: #4caf50;
        }

        .menu-icon {
            font-size: 24px;
            cursor: pointer;
        }

        /* Search Section */
        .search-container {
            padding: 20px 15px 10px 15px;
            max-width: 600px;
            margin: 0 auto;
        }

        .search-box {
            width: 100%;
            padding: 12px 20px;
            border: 1px solid #ccc;
            border-radius: 8px;
            font-size: 16px;
            outline: none;
            box-shadow: inset 0 1px 3px rgba(0,0,0,0.05);
        }

        /* Scrolling Telegram Banner */
        .telegram-ticker {
            background-color: #0088cc;
            color: white;
            padding: 8px 0;
            overflow: hidden;
            white-space: nowrap;
            font-size: 14px;
            font-weight: bold;
            max-width: 600px;
            margin: 0 auto 15px auto;
            border-radius: 4px;
        }

        .telegram-ticker marquee a {
            color: white;
            text-decoration: none;
        }

        /* Main Heading Titles */
        .section-title {
            text-align: center;
            margin-top: 20px;
            font-size: 26px;
            color: #222;
        }

        .section-subtitle {
            text-align: center;
            color: #666;
            font-size: 14px;
            margin-bottom: 25px;
            padding: 0 15px;
        }

        /* Filter Tabs */
        .tabs-container {
            display: flex;
            justify-content: center;
            gap: 8px;
            margin-bottom: 25px;
            padding: 0 15px;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            overflow-x: auto;
            white-space: nowrap;
        }

        .tab-btn {
            padding: 10px 18px;
            background-color: #e0e0e0;
            border-radius: 6px;
            color: #444;
            font-weight: 500;
            font-size: 14px;
            border: none;
            cursor: pointer;
            transition: 0.2s;
        }

        .tab-btn.active {
            background-color: white;
            color: #1a2229;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            font-weight: bold;
        }

        /* Games Grid System */
        .games-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 15px;
            padding: 0 15px 40px 15px;
            max-width: 600px;
            margin: 0 auto;
        }

        /* Individual Game Cards */
        .game-card {
            background: white;
            border-radius: 12px;
            padding: 20px 12px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .hot-badge {
            background-color: #ff3d00;
            color: white;
            font-size: 11px;
            font-weight: bold;
            padding: 2px 8px;
            border-radius: 20px;
            margin-bottom: 8px;
            text-transform: uppercase;
        }

        .game-image-wrapper {
            width: 110px;
            height: 110px;
            margin-bottom: 12px;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .game-img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            border-radius: 50%;
        }

        .rating {
            color: #4caf50;
            font-size: 14px;
            font-weight: bold;
            margin-bottom: 8px;
            display: flex;
            align-items: center;
            gap: 4px;
        }

        .game-name {
            font-size: 15px;
            font-weight: 600;
            color: #222;
            margin-bottom: 15px;
            height: 20px;
            overflow: hidden;
            text-transform: uppercase;
        }

        .play-btn {
            display: block;
            width: 100%;
            padding: 10px 0;
            background-color: #e3f2fd;
            color: #1e88e5;
            text-decoration: none;
            font-weight: bold;
            border-radius: 6px;
            font-size: 14px;
            transition: 0.2s ease-in-out;
        }

        .play-btn:hover {
            background-color: #2196f3;
            color: white;
        }

        @media (max-width: 360px) {
            .games-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

    <!-- Header Style -->
    <header>
        <div class="logo">ProSafe<span>Bet.</span></div>
        <div class="menu-icon">&#9776;</div>
    </header>

    <!-- Search Input Area -->
    <div class="search-container">
        <input type="text" id="searchBox" class="search-box" placeholder="What you want to search ?" onkeyup="filterGames()">
    </div>

    <!-- Scrolling Telegram Link -->
    <div class="telegram-ticker">
        <marquee behavior="scroll" direction="left" scrollamount="5">
            <a href="https://t.me/invitnew" target="_blank">📢 Join Our Official Telegram Channel For Daily Updates! Click Here: https://t.me/invitnew 🚀</a>
        </marquee>
    </div>

    <!-- Titles -->
    <h2 class="section-title">New on Game</h2>
    <p class="section-subtitle">Discover what's new on Game and enjoy the best new game.</p>

    <!-- Filter Tabs Options -->
    <div class="tabs-container">
        <button class="tab-btn active" onclick="filterCategory('casino', this)">Casinos</button>
        <button class="tab-btn" onclick="filterCategory('hot', this)">Hot Game 🔥</button>
        <button class="tab-btn" onclick="filterCategory('news', this)">News</button>
        <button class="tab-btn" onclick="filterCategory('bonuses', this)">Bonuses</button>
        <button class="tab-btn" onclick="filterCategory('promo', this)">Promocode</button>
    </div>

    <!-- Games Grid Container -->
    <div class="games-grid">

        <!-- ================= NAYI 10 HOT GAMES ================= -->

        <!-- Nayi Game 1: Spin 101 -->
        <div class="game-card" data-category="hot">
            <div class="hot-badge">Hot</div>
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/Tq72gZFq/IMG-20260527-084621-601.jpg" alt="Spin 101" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">Spin 101</div>
            <a href="https://spin101-l.org/?code=P4CKGELNRH7&t=1779851685" class="play-btn">Play</a>
        </div>

        <!-- Nayi Game 2: ind club -->
        <div class="game-card" data-category="hot">
            <div class="hot-badge">Hot</div>
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/Df1Ckfb6/IMG-20260527-084343-458.jpg" alt="ind club" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">ind club</div>
            <a href="https://indclub40.com/?code=34U7Q463L21&t=1779851539" class="play-btn">Play</a>
        </div>

        <!-- Nayi Game 3: 789 jackpot -->
        <div class="game-card" data-category="hot">
            <div class="hot-badge">Hot</div>
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/LXHb3q9r/IMG-20260527-084105-646.jpg" alt="789 jackpot" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">789 jackpot</div>
            <a href="https://789jackpotsrefer06.top/?code=J7ZVY7GG8MG&t=1779851510" class="play-btn">Play</a>
        </div>

        <!-- Nayi Game 4: jaiho rummy -->
        <div class="game-card" data-category="hot">
            <div class="hot-badge">Hot</div>
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/S4Lbb73b/IMG-20260527-083816-794.jpg" alt="jaiho rummy" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">jaiho rummy</div>
            <a href="https://jaihorummycash.com/?code=E743FQGJMGT&t=1779851188" class="play-btn">Play</a>
        </div>

        <!-- Nayi Game 5: Hi rummy -->
        <div class="game-card" data-category="hot">
            <div class="hot-badge">Hot</div>
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/Y4QjvfRz/IMG-20260527-083518-645.jpg" alt="Hi rummy" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">Hi rummy</div>
            <a href="https://hirummyapp.vip/?code=RX3RPAXW9YA&t=1779851078" class="play-btn">Play</a>
        </div>

        <!-- Nayi Game 6: gogo rummy -->
        <div class="game-card" data-category="hot">
            <div class="hot-badge">Hot</div>
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/5xFTSv8P/IMG-20260527-083320-198.jpg" alt="gogo rummy" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">gogo rummy</div>
            <a href="https://www.gogorummyfreecash.com/?code=8FW3R3HE1HT&t=1779850964" class="play-btn">Play</a>
        </div>

        <!-- Nayi Game 7: Boss rummy -->
        <div class="game-card" data-category="hot">
            <div class="hot-badge">Hot</div>
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/RpFWTsC2/IMG-20260527-083035-119.jpg" alt="Boss rummy" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">Boss rummy</div>
            <a href="https://bossrummyyy.com/?code=0T8Y8BSL24N" class="play-btn">Play</a>
        </div>

        <!-- Nayi Game 8: Club INR -->
        <div class="game-card" data-category="hot">
            <div class="hot-badge">Hot</div>
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/mCGfLWTQ/IMG-20260527-082911-954.jpg" alt="Club INR" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">Club INR</div>
            <a href="https://clubinrvip1.net/?code=9VCFS6TH9QU&t=1779850732" class="play-btn">Play</a>
        </div>

        <!-- Nayi Game 9: Game Rummy -->
        <div class="game-card" data-category="hot">
            <div class="hot-badge">Hot</div>
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/XfpncM77/IMG-20260527-082804-195.jpg" alt="Game Rummy" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">Game Rummy</div>
            <a href="https://gamerummyd.com/?code=JXA44SSTNVW&t=1779850668" class="play-btn">Play</a>
        </div>

        <!-- Nayi Game 10: Rumble Rummy -->
        <div class="game-card" data-category="hot">
            <div class="hot-badge">Hot</div>
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/6CWcJ9t/IMG-20260527-082552-806.jpg" alt="Rumble Rummy" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">Rumble Rummy</div>
            <a href="https://www.rumblerummy2.vip/?code=UC02RS4D5NF&t=1779850561" class="play-btn">Play</a>
        </div>


        <!-- ================= PURANI 10 CASINO GAMES ================= -->

        <!-- Game 1: Yono rummy -->
        <div class="game-card" data-category="casino">
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/XxTS3tdZ/Screenshot-2026-0524-121950.png" alt="Yono rummy" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">Yono rummy</div>
            <a href="https://dp92t0mhjbqu9.cloudfront.net/yonorummyagent.apk" class="play-btn">Play</a>
        </div>

        <!-- Game 2: Spin 777 -->
        <div class="game-card" data-category="casino">
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/m5xd7qpZ/Screenshot-2026-0524-122312.png" alt="Spin 777" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">Spin 777</div>
            <a href="https://spin777ff.com/?code=7V9FYWPMDEW&t=1779605799" class="play-btn">Play</a>
        </div>

        <!-- Game 3: Spin Crush -->
        <div class="game-card" data-category="casino">
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/mF600568/Screenshot-2026-0524-122402.png" alt="Spin Crush" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">Spin Crush</div>
            <a href="https://bkfadsegtgs.safelyearnmillionsbysharingonepersonaqfxzqyj8.com/?code=ADEX2NMGVQT&t=1779605852" class="play-btn">Play</a>
        </div>

        <!-- Game 4: 567 slots -->
        <div class="game-card" data-category="casino">
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/tTHRNZNj/Screenshot-2026-0524-122448.png" alt="567 slots" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">567 slots</div>
            <a href="https://567slotsrefer08.cc/?code=4NY21SD2TVM&t=1779605926" class="play-btn">Play</a>
        </div>

        <!-- Game 5: IND rummy -->
        <div class="game-card" data-category="casino">
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/39KDGPBr/Screenshot-2026-0524-122547.png" alt="IND rummy" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">IND rummy</div>
            <a href="https://indrummym.in/?code=XU7ZAHJBQM3&t=1779605993" class="play-btn">Play</a>
        </div>

        <!-- Game 6: INR rummy -->
        <div class="game-card" data-category="casino">
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/dwJW89jT/IMG-20260526-094057-833.jpg" alt="INR rummy" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">INR rummy</div>
            <a href="https://inrrummy1.com/?code=7P2T88Y19UP&t=1779768631" class="play-btn">Play</a>
        </div>

        <!-- Game 7: jaiho 91 -->
        <div class="game-card" data-category="casino">
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/N2kGxkGD/IMG-20260526-093823-947.jpg" alt="jaiho 91" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">jaiho 91</div>
            <a href="https://jaiho91gaming.com/?code=C42NGHQ518G&t=1779715488" class="play-btn">Play</a>
        </div>

        <!-- Game 8: Bingo 101 -->
        <div class="game-card" data-category="casino">
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/S46hgCs6/Screenshot-2026-0524-214009.png" alt="Bingo 101" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">Bingo 101</div>
            <a href="https://bingo101aa.com/?code=AZTWFC1LN3P&t=1779638894" class="play-btn">Play</a>
        </div>

        <!-- Game 9: 101Z -->
        <div class="game-card" data-category="casino">
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/QF1qr0Xs/IMG-20260526-095252-042.jpg" alt="101Z" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">101Z</div>
            <a href="https://www.101z12.vip/?code=398ZMFCUX85&t=1779709639" class="play-btn">Play</a>
        </div>

        <!-- Game 10: IND Slots -->
        <div class="game-card" data-category="casino">
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/qYX8344d/IMG-20260526-095508-315.jpg" alt="IND Slots" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">IND Slots</div>
            <a href="https://d1bjlwgcobo9al.cloudfront.net/16/43943299/indslots_T2QDFH0P4AA.apk" class="play-btn">Play</a>
        </div>

    </div>

    <!-- Search & Tab Filtering Logic Script -->
    <script>
        // Search Bar Function
        function filterGames() {
            let input = document.getElementById('searchBox').value.toLowerCase();
            let cards = document.getElementsByClassName('game-card');
            let activeTab = document.querySelector('.tab-btn.active').getAttribute('onclick');
            
            // Determine active category
            let currentCategory = 'casino';
            if(activeTab.includes('hot')) currentCategory = 'hot';
            if(activeTab.includes('news') || activeTab.includes('bonuses') || activeTab.includes('promo')) currentCategory = 'empty';

            for (let i = 0; i < cards.length; i++) {
                let gameNameElement = cards[i].getElementsByClassName('game-name')[0];
                let cardCategory = cards[i].getAttribute('data-category');
                
                if (gameNameElement) {
                    let gameName = gameNameElement.textContent || gameNameElement.innerText;
                    
                    // Match name AND check if it belongs to the active tab category
                    if (gameName.toLowerCase().indexOf(input) > -1 && cardCategory === currentCategory) {
                        cards[i].style.display = "";
                    } else {
                        cards[i].style.display = "none";
                    }
                }
            }
        }

        // Tab Filter Function
        function filterCategory(category, button) {
            let tabs = document.getElementsByClassName('tab-btn');
            for(let i=0; i<tabs.length; i++) {
                tabs[i].classList.remove('active');
            }
            button.classList.add('active');

            // Clear search box text when switching tabs
            document.getElementById('searchBox').value = "";

            let cards = document.getElementsByClassName('game-card');
            for (let i = 0; i < cards.length; i++) {
                let cardCategory = cards[i].getAttribute('data-category');
                
                if (category === 'casino') {
                    if(cardCategory === 'casino') {
                        cards[i].style.display = "";
                    } else {
                        cards[i].style.display = "none";
                    }
                } else if (category === 'hot') {
                    if(cardCategory === 'hot') {
                        cards[i].style.display = "";
                    } else {
                        cards[i].style.display = "none";
                    }
         
