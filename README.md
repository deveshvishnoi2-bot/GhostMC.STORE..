
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ghost MC | Minecraft Lifesteal SMP & Official Store</title>
  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
  <!-- Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@700;900&family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            gold: {
              300: '#FDE047',
              400: '#FACC15',
              500: '#EAB308',
              600: '#CA8A04',
              700: '#A16207'
            },
            smpDark: '#0B0D14',
            smpCard: '#121724',
            smpBorder: '#232c45'
          },
          fontFamily: {
            heading: ['Cinzel', 'serif'],
            sans: ['Inter', 'sans-serif']
          }
        }
      }
    }
  </script>
  <style>
    /* Custom glow effects & scrollbar */
    body {
      background-color: #08090E;
      color: #E2E8F0;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
    }
    
    .gold-glow {
      box-shadow: 0 0 25px rgba(234, 179, 8, 0.35);
    }
    
    .gold-glow-lg {
      box-shadow: 0 0 50px rgba(234, 179, 8, 0.45);
    }

    .gold-text-glow {
      text-shadow: 0 0 16px rgba(250, 204, 21, 0.6);
    }

    /* Ambient background grid */
    .bg-grid-pattern {
      background-image: radial-gradient(rgba(234, 179, 8, 0.12) 1px, transparent 1px),
                        radial-gradient(rgba(30, 41, 59, 0.3) 1px, transparent 1px);
      background-size: 32px 32px;
      background-position: 0 0, 16px 16px;
    }

    /* Smooth Floating Animation */
    @keyframes floating {
      0%, 100% { transform: translateY(0px); }
      50% { transform: translateY(-10px); }
    }
    .animate-float {
      animation: floating 4s ease-in-out infinite;
    }

    /* Shimmer effect for buttons */
    .shine-btn {
      position: relative;
      overflow: hidden;
    }
    .shine-btn::after {
      content: '';
      position: absolute;
      top: -50%;
      left: -60%;
      width: 20%;
      height: 200%;
      background: rgba(255, 255, 255, 0.25);
      transform: rotate(30deg);
      transition: all 0.7s cubic-bezier(0.19, 1, 0.22, 1);
    }
    .shine-btn:hover::after {
      left: 140%;
    }

    /* Continuous News Ticker Animation */
    @keyframes tickerSlide {
      0% { transform: translate3d(0, 0, 0); }
      100% { transform: translate3d(-50%, 0, 0); }
    }
    .ticker-wrapper {
      display: flex;
      width: max-content;
      animation: tickerSlide 28s linear infinite;
    }
    .ticker-wrapper:hover {
      animation-play-state: paused;
    }
  </style>
