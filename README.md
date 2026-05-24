<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Yono Game Zone</title>
    <style>
        /* Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f4f6f9;
            color: #333;
            padding-bottom: 20px;
        }

        /* Navbar Header */
        .navbar {
            background-color: #009640; /* Green theme */
            color: white;
            padding: 12px 15px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .nav-left {
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .menu-icon {
            font-size: 24px;
            cursor: pointer;
        }

        .logo {
            font-weight: bold;
            font-size: 18px;
            line-height: 1.2;
        }

        /* Input field font-size 16px fixes auto-zoom on mobile */
        .search-box {
            width: 45%;
            max-width: 250px;
            padding: 8px 12px;
            border: 1px solid #ccc;
            border-radius: 4px;
            outline: none;
            color: #333;
            font-size: 16px; 
        }

        /* Section Container */
        .container {
            padding: 15px;
            max-width: 600px;
            margin: 0 auto;
        }

        .section-title {
            font-size: 18px;
            font-weight: bold;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        /* Top 3 Games Cards Grid */
        .top-games-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 10px;
            margin-bottom: 25px;
        }

        .top-card {
            background: #fff;
            border: 2px solid #ffe600; /* Yellow border */
            border-radius: 12px;
            padding: 10px 5px;
            text-align: center;
            position: relative;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
            text-decoration: none;
            color: inherit;
            display: block;
        }

        .badge {
            position: absolute;
            top: -10px;
            left: -5px;
            background: #111e30;
            color: white;
            width: 24px;
            height: 24px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 12px;
            font-weight: bold;
        }

        .top-card img {
            width: 100%;
            max-width: 65px;
            aspect-ratio: 1/1;
            border-radius: 12px;
            margin-bottom: 8px;
            object-fit: cover;
        }

        .top-card p {
            font-size: 12px;
            font-weight: bold;
            color: #222;
            white-space: nowrap;
            overflow: hidden;
            text-overflow: ellipsis;
        }

        /* List View Games */
        .game-list-item {
            background: #fff;
            border-radius: 12px;
            padding: 12px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin-bottom: 12px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.04);
        }

        .game-info-box {
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .game-info-box img {
            width: 65px;
            height: 65px;
            border-radius: 12px;
            object-fit: cover;
        }

        .game-details h3 {
            font-size: 15px;
            color: #111;
            margin-bottom: 2px;
            display: flex;
            align-items: center;
            gap: 5px;
        }

        .tag-new {
            background-color: #ff3b30;
            color: white;
            font-size: 9px;
            padding: 1px 4px;
            border-radius: 3px;
            font-weight: bold;
        }

        .bonus-text {
            font-size: 12px;
            color: #222;
            font-weight: 500;
            margin-bottom: 3px;
            line-height: 1.4;
        }

        .stars {
            color: #ffcc00;
            font-size: 12px;
        }

        /* Download Button */
        .download-btn {
            background-color: #009640;
            color: white;
            border: none;
            padding: 8px 16px;
            border-radius: 6px;
            font-weight: bold;
            font-size: 14px;
            cursor: pointer;
            text-decoration: none;
            transition: background 0.2s;
            text-align: center;
        }

        .download-btn:hover {
            background-color: #007a33;
        }
    </style>
</head>
<body>

    <header class="navbar">
        <div class="nav-left">
            <div class="menu-icon">&#9776;</div>
            <div class="logo">🎮 Yono Game<br>Zone</div>
        </div>
        <input type="text" id="gameSearch" class="search-box" placeholder="Search games..." onkeyup="searchGames()">
    </header>

    <main class="container">
        
        <div id="topSection">
            <h2 class="section-title">🏆 Top 3 Games</h2>
            <div class="top-games-grid">
                
                <a href="https://dp92t0mhjbqu9.cloudfront.net/yonorummyagent.apk" class="top-card">
                    <span class="badge">1</span>
                    <img src="https://img.icons8.com/color/144/joker-card.png" alt="Y
                    
