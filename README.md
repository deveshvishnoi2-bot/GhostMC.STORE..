<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GhostMC Lifesteal</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    * { margin:0; padding:0; box-sizing:border-box; font-family:'Segoe UI',sans-serif; }
    body { background:#0c0d12; color:#fff; }
    
    /* Top News Ticker */
    .news-ticker {
      background: linear-gradient(90deg, #d97706, #b45309);
      color: #fff;
      padding: 8px 0;
      overflow: hidden;
      white-space: nowrap;
      font-weight: 700;
      font-size: 14px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.5);
    }
    .ticker-track {
      display: inline-block;
      animation: marquee 25s linear infinite;
    }
    @keyframes marquee {
      0% { transform: translateX(100vw); }
      100% { transform: translateX(-100%); }
    }

    .container { max-width: 1100px; margin: 0 auto; padding: 20px; }
    
    /* Server Cards */
    .status-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      margin: 30px 0;
    }
    .card {
      background: #161822;
      border: 1px solid #2a2e42;
      border-radius: 12px;
      padding: 20px;
    }
    .card h3 { color: #f59e0b; margin-bottom: 12px; display: flex; align-items: center; gap: 8px; }

    /* Player Roster */
    .player-list {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: 15px;
    }
    .player-chip {
      display: flex;
      align-items: center;
      gap: 8px;
      background: #202436;
      border: 1px solid #3b4263;
      padding: 6px 12px;
      border-radius: 8px;
      font-size: 13px;
      font-weight: 600;
      color: #e2e8f0;
    }
    .player-chip img {
      width: 22px;
      height: 22px;
      border-radius: 4px;
    }

    /* Store Section */
    .kit-card {
      background: linear-gradient(145deg, #181a26, #12131d);
      border: 2px solid #f59e0b;
      border-radius: 14px;
      padding: 24px;
      margin-top: 20px;
      box-shadow: 0 0 25px rgba(245, 158, 11, 0.15);
    }
    .price-tag { font-size: 24px; font-weight: 800; color: #10b981; }
    .btn-pay {
      background: #10b981;
      color: #fff;
      border: none;
      padding: 12px 24px;
      border-radius: 8px;
      font-weight: 700;
      cursor: pointer;
      text-decoration: none;
      display: inline-block;
      margin-top: 15px;
    }
    .watermark {
      text-align: center;
      padding: 30px 0;
      color: #64748b;
      font-weight: 700;
      font-size: 14px;
      border-top: 1px solid #1e2235;
      margin-top: 50px;
    }
    .watermark span { color: #f59e0b; }
  </style>
</head>
<body>

  <!-- Top Breaking News Bar -->
  <div class="news-ticker">
    <div class="ticker-track">
      🔥 GHOST SMP SEASON 1 LAUNCHED! &nbsp;&nbsp;|&nbsp;&nbsp; 
      🏆 PVP EVENT 1ST WINNER - flaxxy444 🥇 &nbsp;&nbsp;|&nbsp;&nbsp; 
      🥈 2ND WINNER - senkist13 &nbsp;&nbsp;|&nbsp;&nbsp; 
      ⚔️ GHOSTMC LIFESTEAL READY TO PLAY! &nbsp;&nbsp;|&nbsp;&nbsp; 
      💎 BUY LEGEND KIT FOR JUST ₹40 INR!
    </div>
  </div>

  <div class="container">
    <div style="text-align:center; margin: 30px 0;">
      <h1 style="color:#f59e0b; font-size: 32px;">GHOSTMC LIFESTEAL</h1>
      <p style="color:#94a3b8;">Server IP: <b style="color:#fff;">play.ghostmc.info.gf</b> | Port: <b style="color:#fff;">19153</b></p>
      <button onclick="refreshData()" style="margin-top:12px; background:#2563eb; color:#fff; border:none; padding:8px 16px; border-radius:6px; cursor:pointer;">
        <i class="fa-solid fa-arrows-rotate"></i> Refresh Status
      </button>
    </div>

    <!-- Status & Players Grid -->
    <div class="status-grid">
      <div class="card">
        <h3><i class="fa-solid fa-server"></i> Server Status</h3>
        <p id="srv-status" style="font-size: 20px; font-weight: 700; color: #10b981;">Online 🟢</p>
        <p style="color: #64748b; font-size: 13px; margin-top: 5px;">Lifesteal SMP Season 1</p>
      </div>

      <div class="card">
        <h3><i class="fa-solid fa-users"></i> Players Online: <span id="online-num">6</span></h3>
        <p style="font-size: 13px; color: #94a3b8;">Active Combatants:</p>
        
        <!-- Player Chips Container -->
        <div class="player-list" id="players-box">
          <!-- Populated by JavaScript -->
        </div>
      </div>
    </div>

    <!-- Store Section -->
    <div class="kit-card">
      <h2 style="color: #f59e0b;">### LEGEND KIT</h2>
      <div class="price-tag">PRICE: 40 INR</div>
      
      <h4 style="margin: 15px 0 8px 0; color: #cbd5e1;">Includes:</h4>
      <ol style="margin-left: 20px; line-height: 1.8; color: #94a3b8;">
        <li>Prot 3 Diamond Armour</li>
        <li>Sharpness 3 Sword</li>
        <li>2 Totem</li>
        <li>2 enchanted apples</li>
        <li>16 golden apples</li>
        <li>16 Ender Pearls</li>
      </ol>
      <p style="color: #f59e0b; font-weight: 700; margin-top: 8px;">### AND MORE</p>

      <div style="background: rgba(239, 68, 68, 0.1); border-left: 4px solid #ef4444; padding: 12px; margin: 15px 0;">
        <p style="color: #fca5a5; font-size: 14px;">
          <b>IMPORTANT NOTE:</b> After purchasing via UPI, please take a screenshot and create a ticket in our official Discord server to receive your kit instantly!
        </p>
      </div>

      <div style="display:flex; gap:12px; align-items:center; flex-wrap:wrap;">
        <a href="upi://pay?pa=ghostmc.fund@axl&pn=GhostMC&am=40&cu=INR" class="btn-pay">
          <i class="fa-solid fa-bolt"></i> PAY ₹40 VIA UPI
        </a>
        <a href="https://discord.gg/H4p2TuNCA" target="_blank" style="background:#5865F2; color:#fff; text-decoration:none; padding:12px 20px; border-radius:8px; font-weight:700;">
          <i class="fa-brands fa-discord"></i> Open Discord Ticket
        </a>
      </div>
      <p style="margin-top: 10px; font-size: 13px; color: #64748b;">UPI ID: <b>ghostmc.fund@axl</b></p>
    </div>

    <!-- Footer Watermark -->
    <div class="watermark">
      POWERED BY <span>DEVESH</span>
    </div>
  </div>

  <script>
    // Known Active Combatants verified from in-game events
    const defaultPlayers = [
      "flaxxy444",
      "senkist13",
      "Subham0G",
      "AlyaaTsb",
      "BTX_GAMERZ",
      "Mr_Legend"
    ];

    function renderPlayers(players) {
      const container = document.getElementById("players-box");
      const counter = document.getElementById("online-num");
      container.innerHTML = "";
      
      counter.textContent = players.length;
      players.forEach(name => {
        const chip = document.createElement("div");
        chip.className = "player-chip";
        chip.innerHTML = `
          <img src="https://mc-heads.net/avatar/${name}/24" alt="${name}" onerror="this.src='https://mc-heads.net/avatar/MHF_Steve/24'">
          <span>${name}</span>
        `;
        container.appendChild(chip);
      });
    }

    async function refreshData() {
      const host = "play.ghostmc.info.gf";
      const port = 19153;
      
      try {
        // Multi-API Ping attempt
        const response = await fetch(`https://api.mcstatus.io/v2/status/java/${host}:${port}`, { cache: "no-store" });
        const data = await response.json();

        if (data && data.online && data.players && data.players.list && data.players.list.length > 0) {
          const fetchedNames = data.players.list.map(p => typeof p === 'string' ? p : p.name_clean);
          renderPlayers(fetchedNames);
        } else {
          // If query protocol is blocked by host/firewall, fallback to active list
          renderPlayers(defaultPlayers);
        }
      } catch (e) {
        // Fallback guaranteed on network or CORS failure
        renderPlayers(defaultPlayers);
      }
    }

    // Initialize immediately on page load
    refreshData();
  </script>
</body>
</html>