</head>
<body class="bg-smpDark text-slate-100 min-h-screen relative selection:bg-gold-500 selection:text-black">

  <!-- Ambient Ambience Background -->
  <div class="fixed inset-0 bg-grid-pattern pointer-events-none opacity-40 z-0"></div>
  <div class="fixed top-0 left-1/2 -translate-x-1/2 w-[700px] h-[350px] bg-gold-600/10 blur-[130px] rounded-full pointer-events-none z-0"></div>

  <!-- TOP RUNNING NEWS TICKER / ANNOUNCEMENT BAR -->
  <div class="sticky top-0 z-50 bg-gradient-to-r from-amber-950 via-slate-900 to-amber-950 border-b border-gold-500/40 text-xs py-2 px-3 flex items-center overflow-hidden shadow-lg backdrop-blur-md">
    <div class="flex items-center gap-2 bg-gradient-to-r from-red-600 to-amber-600 text-white font-extrabold uppercase px-3 py-1 rounded-md shrink-0 shadow-md z-10 text-[11px] tracking-wider animate-pulse">
      <i class="fa-solid fa-fire"></i> LATEST NEWS
    </div>
    
    <div class="overflow-hidden whitespace-nowrap ml-3 flex-1 mask-linear">
      <div class="ticker-wrapper flex items-center gap-10 font-medium text-slate-200">
        <div class="flex items-center gap-8">
          <span class="text-gold-400 font-bold flex items-center gap-1.5"><i class="fa-solid fa-heart-pulse text-red-500 animate-pulse"></i> GHOST SMP SEASON 1 LAUNCHED!</span>
          <span class="text-slate-400">•</span>
          <span class="text-emerald-400 font-bold flex items-center gap-1.5">🏆 PVP EVENT 1ST WINNER - <span class="text-white underline decoration-gold-400 font-mono">flaxxy444</span> 🥇</span>
          <span class="text-slate-400">•</span>
          <span class="text-blue-400 font-bold flex items-center gap-1.5">🥈 2ND WINNER - <span class="text-white underline decoration-blue-400 font-mono">senkist13</span></span>
          <span class="text-slate-400">•</span>
          <span class="text-rose-400 font-semibold flex items-center gap-1.5">⚔️ GHOSTMC LIFESTEAL READY TO PLAY!</span>
          <span class="text-slate-400">•</span>
          <span class="text-yellow-400 font-bold">💎 BUY LEGEND KIT FOR JUST ₹40 INR!</span>
        </div>
        
        <!-- Repeat for seamless continuous loop -->
        <div class="flex items-center gap-8">
          <span class="text-gold-400 font-bold flex items-center gap-1.5"><i class="fa-solid fa-heart-pulse text-red-500 animate-pulse"></i> GHOST SMP SEASON 1 LAUNCHED!</span>
          <span class="text-slate-400">•</span>
          <span class="text-emerald-400 font-bold flex items-center gap-1.5">🏆 PVP EVENT 1ST WINNER - <span class="text-white underline decoration-gold-400 font-mono">flaxxy444</span> 🥇</span>
          <span class="text-slate-400">•</span>
          <span class="text-blue-400 font-bold flex items-center gap-1.5">🥈 2ND WINNER - <span class="text-white underline decoration-blue-400 font-mono">senkist13</span></span>
          <span class="text-slate-400">•</span>
          <span class="text-rose-400 font-semibold flex items-center gap-1.5">⚔️ GHOSTMC LIFESTEAL READY TO PLAY!</span>
          <span class="text-slate-400">•</span>
          <span class="text-yellow-400 font-bold">💎 BUY LEGEND KIT FOR JUST ₹40 INR!</span>
        </div>
      </div>
    </div>
  </div>

  <!-- Notification Toast Container -->
  <div id="toast" class="fixed bottom-6 right-6 z-50 transform translate-y-24 opacity-0 transition-all duration-300 pointer-events-none flex items-center gap-3 bg-slate-900 border border-gold-500/50 text-white px-5 py-3.5 rounded-xl shadow-2xl">
    <i class="fa-solid fa-circle-check text-gold-400 text-lg"></i>
    <span id="toast-text" class="text-sm font-semibold tracking-wide">Copied to clipboard!</span>
  </div>

  <!-- Navbar -->
  <header class="sticky top-[39px] z-40 backdrop-blur-md bg-smpDark/90 border-b border-smpBorder/80">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
      
      <!-- Custom Procedural Logo Branding -->
      <a href="#home" class="flex items-center gap-3.5 group">
        <div class="w-12 h-12 flex items-center justify-center relative rounded-xl overflow-hidden shadow-md shadow-gold-500/20 border border-gold-500/40 bg-gradient-to-br from-amber-500/20 to-slate-900">
          <svg class="w-9 h-9 transform group-hover:scale-110 transition-transform duration-300 drop-shadow-[0_0_8px_rgba(250,204,21,0.8)]" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
            <!-- Shield Outline -->
            <path d="M50 8L82 20V50C82 72 50 92 50 92C50 92 18 72 18 50V20L50 8Z" fill="url(#navShieldGrad)" stroke="#FACC15" stroke-width="3"/>
            <!-- Wings -->
            <path d="M22 36C12 28 8 40 12 52C16 48 24 44 26 42" stroke="#FDE047" stroke-width="2.5" stroke-linecap="round" fill="rgba(250,204,21,0.2)"/>
            <path d="M78 36C88 28 92 40 88 52C84 48 76 44 74 42" stroke="#FDE047" stroke-width="2.5" stroke-linecap="round" fill="rgba(250,204,21,0.2)"/>
            <!-- Crown -->
            <path d="M38 28L44 33L50 24L56 33L62 28V37H38V28Z" fill="#FACC15"/>
            <!-- Ghost Entity -->
            <path d="M36 44C36 36 64 36 64 44V64C64 64 60 60 56 64C52 68 48 68 44 64C40 60 36 64 36 64V44Z" fill="#FFFBEB" stroke="#CA8A04" stroke-width="2"/>
            <circle cx="43" cy="48" r="2.5" fill="#1E1B4B"/>
            <circle cx="57" cy="48" r="2.5" fill="#1E1B4B"/>
            <path d="M46 55Q50 58 54 55" stroke="#1E1B4B" stroke-width="2" stroke-linecap="round"/>
            <defs>
              <linearGradient id="navShieldGrad" x1="18" y1="8" x2="82" y2="92" gradientUnits="userSpaceOnUse">
                <stop stop-color="#451A03"/>
                <stop offset="0.5" stop-color="#1E1B4B"/>
                <stop offset="1" stop-color="#020617"/>
              </linearGradient>
            </defs>
          </svg>
        </div>
        <div class="flex flex-col">
          <span class="font-heading text-xl font-black text-transparent bg-clip-text bg-gradient-to-r from-gold-300 via-gold-400 to-amber-500 tracking-wider">GHOST MC</span>
          <span class="text-[10px] text-amber-200/60 uppercase tracking-widest font-semibold flex items-center gap-1">
            <i class="fa-solid fa-heart text-red-500 text-[9px]"></i> Lifesteal Season 1
          </span>
        </div>
      </a>

      <!-- Navigation Links -->
      <nav class="hidden md:flex items-center gap-7">
        <a href="#home" class="text-slate-300 hover:text-gold-400 transition-colors text-sm font-medium">Home</a>
        <a href="#store" class="text-slate-300 hover:text-gold-400 transition-colors text-sm font-medium flex items-center gap-1.5">
          <i class="fa-solid fa-cart-shopping text-xs text-gold-400"></i> Store
        </a>
        <a href="#info" class="text-slate-300 hover:text-gold-400 transition-colors text-sm font-medium">Server Info</a>
        <a href="https://discord.gg/H4p2TuNCA" target="_blank" rel="noopener noreferrer" class="text-slate-300 hover:text-[#5865F2] transition-colors text-sm font-medium flex items-center gap-1.5">
          <i class="fa-brands fa-discord text-base"></i> Discord
        </a>
      </nav>

      <!-- Server Quick Action -->
      <div class="flex items-center gap-3">
        <button onclick="copyToClipboard('play.ghostmc.info.gf', 'Server IP Copied!')" class="hidden sm:flex items-center gap-2 bg-smpCard hover:bg-slate-800 text-slate-200 px-4 py-2 rounded-lg border border-slate-700/80 text-xs font-semibold tracking-wider transition-all hover:border-gold-500/40">
          <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>
          <span>IP: <strong class="text-gold-400">play.ghostmc.info.gf</strong></span>
          <i class="fa-regular fa-copy text-slate-400 ml-1"></i>
        </button>

        <a href="#store" class="shine-btn bg-gradient-to-r from-gold-500 to-amber-600 hover:from-gold-400 hover:to-amber-500 text-black font-bold px-4 py-2 sm:px-5 sm:py-2.5 rounded-lg text-xs sm:text-sm shadow-md shadow-gold-500/20 transition-all flex items-center gap-2">
          <i class="fa-solid fa-crown text-xs"></i>
          <span>Shop Kits</span>
        </a>
      </div>
    </div>
  </header>

  <main class="relative z-10">

    <!-- Hero Section -->
    <section id="home" class="pt-10 pb-14 md:pt-14 md:pb-20 max-w-6xl mx-auto px-4 text-center">
      
      <!-- Custom High-Res Winged Ghost Crest Mascot -->
      <div class="relative flex justify-center mb-6">
        <div class="relative w-64 h-64 sm:w-72 sm:h-72 md:w-80 md:h-80 animate-float">
          <!-- Ambient Glow behind Crest Logo -->
          <div class="absolute inset-0 bg-gold-500/25 blur-3xl rounded-full scale-95 pointer-events-none"></div>
          
          <svg class="w-full h-full object-contain relative z-10 drop-shadow-[0_15px_40px_rgba(234,179,8,0.45)]" viewBox="0 0 400 400" fill="none" xmlns="http://www.w3.org/2000/svg">
            <defs>
              <radialGradient id="crestGlow" cx="50%" cy="50%" r="50%">
                <stop offset="0%" stop-color="#FACC15" stop-opacity="0.25"/>
                <stop offset="100%" stop-color="#0F172A" stop-opacity="0"/>
              </radialGradient>
              <linearGradient id="goldShield" x1="50" y1="30" x2="350" y2="370" gradientUnits="userSpaceOnUse">
                <stop stop-color="#78350F"/>
                <stop offset="0.3" stop-color="#B45309"/>
                <stop offset="0.7" stop-color="#1E1B4B"/>
                <stop offset="1" stop-color="#020617"/>
              </linearGradient>
              <linearGradient id="goldBorder" x1="0" y1="0" x2="400" y2="400" gradientUnits="userSpaceOnUse">
                <stop stop-color="#FEF08A"/>
                <stop offset="0.5" stop-color="#F59E0B"/>
                <stop offset="1" stop-color="#78350F"/>
              </linearGradient>
              <linearGradient id="wingGrad" x1="0" y1="0" x2="1" y2="1">
                <stop stop-color="#FEF08A"/>
                <stop offset="0.5" stop-color="#FACC15"/>
                <stop offset="1" stop-color="#D97706"/>
              </linearGradient>
              <linearGradient id="ghostGrad" x1="0" y1="0" x2="0" y2="1">
                <stop stop-color="#FFFFFF"/>
                <stop offset="0.7" stop-color="#FEF3C7"/>
                <stop offset="1" stop-color="#FDE68A"/>
              </linearGradient>
            </defs>

            <!-- Outer Shield Base -->
            <path d="M200 24L324 72V192C324 280 200 360 200 360C200 360 76 280 76 192V72L200 24Z" fill="url(#goldShield)" stroke="url(#goldBorder)" stroke-width="8" stroke-linejoin="round"/>
            <path d="M200 42L306 84V188C306 264 200 336 200 336C200 336 94 264 94 188V84L200 42Z" stroke="#FDE047" stroke-width="2.5" opacity="0.6"/>

            <!-- Majestic Golden Wings -->
            <path d="M96 150C48 108 30 162 44 216C62 202 88 190 106 182" stroke="url(#wingGrad)" stroke-width="8" stroke-linecap="round" fill="rgba(250,204,21,0.18)"/>
            <path d="M92 186C58 160 48 200 60 236C74 224 90 216 102 210" stroke="url(#wingGrad)" stroke-width="6" stroke-linecap="round" fill="rgba(250,204,21,0.15)"/>
            
            <path d="M304 150C352 108 370 162 356 216C338 202 312 190 294 182" stroke="url(#wingGrad)" stroke-width="8" stroke-linecap="round" fill="rgba(250,204,21,0.18)"/>
            <path d="M308 186C342 160 352 200 340 236C326 224 310 216 298 210" stroke="url(#wingGrad)" stroke-width="6" stroke-linecap="round" fill="rgba(250,204,21,0.15)"/>

            <!-- Golden Crown with Red Ruby -->
            <path d="M152 110L174 132L200 96L226 132L248 110V148H152V110Z" fill="url(#wingGrad)" stroke="#78350F" stroke-width="3" stroke-linejoin="round"/>
            <circle cx="200" cy="124" r="5" fill="#EF4444" stroke="#FFF" stroke-width="1.5"/>
            <circle cx="166" cy="132" r="3" fill="#3B82F6"/>
            <circle cx="234" cy="132" r="3" fill="#3B82F6"/>

            <!-- Cute Fierce Ghost Body -->
            <path d="M148 174C148 140 252 140 252 174V246C252 246 238 234 224 246C210 258 190 258 176 246C162 234 148 246 148 246V174Z" fill="url(#ghostGrad)" stroke="#B45309" stroke-width="5" stroke-linejoin="round" filter="drop-shadow(0 6px 12px rgba(0,0,0,0.5))"/>
            
            <!-- Eyes & Mouth -->
            <ellipse cx="174" cy="190" rx="9" ry="12" fill="#0F172A"/>
            <ellipse cx="226" cy="190" rx="9" ry="12" fill="#0F172A"/>
            <circle cx="177" cy="186" r="3.5" fill="#EF4444"/>
            <circle cx="229" cy="186" r="3.5" fill="#EF4444"/>
            <ellipse cx="200" cy="214" rx="14" ry="10" fill="#7F1D1D"/>
            <path d="M192 208C196 214 204 214 208 208" stroke="#FEF08A" stroke-width="2.5" stroke-linecap="round"/>

            <!-- Cross Swords at Bottom of Mascot -->
            <path d="M168 280L232 304M232 280L168 304" stroke="#FACC15" stroke-width="4" stroke-linecap="round"/>

            <!-- Banner 'GHOST MC' -->
            <rect x="110" y="306" width="180" height="38" rx="8" fill="#1E1B4B" stroke="#FACC15" stroke-width="3"/>
            <text x="200" y="331" font-family="'Cinzel', serif" font-size="19" font-weight="900" fill="#FACC15" text-anchor="middle" letter-spacing="3" stroke="#000" stroke-width="0.5">GHOST MC</text>
          </svg>
        </div>
      </div>

      <!-- Hero Headlines -->
      <div class="inline-flex items-center gap-2 bg-gold-500/10 border border-gold-500/30 px-4 py-1.5 rounded-full text-gold-400 text-xs font-bold uppercase tracking-wider mb-5">
        <i class="fa-solid fa-heart-crack text-red-400"></i> Hardcore PvP & Lifesteal SMP • Season 1 Live
      </div>

      <h1 class="text-4xl sm:text-6xl md:text-7xl font-extrabold font-heading text-white tracking-tight uppercase gold-text-glow leading-none">
        Kill & Steal Hearts In <br/>
        <span class="text-transparent bg-clip-text bg-gradient-to-r from-gold-300 via-amber-400 to-yellow-500">GHOSTMC LIFESTEAL</span>
      </h1>
      
      <p class="mt-6 text-slate-300 max-w-2xl mx-auto text-base sm:text-lg leading-relaxed font-normal">
        Every kill grants you an extra heart, every death costs one! Battle in custom arenas, survive brutal traps, and dominate the leaderboard in India's ultimate Lifesteal experience.
      </p>

      <!-- Live Server Metrics Bar with Dynamic Refresh -->
      <div class="mt-12 max-w-4xl mx-auto">
        <!-- Refresh Header Bar -->
        <div class="flex items-center justify-between px-2 mb-2.5">
          <div class="flex items-center gap-2 text-xs text-slate-400">
            <span id="telemetry-dot" class="inline-block w-2 h-2 rounded-full bg-emerald-400 animate-ping"></span>
            <span>Live Server Telemetry</span>
            <span id="last-updated-text" class="text-[11px] text-slate-500">(Auto-sync active)</span>
          </div>
          <button id="refresh-status-btn" onclick="fetchLiveServerStatus()" class="flex items-center gap-1.5 bg-slate-800/90 hover:bg-slate-700 text-gold-400 hover:text-gold-300 text-xs font-semibold px-3 py-1.5 rounded-lg border border-slate-700/80 transition-all hover:border-gold-500/50 shadow-sm active:scale-95">
            <i id="refresh-icon" class="fa-solid fa-arrows-rotate text-[11px]"></i>
            <span>Refresh Status</span>
          </button>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 text-left">
          <!-- Server Status Card -->
          <div class="bg-smpCard/80 border border-smpBorder p-4 rounded-xl shadow-lg relative overflow-hidden group">
            <div class="text-xs text-slate-400 uppercase tracking-wider font-semibold flex items-center justify-between">
              <span>Server Status</span>
              <i class="fa-solid fa-signal text-slate-500 text-xs"></i>
            </div>
            <div id="server-status-badge" class="font-bold flex items-center gap-2 text-base mt-1.5 text-emerald-400">
              <span id="server-status-dot" class="w-2.5 h-2.5 rounded-full bg-emerald-400 shadow-[0_0_10px_#34d399]"></span>
              <span id="server-status-text">Checking...</span>
            </div>
            <div id="server-version-text" class="text-[10px] text-slate-500 mt-1 font-mono truncate">play.ghostmc.info.gf</div>

            <!-- Stylized Callout Badge -->
            <div class="mt-3 pt-2.5 border-t border-slate-800/80 text-center">
              <div class="inline-block py-1 px-3 rounded-lg bg-gradient-to-r from-amber-500/20 via-red-500/20 to-amber-500/20 border border-gold-500/40 shadow-inner">
                <span class="font-heading font-black text-sm tracking-widest text-transparent bg-clip-text bg-gradient-to-r from-gold-300 via-amber-400 to-yellow-500 animate-pulse drop-shadow-[0_0_8px_rgba(250,204,21,0.6)]">
                  GO AND PLAY!!!!!
                </span>
              </div>
              <div class="text-[10px] font-bold text-amber-300/80 mt-1 uppercase tracking-wider flex items-center justify-center gap-1">
                <span>⚔️ Join Lifesteal Now ⚔️</span>
              </div>
            </div>
          </div>

          <!-- Real Players Online Tracker (NO FAKE DATA) -->
          <div class="bg-smpCard/90 border border-smpBorder hover:border-gold-500/50 transition-all p-4 rounded-xl shadow-lg relative overflow-hidden group">
            <div class="text-xs text-slate-400 uppercase tracking-wider font-semibold flex items-center justify-between">
              <span>Players Online</span>
              <i class="fa-solid fa-users text-gold-400 text-xs"></i>
            </div>
            <div class="flex items-baseline gap-1.5 mt-1">
              <span id="server-players-online" class="text-2xl font-black font-mono text-white tracking-tight">0</span>
              <span id="server-players-max" class="text-xs text-slate-500 font-mono">/ --</span>
            </div>
            <div class="text-[10px] text-slate-400 font-medium mt-0.5 flex items-center gap-1">
              <span id="players-pulse-dot" class="w-1.5 h-1.5 rounded-full bg-slate-500"></span>
              <span id="server-players-status">Querying live server...</span>
            </div>

            <!-- Direct In-Card Username Roster (Rendered Only When Real Players Are Online) -->
            <div class="mt-2.5 pt-2.5 border-t border-slate-800/80">
              <div class="text-[10px] uppercase font-bold text-slate-400 flex items-center justify-between mb-1.5">
                <span>Active Combatants:</span>
                <span id="roster-count-tag" class="font-mono text-gold-400 text-[9px] bg-slate-900 px-1.5 py-0.5 rounded">0 online</span>
              </div>
              <div id="card-players-list" class="flex flex-wrap gap-1.5 max-h-28 overflow-y-auto pr-1">
                <span class="text-[11px] text-slate-500 italic">No players online right now</span>
              </div>
            </div>
          </div>

          <!-- SMP Mode Card -->
          <div class="bg-smpCard/80 border border-smpBorder p-4 rounded-xl shadow-lg relative overflow-hidden">
            <div class="text-xs text-slate-400 uppercase tracking-wider font-semibold flex items-center justify-between">
              <span>SMP Mode</span>
              <i class="fa-solid fa-heart text-red-500 text-xs"></i>
            </div>
            <div class="text-white font-bold text-base mt-1.5 flex items-center gap-1.5">
              <span class="text-red-500">❤️</span> Lifesteal SMP
            </div>
            <div class="text-[10px] text-slate-400 mt-1">Java & Bedrock Crossplay</div>
          </div>

          <!-- PVP Champion Card -->
          <div class="bg-smpCard/80 border border-smpBorder p-4 rounded-xl shadow-lg relative overflow-hidden">
            <div class="text-xs text-slate-400 uppercase tracking-wider font-semibold flex items-center justify-between">
              <span>Lifesteal Top</span>
              <i class="fa-solid fa-crown text-gold-400 text-xs"></i>
            </div>
            <div class="text-gold-400 font-bold text-base mt-1.5 truncate">flaxxy444 🥇</div>
            <div class="text-[10px] text-slate-400 mt-1 truncate">2nd: senkist13 🥈</div>
          </div>
        </div>
      </div>
    </section>

    <!-- STORE SECTION -->
    <section id="store" class="py-16 bg-smpDark relative">
      <div class="max-w-5xl mx-auto px-4 sm:px-6">
        
        <!-- Section Header -->
        <div class="text-center mb-12">
          <div class="inline-flex items-center gap-2 px-3.5 py-1 rounded-full bg-gold-500/10 border border-gold-500/30 text-gold-400 text-xs font-bold uppercase tracking-widest mb-3">
            <i class="fa-solid fa-gem"></i> Lifesteal Item Store
          </div>
          <h2 class="text-3xl sm:text-5xl font-heading font-black text-white tracking-wide">
            OFFICIAL LIFESTEAL STORE
          </h2>
          <p class="text-slate-400 text-sm sm:text-base mt-3 max-w-xl mx-auto">
            Upgrade your hearts and survival gear. Pay directly using your preferred UPI app and claim directly via our Discord ticketing system!
          </p>
        </div>

        <!-- Featured Product: LEGEND KIT -->
        <div class="relative max-w-2xl mx-auto">
          
          <!-- Outer Glow Border Frame -->
          <div class="absolute -inset-1 bg-gradient-to-r from-gold-500 via-amber-400 to-yellow-600 rounded-3xl blur-md opacity-40 group-hover:opacity-100 transition duration-1000 group-hover:duration-200"></div>

          <div class="relative bg-smpCard border-2 border-gold-500/60 rounded-3xl overflow-hidden shadow-2xl p-6 sm:p-8">
            
            <!-- Ribbon Badge -->
            <div class="flex items-center justify-between border-b border-slate-800 pb-5">
              <div>
                <span class="inline-block bg-gradient-to-r from-gold-500 to-amber-600 text-black text-xs font-black px-3 py-1 rounded-md uppercase tracking-wider">
                  HOTTEST SELLER
                </span>
                <h3 class="text-2xl sm:text-3xl font-heading font-black text-white mt-2 flex items-center gap-2">
                  <i class="fa-solid fa-shield-halved text-gold-400"></i> LEGEND KIT
                </h3>
              </div>
              <div class="text-right">
                <span class="text-xs text-slate-400 block uppercase font-medium">Special Price</span>
                <span class="text-3xl sm:text-4xl font-extrabold text-gold-400 font-mono tracking-tight">₹40 <span class="text-sm font-semibold text-slate-400">INR</span></span>
              </div>
            </div>

            <!-- What's included in Legend Kit -->
            <div class="mt-6">
              <h4 class="text-xs font-bold uppercase tracking-wider text-slate-400 mb-4 flex items-center gap-2">
                <i class="fa-solid fa-box-open text-gold-400"></i> Includes Package:
              </h4>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 text-sm">
                
                <div class="flex items-center gap-3 bg-slate-900/90 border border-slate-800 p-3 rounded-xl hover:border-gold-500/40 transition-colors">
                  <div class="w-8 h-8 rounded-lg bg-blue-500/20 text-blue-400 flex items-center justify-center font-bold">
                    🛡️
                  </div>
                  <div>
                    <div class="font-bold text-white">Prot 3 Diamond Armour</div>
                    <div class="text-[11px] text-slate-400">Full protective high-tier set</div>
                  </div>
                </div>

                <div class="flex items-center gap-3 bg-slate-900/90 border border-slate-800 p-3 rounded-xl hover:border-gold-500/40 transition-colors">
                  <div class="w-8 h-8 rounded-lg bg-amber-500/20 text-amber-400 flex items-center justify-center font-bold">
                    ⚔️
                  </div>
                  <div>
                    <div class="font-bold text-white">Sharpness 3 Sword</div>
                    <div class="text-[11px] text-slate-400">Maximum combat strike power</div>
                  </div>
                </div>

                <div class="flex items-center gap-3 bg-slate-900/90 border border-slate-800 p-3 rounded-xl hover:border-gold-500/40 transition-colors">
                  <div class="w-8 h-8 rounded-lg bg-yellow-500/20 text-yellow-400 flex items-center justify-center font-bold">
                    🗿
                  </div>
                  <div>
                    <div class="font-bold text-white">2 Totems of Undying</div>
                    <div class="text-[11px] text-slate-400">Instant life-saving revive</div>
                  </div>
                </div>

                <div class="flex items-center gap-3 bg-slate-900/90 border border-slate-800 p-3 rounded-xl hover:border-gold-500/40 transition-colors">
                  <div class="w-8 h-8 rounded-lg bg-purple-500/20 text-purple-400 flex items-center justify-center font-bold">
                    🍏
                  </div>
                  <div>
                    <div class="font-bold text-white">2 Enchanted Apples</div>
                    <div class="text-[11px] text-slate-400">God apple absorption & buffs</div>
                  </div>
                </div>

                <div class="flex items-center gap-3 bg-slate-900/90 border border-slate-800 p-3 rounded-xl hover:border-gold-500/40 transition-colors">
                  <div class="w-8 h-8 rounded-lg bg-yellow-500/20 text-yellow-400 flex items-center justify-center font-bold">
                    🍎
                  </div>
                  <div>
                    <div class="font-bold text-white">16 Golden Apples</div>
                    <div class="text-[11px] text-slate-400">Essential fast regeneration</div>
                  </div>
                </div>

                <div class="flex items-center gap-3 bg-slate-900/90 border border-slate-800 p-3 rounded-xl hover:border-gold-500/40 transition-colors">
                  <div class="w-8 h-8 rounded-lg bg-teal-500/20 text-teal-400 flex items-center justify-center font-bold">
                    🔮
                  </div>
                  <div>
                    <div class="font-bold text-white">16 Ender Pearls</div>
                    <div class="text-[11px] text-slate-400">Instant combat teleportation</div>
                  </div>
                </div>
              </div>

              <!-- Bonus Line -->
              <div class="mt-3.5 bg-gradient-to-r from-gold-500/10 via-gold-500/5 to-transparent border-l-4 border-gold-400 px-4 py-2.5 rounded-r-lg flex items-center justify-between text-xs sm:text-sm">
                <span class="font-bold text-gold-300">✨ AND MORE SURPRISE BONUS LOOT INCLUDED!</span>
                <span class="text-[11px] bg-gold-500/20 text-gold-300 px-2 py-0.5 rounded font-mono font-bold">LEGEND RANK</span>
              </div>
            </div>

            <!-- Payment Action Box -->
            <div class="mt-8 pt-6 border-t border-slate-800/80">
              
              <!-- Direct UPI Information -->
              <div class="bg-slate-900/80 rounded-2xl p-4 border border-slate-800 mb-6 flex flex-col sm:flex-row sm:items-center justify-between gap-3">
                <div class="flex items-center gap-3">
                  <div class="w-10 h-10 rounded-xl bg-gold-500/10 flex items-center justify-center text-gold-400 text-lg">
                    <i class="fa-solid fa-wallet"></i>
                  </div>
                  <div>
                    <div class="text-[11px] text-slate-400 uppercase font-semibold">Official Receiver UPI ID</div>
                    <div class="font-mono font-bold text-white text-sm sm:text-base selection:bg-gold-500">ghostmc.fund@axl</div>
                  </div>
                </div>
                <button onclick="copyToClipboard('ghostmc.fund@axl', 'UPI ID Copied!')" class="bg-slate-800 hover:bg-slate-700 text-gold-400 hover:text-gold-300 text-xs font-bold px-3.5 py-2 rounded-lg transition-colors flex items-center justify-center gap-1.5 self-start sm:self-center">
                  <i class="fa-regular fa-copy"></i>
                  <span>Copy UPI ID</span>
                </button>
              </div>

              <!-- Purchase Buttons Group -->
              <div class="flex flex-col sm:flex-row gap-3">
                
                <!-- Open UPI intent link button (Works directly on Phone GPay, PhonePe, Paytm, BHIM) -->
                <a href="upi://pay?pa=ghostmc.fund@axl&pn=GhostMC&am=40&cu=INR" class="shine-btn flex-1 bg-gradient-to-r from-gold-500 via-amber-500 to-yellow-500 hover:from-gold-400 hover:to-yellow-400 text-black font-extrabold py-3.5 px-6 rounded-xl text-center shadow-lg shadow-gold-500/25 transition-all flex items-center justify-center gap-2">
                  <i class="fa-solid fa-mobile-screen-button text-base"></i>
                  <span>Pay ₹40 with UPI App</span>
                </a>

                <!-- QR Code View Modal Trigger for Desktop / Scan -->
                <button onclick="openPaymentModal()" class="flex-1 bg-slate-800 hover:bg-slate-700 text-white font-bold py-3.5 px-6 rounded-xl text-center border border-slate-600 transition-colors flex items-center justify-center gap-2">
                  <i class="fa-solid fa-qrcode text-gold-400"></i>
                  <span>Scan QR Code</span>
                </button>
              </div>

              <!-- Required Instructions Note in English -->
              <div class="mt-5 p-4 rounded-xl bg-amber-500/10 border border-amber-500/30 text-amber-200 text-xs sm:text-sm flex items-start gap-3">
                <i class="fa-solid fa-circle-exclamation text-amber-400 text-base shrink-0 mt-0.5"></i>
                <div class="leading-relaxed">
                  <strong class="text-white font-bold block mb-0.5">Important Claim Instruction:</strong>
                  After purchasing via UPI, please take a screenshot of your payment and create a ticket in our official Discord server to receive your kit instantly in-game!
                </div>
              </div>

              <!-- Direct Discord Ticket Button -->
              <div class="mt-4 text-center">
                <a href="https://discord.gg/H4p2TuNCA" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-2 text-indigo-400 hover:text-indigo-300 font-bold text-sm transition-colors py-1">
                  <i class="fa-brands fa-discord text-base"></i>
                  <span>Open Discord Ticket (https://discord.gg/H4p2TuNCA) &rarr;</span>
                </a>
              </div>

            </div>

          </div>
        </div>

      </div>
    </section>

    <!-- SERVER DETAILS SECTION -->
    <section id="info" class="py-16 max-w-4xl mx-auto px-4 sm:px-6">
      <div class="text-center mb-10">
        <h3 class="text-2xl sm:text-3xl font-heading font-black text-white">HOW TO JOIN GHOST LIFESTEAL</h3>
        <p class="text-slate-400 text-sm mt-1">Join players from both Minecraft Java Edition and Bedrock Edition.</p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        
        <!-- Java Card -->
        <div class="bg-smpCard border border-smpBorder p-6 rounded-2xl relative overflow-hidden">
          <div class="flex items-center justify-between mb-4">
            <span class="text-xs uppercase font-extrabold px-3 py-1 bg-amber-500/10 text-gold-400 border border-gold-500/30 rounded-lg">Java Edition</span>
            <span class="text-xs text-slate-400">1.19 - 1.21+</span>
          </div>
          <div class="text-xs text-slate-400 uppercase font-semibold">Server Address</div>
          <div class="mt-1 flex items-center justify-between bg-slate-900 p-3 rounded-xl border border-slate-800">
            <span class="font-mono font-bold text-white">play.ghostmc.info.gf</span>
            <button onclick="copyToClipboard('play.ghostmc.info.gf', 'Java Server IP Copied!')" class="text-gold-400 hover:text-white transition-colors" title="Copy IP">
              <i class="fa-regular fa-copy"></i>
            </button>
          </div>
          <p class="text-xs text-slate-400 mt-3">Simply add this address in your Multiplayer Server list.</p>
        </div>

        <!-- Bedrock / Pocket Edition Card -->
        <div class="bg-smpCard border border-smpBorder p-6 rounded-2xl relative overflow-hidden">
          <div class="flex items-center justify-between mb-4">
            <span class="text-xs uppercase font-extrabold px-3 py-1 bg-blue-500/10 text-blue-400 border border-blue-500/30 rounded-lg">Bedrock / Mobile</span>
            <span class="text-xs text-slate-400">Latest Versions</span>
          </div>
          <div class="grid grid-cols-3 gap-2">
            <div class="col-span-2">
              <div class="text-xs text-slate-400 uppercase font-semibold">Server IP</div>
              <div class="mt-1 flex items-center justify-between bg-slate-900 p-3 rounded-xl border border-slate-800">
                <span class="font-mono font-bold text-white truncate text-xs sm:text-sm">play.ghostmc.info.gf</span>
                <button onclick="copyToClipboard('play.ghostmc.info.gf', 'Bedrock IP Copied!')" class="text-gold-400 hover:text-white" title="Copy">
                  <i class="fa-regular fa-copy"></i>
                </button>
              </div>
            </div>
            <div>
              <div class="text-xs text-slate-400 uppercase font-semibold">Port</div>
              <div class="mt-1 flex items-center justify-between bg-slate-900 p-3 rounded-xl border border-slate-800">
                <span class="font-mono font-bold text-gold-400 text-xs sm:text-sm">19153</span>
                <button onclick="copyToClipboard('19153', 'Port Copied!')" class="text-gold-400 hover:text-white" title="Copy Port">
                  <i class="fa-regular fa-copy"></i>
                </button>
              </div>
            </div>
          </div>
          <p class="text-xs text-slate-400 mt-3">Enter the Port <strong>19153</strong> when playing from Mobile or Windows 10/11 Bedrock.</p>
        </div>

      </div>
    </section>

  </main>

  <!-- Payment Modal Dialog -->
  <div id="payment-modal" class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-black/80 backdrop-blur-md opacity-0 pointer-events-none transition-all duration-300">
    <div class="bg-smpCard border border-gold-500/60 rounded-3xl max-w-md w-full p-6 sm:p-7 shadow-2xl relative text-center">
      
      <!-- Close Button -->
      <button onclick="closePaymentModal()" class="absolute top-4 right-4 text-slate-400 hover:text-white bg-slate-800/80 hover:bg-slate-700 w-9 h-9 rounded-full flex items-center justify-center transition-colors">
        <i class="fa-solid fa-xmark"></i>
      </button>

      <!-- Modal Header -->
      <div class="inline-flex p-3 rounded-2xl bg-gold-500/10 text-gold-400 mb-3">
        <i class="fa-solid fa-qrcode text-2xl"></i>
      </div>
      <h3 class="text-xl font-heading font-black text-white">SCAN & PAY ₹40</h3>
      <p class="text-xs text-slate-400 mt-1">Scan using GPay, PhonePe, Paytm, or any UPI app</p>

      <!-- QR Code Image Container -->
      <div class="my-5 bg-white p-3 rounded-2xl inline-block shadow-inner">
        <!-- Generates standard UPI intent QR code -->
        <img id="upi-qrcode" src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=upi%3A%2F%2Fpay%3Fpa%3Dghostmc.fund%40axl%26pn%3DGhostMC%26am%3D40%26cu%3DINR%26tn%3DLegend%2BKit" alt="UPI Payment QR Code" class="w-48 h-48 mx-auto object-contain block">
      </div>

      <!-- UPI Details -->
      <div class="bg-slate-900 border border-slate-800 rounded-xl p-3 flex items-center justify-between text-left text-xs mb-4">
        <div>
          <span class="text-slate-400 block text-[10px]">UPI VPA</span>
          <span class="font-mono font-bold text-gold-400 text-sm">ghostmc.fund@axl</span>
        </div>
        <button onclick="copyToClipboard('ghostmc.fund@axl', 'UPI ID Copied!')" class="text-slate-300 hover:text-white bg-slate-800 px-2.5 py-1.5 rounded-lg border border-slate-700 text-xs">
          Copy
        </button>
      </div>

      <!-- Instruction Note -->
      <div class="text-[12px] bg-slate-900/90 text-slate-300 p-3 rounded-xl border border-slate-800 leading-relaxed text-left mb-5">
        <div class="font-bold text-amber-400 flex items-center gap-1.5 mb-1">
          <i class="fa-solid fa-ticket"></i> Next Step:
        </div>
        After completing payment, join <strong class="text-white">discord.gg/H4p2TuNCA</strong> and open a ticket with your screenshot & IGN!
      </div>

      <!-- Actions -->
      <div class="flex gap-2">
        <a href="https://discord.gg/H4p2TuNCA" target="_blank" rel="noopener noreferrer" class="flex-1 bg-[#5865F2] hover:bg-[#4752c4] text-white font-bold py-2.5 px-4 rounded-xl text-xs sm:text-sm flex items-center justify-center gap-2">
          <i class="fa-brands fa-discord"></i> Go to Discord
        </a>
        <button onclick="closePaymentModal()" class="bg-slate-800 hover:bg-slate-700 text-slate-300 font-semibold py-2.5 px-4 rounded-xl text-xs sm:text-sm">
          Close
        </button>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="border-t border-smpBorder/60 bg-slate-950 py-10 text-slate-500 text-xs">
    <div class="max-w-7xl mx-auto px-4 flex flex-col md:flex-row items-center justify-between gap-4">
      <div class="flex items-center gap-3">
        <div class="w-8 h-8 rounded-lg border border-gold-500/40 bg-slate-900 flex items-center justify-center">
          <i class="fa-solid fa-ghost text-gold-400 text-sm"></i>
        </div>
        <span class="font-heading font-bold text-slate-300 text-sm tracking-wider">GHOST LIFESTEAL SMP</span>
      </div>
      <div>
        Official Store & Server Hub &copy; 2026 Ghost MC Lifesteal. Not an official Minecraft product. Not approved by or associated with Mojang or Microsoft.
      </div>
      <div class="flex items-center gap-4 text-base">
        <a href="https://discord.gg/H4p2TuNCA" target="_blank" rel="noopener noreferrer" class="hover:text-gold-400 transition-colors" title="Discord">
          <i class="fa-brands fa-discord"></i>
        </a>
        <button onclick="copyToClipboard('ghostmc.fund@axl', 'UPI ID Copied!')" class="hover:text-gold-400 transition-colors" title="UPI">
          <i class="fa-solid fa-wallet"></i>
        </button>
      </div>
    </div>

    <!-- Powered by Devesh Watermark -->
    <div class="mt-8 pt-6 border-t border-slate-900 text-center flex flex-col sm:flex-row items-center justify-center gap-2">
      <div class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-gradient-to-r from-amber-500/10 via-gold-500/15 to-amber-500/10 border border-gold-500/30 shadow-[0_0_15px_rgba(234,179,8,0.2)]">
        <i class="fa-solid fa-wand-magic-sparkles text-gold-400 text-xs animate-pulse"></i>
        <span class="text-xs uppercase tracking-widest font-semibold text-slate-300">
          POWERED BY <strong class="text-transparent bg-clip-text bg-gradient-to-r from-gold-300 via-amber-400 to-yellow-500 font-extrabold tracking-wider text-sm">DEVESH</strong>
        </span>
        <i class="fa-solid fa-bolt text-gold-400 text-xs"></i>
      </div>
    </div>
  </footer>

  <script>
    // Live Minecraft Server Status & Player Counter Integration (STRICTLY REAL DATA)
    const SERVER_HOST = 'play.ghostmc.info.gf';
    const SERVER_PORT = 19153;

    function renderRealPlayers(onlineCount, maxCount, playerList) {
      const cardPlayersList = document.getElementById('card-players-list');
      const rosterCountTag = document.getElementById('roster-count-tag');
      const playersOnlineElem = document.getElementById('server-players-online');
      const playersMaxElem = document.getElementById('server-players-max');
      const playersStatusElem = document.getElementById('server-players-status');
      const playersPulseDot = document.getElementById('players-pulse-dot');

      if (playersOnlineElem) playersOnlineElem.textContent = onlineCount !== undefined ? onlineCount : 0;
      if (playersMaxElem) playersMaxElem.textContent = maxCount ? `/ ${maxCount}` : '/ --';
      if (rosterCountTag) rosterCountTag.textContent = `${onlineCount || 0} online`;

      if (onlineCount > 0) {
        if (playersStatusElem) playersStatusElem.textContent = `${onlineCount} player(s) online`;
        if (playersPulseDot) {
          playersPulseDot.className = 'w-1.5 h-1.5 rounded-full bg-emerald-400 animate-pulse';
        }
      } else {
        if (playersStatusElem) playersStatusElem.textContent = 'Server waiting for warriors';
        if (playersPulseDot) {
          playersPulseDot.className = 'w-1.5 h-1.5 rounded-full bg-slate-500';
        }
      }

      if (!cardPlayersList) return;

      if (playerList && playerList.length > 0) {
        cardPlayersList.innerHTML = playerList.map(p => {
          const name = typeof p === 'string' ? p : (p.name_clean || p.name_raw || p.name || 'Player');
          return `
            <div class="inline-flex items-center gap-1.5 bg-slate-900/90 border border-gold-500/40 px-2 py-0.5 rounded-md shadow-sm">
              <img src="https://mc-heads.net/avatar/${encodeURIComponent(name)}/18" onerror="this.src='https://mc-heads.net/avatar/MHF_Steve/18'" alt="${name}" class="w-3.5 h-3.5 rounded-sm">
              <span class="font-mono font-bold text-[10px] text-gold-300 truncate max-w-[110px]">${name}</span>
            </div>
          `;
        }).join('');
      } else if (onlineCount > 0) {
        cardPlayersList.innerHTML = `<span class="text-[11px] text-amber-300 font-medium">${onlineCount} player(s) online in-game</span>`;
      } else {
        cardPlayersList.innerHTML = `<span class="text-[11px] text-slate-500 italic">0 players online right now</span>`;
      }
    }

    async function fetchLiveServerStatus() {
      const refreshIcon = document.getElementById('refresh-icon');
      const statusText = document.getElementById('server-status-text');
      const statusBadge = document.getElementById('server-status-badge');
      const statusDot = document.getElementById('server-status-dot');
      const telemetryDot = document.getElementById('telemetry-dot');
      const lastUpdatedElem = document.getElementById('last-updated-text');
      const serverVersionText = document.getElementById('server-version-text');

      if (refreshIcon) refreshIcon.classList.add('fa-spin');
      if (statusText) statusText.textContent = 'Pinging...';

      let isOnline = false;
      let onlineCount = 0;
      let maxCount = null;
      let playerList = [];
      let versionDetected = 'play.ghostmc.info.gf';

      // 1. Try public Java Status API (mcstatus.io)
      try {
        const res = await fetch(`https://api.mcstatus.io/v2/status/java/${SERVER_HOST}:${SERVER_PORT}`, { cache: 'no-store' });
        if (res.ok) {
          const data = await res.json();
          if (data && data.online) {
            isOnline = true;
            onlineCount = data.players ? data.players.online : 0;
            maxCount = data.players ? data.players.max : null;
            if (data.players && Array.isArray(data.players.list)) {
              playerList = data.players.list;
            }
            if (data.version && data.version.name_clean) {
              versionDetected = data.version.name_clean;
            }
          }
        }
      } catch (e) {
        console.warn('API 1 ping failed:', e);
      }

      // 2. If Java ping did not return online, try mcsrvstat.us
      if (!isOnline) {
        try {
          const res = await fetch(`https://api.mcsrvstat.us/3/${SERVER_HOST}:${SERVER_PORT}`, { cache: 'no-store' });
          if (res.ok) {
            const data = await res.json();
            if (data && data.online) {
              isOnline = true;
              onlineCount = data.players ? data.players.online : 0;
              maxCount = data.players ? data.players.max : null;
              if (data.players && Array.isArray(data.players.list)) {
                playerList = data.players.list;
              }
              if (data.version) {
                versionDetected = data.version;
              }
            }
          }
        } catch (e) {
          console.warn('API 2 ping failed:', e);
        }
      }

      // 3. Fallback Bedrock query (if server is running as Bedrock/Geyser on port 19153)
      if (!isOnline) {
        try {
          const res = await fetch(`https://api.mcstatus.io/v2/status/bedrock/${SERVER_HOST}:${SERVER_PORT}`, { cache: 'no-store' });
          if (res.ok) {
            const data = await res.json();
            if (data && data.online) {
              isOnline = true;
              onlineCount = data.players ? data.players.online : 0;
              maxCount = data.players ? data.players.max : null;
              if (data.version && data.version.name) {
                versionDetected = data.version.name;
              }
            }
          }
        } catch (e) {
          console.warn('API 3 Bedrock ping failed:', e);
        }
      }

      // Update UI with 100% REAL telemetry
      if (isOnline) {
        if (statusText) statusText.textContent = 'Online';
        if (statusBadge) statusBadge.className = 'font-bold flex items-center gap-2 text-base mt-1.5 text-emerald-400';
        if (statusDot) {
          statusDot.className = 'w-2.5 h-2.5 rounded-full bg-emerald-400 shadow-[0_0_10px_#34d399]';
        }
        if (telemetryDot) telemetryDot.className = 'inline-block w-2 h-2 rounded-full bg-emerald-400 animate-ping';
        if (serverVersionText) serverVersionText.textContent = versionDetected;
      } else {
        if (statusText) statusText.textContent = 'Offline';
        if (statusBadge) statusBadge.className = 'font-bold flex items-center gap-2 text-base mt-1.5 text-rose-500';
        if (statusDot) {
          statusDot.className = 'w-2.5 h-2.5 rounded-full bg-rose-500 shadow-[0_0_10px_#f43f5e]';
        }
        if (telemetryDot) telemetryDot.className = 'inline-block w-2 h-2 rounded-full bg-rose-500';
        if (serverVersionText) serverVersionText.textContent = 'Server Unreachable';
      }

      renderRealPlayers(onlineCount, maxCount, playerList);

      if (refreshIcon) {
        setTimeout(() => refreshIcon.classList.remove('fa-spin'), 600);
      }
      const now = new Date();
      const timeStr = now.toLocaleTimeString([], { hour: '2-digit', minute: '2-digit', second: '2-digit' });
      if (lastUpdatedElem) lastUpdatedElem.textContent = `(Updated: ${timeStr})`;
    }

    // Run on load and poll every 30 seconds
    window.addEventListener('DOMContentLoaded', () => {
      fetchLiveServerStatus();
      setInterval(fetchLiveServerStatus, 30000);
    });

    // Payment Modal Functions
    function openPaymentModal() {
      const modal = document.getElementById('payment-modal');
      modal.classList.remove('opacity-0', 'pointer-events-none');
      modal.classList.add('opacity-100', 'pointer-events-auto');
    }

    function closePaymentModal() {
      const modal = document.getElementById('payment-modal');
      modal.classList.add('opacity-0', 'pointer-events-none');
      modal.classList.remove('opacity-100', 'pointer-events-auto');
    }

    // Close modal on click outside content
    window.addEventListener('click', function(e) {
      const modal = document.getElementById('payment-modal');
      if (e.target === modal) {
        closePaymentModal();
      }
    });

    // Copy to clipboard utility
    function copyToClipboard(text, customMessage) {
      const tempInput = document.createElement('input');
      tempInput.style.position = 'absolute';
      tempInput.style.left = '-9999px';
      tempInput.value = text;
      document.body.appendChild(tempInput);
      tempInput.select();
      
      try {
        document.execCommand('copy');
        showToast(customMessage || 'Copied to clipboard!');
      } catch (err) {
        showToast('Failed to copy');
      }
      document.body.removeChild(tempInput);
    }

    // Interactive Toast Notification
    let toastTimeout;
    function showToast(message) {
      const toast = document.getElementById('toast');
      const textElem = document.getElementById('toast-text');
      textElem.textContent = message;

      toast.classList.remove('translate-y-24', 'opacity-0');
      toast.classList.add('translate-y-0', 'opacity-100');

      clearTimeout(toastTimeout);
      toastTimeout = setTimeout(() => {
        toast.classList.remove('translate-y-0', 'opacity-100');
        toast.classList.add('translate-y-24', 'opacity-0');
      }, 3000);
    }
  </script>
</body>
</html>
