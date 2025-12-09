<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover" />
  <title>BCA Farewell Invitation</title>
  <style>
    /* --- Variables --- */
    :root{
      --bg1:#021428; 
      --bg2:#002a5c; 
      --accent:#ffcc00; /* Primary gold/yellow */
      --muted:rgba(255,255,255,0.08);
      --card-bg: rgba(255,255,255,0.04);
      --glass: rgba(255,255,255,0.03);
      --cta:#00d1ff; 
      --danger:#ff6b6b;
      --success: #3be985;
      --game-color: #00d1ff; 
      /* --- NEW BACKGROUND COLORS FOR PREMIUM FEEL --- */
      --dark-box-bg: rgba(0, 0, 0, 0.2); /* Deep dark background */
      --dark-box-border: rgba(255, 255, 255, 0.05); /* Subtle border */
    }
    /* --- Reset & Base Styles --- */
    *{box-sizing:border-box}
    html,body{
      height:100%;
      margin:0;
      font-family:'Inter', 'Poppins', system-ui, Arial, sans-serif;
      background:linear-gradient(135deg,var(--bg1),var(--bg2));
      color:#fff
    }

    /* --- Layout --- */
    .wrap{
      min-height:100vh;
      display:flex;
      align-items:center;
      justify-content:center;
      padding:20px 
    }
    .grid{
      width:min(1100px,98%);
      display:grid;
      grid-template-columns:1fr 380px;
      gap:20px
    }

    /* --- Main Card Styles --- */
    .card{
      background:linear-gradient(180deg,var(--card-bg), rgba(255,255,255,0.02));
      padding:20px;
      border-radius:14px;
      backdrop-filter:blur(8px);
      box-shadow:0 12px 40px rgba(0,0,0,0.5)
    }
    .top{
      display:flex;
      gap:16px;
      align-items:center
    }
    .greet{flex:1}
    h1{margin:0;font-size:20px}
    p.lead{margin:6px 0 12px 0;color:rgba(255,255,255,0.9)}

    /* --- Input & Buttons --- */
    input[type=text]{
      width:100%;
      padding:12px;
      border-radius:10px;
      border:none;
      background:transparent;
      border:1px solid var(--muted);
      color:#fff;
      font-size:16px;
      transition:box-shadow 0.2s;
    }
    .controls{display:flex;gap:10px;margin-top:12px;flex-wrap:wrap}
    .btn{
      padding:10px 16px;
      border-radius:10px;
      border:none;
      background:var(--accent);
      color:#000;
      font-weight:700;
      cursor:pointer;
      transition:background 0.2s, transform 0.1s;
    }
    .btn:active{transform:scale(0.98)}
    #playNamaste{
      background: rgba(255,255,255,0.1);
      color: #fff;
    }
    
    /* --- Countdown & Text Lines (Same as before) --- */
    .countwrap{display:flex;flex-direction:column;align-items:center;gap:8px}
    .countbox{
      display:flex;
      gap:10px;
      padding:12px;
      border-radius:12px;
      background:linear-gradient(90deg,rgba(255,255,255,0.03),rgba(255,255,255,0.02));
    }
    .digit{
      min-width:72px;
      padding:10px 12px;
      border-radius:8px;
      background:rgba(0,0,0,0.45);
      text-align:center;
      font-family:'Orbitron',sans-serif;
      font-size:28px;
      color:var(--accent);
      box-shadow:0 6px 18px rgba(0,0,0,0.45), inset 0 -6px 18px rgba(255,255,255,0.02)
    }
    .label{
      font-size:12px;
      color:rgba(255,255,255,0.6);
      text-align:center;
      margin-top:6px
    }
    .lines{margin-top:16px;min-height:140px;overflow:auto}
    .line{
      font-size:17px;
      margin:10px 0;
      opacity:0;
      transform:translateY(12px);
      animation:lineIn .6s forwards
    }
    @keyframes lineIn{to{opacity:1;transform:translateY(0)}}

    /* --- Right Column (Details + Emojis) --- */
    .side{
      background:linear-gradient(180deg,var(--card-bg), rgba(255,255,255,0.01));
      padding:16px;
      border-radius:12px
    }
    .side h3{margin:0 0 10px 0}
    .detailBtns{display:flex;flex-direction:column;gap:10px;margin-bottom:12px}
    .detailBtn{
      padding:12px;
      border-radius:10px;
      border:none;
      text-align:left;
      font-weight:700;
      cursor:pointer;
      transition:transform 0.1s;
    }
    .detailBtn:active{transform:scale(0.99)}

    .detailBtn.venue{background:linear-gradient(90deg,#6ce7b8,#00d1ff);color:#003}
    .detailBtn.date{background:linear-gradient(90deg,#ffd76b,#ff8a00);color:#103}
    .detailBtn.time{background:linear-gradient(90deg,#aab6ff,#6e9cff);color:#012}
    .detailBtn.msg{background:linear-gradient(90deg,#ff9bb3,#ff6b6b);color:#200}

    #detailBox{
      min-height:60px;
      padding:10px;
      border-radius:8px;
      background:rgba(0,0,0,0.25);
      margin-top:6px;
      color: var(--accent);
    }

    /* --- EMOJI section --- */
    .memeBox{
      margin-top:14px;
      border-radius:10px;
      overflow:hidden;
      background: var(--dark-box-bg); 
      border: 1px solid var(--dark-box-border);
      padding:10px;
      text-align:center;
    }
    .emojiDisplay{
      height:100px;
      font-size:72px; 
      display:flex;
      align-items:center;
      justify-content:center;
      border-radius:8px;
      background:rgba(0,0,0,0.3);
      margin-bottom: 10px;
      transition: background 0.3s;
    }
    .memeText{padding:10px 0;font-size:14px;color:rgba(255,255,255,0.9);min-height:44px}
    .memeBtn{
      margin-top:8px;
      padding:8px 12px;
      border-radius:10px;
      border:none;
      background:var(--accent);
      color:#000;
      cursor:pointer
    }

    /* --- GAME ARCADE SECTION --- */
    .gameBox{
        margin-top: 20px;
        padding: 15px;
        border-radius: 12px;
        background: var(--dark-box-bg);
        box-shadow: 0 4px 10px rgba(0,0,0,0.3);
        border: 2px solid var(--dark-box-border);
    }
    .gameBox h4 {
        margin-top: 0;
        color: var(--game-color);
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 8px;
        font-size: 18px;
        margin-bottom: 15px;
    }

    /* Tab styles */
    .gameTabs {
        display: flex;
        gap: 5px;
        margin-bottom: 15px;
        border-bottom: 1px solid var(--muted);
        padding-bottom: 5px;
    }
    .gameTabs button {
        flex: 1;
        padding: 8px 5px;
        border: none;
        border-radius: 6px 6px 0 0;
        background: rgba(255, 255, 255, 0.05);
        color: rgba(255, 255, 255, 0.7);
        cursor: pointer;
        transition: background 0.2s, color 0.2s;
    }
    .gameTabs button.active {
        background: var(--game-color);
        color: #000;
        font-weight: 700;
    }
    
    .gameContent {
        min-height: 200px; 
        padding: 10px 0;
    }
    .gamePane {
        display: none;
        text-align: center;
    }
    .gamePane.active {
        display: block;
    }

    /* Tic-Tac-Toe Styles */
    #tictactoe-board {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 5px;
        width: 180px;
        height: 180px;
        margin: 0 auto;
        border: 3px solid var(--game-color);
        background: rgba(0, 0, 0, 0.3);
    }
    .cell {
        background: rgba(255, 255, 255, 0.1);
        display: flex;
        align-items: center;
        justify-content: center;
        font-size: 40px;
        font-weight: 800;
        color: var(--accent);
        cursor: pointer;
        transition: background 0.1s;
    }
    .cell:hover {
        background: rgba(255, 255, 255, 0.2);
    }
    #tictactoe-message {
        margin-top: 10px;
        font-weight: 600;
        color: var(--success);
    }

    /* Dice/Coin Styles */
    .visual-display {
        font-size: 80px;
        min-height: 100px;
        display: flex;
        align-items: center;
        justify-content: center;
        margin: 15px 0;
        color: var(--accent);
    }
    .game-result-message {
        font-size: 16px;
        font-weight: 600;
        min-height: 40px;
        margin-bottom: 10px;
        color: var(--success);
    }
    .game-action-btn {
        background: var(--game-color);
        color: #000;
        font-weight: 700;
        padding: 10px 15px;
        border-radius: 8px;
        border: none;
        cursor: pointer;
    }

    /* --- Final message --- */
    .fullmsg{
        display:flex;
        align-items:center;
        justify-content:center;
        height:100vh;
        text-align:center;
        background:linear-gradient(135deg,#001f3f,#002a5c);
    }
    .fullmsg h2{font-size:28px; color: #fff;}

    /* ------------------------------------- */
    /* --- MOBILE RESPONSIVENESS ENHANCED --- */
    /* ------------------------------------- */
    @media(max-width:920px){
      .grid{grid-template-columns:1fr} 
      .wrap{padding:10px} 
      .top{flex-direction:column; align-items:flex-start} 
      .greet{width:100%; text-align:center; margin-bottom: 10px;} 
      .countwrap{width:100%} 
      .countbox{width:100%; justify-content:space-around} 
      .digit{min-width:52px;font-size:20px}
      .emojiDisplay{height:80px; font-size: 60px;} 
    }

    @media(max-width:480px){
      .digit{min-width:40px; font-size:18px; padding:8px} 
      .label{font-size:10px} 
      .btn, .detailBtn, .memeBtn{font-size:14px; padding:10px 12px;} 
      .detailBtns{gap:8px} 
      .lines{min-height:100px} 
      .line{font-size:16px}
      .memeBox{padding:8px}
      #tictactoe-board{width: 150px; height: 150px;}
      .cell{font-size: 30px;}
      .visual-display{font-size: 60px;}
    }
  </style>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@600&family=Poppins:wght@400;700;800&family=Inter:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>

  <div class="wrap">
    <div class="grid">

      <section class="card" aria-labelledby="inviteTitle">
        <div class="top">
          <div class="greet">
            <h1 id="inviteTitle">Namastey 🙏</h1>
            <p class="lead">With respect — please enter your good name to begin.</p>
          </div>
          <div class="countwrap">
            <div class="countbox" aria-hidden="true">
              <div class="digit" id="days">00</div>
              <div class="digit" id="hours">00</div>
              <div class="digit" id="minutes">00</div>
              <div class="digit" id="seconds">00</div>
            </div>
            <div style="display:flex;gap:8px;width:100%;justify-content:space-between">
              <div class="label">Days</div>
              <div class="label">Hours</div>
              <div class="label">Mins</div>
              <div class="label">Secs</div>
            </div>
          </div>
        </div>

        <input id="nameInput" type="text" placeholder="Your name (e.g. Sagar)" aria-label="Name" />
        <div style="display:flex;gap:10px;margin-top:12px;align-items:center">
          <button class="btn" id="startBtn">Next</button>
          <button class="btn" id="playNamaste">🔊 Namaste</button>
        </div>

        <div class="lines" id="lines" aria-live="polite"></div>
      </section>

      <aside class="side" aria-label="Event details">
        <h3>Event Details 🎉</h3>

        <div class="detailBtns">
          <button class="detailBtn venue" id="venueBtn">📍 Venue</button>
          <button class="detailBtn date" id="dateBtn">📅 Date</button>
          <button class="detailBtn time" id="timeBtn">⏰ Time</button>
          <button class="detailBtn msg" id="messageBtn">💌 Special Message</button>
        </div>

        <div id="detailBox" aria-live="polite"></div>

        <div class="memeBox">
          <div class="emojiDisplay" id="emojiDisplay">
            👋
          </div>
          <div class="memeText" id="memeText">Tap "New Emoji Tap" for a quick welcome message!</div>
          <button class="memeBtn" id="newMemeBtn">New Emoji Tap</button>
        </div>

        <div class="gameBox">
            <h4>🕹️ BCA Game Arcade</h4>
            
            <div class="gameTabs">
                <button class="tab-btn active" data-game="tictactoe">⭕❌ Tic-Tac-Toe</button>
                <button class="tab-btn" data-game="diceroll">🎲 Dice Roll</button>
                <button class="tab-btn" data-game="coinflip">🪙 Coin Flip</button>
            </div>

            <div class="gameContent">
                
                <div id="tictactoe" class="gamePane active">
                    <div id="tictactoe-board">
                        <div class="cell" data-index="0"></div>
                        <div class="cell" data-index="1"></div>
                        <div class="cell" data-index="2"></div>
                        <div class="cell" data-index="3"></div>
                        <div class="cell" data-index="4"></div>
                        <div class="cell" data-index="5"></div>
                        <div class="cell" data-index="6"></div>
                        <div class="cell" data-index="7"></div>
                        <div class="cell" data-index="8"></div>
                    </div>
                    <div id="tictactoe-message">Senior's Turn (X)</div>
                    <button class="game-action-btn" id="tictactoe-reset" style="margin-top: 10px;">Reset Game</button>
                </div>

                <div id="diceroll" class="gamePane">
                    <div class="visual-display" id="dice-display">
                        ❓
                    </div>
                    <div id="dice-message" class="game-result-message">
                        Roll the die to determine your "Farewell Luck" factor!
                    </div>
                    <button class="game-action-btn" id="dice-roll-btn">Roll Dice 🎲</button>
                </div>

                <div id="coinflip" class="gamePane">
                    <div class="visual-display" id="coin-display">
                        🪙
                    </div>
                    <div id="coin-message" class="game-result-message">
                        Flip the coin to decide: Attend Farewell **(Heads)** or Skip **(Tails)**?
                    </div>
                    <button class="game-action-btn" id="coin-flip-btn">Flip Coin 🪙</button>
                </div>

            </div>
        </div>


        <div style="margin-top:12px">
          <button class="btn" id="continueBtn">Continue</button>
        </div>
      </aside>

    </div>
  </div>

<script>
  // ---- speech & typing helpers ----
  const synth = window.speechSynthesis;
  function stopSpeech(){ try{ if(synth.speaking) synth.cancel(); }catch(e){} }
  function speak(text){ 
    stopSpeech(); 
    const u=new SpeechSynthesisUtterance(text); 
    u.rate=1; 
    u.lang='en-IN'; 
    synth.speak(u); 
  }

  let typingTimer=null;
  function typeText(el, text){ 
    if(typingTimer){ clearInterval(typingTimer); typingTimer=null;} 
    stopSpeech(); 
    el.textContent=''; 
    let i=0; 
    typingTimer=setInterval(()=>{ 
      el.textContent += text.charAt(i) || ''; 
      i++; 
      if(i>text.length){ 
        clearInterval(typingTimer); 
        typingTimer=null; 
      } 
    },28); 
  }

  // ---- content (UPDATED WITH EMOJIS) ----
  const LINES = [
    'With deep respect and warm hearts, we invite our beloved seniors to their Farewell Ceremony, organised by the BCA Department. 🙏🎓',
    'Your journey has inspired us every day. Please grace the Farewell Program with your presence. ✨',
    'We request the honour of your presence as we bid a heartfelt farewell to our seniors. ❤️',
    'Dear seniors, your system may log out from college, but your memories will always run in our background processes. 💾💻',
    'Your batch has been the perfect algorithm of inspiration. We invite you to the Final Output — your Farewell Celebration! 🥳📊',
    'Before you upgrade to the next version of life, please join us for one last gathering—your Farewell. ⬆️👋',
    "You didn't just earn degrees; you coded the culture of our department. Your time here was an algorithm of success — a blueprint that inspired us all. 💡 blueprint",
    'As you step into your next professional adventure, we invite you back one final time to celebrate the journeys we shared, the deadlines we conquered, and the incredible legacy you leave behind. 🚀🏆'
  ];

  const VENUE = 'The Venue: G.S. Sanyal Memorial Hall, Hijli College';
  const DATE = 'The Date: Thursday, December 11, 2025';
  const TIME = 'The Time: 11:00 AM sharp';
  const SPECIAL = 'We are eagerly waiting for your graceful presence. Please come and bless us with your presence.';

  // ---- DOM refs ----
  const daysEl = document.getElementById('days');
  const hoursEl = document.getElementById('hours');
  const minsEl = document.getElementById('minutes');
  const secsEl = document.getElementById('seconds');
  const nameInput = document.getElementById('nameInput');
  const startBtn = document.getElementById('startBtn');
  const playNamaste = document.getElementById('playNamaste');
  const linesBox = document.getElementById('lines');
  const venueBtn = document.getElementById('venueBtn');
  const dateBtn = document.getElementById('dateBtn');
  const timeBtn = document.getElementById('timeBtn');
  const messageBtn = document.getElementById('messageBtn');
  const detailBox = document.getElementById('detailBox');
  const continueBtn = document.getElementById('continueBtn');
  const newMemeBtn = document.getElementById('newMemeBtn');
  const emojiDisplay = document.getElementById('emojiDisplay');
  const memeText = document.getElementById('memeText');
  
  // Game Refs
  const tabButtons = document.querySelectorAll('.tab-btn');
  const gamePanes = document.querySelectorAll('.gamePane');

  // --- TIC-TAC-TOE Refs
  const cells = document.querySelectorAll('#tictactoe-board .cell');
  const tttMessage = document.getElementById('tictactoe-message');
  const tttResetBtn = document.getElementById('tictactoe-reset');
  
  // --- DICE ROLL Refs
  const diceDisplay = document.getElementById('dice-display');
  const diceMessage = document.getElementById('dice-message');
  const diceRollBtn = document.getElementById('dice-roll-btn');

  // --- COIN FLIP Refs
  const coinDisplay = document.getElementById('coin-display');
  const coinMessage = document.getElementById('coin-message');
  const coinFlipBtn = document.getElementById('coin-flip-btn');


  // ---- countdown ----
  const eventTs = new Date('December 11, 2025 11:00:00').getTime();
  function pad(n){ return n.toString().padStart(2,'0'); }
  function updateCountdown(){ 
    const diff = eventTs - Date.now(); 
    if(diff<=0){ 
      daysEl.textContent='00'; hoursEl.textContent='00'; minsEl.textContent='00'; secsEl.textContent='00'; 
      return; 
    } 
    const d=Math.floor(diff/(1000*60*60*24)); 
    const h=Math.floor((diff%(1000*60*60*24))/(1000*60*60)); 
    const m=Math.floor((diff%(1000*60*60))/(1000*60)); 
    const s=Math.floor((diff%(1000*60))/1000); 
    
    daysEl.textContent=pad(d); 
    hoursEl.textContent=pad(h); 
    minsEl.textContent=pad(m); 
    secsEl.textContent=pad(s); 
  }
  updateCountdown(); 
  setInterval(updateCountdown,1000);

  // ---- render lines (text animation) ----
  function renderLines(){ 
    linesBox.innerHTML=''; 
    let i=0; 
    function next(){ 
      if(i>=LINES.length) return; 
      const d=document.createElement('div'); 
      d.className='line'; 
      d.textContent=LINES[i]; 
      linesBox.appendChild(d); 
      i++; 
      linesBox.scrollTop = linesBox.scrollHeight;
      setTimeout(next,900);
    } 
    next(); 
  }

  // ---- handlers ----
  startBtn.addEventListener('click', ()=>{ 
    const name=nameInput.value.trim(); 
    if(!name){ 
      nameInput.focus(); 
      nameInput.style.boxShadow='0 0 0 4px rgba(255,204,0,0.12)'; 
      setTimeout(() => nameInput.style.boxShadow = '', 1000); 
      return; 
    } 
    document.getElementById('inviteTitle').textContent = `Welcome ${name} 🙏`; 
    speak(`Namaste ${name}. With respect, we invite you to your Farewell.`); 
    renderLines(); 
  });
  playNamaste.addEventListener('click', ()=>{ speak('Namastey'); });

  venueBtn.addEventListener('click', ()=>{ typeText(detailBox, VENUE); speak(VENUE); });
  dateBtn.addEventListener('click', ()=>{ typeText(detailBox, DATE); speak(DATE); });
  timeBtn.addEventListener('click', ()=>{ typeText(detailBox, TIME); speak(TIME); });
  messageBtn.addEventListener('click', ()=>{ typeText(detailBox, SPECIAL); speak(SPECIAL); });

  continueBtn.addEventListener('click', ()=>{ 
    stopSpeech(); 
    speak('Please come, we are waiting for you'); 
    document.body.innerHTML = `
      <div class="fullmsg">
        <h2>Please come... We are waiting for you 🙏❤️</h2>
      </div>
    `; 
  });

  // ---- EMOJI CONTENT (FINAL PREMIUM UPDATE) ----
  const EMOJI_MEMES = [
    {emoji:'✨', msg:"Your time here was brilliant. May your future career always shine brightly."},
    {emoji:'✅', msg:"Mission Accomplished: BCA degree secured. Ready for the next verified step."},
    {emoji:'📈', msg:"Here's to a future of exponential growth and unparalleled professional success."},
    {emoji:'🔑', msg:"You hold the key to endless opportunities. Unlock your potential, senior!"},
    {emoji:'♾️', msg:"Our bond is infinite. The memories we made will never fade."},
    {emoji:'💡', msg:"Keep that spark of innovation alive. You are the future problem solvers."},
    {emoji:'⭐', msg:"Leave a trail of stardust wherever you go. You are stars in the making."},
    {emoji:'🤝', msg:"Thank you for the guidance and the friendship. We value the connection."}
  ];
  
  let emojiIdx = 0;
  function showEmoji(idx){ 
    const item = EMOJI_MEMES[idx % EMOJI_MEMES.length]; 
    emojiDisplay.textContent = item.emoji;
    memeText.textContent = item.msg; 
    speak(item.msg);
  }
  
  newMemeBtn.addEventListener('click', ()=>{ 
    emojiIdx++; 
    showEmoji(emojiIdx); 
  });
  
  document.addEventListener('DOMContentLoaded', () => {
    if (EMOJI_MEMES.length > 0) {
      showEmoji(0);
    }
  });


  // ---- GAME ARCADE LOGIC ----

  // --- TAB SWITCHING ---
  tabButtons.forEach(btn => {
      btn.addEventListener('click', () => {
          // Deactivate all
          tabButtons.forEach(b => b.classList.remove('active'));
          gamePanes.forEach(p => p.classList.remove('active'));

          // Activate selected tab and pane
          btn.classList.add('active');
          const gameId = btn.getAttribute('data-game');
          document.getElementById(gameId).classList.add('active');
          
          speak(`Switched to ${btn.textContent.trim()}`);
      });
  });

  // --- GAME 1: TIC-TAC-TOE ---
  let boardState = ["", "", "", "", "", "", "", "", ""];
  let currentPlayer = "X"; // Senior is X
  let isGameActive = true;

  const WINNING_CONDITIONS = [
      [0, 1, 2], [3, 4, 5], [6, 7, 8], // rows
      [0, 3, 6], [1, 4, 7], [2, 5, 8], // columns
      [0, 4, 8], [2, 4, 6]            // diagonals
  ];

  function handleResultValidation() {
      let roundWon = false;
      for (let i = 0; i < WINNING_CONDITIONS.length; i++) {
          const winCondition = WINNING_CONDITIONS[i];
          let a = boardState[winCondition[0]];
          let b = boardState[winCondition[1]];
          let c = boardState[winCondition[2]];

          if (a === '' || b === '' || c === '') continue;
          
          if (a === b && b === c) {
              roundWon = true;
              break;
          }
      }

      if (roundWon) {
          isGameActive = false;
          tttMessage.textContent = `${currentPlayer} Won! Congratulations!`;
          speak(`${currentPlayer} won the game!`);
          return;
      }

      if (!boardState.includes("")) {
          isGameActive = false;
          tttMessage.textContent = "It's a Draw! Play again.";
          speak("It's a draw!");
          return;
      }

      changePlayer();
  }

  function changePlayer() {
      currentPlayer = currentPlayer === "X" ? "O" : "X";
      tttMessage.textContent = `${currentPlayer}'s Turn`;
  }

  function handleCellPlayed(clickedCell, clickedCellIndex) {
      if (boardState[clickedCellIndex] !== "" || !isGameActive) return;

      boardState[clickedCellIndex] = currentPlayer;
      clickedCell.textContent = currentPlayer;
      
      handleResultValidation();

      // Simple AI for "O" (The Junior/Organizer)
      if (isGameActive && currentPlayer === "O") {
        setTimeout(computerTurn, 500);
      }
  }
  
  function computerTurn() {
      let availableCells = [];
      boardState.forEach((cell, index) => {
          if (cell === "") availableCells.push(index);
      });

      if (availableCells.length > 0) {
          // Simple random move
          const randomIndex = availableCells[Math.floor(Math.random() * availableCells.length)];
          const cellElement = document.querySelector(`.cell[data-index="${randomIndex}"]`);
          
          boardState[randomIndex] = currentPlayer;
          cellElement.textContent = currentPlayer;
          handleResultValidation();
      }
  }

  cells.forEach(cell => {
      cell.addEventListener('click', (event) => {
          const clickedCellIndex = parseInt(event.target.getAttribute('data-index'));
          if (currentPlayer === "X") { // Only allow Senior (X) to click
            handleCellPlayed(event.target, clickedCellIndex);
          }
      });
  });

  tttResetBtn.addEventListener('click', () => {
      boardState = ["", "", "", "", "", "", "", "", ""];
      currentPlayer = "X";
      isGameActive = true;
      tttMessage.textContent = "Senior's Turn (X)";
      cells.forEach(cell => cell.textContent = "");
      speak("Tic-Tac-Toe reset. Senior starts.");
  });
  
  // --- GAME 2: DICE ROLL ---
  const DICE_EMOJIS = ['🎲', '⚀', '⚁', '⚂', '⚃', '⚄', '⚅'];
  const DICE_MESSAGES = [
      '', // Placeholder for index 0
      "Farewell Luck: 1. You must give a shout-out to the student who always sat next to you.",
      "Farewell Luck: 2. You must take a picture with the youngest junior present.",
      "Farewell Luck: 3. You must publicly thank your favourite faculty member.",
      "Farewell Luck: 4. You must give a high-five to three different organizing committee members.",
      "Farewell Luck: 5. You must start a small dance circle at the party.",
      "Farewell Luck: 6. You get a special reward (e.g., first in line for food) at the party!"
  ];

  diceRollBtn.addEventListener('click', () => {
      diceRollBtn.disabled = true;
      diceDisplay.textContent = DICE_EMOJIS[0]; // Show rolling emoji
      diceMessage.textContent = "Rolling...";

      setTimeout(() => {
          const roll = Math.floor(Math.random() * 6) + 1; // 1 to 6
          diceDisplay.textContent = DICE_EMOJIS[roll];
          diceMessage.textContent = DICE_MESSAGES[roll];
          speak(`You rolled a ${roll}. ${DICE_MESSAGES[roll]}`);
          diceRollBtn.disabled = false;
      }, 1000);
  });
  
  // --- GAME 3: COIN FLIP ---
  const COIN_RESULTS = {
      'Heads': 'You are destined to attend! Your Farewell Task: Start the first group activity (e.g., a group photo or a toast)!',
      'Tails': 'You must attend anyway! Your Farewell Task: Bring one embarrassing (but harmless) college photo of yourself to share with a friend at the party.',
  };

  coinFlipBtn.addEventListener('click', () => {
      coinFlipBtn.disabled = true;
      coinDisplay.textContent = '🔄'; // Spinning coin
      coinMessage.textContent = "Flipping...";

      setTimeout(() => {
          const result = Math.random() < 0.5 ? 'Heads' : 'Tails';
          coinDisplay.textContent = result === 'Heads' ? '👑' : '🪙'; 
          coinMessage.textContent = `Result: ${result}. ${COIN_RESULTS[result]}`;
          speak(`Coin landed on ${result}. ${COIN_RESULTS[result]}`);
          coinFlipBtn.disabled = false;
      }, 1000);
  });

  // ---- END GAME ARCADE LOGIC ----


  // stop speech on hide
  document.addEventListener('visibilitychange', ()=>{ if(document.hidden) stopSpeech(); });

  // try small auto-speak after first interaction
  let didAuto=false; 
  function tryAuto(){ 
    if(didAuto) return; 
    didAuto=true; 
    try{ speak('Namastey'); }catch(e){} 
    window.removeEventListener('click', tryAuto); 
    window.removeEventListener('touchstart', tryAuto); 
  }
  window.addEventListener('click', tryAuto); 
  window.addEventListener('touchstart', tryAuto, {passive:true});

</script>
</body>
</html>
