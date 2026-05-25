
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Yono Game Zone</title>
    <style>
        /* Base Styles for compact grid */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
        }

        body {
            background-color: #f7f7f7;
            color: #333;
            -webkit-text-size-adjust: 100%;
        }

        /* Redesigned Header: ProSafe Bet Style */
        .header {
            background-color: #009640; /* Solid Green */
            color: white;
            padding: 8px 12px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .header-logo {
            display: flex;
            align-items: center;
            gap: 5px;
            font-weight: bold;
            font-size: 16px;
        }

        .header-logo img {
            width: 20px;
            height: 20px;
        }

        /* Search input moved inside header, styled like target image */
        .search-container {
            flex-grow: 1;
            margin: 0 15px;
            max-width: 250px;
            position: relative;
        }

        .search-box {
            width: 100%;
            padding: 6px 12px 6px 12px;
            border: 1px solid rgba(255,255,255,0.4);
            border-radius: 4px;
            background-color: rgba(255,255,255,0.2);
            color: white;
            font-size: 14px;
            outline: none;
        }

        .search-box::placeholder {
            color: rgba(255,255,255,0.7);
        }

        .header-menu {
            font-size: 20px;
            cursor: pointer;
        }

        /* Main Content Grid: Zero gap ProSafe style */
        .content-container {
            display: grid;
            grid-template-columns: repeat(2, 1fr); /* Two column grid */
            gap: 10px;
            padding: 10px;
        }

        .section-header {
            grid-column: 1 / -1; /* Header spans across both columns */
            font-size: 16px;
            font-weight: bold;
            color: #009640;
            padding: 5px 0;
            display: flex;
            align-items: center;
            gap: 6px;
        }

        /* Re-styled Card: ProSafe Bet Style (No gaps) */
        .game-card {
            background-color: white;
            border: 1px solid #eaeaea;
            border-radius: 8px;
            overflow: hidden;
            text-align: center;
            text-decoration: none;
            color: inherit;
            display: flex;
            flex-direction: column;
            position: relative;
            box-shadow: 0 1px 3px rgba(0,0,0,0.05);
            transition: transform 0.2s;
        }

        .game-card:active {
            transform: scale(0.98);
        }

        /* Rank Badge for Top 3 */
        .rank-badge {
            position: absolute;
            top: 6px;
            left: 6px;
            background-color: rgba(0,0,0,0.8);
            color: white;
            font-size: 10px;
            font-weight: bold;
            padding: 2px 6px;
            border-radius: 4px;
            z-index: 10;
        }

        .card-image-container {
            padding: 20px 20px 10px 20px;
        }

        /* Full circle game icon like ProSafe Bet */
        .game-card img.game-icon {
            width: 100%;
            aspect-ratio: 1/1;
            object-fit: cover;
            border-radius: 50%;
            display: block;
        }

        .card-details {
            padding: 0 10px 10px 10px;
            display: flex;
            flex-direction: column;
            gap: 2px;
            flex-grow: 1;
        }

        .rating-row {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 3px;
            color: #ff9f00; /* Star Color */
            font-size: 12px;
            font-weight: bold;
        }

        .game-title {
            font-size: 13px;
            font-weight: bold;
            color: #222;
            white-space: nowrap;
            overflow: hidden;
            text-overflow: ellipsis;
        }

        /* Wider blue button like target image */
        .card-action-btn {
            background-color: #1e88e5; /* ProSafe Blue Button */
            color: white;
            font-size: 12px;
            font-weight: bold;
            padding: 8px;
            border-radius: 4px;
            border: none;
            cursor: pointer;
            margin-top: auto;
            text-align: center;
            width: 100%;
            display: inline-block;
            transition: background-color 0.2s;
        }

        .card-action-btn:hover {
            background-color: #1565c0;
        }

    </style>
</head>
<body>

    <header class="header">
        <div class="header-logo">
            <img src="https://img.icons8.com/material-rounded/24/ffffff/dice.png" alt="Dice Icon">
            <span>Yono Game Zone</span>
        </div>
        <div class="search-container">
            <input type="text" id="gameSearch" class="search-box" placeholder="Search..." onkeyup="searchGames()">
        </div>
        <div class="header-menu">☰</div>
    </header>

    <main class="content-container">
        
        <h2 class="section-header" id="topHeader">🏆 Top 3 Games</h2>
        
        <a href="https://diwaslot.com" class="game-card top-game-item">
            <span class="rank-badge">1</span>
            <div class="card-image-container">
                <img src="https://kommodo.ai/i/7S8lx5PODYclMxvtgyJg/raw" class="game-icon" alt="Diva Slots">
            </div>
            <div class="card-details">
                <div class="rating-row">
                    <span>⭐</span>
                    <span>9.9</span>
                </div>
                <p class="game-title">Diva Slots</p>
                <span class="card-action-btn">Download</span>
            </div>
        </a>

        <a href="https://jaiho91.com" class="game-card top-game-item">
            <span class="rank-badge">2</span>
            <div class="card-image-container">
                <img src="https://kommodo.ai/i/GKnzMCTD18tNEOb9fXH2/raw" class="game-icon" alt="Jai Ho 91">
            </div>
            <div class="card-details">
                <div class="rating-row">
                    <span>⭐</span>
                    <span>9.9</span>
                </div>
                <p class="game-title">Jai Ho 91</p>
                <span class="card-action-btn">Download</span>
            </div>
        </a>

        <a href="https://yonogames.com" class="game-card top-game-item">
            <span class="rank-badge">3</span>
            <div class="card-image-container">
                <img src="https://kommodo.ai/i/nPz8bs8X1zwcww192mHh/raw" class="game-icon" alt="Yono Games">
            </div>
            <div class="card-details">
                <div class="rating-row">
                    <span>⭐</span>
                    <span>10.0</span>
                </div>
                <p class="game-title">Yono Games</p>
                <span class="card-action-btn">Download</span>
            </div>
        </a>

        <h2 class="section-header">✨ All Games List</h2>

        <a href="https://567slots.com" class="game-card main-game-item">
            <div class="card-image-container">
                <img src="https://kommodo.ai/i/qJM9vbDfqYD5rC2ZZQ80/raw" class="game-icon" alt="567 Slots">
            </div>
            <div class="card-details">
                <div class="rating-row">
                    <span>⭐</span>
                    <span>9.8</span>
                </div>
                <p class="game-title">567 Slots</p>
                <span class="card-action-btn">Download</span>
            </div>
        </a>

        <a href="https://indrummy.com" class="game-card main-game-item">
            <div class="card-image-container">
                <img src="https://kommodo.ai/i/8MwDhM3mLfBlpVG8eG9c/raw" class="game-icon" alt="IND Rummy">
            </div>
            <div class="card-details">
                <div class="rating-row">
                    <span>⭐</span>
                    <span>10.0</span>
                </div>
                <p class="game-title">IND Rummy</p>
                <span class="card-action-btn">Download</span>
            </div>
        </a>

        <a href="https://bkfadsegtgs.safelyearnmillionsbysharingonepersonaqfxzqyj8.com/?code=ADEX2NMGVQT&t=1779605852" class="game-card main-game-item">
            <div class="card-image-container">
                <img src="https://img.icons8.com/color/144/casino-chips.png" class="game-icon" alt="Spin Crush">
            </div>
            <div class="card-details">
                <div class="rating-row">
                    <span>⭐</span>
                    <span>9.7</span>
                </div>
                <p class="game-title">Spin Crush</p>
                <span class="card-action-btn">Download</span>
            </div>
        </a>

        <a href="https://spin777ff.com/?code=7V9FYWPMDEW&t=1779605799" class="game-card main-game-item">
            <div class="card-image-container">
                <img src="https://img.icons8.com/color/144/slot-machine.png" class="game-icon" alt="Spin 777">
            </div>
            <div class="card-details">
                <div class="rating-row">
                    <span>⭐</span>
                    <span>9.8</span>
                </div>
                <p class="game-title">Spin 777</p>
                <span class="card-action-btn">Download</span>
            </div>
        </a>

    </main>

    <script>
        // Data load hone ke baad search function chalega
        function searchGames() {
            let input = document.getElementById('gameSearch').value.toLowerCase();
            let gameItems = document.getElementsByClassName('game-card');
            let topHeader = document.getElementById('topHeader');

            // Searching ke waqt "Top 3 Games" title chhupane ke liye
            if (input.length > 0) {
                topHeader.style.display = 'none';
            } else {
                topHeader.style.display = 'flex';
            }

            for (let i = 0; i < gameItems.length; i++) {
                // Game title ko search kar rahe hain
                let gameTitle = gameItems[i].getElementsByClassName('game-title')[0].innerText.toLowerCase();
                
                if (gameTitle.includes(input)) {
                    // Title check kar rahe hain, full rank span nahi
                    if (gameItems[i].classList.contains('top-game-item') && input.length === 0) {
                         gameItems[i].style.display = "flex";
                    } else if (gameItems[i].classList.contains('main-game-item')) {
                         gameItems[i].style.display = "flex";
                    } else if (gameItems[i].classList.contains('top-game-item') && input.length > 0) {
                        // Title check only while searching within top items
                         gameItems[i].style.display = "flex";
                    } else {
                        gameItems[i].style.display = "none";
                    }
                    
                    // Standard filtering check
                    gameItems[i].style.display = "flex";

                } else {
                    gameItems[i].style.display = "none";
                }
            }
        }
    </script>
</body>
</html>
/* Banner Main Container Style */
.telegram-banner-link {
  text-decoration: none; /* Link underline hatane ke liye */
  display: block;
  margin: 15px auto;
  max-width: 600px; /* Aap isse chota-bada kar sakte hain */
  width: 90%;
}

.telegram-banner-container {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: #f0f7ff; /* Halka blue background */
  border: 2px solid #1e65a3; /* Dark blue border */
  border-radius: 12px; /* Curved corners */
  padding: 10px 15px;
  overflow: hidden;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
  cursor: pointer;
  position: relative;
}

/* Rolling Text Container */
.marquee-box {
  flex: 1;
  overflow: hidden;
  white-space: nowrap;
  display: flex;
  align-items: center;
}

/* Rolling Text Animation */
.marquee-text {
  display: inline-block;
  font-family: Arial, sans-serif;
  font-size: 18px;
  font-weight: bold;
  color: #114b7a; /* Image jaisa blue color */
  padding-right: 50px;
  animation: rollText 10s linear infinite; /* 10s se speed control hogi */
}

@keyframes rollText {
  0% {
    transform: translateX(100%);
  }
  100% {
    transform: translateX(-100%);
  }
}

/* Button Style */
.join-btn {
  background-color: #005691; /* Dark blue button */
  color: white;
  border: none;
  border-radius: 8px;
  padding: 10px 20px;
  font-size: 16px;
  font-weight: bold;
  cursor: pointer;
  white-space: nowrap;
  margin-left: 10px;
  transition: background 0.3s ease;
  z-index: 2; /* Taaki button text ke upar rahe */
}

/* Button Hover Effect */
.join-btn:hover {
  background-color: #003d66;
}
