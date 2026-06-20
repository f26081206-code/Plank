<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Training Log</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700&family=JetBrains+Mono:wght@400;500;600;700&display=swap');

  :root{
    --ink:#16191c;
    --paper:#f6f4ee;
    --paper-2:#eeeae0;
    --line:#d9d4c6;
    --accent:#ff5a36;   /* effort / plank */
    --accent-2:#2f6f5e; /* nutrition / calm */
    --muted:#8a8478;
    --good:#2f6f5e;
    --warn:#c2452c;
  }

  *{box-sizing:border-box; margin:0; padding:0;}

  body{
    background:var(--paper);
    color:var(--ink);
    font-family:'Space Grotesk', sans-serif;
    min-height:100vh;
    padding:24px 16px 60px;
  }

  .wrap{ max-width:640px; margin:0 auto; }

  header{
    display:flex;
    justify-content:space-between;
    align-items:flex-end;
    border-bottom:3px solid var(--ink);
    padding-bottom:14px;
    margin-bottom:22px;
  }
  header .label{
    font-family:'JetBrains Mono', monospace;
    font-size:11px;
    letter-spacing:0.12em;
    text-transform:uppercase;
    color:var(--muted);
  }
  header h1{
    font-size:28px;
    font-weight:700;
    letter-spacing:-0.01em;
    margin-top:2px;
  }
  header .date{
    font-family:'JetBrains Mono', monospace;
    font-size:12px;
    color:var(--muted);
    text-align:right;
  }

  /* ---- Section shell ---- */
  .section{ margin-bottom:28px; }
  .section-head{
    display:flex;
    align-items:baseline;
    justify-content:space-between;
    margin-bottom:10px;
  }
  .section-head h2{
    font-size:14px;
    text-transform:uppercase;
    letter-spacing:0.08em;
    font-weight:600;
  }
  .section-head .tag{
    font-family:'JetBrains Mono', monospace;
    font-size:11px;
    color:var(--muted);
  }

  /* ---- Plank card ---- */
  .plank-card{
    background:var(--ink);
    color:var(--paper);
    border-radius:4px;
    padding:22px;
    position:relative;
    overflow:hidden;
  }
  .plank-top{
    display:flex;
    justify-content:space-between;
    align-items:flex-start;
  }
  .plank-best{
    font-family:'JetBrains Mono', monospace;
    font-size:11px;
    color:#b9b3a3;
    text-transform:uppercase;
    letter-spacing:0.08em;
  }
  .plank-best b{
    display:block;
    color:var(--accent);
    font-size:20px;
    font-family:'JetBrains Mono', monospace;
    margin-top:2px;
  }
  .timer-display{
    font-family:'JetBrains Mono', monospace;
    font-size:56px;
    font-weight:700;
    text-align:center;
    margin:18px 0 6px;
    letter-spacing:0.02em;
    font-variant-numeric:tabular-nums;
  }
  .timer-sub{
    text-align:center;
    font-size:12px;
    color:#b9b3a3;
    font-family:'JetBrains Mono', monospace;
    margin-bottom:18px;
  }
  .timer-controls{
    display:flex;
    gap:10px;
  }
  .btn{
    flex:1;
    border:none;
    border-radius:3px;
    padding:13px 10px;
    font-family:'Space Grotesk', sans-serif;
    font-weight:600;
    font-size:14px;
    cursor:pointer;
    transition:transform 0.08s ease, opacity 0.15s ease;
  }
  .btn:active{ transform:scale(0.97); }
  .btn-start{ background:var(--accent); color:#fff; }
  .btn-stop{ background:#3a3530; color:var(--paper); }
  .btn-reset{ background:transparent; color:#8a8478; border:1px solid #4a463d; flex:0 0 70px; }
  .btn:disabled{ opacity:0.4; cursor:default; }

  .plank-log{
    margin-top:16px;
    border-top:1px solid #3a3530;
    padding-top:12px;
  }
  .plank-log-row{
    display:flex;
    justify-content:space-between;
    font-family:'JetBrains Mono', monospace;
    font-size:12px;
    padding:5px 0;
    color:#cfc9ba;
  }
  .plank-log-row span:last-child{ color:var(--accent); font-weight:600; }
  .plank-empty{
    font-family:'JetBrains Mono', monospace;
    font-size:12px;
    color:#6f6a5e;
    padding:6px 0;
  }

  /* ---- Stat grid ---- */
  .stat-grid{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:10px;
  }
  .stat-card{
    background:var(--paper-2);
    border:1px solid var(--line);
    border-radius:4px;
    padding:14px 16px;
  }
  .stat-card .stat-label{
    font-family:'JetBrains Mono', monospace;
    font-size:10px;
    text-transform:uppercase;
    letter-spacing:0.08em;
    color:var(--muted);
    margin-bottom:6px;
  }
  .stat-card .stat-value{
    font-family:'JetBrains Mono', monospace;
    font-size:24px;
    font-weight:700;
  }
  .stat-card .stat-value.accent{ color:var(--accent-2); }
  .stat-card .stat-sub{
    font-size:11px;
    color:var(--muted);
    margin-top:3px;
  }

  /* ---- Nutrition input ---- */
  .nutrition-card{
    background:#fff;
    border:1px solid var(--line);
    border-radius:4px;
    padding:18px;
  }
  .input-row{
    display:flex;
    gap:10px;
    margin-bottom:10px;
  }
  .field{ flex:1; }
  .field label{
    display:block;
    font-family:'JetBrains Mono', monospace;
    font-size:10px;
    text-transform:uppercase;
    letter-spacing:0.06em;
    color:var(--muted);
    margin-bottom:5px;
  }
  .field input{
    width:100%;
    border:1px solid var(--line);
    border-radius:3px;
    padding:10px 10px;
    font-family:'JetBrains Mono', monospace;
    font-size:15px;
    background:var(--paper);
    color:var(--ink);
  }
  .field input:focus{ outline:2px solid var(--accent-2); outline-offset:-1px; }
  .btn-log{
    width:100%;
    background:var(--accent-2);
    color:#fff;
    border:none;
    border-radius:3px;
    padding:12px;
    font-family:'Space Grotesk', sans-serif;
    font-weight:600;
    font-size:14px;
    cursor:pointer;
    margin-top:4px;
  }
  .btn-log:active{ transform:scale(0.98); }

  .history{
    margin-top:6px;
  }
  .history-row{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:9px 0;
    border-bottom:1px solid var(--paper-2);
    font-family:'JetBrains Mono', monospace;
    font-size:12px;
  }
  .history-row:last-child{ border-bottom:none; }
  .history-date{ color:var(--muted); }
  .history-vals{ display:flex; gap:14px; }
  .history-vals .w{ color:var(--ink); font-weight:600; }
  .history-vals .c{ color:var(--accent-2); }
  .del-btn{
    background:none; border:none; color:var(--muted); cursor:pointer;
    font-size:14px; padding:0 0 0 10px;
  }

  .empty-state{
    font-family:'JetBrains Mono', monospace;
    font-size:12px;
    color:var(--muted);
    padding:10px 0;
  }

  footer{
    margin-top:30px;
    text-align:center;
    font-family:'JetBrains Mono', monospace;
    font-size:10px;
    color:var(--muted);
    letter-spacing:0.06em;
  }

  ::selection{ background:var(--accent); color:#fff; }
</style>
</head>
<body>
<div class="wrap">

  <header>
    <div>
      <div class="label">King — Personal</div>
      <h1>Training Log</h1>
    </div>
    <div class="date" id="todayDate">—</div>
  </header>

  <!-- PLANK SECTION -->
  <div class="section">
    <div class="section-head">
      <h2>Plank Timer</h2>
      <span class="tag">SECONDS HELD</span>
    </div>
    <div class="plank-card">
      <div class="plank-top">
        <div class="plank-best">PERSONAL BEST<b id="bestTime">0:00</b></div>
        <div class="plank-best" style="text-align:right">STREAK<b id="streakDays" style="color:#fff">0 days</b></div>
      </div>
      <div class="timer-display" id="timerDisplay">0:00</div>
      <div class="timer-sub" id="timerSub">Press start when you're set</div>
      <div class="timer-controls">
        <button class="btn btn-start" id="startBtn">Start</button>
        <button class="btn btn-stop" id="stopBtn" disabled>Stop &amp; Log</button>
        <button class="btn btn-reset" id="resetBtn">Reset</button>
      </div>
      <div class="plank-log" id="plankLog">
        <div class="plank-empty">No sessions logged yet today.</div>
      </div>
    </div>
  </div>

  <!-- STATS -->
  <div class="section">
    <div class="stat-grid">
      <div class="stat-card">
        <div class="stat-label">Current Weight</div>
        <div class="stat-value" id="currentWeight">—</div>
        <div class="stat-sub" id="weightTrend">No data yet</div>
      </div>
      <div class="stat-card">
        <div class="stat-label">Today's Calories</div>
        <div class="stat-value accent" id="todayCalories">—</div>
        <div class="stat-sub" id="calorieSub">No entry today</div>
      </div>
    </div>
  </div>

  <!-- NUTRITION LOG -->
  <div class="section">
    <div class="section-head">
      <h2>Daily Log</h2>
      <span class="tag">WEIGHT (KG) · CALORIES</span>
    </div>
    <div class="nutrition-card">
      <div class="input-row">
        <div class="field">
          <label>Weight (kg)</label>
          <input type="number" step="0.1" id="weightInput" placeholder="e.g. 78.5">
        </div>
        <div class="field">
          <label>Calories</label>
          <input type="number" id="calorieInput" placeholder="e.g. 2100">
        </div>
      </div>
      <button class="btn-log" id="logBtn">Log Today's Entry</button>

      <div class="history" id="historyList">
        <div class="empty-state">No entries yet — log your first day above.</div>
      </div>
    </div>
  </div>

  <footer>STORED LOCALLY ON THIS DEVICE · ARTIFACT SESSION MEMORY</footer>
</div>

<script>
(function(){
  // ---------- State ----------
  let plankSessions = {};   // { 'YYYY-MM-DD': [seconds, seconds...] }
  let nutritionLog = {};    // { 'YYYY-MM-DD': {weight, calories} }
  let bestPlank = 0;
  let timerInterval = null;
  let elapsedMs = 0;
  let timerRunning = false;

  function todayKey(){
    const d = new Date();
    return d.getFullYear()+'-'+String(d.getMonth()+1).padStart(2,'0')+'-'+String(d.getDate()).padStart(2,'0');
  }
  function fmtDateLabel(key){
    const d = new Date(key+'T00:00:00');
    return d.toLocaleDateString('en-US', {month:'short', day:'numeric'});
  }
  function fmtTime(totalSeconds){
    const m = Math.floor(totalSeconds/60);
    const s = Math.floor(totalSeconds%60);
    return m+':'+String(s).padStart(2,'0');
  }

  // ---------- Storage (browser localStorage — works on any website) ----------
  async function loadAll(){
    try{
      const p = localStorage.getItem('plank-sessions');
      plankSessions = p ? JSON.parse(p) : {};
    }catch(e){ plankSessions = {}; }

    try{
      const n = localStorage.getItem('nutrition-log');
      nutritionLog = n ? JSON.parse(n) : {};
    }catch(e){ nutritionLog = {}; }

    try{
      const b = localStorage.getItem('plank-best');
      bestPlank = b ? JSON.parse(b) : 0;
    }catch(e){ bestPlank = 0; }

    renderAll();
  }

  async function savePlank(){
    try{ localStorage.setItem('plank-sessions', JSON.stringify(plankSessions)); }catch(e){}
  }
  async function saveNutrition(){
    try{ localStorage.setItem('nutrition-log', JSON.stringify(nutritionLog)); }catch(e){}
  }
  async function saveBest(){
    try{ localStorage.setItem('plank-best', JSON.stringify(bestPlank)); }catch(e){}
  }

  // ---------- Render ----------
  function renderAll(){
    document.getElementById('todayDate').textContent = new Date().toLocaleDateString('en-US', {weekday:'short', month:'short', day:'numeric'});
    document.getElementById('bestTime').textContent = fmtTime(bestPlank);
    renderPlankLog();
    renderStreak();
    renderStats();
    renderHistory();
  }

  function renderPlankLog(){
    const key = todayKey();
    const sessions = plankSessions[key] || [];
    const container = document.getElementById('plankLog');
    if(sessions.length === 0){
      container.innerHTML = '<div class="plank-empty">No sessions logged yet today.</div>';
      return;
    }
    container.innerHTML = sessions.map((s,i)=>
      `<div class="plank-log-row"><span>Session ${i+1}</span><span>${fmtTime(s)}</span></div>`
    ).join('');
  }

  function renderStreak(){
    // count consecutive days (including today if logged) with at least one plank session
    const keys = Object.keys(plankSessions).filter(k => plankSessions[k] && plankSessions[k].length>0);
    const keySet = new Set(keys);
    let streak = 0;
    let cursor = new Date();
    // if today has no session yet, start counting from yesterday
    if(!keySet.has(todayKey())){
      cursor.setDate(cursor.getDate()-1);
    }
    while(true){
      const k = cursor.getFullYear()+'-'+String(cursor.getMonth()+1).padStart(2,'0')+'-'+String(cursor.getDate()).padStart(2,'0');
      if(keySet.has(k)){
        streak++;
        cursor.setDate(cursor.getDate()-1);
      } else break;
    }
    document.getElementById('streakDays').textContent = streak + (streak===1 ? ' day' : ' days');
  }

  function renderStats(){
    const dates = Object.keys(nutritionLog).sort();
    const todayEntry = nutritionLog[todayKey()];

    if(dates.length === 0){
      document.getElementById('currentWeight').textContent = '—';
      document.getElementById('weightTrend').textContent = 'No data yet';
    } else {
      const lastKey = dates[dates.length-1];
      const last = nutritionLog[lastKey];
      document.getElementById('currentWeight').textContent = last.weight + ' kg';
      if(dates.length > 1){
        const prev = nutritionLog[dates[dates.length-2]];
        const diff = (last.weight - prev.weight).toFixed(1);
        const arrow = diff > 0 ? '↑' : diff < 0 ? '↓' : '→';
        document.getElementById('weightTrend').textContent = `${arrow} ${Math.abs(diff)} kg vs last entry`;
      } else {
        document.getElementById('weightTrend').textContent = 'First entry logged';
      }
    }

    if(todayEntry){
      document.getElementById('todayCalories').textContent = todayEntry.calories;
      document.getElementById('calorieSub').textContent = 'Logged today';
    } else {
      document.getElementById('todayCalories').textContent = '—';
      document.getElementById('calorieSub').textContent = 'No entry today';
    }
  }

  function renderHistory(){
    const dates = Object.keys(nutritionLog).sort().reverse();
    const container = document.getElementById('historyList');
    if(dates.length === 0){
      container.innerHTML = '<div class="empty-state">No entries yet — log your first day above.</div>';
      return;
    }
    container.innerHTML = dates.slice(0,14).map(k => {
      const e = nutritionLog[k];
      return `<div class="history-row">
        <span class="history-date">${fmtDateLabel(k)}</span>
        <div class="history-vals">
          <span class="w">${e.weight} kg</span>
          <span class="c">${e.calories} kcal</span>
        </div>
        <button class="del-btn" data-key="${k}" title="Delete entry">✕</button>
      </div>`;
    }).join('');

    container.querySelectorAll('.del-btn').forEach(btn=>{
      btn.addEventListener('click', async (e)=>{
        const k = e.target.getAttribute('data-key');
        delete nutritionLog[k];
        await saveNutrition();
        renderAll();
      });
    });
  }

  // ---------- Timer ----------
  const timerDisplay = document.getElementById('timerDisplay');
  const timerSub = document.getElementById('timerSub');
  const startBtn = document.getElementById('startBtn');
  const stopBtn = document.getElementById('stopBtn');
  const resetBtn = document.getElementById('resetBtn');
  let startTimestamp = 0;

  function tick(){
    const now = Date.now();
    const total = elapsedMs + (now - startTimestamp);
    timerDisplay.textContent = fmtTime(total/1000);
  }

  startBtn.addEventListener('click', ()=>{
    timerRunning = true;
    startTimestamp = Date.now();
    timerInterval = setInterval(tick, 200);
    startBtn.disabled = true;
    stopBtn.disabled = false;
    timerSub.textContent = 'Hold steady...';
  });

  stopBtn.addEventListener('click', async ()=>{
    if(!timerRunning) return;
    clearInterval(timerInterval);
    const now = Date.now();
    elapsedMs += (now - startTimestamp);
    const seconds = elapsedMs/1000;
    timerRunning = false;
    startBtn.disabled = false;
    stopBtn.disabled = true;

    const key = todayKey();
    if(!plankSessions[key]) plankSessions[key] = [];
    plankSessions[key].push(seconds);
    if(seconds > bestPlank){
      bestPlank = seconds;
      timerSub.textContent = 'New personal best! 🔥';
      await saveBest();
    } else {
      timerSub.textContent = 'Session logged';
    }
    await savePlank();
    elapsedMs = 0;
    timerDisplay.textContent = '0:00';
    renderAll();
  });

  resetBtn.addEventListener('click', ()=>{
    clearInterval(timerInterval);
    timerRunning = false;
    elapsedMs = 0;
    startBtn.disabled = false;
    stopBtn.disabled = true;
    timerDisplay.textContent = '0:00';
    timerSub.textContent = "Press start when you're set";
  });

  // ---------- Nutrition logging ----------
  document.getElementById('logBtn').addEventListener('click', async ()=>{
    const w = parseFloat(document.getElementById('weightInput').value);
    const c = parseInt(document.getElementById('calorieInput').value);
    if(!w && !c){
      return;
    }
    const key = todayKey();
    const existing = nutritionLog[key] || {};
    nutritionLog[key] = {
      weight: w || existing.weight || null,
      calories: c || existing.calories || null
    };
    await saveNutrition();
    document.getElementById('weightInput').value = '';
    document.getElementById('calorieInput').value = '';
    renderAll();
  });

  loadAll();
})();
</script>
</body>
</html>
