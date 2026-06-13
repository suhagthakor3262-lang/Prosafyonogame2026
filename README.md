<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ProSafe Yono Games Portal</title>
    <style>
        body { background-color: #121212; color: #fff; margin: 0; padding: 15px; font-family: sans-serif; }
        .live-ticker { background: #1e1e1e; padding: 12px; border-radius: 8px; margin-bottom: 20px; border-left: 4px solid #ff0000; }
        .live-badge { background: #ff0000; color: #fff; padding: 2px 6px; font-size: 11px; font-weight: bold; border-radius: 3px; margin-right: 8px; }
        .game-card { background: #1e1e1e; border-radius: 12px; padding: 20px; text-align: center; margin-bottom: 20px; border: 1px solid #333; }
        .game-logo { width: 80px; height: 80px; border-radius: 15px; margin-bottom: 10px; }
        .play-btn { display: block; background: #00ffcc; color: #000; padding: 15px; border-radius: 10px; font-weight: bold; text-decoration: none; font-size: 16px; margin-top: 15px; }
        .disclaimer-box { background: #1e1e1e; padding: 15px; border-radius: 10px; font-size: 12px; color: #aaa; border: 1px solid #333; text-align: justify; margin-top: 20px; }
    </style>
</head>
<body>

    <div class="live-ticker">
        <span class="live-badge">LIVE</span>
        <span id="ticker">User ID 234*** just won ₹22,400 in Club INR!</span>
    </div>

    <!-- IND Club Section -->
    <div class="game-card">
        <img src="https://i.ibb.co/Df1Ckfb6/IMG-20260527-084343-458.jpg" class="game-logo" alt="IND Club App">
        <h3>IND Club</h3>
        <p style="color: #ef4444; font-size: 12px; font-weight: bold;">NEW ⭐ 10</p>
        <a href="ind-club-page.html" class="play-btn">Play</a>
    </div>

    <!-- Content Area -->
    <h3>Welcome to ProSafe Yono Games Portal 2026</h3>
    <p style="color: #aaa; font-size: 14px; margin: 10px 0;">Your ultimate destination to find verified and secure direct download links for all top-rated Yono gaming applications.</p>

    <div class="disclaimer-box">
        Responsible Gaming Disclaimer: This platform only provides verified app links and official descriptions for informational and educational purposes. All gaming applications available on this portal carry financial risks and can be addictive. We strictly encourage players to play responsibly.
    </div>

    <p style="text-align: center; font-size: 12px; color: #666; margin-top: 20px;">© 2026 ProSafe Yono Games. All Rights Reserved.</p>

    <script>
        setInterval(() => {
            document.getElementById('ticker').innerText = "User ID " + Math.floor(100+Math.random()*900) + "*** just won ₹" + (Math.floor(Math.random()*20000)+5000) + " in Yono 777!";
        }, 4000);
    </script>
</body>
</html>
