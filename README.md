<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>$BUFF - The Strongest Community</title>
    <style>
        :root {
            --bg-navy: #0f172a;
            --accent-yellow: #facc15;
            --accent-orange: #fb923c;
            --card-bg: rgba(30, 41, 59, 0.5);
            --text-gray: #94a3b8;
        }

        body {
            margin: 0; padding: 0;
            background-color: var(--bg-navy);
            font-family: 'Inter', sans-serif;
            color: white;
            display: flex; flex-direction: column; align-items: center;
        }

        /* --- HERO SECTION --- */
        header {
            width: 100%; max-width: 500px;
            display: flex; justify-content: space-between; align-items: center;
            padding: 30px 20px;
        }

        .logo { color: var(--accent-yellow); font-size: 1.8rem; font-weight: 900; }
        .buy-btn { background: var(--accent-yellow); color: black; padding: 10px 25px; border-radius: 25px; font-weight: bold; text-decoration: none; }

        .hero { text-align: center; padding: 40px 20px; }
        .hero h1 { font-size: 4.5rem; margin: 0; font-weight: 900; font-style: italic; line-height: 1; }
        .hero h1 span { color: transparent; -webkit-text-stroke: 1px white; }
        .gradient-text { background: linear-gradient(to right, var(--accent-yellow), var(--accent-orange)); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        
        .hero p { color: var(--text-gray); font-size: 1.2rem; margin: 30px 0; max-width: 400px; }

        /* --- CA BOX --- */
        .ca-box {
            background: var(--card-bg); border: 1px solid rgba(255,255,255,0.1);
            padding: 20px; border-radius: 20px; width: 85%; max-width: 400px;
            text-align: center; cursor: pointer; position: relative;
        }
        .ca-text { color: var(--accent-yellow); font-family: monospace; word-break: break-all; font-size: 1rem; }

        /* --- ABOUT SECTION --- */
        .section-title { font-size: 2.5rem; font-weight: 900; margin-top: 80px; }
        .about-text { color: white; padding: 0 25px; line-height: 1.6; max-width: 450px; text-align: center; }
        .highlight { color: var(--accent-yellow); font-weight: bold; }

        /* --- TOKENOMICS --- */
        .token-card {
            background: var(--card-bg); border: 1px solid rgba(255,255,255,0.1);
            border-radius: 20px; width: 85%; max-width: 400px;
            padding: 40px 20px; margin-top: 20px; text-align: center;
        }
        .token-val { color: var(--accent-yellow); font-size: 2.5rem; font-weight: 900; margin: 0; }
        .token-label { color: var(--text-gray); text-transform: uppercase; letter-spacing: 2px; font-size: 0.9rem; margin-top: 10px; }

        /* --- WHITEPAPER CARD --- */
        .whitepaper-card {
            background: linear-gradient(to bottom, var(--accent-yellow), var(--accent-orange));
            border-radius: 20px; width: 85%; max-width: 400px;
            padding: 40px 20px; margin: 60px 0; text-align: center; color: black;
        }
        .whitepaper-card h2 { font-size: 2rem; font-weight: 900; margin: 0; }
        .whitepaper-card p { font-weight: 500; margin: 20px 0; }
        .view-btn { background: var(--bg-navy); color: white; padding: 15px 40px; border-radius: 12px; font-weight: bold; text-decoration: none; display: inline-block; }

        footer { padding-bottom: 50px; display: flex; gap: 20px; }
    </style>
</head>
<body>

    <header>
        <div class="logo">$BUFF</div>
        <a href="#" class="buy-btn">Buy Now</a>
    </header>

    <div class="hero">
        <h1>GET <span class="gradient-text">BUFF</span></h1>
        <p>The strongest community-driven token on the chain. No taxes, no nonsense. Just gains.</p>
        
        <div class="ca-box" onclick="copyCA()">
            <div class="ca-text" id="caValue">8B2eFjFFWiiquE3paXppwRtnswBEE8J9dU17jPfJZvJr</div>
        </div>
    </div>

    <h2 class="section-title">About</h2>
    <p class="about-text">
        In a market often saturated with complexity and hidden agendas, <span class="highlight">$BUFF</span> was born from a simple realization: The true strength of a blockchain project lies in its community, not its complexity.
    </p>

    <h2 class="section-title">Tokenomics</h2>
    
    <div class="token-card">
        <p class="token-val">1B</p>
        <p class="token-label">Total Supply</p>
    </div>

    <div class="token-card">
        <p class="token-val">0%</p>
        <p class="token-label">Buy/Sell Tax</p>
    </div>

    <div class="token-card">
        <p class="token-val">Burned</p>
        <p class="token-label">Liquidity Pool</p>
    </div>

    <div class="whitepaper-card">
        <h2>Read the Whitepaper</h2>
        <p>Deep dive into the utility and future roadmap of $BUFF.</p>
        <a href="#" class="view-btn">View WhitePaper</a>
    </div>

    <footer>
        <a href="#"><img src="https://cdn-icons-png.flaticon.com/512/2111/2111646.png" width="30"></a>
        <a href="#"><img src="https://cdn-icons-png.flaticon.com/512/733/733579.png" width="30"></a>
    </footer>

    <script>
        function copyCA() {
            const ca = document.getElementById('caValue').innerText;
            navigator.clipboard.writeText(ca);
            alert("Contract Address Copied! 🐃");
        }
    </script>

</body>
</html>
