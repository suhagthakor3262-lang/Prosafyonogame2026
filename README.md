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

        /* Games Grid System (2 Columns Layout) */
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

    <header>
        <div class="logo">ProSafe<span>Bet.</span></div>
        <div class="menu-icon">&#9776;</div>
    </header>

    <div class="search-container">
        <input type="text" id="searchBox" class="search-box" placeholder="What you want to search ?" onkeyup="filterGames()">
    </div>

    <div class="telegram-ticker">
        <marquee behavior="scroll" direction="left" scrollamount="5">
            <a href="https://t.me/invitnew" target="_blank">📢 Join Our Official Telegram Channel For Daily Updates! Click Here: https://t.me/invitnew 🚀</a>
        </marquee>
    </div>

    <h2 class="section-title">New on Game</h2>
    <p class="section-subtitle">Discover what's new on Game and enjoy the best new game.</p>

    <div class="games-grid">

        <div class="game-card">
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/XxTS3tdZ/Screenshot-2026-0524-121950.png" alt="Yono rummy" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">Yono rummy</div>
            <a href="https://dp92t0mhjbqu9.cloudfront.net/yonorummyagent.apk" class="play-btn">Play</a>
        </div>

        <div class="game-card">
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/m5xd7qpZ/Screenshot-2026-0524-122312.png" alt="Spin 777" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">Spin 777</div>
            <a href="https://spin777ff.com/?code=7V9FYWPMDEW&t=1779605799" class="play-btn">Play</a>
        </div>

        <div class="game-card">
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/mF600568/Screenshot-2026-0524-122402.png" alt="Spin Crush" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">Spin Crush</div>
            <a href="https://bkfadsegtgs.safelyearnmillionsbysharingonepersonaqfxzqyj8.com/?code=ADEX2NMGVQT&t=1779605852" class="play-btn">Play</a>
        </div>

        <div class="game-card">
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/tTHRNZNj/Screenshot-2026-0524-122448.png" alt="567 slots" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">567 slots</div>
            <a href="https://567slotsrefer08.cc/?code=4NY21SD2TVM&t=1779605926" class="play-btn">Play</a>
        </div>

        <div class="game-card">
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/39KDGPBr/Screenshot-2026-0524-122547.png" alt="IND rummy" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">IND rummy</div>
            <a href="https://indrummym.in/?code=XU7ZAHJBQM3&t=1779605993" class="play-btn">Play</a>
        </div>

        <div class="game-card">
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/dwJW89jT/IMG-20260526-094057-833.jpg" alt="INR rummy" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">INR rummy</div>
            <a href="https://inrrummy1.com/?code=7P2T88Y19UP&t=1779768631" class="play-btn">Play</a>
        </div>

        <div class="game-card">
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/N2kGxkGD/IMG-20260526-093823-947.jpg" alt="jaiho 91" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">jaiho 91</div>
            <a href="https://jaiho91gaming.com/?code=C42NGHQ518G&t=1779715488" class="play-btn">Play</a>
        </div>

        <div class="game-card">
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/S46hgCs6/Screenshot-2026-0524-214009.png" alt="Bingo 101" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">Bingo 101</div>
            <a href="https://bingo101aa.com/?code=AZTWFC1LN3P&t=1779638894" class="play-btn">Play</a>
        </div>

        <div class="game-card">
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/QF1qr0Xs/IMG-20260526-095252-042.jpg" alt="101Z" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">101Z</div>
            <a href="https://www.101z12.vip/?code=398ZMFCUX85&t=1779709639" class="play-btn">Play</a>
        </div>

        <div class="game-card">
            <div class="game-image-wrapper">
                <img src="https://i.ibb.co/qYX8344d/IMG-20260526-095508-315.jpg" alt="IND Slots" class="game-img">
            </div>
            <div class="rating">★ 10</div>
            <div class="game-name">IND Slots</div>
            <a href="https://d1bjlwgcobo9al.cloudfront.net/16/43943299/indslots_T2QDFH0P4AA.apk" class="play-btn">Play</a>
        </div>

    </div>

    <script>
        function filterGames() {
            let input = document.getElementById('searchBox').value.toLowerCase();
            let cards = document.getElementsByClassName('game-card');
            
            for (let i = 0; i < cards.length; i++) {
                let gameNameElement = cards[i].getElementsByClassName('game-name')[0];
                if (gameNameElement) {
                    let gameName = gameNameElement.textContent || gameNameElement.innerText;
                    if (gameName.toLowerCase().indexOf(input) > -1) {
                        cards[i].style.display = "";
                    } else {
                        cards[i].style.display = "none";
                    }
                }
            }
        }
    </script>

</body>
</html>
