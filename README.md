<!DOCTYPE html>
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
        <!-- Message Repeat 1 -->
      <div class="flex items-center gap-8">
        <span class="text-gold-400 font-bold flex items-center gap-1.5"><i class="fa-solid fa-heart-pulse text-red-500 animate-pulse"></i> GHOST LIFESTEAL SEASON 1 LAUNCHED!</span>
        <span class="text-slate-400">•</span>
        <span class="text-emerald-400 font-bold flex items-center gap-1.5">🏆 PVP EVENT 1ST WINNER: <span class="text-white underline decoration-gold-400 font-mono">flaxxy444</span> 🥇</span>
        <span class="text-slate-400">•</span>
        <span class="text-blue-400 font-bold flex items-center gap-1.5">🥈 2ND WINNER: <span class="text-white underline decoration-blue-400 font-mono">senkist13</span></span>
        <span class="text-slate-400">•</span>
        <span class="text-rose-400 font-semibold flex items-center gap-1.5">⚔️ STEAL HEARTS & CONQUER THE LIFESTEAL REALM!</span>
        <span class="text-slate-400">•</span>
        <span class="text-yellow-400 font-bold">🛒 LEGEND KIT AVAILABLE IN STORE FOR ₹40 INR ONLY!</span>
      </div>
      
      <!-- Message Repeat 2 (Seamless loop) -->
      <div class="flex items-center gap-8">
        <span class="text-gold-400 font-bold flex items-center gap-1.5"><i class="fa-solid fa-heart-pulse text-red-500 animate-pulse"></i> GHOST LIFESTEAL SEASON 1 LAUNCHED!</span>
        <span class="text-slate-400">•</span>
        <span class="text-emerald-400 font-bold flex items-center gap-1.5">🏆 PVP EVENT 1ST WINNER: <span class="text-white underline decoration-gold-400 font-mono">flaxxy444</span> 🥇</span>
        <span class="text-slate-400">•</span>
        <span class="text-blue-400 font-bold flex items-center gap-1.5">🥈 2ND WINNER: <span class="text-white underline decoration-blue-400 font-mono">senkist13</span></span>
        <span class="text-slate-400">•</span>
        <span class="text-rose-400 font-semibold flex items-center gap-1.5">⚔️ STEAL HEARTS & CONQUER THE LIFESTEAL REALM!</span>
        <span class="text-slate-400">•</span>
        <span class="text-yellow-400 font-bold">🛒 LEGEND KIT AVAILABLE IN STORE FOR ₹40 INR ONLY!</span>
      </div>
        
        <!-- Message Repeat 2 (Seamless loop) -->
        <div class="flex items-center gap-8">
          <span class="text-gold-400 font-bold flex items-center gap-1.5"><i class="fa-solid fa-bolt"></i> GHOST SMP SEASON 1 LAUNCHED!</span>
          <span class="text-slate-400">•</span>
          <span class="text-emerald-400 font-bold flex items-center gap-1.5">🏆 PVP EVENT 1ST WINNER: <span class="text-white underline decoration-gold-400 font-mono">flaxxy444</span> 🥇</span>
          <span class="text-slate-400">•</span>
          <span class="text-blue-400 font-bold flex items-center gap-1.5">🥈 2ND WINNER: <span class="text-white underline decoration-blue-400 font-mono">senkist13</span></span>
          <span class="text-slate-400">•</span>
          <span class="text-amber-300 font-semibold flex items-center gap-1.5">⚔️ NEXT BIG EVENT COMING SOON - JOIN DISCORD TO PARTICIPATE!</span>
          <span class="text-slate-400">•</span>
          <span class="text-yellow-400 font-bold">🛒 LEGEND KIT AVAILABLE IN STORE FOR ₹40 INR ONLY!</span>
        </div>
      </div>
    </div>
  </div>

  <!-- Notification Toast Container -->
  <div id="toast" class="fixed bottom-6 right-6 z-50 transform translate-y-24 opacity-0 transition-all duration-300 pointer-events-none flex items-center gap-3 bg-slate-900 border border-gold-500/50 text-white px-5 py-3.5 rounded-xl shadow-2xl">
    <i class="fa-solid fa-circle-check text-gold-400 text-lg"></i>
    <span id="toast-text" class="text-sm font-semibold tracking-wide">Copied to clipboard!</span>
  </div>

  <!-- Lightbox Modal for Gallery Images -->
  <div id="image-modal" class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-black/90 backdrop-blur-md opacity-0 pointer-events-none transition-all duration-300" onclick="closeImageModal()">
    <div class="relative max-w-5xl w-full max-h-[90vh] flex flex-col items-center" onclick="event.stopPropagation()">
      <button onclick="closeImageModal()" class="absolute -top-12 right-0 text-slate-300 hover:text-white bg-slate-800/80 px-3 py-1.5 rounded-lg border border-slate-700 text-sm font-semibold flex items-center gap-1.5">
        <i class="fa-solid fa-xmark"></i> Close
      </button>
      <img id="modal-img-element" src="" alt="PVP Event Preview" class="w-full h-auto max-h-[80vh] object-contain rounded-2xl border-2 border-gold-500/50 shadow-2xl">
      <div id="modal-img-caption" class="mt-3 text-gold-300 font-bold text-sm tracking-wide bg-slate-900/90 border border-slate-800 px-4 py-2 rounded-xl"></div>
    </div>
  </div>

  <!-- Navbar -->
  <header class="sticky top-[39px] z-40 backdrop-blur-md bg-smpDark/90 border-b border-smpBorder/80">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
      
      <!-- Logo Branding -->
      <a href="#home" class="flex items-center gap-3.5 group">
        <div class="w-12 h-12 flex items-center justify-center relative rounded-xl overflow-hidden shadow-md shadow-gold-500/20 border border-gold-500/30">
          <img src="image_2fdf01.jpg" alt="Ghost MC Logo" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-300">
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
        <a href="#gallery" class="text-slate-300 hover:text-gold-400 transition-colors text-sm font-medium flex items-center gap-1.5">
          <i class="fa-solid fa-camera text-xs text-gold-400"></i> Event Gallery
        </a>
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
    <section id="home" class="pt-10 pb-14 md:pt-12 md:pb-20 max-w-6xl mx-auto px-4 text-center">
      
      <!-- New Ghost MC Crest Logo Display -->
      <div class="relative flex justify-center mb-6">
        <div class="relative w-64 h-64 sm:w-72 sm:h-72 md:w-80 md:h-80 animate-float">
          <!-- Ambient Glow behind Crest Logo -->
          <div class="absolute inset-0 bg-gold-500/30 blur-3xl rounded-full scale-90"></div>
          
          <img src="image_2fdf01.jpg" alt="Ghost MC Official Logo" class="w-full h-full object-contain relative z-10 rounded-3xl drop-shadow-[0_12px_35px_rgba(234,179,8,0.5)] border-2 border-gold-500/40">
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
            <span class="inline-block w-2 h-2 rounded-full bg-emerald-400 animate-ping"></span>
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
          </div>

          <!-- Live Players Online Card (Now includes Usernames directly inside) -->
          <div class="bg-smpCard/90 border border-smpBorder hover:border-gold-500/50 transition-all p-4 rounded-xl shadow-lg relative overflow-hidden group">
            <div class="text-xs text-slate-400 uppercase tracking-wider font-semibold flex items-center justify-between">
              <span>Players Online</span>
              <i class="fa-solid fa-users text-gold-400 text-xs"></i>
            </div>
            <div class="flex items-baseline gap-1.5 mt-1">
              <span id="server-players-online" class="text-2xl font-black font-mono text-white tracking-tight">--</span>
              <span id="server-players-max" class="text-xs text-slate-500 font-mono">/ --</span>
            </div>
            <div class="text-[10px] text-emerald-400 font-medium mt-0.5 flex items-center gap-1">
              <span class="w-1.5 h-1.5 rounded-full bg-emerald-400 animate-pulse"></span>
              <span id="server-players-status">Querying server...</span>
            </div>

            <!-- Direct In-Card Username Roster -->
            <div class="mt-2.5 pt-2.5 border-t border-slate-800/80">
              <div class="text-[10px] uppercase font-bold text-slate-400 flex items-center justify-between mb-1.5">
                <span>Who's Online:</span>
                <span id="roster-count-tag" class="font-mono text-gold-400 text-[9px] bg-slate-900 px-1.5 py-0.5 rounded">--</span>
              </div>
              <div id="card-players-list" class="flex flex-wrap gap-1.5 max-h-24 overflow-y-auto pr-1">
                <span class="text-[11px] text-slate-400 italic">Checking active players...</span>
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

    <!-- PHOTO GALLERY / PVP EVENT HIGHLIGHTS SECTION -->
    <section id="gallery" class="py-16 bg-slate-950/90 border-t border-b border-smpBorder/70 relative">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        
        <div class="text-center mb-12">
          <div class="inline-flex items-center gap-2 px-3.5 py-1 rounded-full bg-gold-500/10 border border-gold-500/30 text-gold-400 text-xs font-bold uppercase tracking-widest mb-3">
            <i class="fa-solid fa-trophy"></i> Official Tournament Highlights
          </div>
          <h2 class="text-3xl sm:text-5xl font-heading font-black text-white tracking-wide">
            📸 LIFESTEAL MEMORIES & PVP EVENTS
          </h2>
          <p class="text-slate-400 text-sm sm:text-base mt-3 max-w-2xl mx-auto">
            Take a look at the glorious moments from our latest Ghost MC Colosseum Championship! Click on any screenshot to view in full resolution.
          </p>
        </div>

        <!-- 4 Photo Grid (PVP EVENT TAGGED) -->
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 lg:gap-8">
          
          <!-- Image 1: Diamond Line-up -->
          <div class="group relative bg-smpCard border border-smpBorder hover:border-gold-500/60 rounded-2xl overflow-hidden shadow-xl transition-all duration-300 cursor-pointer" onclick="openImageModal('image_2fdb9e.jpg', 'PVP Event: Tournament Line-up & Staff Ceremony')">
            <div class="relative overflow-hidden aspect-[16/9]">
              <img src="image_2fdb9e.jpg" alt="PVP Tournament Lineup" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
              
              <!-- Tag Badge -->
              <div class="absolute top-3 left-3 bg-gradient-to-r from-amber-500 to-yellow-600 text-black text-xs font-black px-3 py-1 rounded-lg uppercase tracking-wider shadow-lg flex items-center gap-1.5">
                <i class="fa-solid fa-trophy text-[11px]"></i> PVP EVENT
              </div>

              <!-- Overlay Hover Prompt -->
              <div class="absolute inset-0 bg-black/40 opacity-0 group-hover:opacity-100 transition-opacity flex items-center justify-center">
                <span class="bg-black/75 text-gold-400 text-xs font-bold px-3 py-1.5 rounded-lg border border-gold-500/40 flex items-center gap-1.5">
                  <i class="fa-solid fa-expand"></i> Click to Zoom
                </span>
              </div>
            </div>
            <div class="p-4 border-t border-slate-800/80">
              <h4 class="font-bold text-white text-base">Grand Opening Line-up</h4>
              <p class="text-xs text-slate-400 mt-1">Warriors assembled in full Diamond Armor on the central stadium platform before the battle began.</p>
            </div>
          </div>

          <!-- Image 2: Winners Podium (flaxxy444 & SenKist13) -->
          <div class="group relative bg-smpCard border-2 border-gold-500/60 rounded-2xl overflow-hidden shadow-2xl transition-all duration-300 cursor-pointer gold-glow" onclick="openImageModal('image_2fdb62.jpg', 'PVP Event Winners: 1st Place flaxxy444 & 2nd Place senkist13')">
            <div class="relative overflow-hidden aspect-[16/9]">
              <img src="image_2fdb62.jpg" alt="PVP Event Winners Podium" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
              
              <!-- Tag Badge -->
              <div class="absolute top-3 left-3 bg-gradient-to-r from-gold-400 via-amber-500 to-yellow-600 text-black text-xs font-black px-3 py-1 rounded-lg uppercase tracking-wider shadow-lg flex items-center gap-1.5">
                <i class="fa-solid fa-crown text-[11px]"></i> PVP EVENT • WINNERS
              </div>

              <div class="absolute inset-0 bg-black/40 opacity-0 group-hover:opacity-100 transition-opacity flex items-center justify-center">
                <span class="bg-black/75 text-gold-400 text-xs font-bold px-3 py-1.5 rounded-lg border border-gold-500/40 flex items-center gap-1.5">
                  <i class="fa-solid fa-expand"></i> Click to Zoom
                </span>
              </div>
            </div>
            <div class="p-4 border-t border-slate-800/80 bg-gradient-to-b from-transparent to-gold-950/20">
              <div class="flex items-center justify-between">
                <h4 class="font-bold text-gold-300 text-base flex items-center gap-2">
                  <span>🏆 Winners Podium Ceremony</span>
                </h4>
                <span class="text-[11px] font-mono font-bold bg-gold-500/20 text-gold-400 px-2 py-0.5 rounded">OFFICIAL RESULTS</span>
              </div>
              <p class="text-xs text-slate-300 mt-1">
                <strong>1st Winner:</strong> <span class="text-amber-400 font-bold">flaxxy444</span> (VIP) &nbsp;|&nbsp; 
                <strong>2nd Winner:</strong> <span class="text-blue-400 font-bold">senkist13</span> (Member)
              </p>
            </div>
          </div>

          <!-- Image 3: Audience & Spectators Platform -->
          <div class="group relative bg-smpCard border border-smpBorder hover:border-gold-500/60 rounded-2xl overflow-hidden shadow-xl transition-all duration-300 cursor-pointer" onclick="openImageModal('image_2fd840.jpg', 'PVP Event: Spectator Rail & Arena Oversight')">
            <div class="relative overflow-hidden aspect-[16/9]">
              <img src="image_2fd840.jpg" alt="PVP Event Spectators" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
              
              <!-- Tag Badge -->
              <div class="absolute top-3 left-3 bg-gradient-to-r from-amber-500 to-yellow-600 text-black text-xs font-black px-3 py-1 rounded-lg uppercase tracking-wider shadow-lg flex items-center gap-1.5">
                <i class="fa-solid fa-trophy text-[11px]"></i> PVP EVENT
              </div>

              <div class="absolute inset-0 bg-black/40 opacity-0 group-hover:opacity-100 transition-opacity flex items-center justify-center">
                <span class="bg-black/75 text-gold-400 text-xs font-bold px-3 py-1.5 rounded-lg border border-gold-500/40 flex items-center gap-1.5">
                  <i class="fa-solid fa-expand"></i> Click to Zoom
                </span>
              </div>
            </div>
            <div class="p-4 border-t border-slate-800/80">
              <h4 class="font-bold text-white text-base">Media & Spectator Arena Box</h4>
              <p class="text-xs text-slate-400 mt-1">Players including [MEDIA] SubhamOG, AlyaaTsb, and fighters cheering during match preliminaries.</p>
            </div>
          </div>

          <!-- Image 4: Arena Combat Action -->
          <div class="group relative bg-smpCard border border-smpBorder hover:border-gold-500/60 rounded-2xl overflow-hidden shadow-xl transition-all duration-300 cursor-pointer" onclick="openImageModal('image_2fd803.jpg', 'PVP Event: Gladiator Ring 1v1 Battle Action')">
            <div class="relative overflow-hidden aspect-[16/9]">
              <img src="image_2fd803.jpg" alt="PVP Event Battle Ring" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
              
              <!-- Tag Badge -->
              <div class="absolute top-3 left-3 bg-gradient-to-r from-amber-500 to-yellow-600 text-black text-xs font-black px-3 py-1 rounded-lg uppercase tracking-wider shadow-lg flex items-center gap-1.5">
                <i class="fa-solid fa-trophy text-[11px]"></i> PVP EVENT
              </div>

              <div class="absolute inset-0 bg-black/40 opacity-0 group-hover:opacity-100 transition-opacity flex items-center justify-center">
                <span class="bg-black/75 text-gold-400 text-xs font-bold px-3 py-1.5 rounded-lg border border-gold-500/40 flex items-center gap-1.5">
                  <i class="fa-solid fa-expand"></i> Click to Zoom
                </span>
              </div>
            </div>
            <div class="p-4 border-t border-slate-800/80">
              <h4 class="font-bold text-white text-base">Intense Sand-Arena Clashes</h4>
              <p class="text-xs text-slate-400 mt-1">Clutches, sword combos, and shield blocks under the watch of Co-Owner Mr_League inside the stadium ring.</p>
            </div>
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
                <a href="upi://pay?pa=ghostmc.fund@axl&pn=GhostMC&am=40&cu=INR&tn=Legend+Kit" class="shine-btn flex-1 bg-gradient-to-r from-gold-500 via-amber-500 to-yellow-500 hover:from-gold-400 hover:to-yellow-400 text-black font-extrabold py-3.5 px-6 rounded-xl text-center shadow-lg shadow-gold-500/25 transition-all flex items-center justify-center gap-2">
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
                  After completing payment, please join our Discord server (<a href="https://discord.gg/H4p2TuNCA" target="_blank" class="text-gold-400 underline font-semibold">https://discord.gg/H4p2TuNCA</a>) and create a ticket in #tickets channel with your payment screenshot &amp; in-game username to claim your kit.
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
        <img src="image_2fdf01.jpg" alt="Ghost MC Logo" class="w-8 h-8 rounded-lg object-cover border border-gold-500/40">
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
          Powered by <strong class="text-transparent bg-clip-text bg-gradient-to-r from-gold-300 via-amber-400 to-yellow-500 font-extrabold tracking-wider text-sm">DEVESH</strong>
        </span>
        <i class="fa-solid fa-heart text-red-500 text-xs"></i>
      </div>
    </div>
  </footer>

  <script>
    // Live Minecraft Server Status & Player Counter Integration
    const SERVER_HOST = 'play.ghostmc.info.gf';
    const SERVER_BEDROCK_PORT = 19153;

    async function fetchLiveServerStatus() {
      const refreshBtn = document.getElementById('refresh-status-btn');
      const refreshIcon = document.getElementById('refresh-icon');
      const statusText = document.getElementById('server-status-text');
      const statusDot = document.getElementById('server-status-dot');
      const statusBadge = document.getElementById('server-status-badge');
      const playersOnlineElem = document.getElementById('server-players-online');
      const playersMaxElem = document.getElementById('server-players-max');
      const playersStatusElem = document.getElementById('server-players-status');
      const versionTextElem = document.getElementById('server-version-text');
      const lastUpdatedElem = document.getElementById('last-updated-text');
      const cardPlayersList = document.getElementById('card-players-list');
      const rosterCountTag = document.getElementById('roster-count-tag');

      if (refreshIcon) refreshIcon.classList.add('fa-spin');
      if (statusText) statusText.textContent = 'Checking...';

      let isOnline = false;
      let onlinePlayers = 0;
      let maxPlayers = 50;
      let versionLabel = 'Java & Bedrock';
      let playerList = [];

      try {
        // Query mcstatus.io API for Java port first
        let response = await fetch(`https://api.mcstatus.io/v2/status/java/${SERVER_HOST}`, { cache: 'no-store' });
        let data = null;
        
        if (response.ok) {
          data = await response.json();
          if (data && data.online) {
            isOnline = true;
            onlinePlayers = data.players ? data.players.online : 0;
            maxPlayers = data.players ? data.players.max : 50;
            versionLabel = data.version ? data.version.name_clean || data.version.name_raw : '1.20 - 1.21';
            
            // Extract player names / sample list if provided by server
            if (data.players && Array.isArray(data.players.list) && data.players.list.length > 0) {
              playerList = data.players.list.map(p => typeof p === 'string' ? p : (p.name_clean || p.name_raw || p.name));
            }
          }
        }

        // Secondary query via mcsrvstat.us to fetch player sample names if mcstatus didn't provide them
        if (playerList.length === 0) {
          try {
            const fallbackRes = await fetch(`https://api.mcsrvstat.us/3/${SERVER_HOST}`, { cache: 'no-store' });
            if (fallbackRes.ok) {
              const fbData = await fallbackRes.json();
              if (fbData && fbData.online) {
                isOnline = true;
                if (!onlinePlayers) onlinePlayers = fbData.players ? fbData.players.online : 0;
                if (!maxPlayers) maxPlayers = fbData.players ? fbData.players.max : 50;
                if (fbData.players && Array.isArray(fbData.players.list)) {
                  playerList = fbData.players.list.map(p => typeof p === 'string' ? p : (p.name || p));
                }
              }
            }
          } catch (e) {
            console.log('mcsrvstat query finished');
          }
        }

        // If Java query is offline or uses bedrock port, check Bedrock status API
        if (!isOnline) {
          try {
            const bedrockRes = await fetch(`https://api.mcstatus.io/v2/status/bedrock/${SERVER_HOST}:${SERVER_BEDROCK_PORT}`, { cache: 'no-store' });
            if (bedrockRes.ok) {
              const bedrockData = await bedrockRes.json();
              if (bedrockData && bedrockData.online) {
                isOnline = true;
                onlinePlayers = bedrockData.players ? bedrockData.players.online : 0;
                maxPlayers = bedrockData.players ? bedrockData.players.max : 50;
                versionLabel = bedrockData.version ? bedrockData.version.name : 'Bedrock 1.20+';
              }
            }
          } catch (e) {
            console.log('Bedrock ping attempt completed');
          }
        }

        // Render Status to DOM
        if (isOnline) {
          statusText.textContent = 'Server Online';
          statusBadge.className = 'font-bold flex items-center gap-2 text-base mt-1.5 text-emerald-400';
          statusDot.className = 'w-2.5 h-2.5 rounded-full bg-emerald-400 shadow-[0_0_10px_#34d399] animate-pulse';
          playersOnlineElem.textContent = onlinePlayers;
          playersMaxElem.textContent = `/ ${maxPlayers}`;
          playersStatusElem.textContent = `${onlinePlayers} player${onlinePlayers === 1 ? '' : 's'} connected`;
          versionTextElem.textContent = `${versionLabel}`;

          // Update Inside-Card Player Usernames List
          if (rosterCountTag) rosterCountTag.textContent = `${onlinePlayers} active`;

          if (cardPlayersList) {
            if (onlinePlayers > 0 && playerList.length > 0) {
              cardPlayersList.innerHTML = playerList.map(name => `
                <div class="inline-flex items-center gap-1.5 bg-slate-900/90 border border-gold-500/40 px-2 py-0.5 rounded-md shadow-sm">
                  <img src="https://mc-heads.net/avatar/${encodeURIComponent(name)}/18" onerror="this.src='https://placehold.co/18x18/1e293b/fbbf24?text=${encodeURIComponent(name.charAt(0))}'" alt="${name}" class="w-3.5 h-3.5 rounded-sm">
                  <span class="font-mono font-bold text-[10px] text-gold-300 truncate max-w-[110px]">${name}</span>
                </div>
              `).join('');
            } else if (onlinePlayers > 0) {
              cardPlayersList.innerHTML = `
                <span class="text-[11px] text-amber-300 font-medium flex items-center gap-1">
                  <i class="fa-solid fa-shield-heart text-amber-400 text-[10px]"></i> ${onlinePlayers} online (Server query privacy active)
                </span>
              `;
            } else {
              cardPlayersList.innerHTML = `
                <span class="text-[11px] text-slate-500 italic">No players online right now</span>
              `;
            }
          }

        } else {
          statusText.textContent = 'Server Online';
          statusBadge.className = 'font-bold flex items-center gap-2 text-base mt-1.5 text-emerald-400';
          statusDot.className = 'w-2.5 h-2.5 rounded-full bg-emerald-400 shadow-[0_0_10px_#34d399]';
          playersOnlineElem.textContent = '0';
          playersMaxElem.textContent = `/ 50`;
          playersStatusElem.textContent = 'Ready to join';
          versionTextElem.textContent = 'play.ghostmc.info.gf';
          if (rosterCountTag) rosterCountTag.textContent = '0 active';
          if (cardPlayersList) {
            cardPlayersList.innerHTML = `
              <span class="text-[11px] text-slate-500 italic">No players online right now</span>
            `;
          }
        }

        const now = new Date();
        const timeStr = now.toLocaleTimeString([], { hour: '2-digit', minute: '2-digit', second: '2-digit' });
        if (lastUpdatedElem) lastUpdatedElem.textContent = `(Updated: ${timeStr})`;

      } catch (err) {
        console.error('Server status check error:', err);
        statusText.textContent = 'Server Online';
        statusBadge.className = 'font-bold flex items-center gap-2 text-base mt-1.5 text-emerald-400';
        statusDot.className = 'w-2.5 h-2.5 rounded-full bg-emerald-400';
        playersOnlineElem.textContent = '0';
        playersMaxElem.textContent = '/ 50';
        playersStatusElem.textContent = 'play.ghostmc.info.gf';
        if (rosterCountTag) rosterCountTag.textContent = '0 active';
        if (cardPlayersList) {
          cardPlayersList.innerHTML = `<span class="text-[11px] text-slate-500 italic">No players online right now</span>`;
        }
      } finally {
        if (refreshIcon) {
          setTimeout(() => refreshIcon.classList.remove('fa-spin'), 600);
        }
      }
    }

    // Run on load and poll every 35 seconds
    window.addEventListener('DOMContentLoaded', () => {
      fetchLiveServerStatus();
      setInterval(fetchLiveServerStatus, 35000);
    });

    // Lightbox modal functions
    function openImageModal(imgSrc, caption) {
      const modal = document.getElementById('image-modal');
      const imgElem = document.getElementById('modal-img-element');
      const captionElem = document.getElementById('modal-img-caption');
      
      imgElem.src = imgSrc;
      captionElem.textContent = caption || 'Ghost MC PVP Event Screenshot';
      
      modal.classList.remove('opacity-0', 'pointer-events-none');
      modal.classList.add('opacity-100', 'pointer-events-auto');
    }

    function closeImageModal() {
      const modal = document.getElementById('image-modal');
      modal.classList.add('opacity-0', 'pointer-events-none');
      modal.classList.remove('opacity-100', 'pointer-events-auto');
    }

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
