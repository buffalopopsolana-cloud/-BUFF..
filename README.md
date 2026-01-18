<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>$BUFF - POPBUFFALO</title>
    <style>
        :root { --bg-color: #5d9e52; --text-color: #ffffff; --header-bg: #000000; }
        body { margin: 0; padding: 0; background-color: var(--bg-color); font-family: 'Arial Black', sans-serif; text-align: center; color: var(--text-color); overflow-x: hidden; }

        /* Top CA Bar - Sticky Header */
        .ca-header { background: var(--header-bg); padding: 15px; border-radius: 0 0 40px 40px; width: 90%; margin: 0 auto; position: fixed; top: 0; left: 0; right: 0; z-index: 1000; box-shadow: 0 4px 15px rgba(0,0,0,0.3); cursor: pointer; }
        .ca-label { font-size: 0.7rem; color: #888; margin-bottom: 5px; }
        .ca-value { font-size: 0.8rem; word-break: break-all; color: #fff; font-family: monospace; }

        /* Main Content */
        .content { margin-top: 140px; padding: 20px; }
        .small-icon { width: 80px; height: 80px; border-radius: 50%; border: 3px solid white; margin-bottom: 10px; object-fit: cover; }

        /* Social Icons */
        .social-row { display: flex; justify-content: center; align-items: center; gap: 15px; margin-top: 15px; }
        .social-icon { width: 35px; height: 35px; cursor: pointer; background: white; border-radius: 8px; padding: 2px; }
        .about-btn { background: rgba(255,255,255,0.3); padding: 12px 30px; border-radius: 30px; border: 2px solid white; color: white; text-decoration: none; font-weight: bold; }

        /* Counter */
        .pop-count { font-size: 6rem; margin: 10px 0; text-shadow: 4px 4px 0px rgba(0,0,0,0.2); }

        /* The Buffalo - Clickable Area */
        .buffalo-container { position: relative; cursor: pointer; user-select: none; -webkit-tap-highlight-color: transparent; padding: 20px 0; }
        .buffalo-img { width: 80%; max-width: 350px; transition: transform 0.05s; border-radius: 20px; border: 5px solid white; box-shadow: 0 10px 30px rgba(0,0,0,0.4); }
        .buffalo-img:active { transform: scale(0.92); }

        /* Bottom Status Bar */
        .status-bar { background: rgba(255,255,255,0.2); backdrop-filter: blur(5px); padding: 15px; width: 85%; max-width: 400px; margin: 20px auto; border-radius: 20px; display: flex; justify-content: space-between; align-items: center; font-size: 1.1rem; }
    </style>
</head>
<body>

    <div class="ca-header" onclick="copyCA()">
        <div class="ca-label">CA:</div>
        <div class="ca-value" id="caValue">8B2eFjFFWiiquE3paXppwRtnswBEE8J9dU17jPfJZvJr</div>
    </div>

    <div class="content">
        <img src="https://github.com/BuffaloPopSolana-cloud/-BUFF../raw/main/1000112683.jpg" class="small-icon" alt="Buff Icon">
        
        <div class="social-row">
            <a href="https://t.me/buffalopop" class="about-btn">ABOUT $BUFF</a>
            <a href="https://t.me/buffalopop"><img src="https://cdn-icons-png.flaticon.com/512/2111/2111646.png" class="social-icon"></a>
            <a href="https://x.com/buffalopop35321"><img src="https://cdn-icons-png.flaticon.com/512/733/733579.png" class="social-icon"></a>
        </div>

        <h1>$BUFFALO</h1>

        <div class="pop-count" id="count">0</div>

        <div class="buffalo-container" onclick="popBuffalo()">
            <img src="https://github.com/BuffaloPopSolana-cloud/-BUFF../raw/main/1000112683.jpg" id="buffImg" class="buffalo-img" alt="Buffalo Inferno Mascot">
        </div>

        <div class="status-bar">
            <span>TOTAL POPS</span>
            <span id="totalPops">1,240,510</span>
            <span style="color: #00ff00;">✓</span>
        </div>
    </div>

    <script>
        let clicks = 0;
        let total = 1240510;

        function popBuffalo() {
            clicks++;
            total++;
            document.getElementById('count').innerText = clicks;
            document.getElementById('totalPops').innerText = total.toLocaleString();

            // Click Animation
            const img = document.getElementById('buffImg');
            img.style.transform = "scale(1.1)";
            setTimeout(() => { img.style.transform = "scale(1)"; }, 50);
        }

        function copyCA() {
            const ca = document.getElementById('caValue').innerText;
            navigator.clipboard.writeText(ca);
            alert("CA Copied! Time to buy $BUFF! 🐃🔥");
        }
    </script>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>$BUFF - POPBUFFALO</title>
    <style>
        :root { --bg-color: #5d9e52; --text-color: #ffffff; --header-bg: #000000; }
        body { margin: 0; padding: 0; background-color: var(--bg-color); font-family: 'Arial Black', sans-serif; text-align: center; color: var(--text-color); overflow-x: hidden; }

        /* Top CA Bar - Sticky Header */
        .ca-header { background: var(--header-bg); padding: 15px; border-radius: 0 0 40px 40px; width: 90%; margin: 0 auto; position: fixed; top: 0; left: 0; right: 0; z-index: 1000; box-shadow: 0 4px 15px rgba(0,0,0,0.3); cursor: pointer; }
        .ca-label { font-size: 0.7rem; color: #888; margin-bottom: 5px; }
        .ca-value { font-size: 0.8rem; word-break: break-all; color: #fff; font-family: monospace; }

        /* Main Content */
        .content { margin-top: 140px; padding: 20px; }
        .small-icon { width: 80px; height: 80px; border-radius: 50%; border: 3px solid white; margin-bottom: 10px; object-fit: cover; }

        /* Social Icons */
        .social-row { display: flex; justify-content: center; align-items: center; gap: 15px; margin-top: 15px; }
        .social-icon { width: 35px; height: 35px; cursor: pointer; background: white; border-radius: 8px; padding: 2px; }
        .about-btn { background: rgba(255,255,255,0.3); padding: 12px 30px; border-radius: 30px; border: 2px solid white; color: white; text-decoration: none; font-weight: bold; }

        /* Counter */
        .pop-count { font-size: 6rem; margin: 10px 0; text-shadow: 4px 4px 0px rgba(0,0,0,0.2); }

        /* The Buffalo - Clickable Area */
        .buffalo-container { position: relative; cursor: pointer; user-select: none; -webkit-tap-highlight-color: transparent; padding: 20px 0; }
        .buffalo-img { width: 80%; max-width: 350px; transition: transform 0.05s; border-radius: 20px; border: 5px solid white; box-shadow: 0 10px 30px rgba(0,0,0,0.4); }
        .buffalo-img:active { transform: scale(0.92); }

        /* Bottom Status Bar */
        .status-bar { background: rgba(255,255,255,0.2); backdrop-filter: blur(5px); padding: 15px; width: 85%; max-width: 400px; margin: 20px auto; border-radius: 20px; display: flex; justify-content: space-between; align-items: center; font-size: 1.1rem; }
    </style>
</head>
<body>

    <div class="ca-header" onclick="copyCA()">
        <div class="ca-label">CA:</div>
        <div class="ca-value" id="caValue">8B2eFjFFWiiquE3paXppwRtnswBEE8J9dU17jPfJZvJr</div>
    </div>

    <div class="content">
        <img src="https://github.com/BuffaloPopSolana-cloud/-BUFF../raw/main/1000112683.jpg" class="small-icon" alt="Buff Icon">
        
        <div class="social-row">
            <a href="https://t.me/buffalopop" class="about-btn">ABOUT $BUFF</a>
            <a href="https://t.me/buffalopop"><img src="https://cdn-icons-png.flaticon.com/512/2111/2111646.png" class="social-icon"></a>
            <a href="https://x.com/buffalopop35321"><img src="https://cdn-icons-png.flaticon.com/512/733/733579.png" class="social-icon"></a>
        </div>

        <h1>$BUFFALO</h1>

        <div class="pop-count" id="count">0</div>

        <div class="buffalo-container" onclick="popBuffalo()">
            <img src="https://github.com/BuffaloPopSolana-cloud/-BUFF../raw/main/1000112683.jpg" id="buffImg" class="buffalo-img" alt="Buffalo Inferno Mascot">
        </div>

        <div class="status-bar">
            <span>TOTAL POPS</span>
            <span id="totalPops">1,240,510</span>
            <span style="color: #00ff00;">✓</span>
        </div>
    </div>

    <script>
        let clicks = 0;
        let total = 1240510;

        function popBuffalo() {
            clicks++;
            total++;
            document.getElementById('count').innerText = clicks;
            document.getElementById('totalPops').innerText = total.toLocaleString();

            // Click Animation
            const img = document.getElementById('buffImg');
            img.style.transform = "scale(1.1)";
            setTimeout(() => { img.style.transform = "scale(1)"; }, 50);
        }

        function copyCA() {
            const ca = document.getElementById('caValue').innerText;
            navigator.clipboard.writeText(ca);
            alert("CA Copied! Time to buy $BUFF! 🐃🔥");
        }
    </script>

</body>
</html>
