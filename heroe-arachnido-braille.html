<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1">
<title>El Héroe Arácnido · Abecedario en Braille</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Baloo+2:wght@600;700;800&family=Nunito:wght@600;700;800;900&display=swap" rel="stylesheet">
<style>
  :root{
    --bg:#0d0b1a;
    --ink:#ffffff;
    --ink-soft:#e7e2ff;
    --card:#1a1730;
    --accent:#ffd60a;
    --accent-dark:#e0b400;
    --purple:#7b3ff2;
    --success:#4ee08a;
    --success-bg:#0f2e1c;
    --error:#ff6b5e;
    --error-bg:#3a1410;
    --border:#4a4470;
    --focus-ring:#ffffff;
    --radius-lg:24px;
    --radius-md:16px;
    --scale:1.1;
    font-size: calc(20px * var(--scale));
  }
  body.soft{
    --bg:#f7f5ff;
    --ink:#1a1730;
    --ink-soft:#403a5c;
    --card:#ffffff;
    --accent:#7b3ff2;
    --accent-dark:#5c26c9;
    --border:#d8d2f0;
    --success:#1c7a3e;
    --success-bg:#e3f6e8;
    --error:#a3311a;
    --error-bg:#fdeae5;
    --focus-ring:#7b3ff2;
  }

  *{ box-sizing:border-box; }
  html,body{
    margin:0; padding:0; min-height:100%;
    background: var(--bg);
    color: var(--ink);
    font-family:'Nunito', sans-serif;
    transition: background .2s ease, color .2s ease;
  }
  h1,h2,h3,.display{ font-family:'Baloo 2', sans-serif; margin:0; }

  .sr-only{
    position:absolute; width:1px; height:1px; padding:0; margin:-1px;
    overflow:hidden; clip:rect(0,0,0,0); white-space:nowrap; border:0;
  }

  button{ cursor:pointer; font-family:'Nunito', sans-serif; }
  a:focus, button:focus, [tabindex]:focus{
    outline: 5px solid var(--focus-ring);
    outline-offset: 3px;
  }

  #app{
    max-width: 760px;
    margin: 0 auto;
    padding: 18px 16px 60px;
    display:flex;
    flex-direction:column;
    gap:18px;
  }
  .hidden{ display:none !important; }

  /* ---------- barra de accesibilidad ---------- */
  .toolbar{
    display:flex; flex-wrap:wrap; gap:10px;
    justify-content:space-between; align-items:center;
    border-bottom: 2px solid var(--border);
    padding-bottom: 12px;
  }
  .toolbar-group{ display:flex; gap:8px; flex-wrap:wrap; }
  .tool-btn{
    background: var(--card);
    border: 2.5px solid var(--border);
    color: var(--ink);
    border-radius: 999px;
    padding: 10px 16px;
    font-weight:800;
    font-size: 0.95rem;
  }
  .tool-btn[aria-pressed="true"]{
    background: var(--accent); color: var(--bg); border-color: var(--accent);
  }

  header.title-block{ text-align:center; }
  .display.title{ font-size: 2.1rem; color: var(--accent); }
  .subtitle{ font-weight:800; color: var(--ink-soft); margin-top:4px; font-size:1.1rem; }
  .hero-emoji{ font-size: 4.4rem; text-align:center; margin: 2px 0; }

  .card{
    background: var(--card);
    border: 2.5px solid var(--border);
    border-radius: var(--radius-lg);
    padding: 22px 20px;
  }
  .instructions p{ line-height:1.6; font-weight:700; color: var(--ink-soft); margin:0 0 10px; }
  .instructions p:last-child{ margin-bottom:0; }

  .btn{
    font-family:'Baloo 2', sans-serif;
    font-weight:700; font-size: 1.25rem; color:#1a1730;
    background: var(--accent);
    padding: 16px 30px;
    border-radius: 999px;
    border: 3px solid var(--accent-dark);
  }
  .btn:active{ transform: translateY(2px); }
  .btn.secondary{
    background: var(--card); color: var(--accent);
    border: 3px solid var(--accent);
  }
  .btn-row{ display:flex; gap:12px; flex-wrap:wrap; justify-content:center; }

  .status-row{
    display:flex; justify-content:space-between; flex-wrap:wrap; gap:10px; font-weight:800;
  }
  .status-chip{
    background: var(--card); border: 2.5px solid var(--border);
    border-radius: 999px; padding: 8px 16px; font-size:0.95rem;
  }

  /* ---------- escena: héroe y edificios ---------- */
  .scene{
    background: linear-gradient(180deg, var(--purple) 0%, #2a1f55 60%, #1a1730 100%);
    border-radius: var(--radius-lg);
    padding: 18px 14px 10px;
    position:relative;
    overflow:hidden;
  }
  body.soft .scene{ background: linear-gradient(180deg, #c9b6ff 0%, #a78bf5 100%); }
  .buildings-row{
    display:flex; gap:6px; align-items:flex-end;
    min-height: 70px;
    position:relative;
  }
  .building{
    flex:1;
    background: #352a63;
    border: 2px solid #4a3d80;
    border-radius: 6px 6px 0 0;
    height: 46px;
    display:flex; align-items:flex-start; justify-content:center;
    padding-top:4px;
    font-size: 0.9rem;
  }
  .building.done{ background: var(--accent); border-color: var(--accent-dark); }
  body.soft .building{ background:#e3d9ff; border-color:#b9a3f0; }
  body.soft .building.done{ background: var(--accent); border-color: var(--accent-dark); }
  .hero-pos{
    position:absolute;
    top: -34px;
    font-size: 2rem;
    transform: translateX(-50%);
    transition: left .5s cubic-bezier(.34,1.56,.64,1);
  }
  .web-line{
    position:absolute; top:-6px; height:34px; width:2px;
    background: rgba(255,255,255,0.35);
    transform: translateX(-50%);
    transition: left .5s ease;
  }

  /* ---------- pregunta ---------- */
  .prompt{
    font-family:'Baloo 2', sans-serif;
    font-size: 1.35rem;
    text-align:center;
    margin: 14px 0 16px;
    line-height:1.4;
  }
  .big-letter{
    font-family:'Baloo 2', sans-serif;
    font-size: 4.5rem;
    text-align:center;
    color: var(--accent);
    margin-bottom: 10px;
  }

  /* diagrama de puntos (grande, para mostrar) */
  .cell-diagram{
    display:grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr;
    gap: 8px;
    width: 120px;
    margin: 0 auto 8px;
  }
  .cell-diagram .d{
    width: 100%; aspect-ratio:1;
    border-radius:50%;
    border: 3px solid var(--ink-soft);
    background: transparent;
  }
  .cell-diagram .d.on{ background: var(--accent); border-color: var(--accent-dark); }

  .caption{
    text-align:center;
    font-weight:800;
    color: var(--ink-soft);
    font-size: 1rem;
    margin-bottom: 6px;
  }

  /* ---------- opciones de respuesta ---------- */
  .answers{
    display:grid;
    grid-template-columns: 1fr 1fr;
    gap: 14px;
    margin-top: 10px;
  }
  .ans-btn{
    background: var(--bg);
    border: 3px solid var(--border);
    border-radius: var(--radius-md);
    padding: 16px 10px;
    min-height: 110px;
    display:flex; flex-direction:column; align-items:center; justify-content:center;
    gap: 6px;
  }
  .ans-btn .letter-opt{
    font-family:'Baloo 2', sans-serif;
    font-size: 2.6rem;
    color: var(--ink);
  }
  .ans-btn .mini-diagram{
    display:grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr;
    gap: 4px;
    width: 54px;
  }
  .ans-btn .mini-diagram .d{
    width:100%; aspect-ratio:1; border-radius:50%;
    border: 2.5px solid var(--ink-soft);
    background: transparent;
  }
  .ans-btn .mini-diagram .d.on{ background: var(--accent); border-color: var(--accent-dark); }
  .ans-btn .mini-caption{ font-size:0.85rem; font-weight:800; color: var(--ink-soft); }

  .ans-btn.correct{ background: var(--success-bg); border-color: var(--success); }
  .ans-btn.incorrect{ background: var(--error-bg); border-color: var(--error); }
  .ans-btn:disabled{ pointer-events:none; }

  .feedback-text{
    text-align:center; font-weight:900; font-size: 1.15rem;
    min-height: 30px; margin-top: 14px;
  }
  .feedback-text.good{ color: var(--success); }
  .feedback-text.bad{ color: var(--error); }

  /* ---------- explorador del abecedario ---------- */
  .explorer-nav{
    display:flex; justify-content:center; align-items:center; gap:18px; margin-top: 14px;
  }
  .explorer-nav .btn{ min-width: 120px; }
  .letter-index{ font-weight:800; color: var(--ink-soft); text-align:center; }

  /* ---------- resultado ---------- */
  .result-card{ text-align:center; }
  .result-title{ font-size:1.7rem; color: var(--accent); margin-bottom:8px; }
  .result-stats{ display:flex; gap:12px; justify-content:center; flex-wrap:wrap; margin: 16px 0; }
  .stat-chip{ background: var(--card); border:2.5px solid var(--border); border-radius: 14px; padding: 10px 16px; font-weight:900; }
  .new-achv-box{
    margin-top:12px; background: var(--card); border: 2.5px solid var(--accent);
    border-radius: var(--radius-md); padding: 12px; font-weight:800; color: var(--accent);
  }

  .achv-list{ display:flex; flex-direction:column; gap:10px; }
  .achv-item{
    display:flex; gap:12px; align-items:flex-start;
    background: var(--bg); border: 2.5px solid var(--border);
    border-radius: var(--radius-md); padding: 12px 14px; text-align:left;
  }
  .achv-item.locked{ opacity:0.5; }
  .achv-item .a-icon{ font-size:1.6rem; }
  .achv-item .a-name{ font-weight:900; }
  .achv-item .a-desc{ font-weight:700; color: var(--ink-soft); font-size:0.9rem; }

  footer.credit{ text-align:center; font-weight:700; color: var(--ink-soft); font-size:0.85rem; margin-top:10px; }

  @media (max-width:480px){
    .display.title{ font-size:1.7rem; }
    .big-letter{ font-size:3.4rem; }
    .ans-btn{ min-height:96px; }
  }
  @media (prefers-reduced-motion: reduce){
    *{ animation-duration:0.001ms !important; transition-duration:0.001ms !important; }
  }
</style>
</head>
<body>

<div id="live-announcer" class="sr-only" role="status" aria-live="assertive"></div>

<div id="app">

  <div class="toolbar">
    <div class="toolbar-group" role="group" aria-label="Controles de accesibilidad">
      <button class="tool-btn" id="btn-voice" aria-pressed="true">🔊 Voz: activada</button>
      <button class="tool-btn" id="btn-theme" aria-pressed="false">◐ Modo claro</button>
    </div>
    <div class="toolbar-group" role="group" aria-label="Tamaño de texto">
      <button class="tool-btn" id="btn-font-minus" aria-label="Reducir tamaño de texto">A−</button>
      <button class="tool-btn" id="btn-font-plus" aria-label="Aumentar tamaño de texto">A+</button>
    </div>
  </div>

  <header class="title-block">
    <div class="hero-emoji" aria-hidden="true">🕷️🕸️</div>
    <h1 class="display title">El Héroe Arácnido</h1>
    <p class="subtitle">Aprende el abecedario en braille</p>
  </header>

  <!-- ===================== INICIO ===================== -->
  <main id="screen-start">
    <div class="card instructions">
      <h2>¿Cómo se juega?</h2>
      <p>Un héroe arácnido se balancea de edificio en edificio con su telaraña. Cada letra que aciertes lo ayuda a avanzar por la ciudad.</p>
      <p>Cada letra del abecedario tiene su propio dibujo de puntos en el cajetín braille. A veces te mostraremos la letra y vos elegís el dibujo correcto; otras veces te mostraremos el dibujo y vos elegís la letra correcta.</p>
      <p>Primero podés explorar el abecedario completo, letra por letra, con calma. Después, el desafío te va a preguntar de a poco, empezando por las primeras letras.</p>
    </div>

    <div class="btn-row" style="margin-top:16px;">
      <button class="btn secondary" id="btn-open-explorer">🔎 Explorar el abecedario</button>
    </div>

    <div class="btn-row" style="margin-top:20px;">
      <button class="btn" id="btn-play">🕸️ Comenzar desafío</button>
    </div>

    <div class="btn-row" style="margin-top:6px;">
      <button class="btn secondary" id="btn-open-achv-start">🏆 Ver logros</button>
      <button class="btn secondary" id="btn-full-reset">↺ Reiniciar todo</button>
    </div>

    <p class="status-chip" id="start-round-badge" style="display:block; text-align:center; margin:16px auto 0; width:fit-content;">Bloque 1 de 5: letras A-E</p>

    <footer class="credit">Juego del abecedario en braille · adaptado para baja visión (texto grande, alto contraste y voz)</footer>
  </main>

  <!-- ===================== EXPLORADOR DEL ABECEDARIO ===================== -->
  <main id="screen-explorer" class="hidden">
    <div class="card">
      <h2 class="sr-only">Explorador del abecedario</h2>
      <p class="letter-index" id="explorer-index">Letra 1 de 26</p>
      <div class="big-letter" id="explorer-letter">A</div>
      <div class="cell-diagram" id="explorer-diagram" aria-hidden="true"></div>
      <p class="caption" id="explorer-caption">Puntos: 1</p>
      <div class="explorer-nav">
        <button class="btn secondary" id="btn-explorer-prev">◀ Anterior</button>
        <button class="btn secondary" id="btn-explorer-next">Siguiente ▶</button>
      </div>
    </div>
    <div class="btn-row" style="margin-top:16px;">
      <button class="btn" id="btn-explorer-back">🏠 Volver al menú</button>
    </div>
  </main>

  <!-- ===================== JUEGO ===================== -->
  <main id="screen-game" class="hidden">
    <div class="status-row">
      <span class="status-chip" id="lives-chip">Vidas: 3 de 5</span>
      <span class="status-chip" id="stars-chip">Telarañas: 0</span>
      <span class="status-chip" id="progress-chip">Letra 1 de 10</span>
      <button class="tool-btn" id="btn-open-achv-game">🏆 Logros</button>
    </div>

    <div class="scene" style="margin-top:14px;">
      <div class="buildings-row" id="buildings-row"></div>
    </div>

    <section class="card" style="margin-top:16px;">
      <p class="prompt" id="q-prompt">¿Qué letra es este cajetín?</p>
      <div id="q-visual"></div>
      <div class="answers" id="answers-row"></div>
      <p class="feedback-text" id="feedback"></p>
    </section>
  </main>

  <!-- ===================== BLOQUE COMPLETADO ===================== -->
  <main id="screen-win" class="hidden">
    <div class="card result-card">
      <h2 class="result-title">🕸️ ¡El héroe llegó al final!</h2>
      <p class="instructions" style="font-weight:700; color:var(--ink-soft);">Reconociste esas letras en braille. ¡Excelente trabajo!</p>
      <div class="result-stats">
        <span class="stat-chip" id="win-stars">Telarañas: 0</span>
        <span class="stat-chip" id="win-round">Bloque completado</span>
      </div>
      <div class="new-achv-box hidden" id="win-new-achv"></div>
    </div>
    <div class="btn-row" style="margin-top:16px;">
      <button class="btn" id="btn-next-round">Siguiente bloque ▶</button>
      <button class="btn secondary" id="btn-win-menu">🏠 Menú principal</button>
    </div>
  </main>

  <!-- ===================== INTENTAR DE NUEVO ===================== -->
  <main id="screen-lose" class="hidden">
    <div class="card result-card">
      <h2 class="result-title">🕷️ Sigue practicando</h2>
      <p class="instructions" style="font-weight:700; color:var(--ink-soft);">Vamos a intentarlo otra vez. ¡Cada intento ayuda a recordar mejor las letras!</p>
      <div class="result-stats">
        <span class="stat-chip" id="lose-progress">Llegaste a la letra 1</span>
      </div>
    </div>
    <div class="btn-row" style="margin-top:16px;">
      <button class="btn" id="btn-retry">🔁 Intentar de nuevo</button>
      <button class="btn secondary" id="btn-lose-menu">🏠 Menú principal</button>
    </div>
  </main>

</div>

<!-- ===================== LOGROS ===================== -->
<div id="achv-overlay" class="hidden" role="dialog" aria-modal="true" aria-labelledby="achv-title" style="position:fixed; inset:0; background:rgba(0,0,0,0.6); display:flex; align-items:center; justify-content:center; padding:18px; z-index:50;">
  <div class="card" style="max-width:460px; width:100%; max-height:80vh; overflow-y:auto;">
    <div style="display:flex; justify-content:space-between; align-items:center; margin-bottom:14px;">
      <h2 id="achv-title">🏆 Logros</h2>
      <button class="tool-btn" id="btn-close-achv">✕ Cerrar</button>
    </div>
    <div class="achv-list" id="achv-list"></div>
  </div>
</div>

<script>
(function(){
  "use strict";

  /* ---------------- Mapa del abecedario en braille (grado 1) ---------------- */
  var BRAILLE_MAP = {
    a:[1], b:[1,2], c:[1,4], d:[1,4,5], e:[1,5],
    f:[1,2,4], g:[1,2,4,5], h:[1,2,5], i:[2,4], j:[2,4,5],
    k:[1,3], l:[1,2,3], m:[1,3,4], n:[1,3,4,5], o:[1,3,5],
    p:[1,2,3,4], q:[1,2,3,4,5], r:[1,2,3,5], s:[2,3,4], t:[2,3,4,5],
    u:[1,3,6], v:[1,2,3,6], w:[2,4,5,6], x:[1,3,4,6], y:[1,3,4,5,6], z:[1,3,5,6]
  };
  var ALPHABET = Object.keys(BRAILLE_MAP);
  var BLOCKS = [
    ['a','b','c','d','e'],
    ['f','g','h','i','j'],
    ['k','l','m','n','o'],
    ['p','q','r','s','t'],
    ['u','v','w','x','y','z']
  ];
  var DOT_ORDER = [1,4,2,5,3,6];

  function dotsCaption(pattern){
    var sorted = pattern.slice().sort(function(a,b){return a-b;});
    return 'Puntos: ' + sorted.join(', ');
  }
  function letterDesc(letter){
    return 'Letra ' + letter.toUpperCase() + '. ' + dotsCaption(BRAILLE_MAP[letter]) + '.';
  }

  var ACHIEVEMENTS = {
    firstStep:  { icon:'🥇', name:'Primera letra',       desc:'Acierta tu primera letra en braille.' },
    streak3:    { icon:'🔥', name:'Racha de 3',           desc:'Acierta 3 letras seguidas.' },
    blockDone:  { icon:'🏙️', name:'Cruzó la cuadra',      desc:'Completa un bloque de letras.' },
    noErrors:   { icon:'✨', name:'Sin errores',           desc:'Completa un bloque sin perder ninguna vida.' },
    extraLife:  { icon:'💖', name:'Telaraña extra',        desc:'Consigue una vida bonus.' },
    explorer:   { icon:'🔎', name:'Explorador de la ciudad', desc:'Recorre el abecedario completo en el explorador.' },
    alphabetDone:{ icon:'👑', name:'Abecedario completo',  desc:'Completa los 5 bloques de letras.' }
  };

  var state = {
    roundIndex: 0,
    roundsCompleted: 0,
    phase: 'learn', // 'learn' o 'review'
    questions: [],
    qIndex: 0,
    lives: 3,
    maxLives: 5,
    streak: 0,
    stars: 0,
    roundHadError: false,
    unlocked: {},
    voiceOn: true,
    lightTheme: false,
    explorerIdx: 0,
    explorerVisited: {}
  };

  var $ = function(id){ return document.getElementById(id); };

  /* ---------------- Voz ---------------- */
  var announcer = $('live-announcer');
  var speechSupported = ('speechSynthesis' in window);
  function speak(text){
    announcer.textContent = '';
    window.setTimeout(function(){ announcer.textContent = text; }, 30);
    if(state.voiceOn && speechSupported){
      try{
        window.speechSynthesis.cancel();
        var u = new SpeechSynthesisUtterance(text);
        u.lang = 'es-ES';
        u.rate = 0.95;
        window.speechSynthesis.speak(u);
      }catch(e){}
    }
  }

  /* ---------------- Sonidos ---------------- */
  var AudioCtx = window.AudioContext || window.webkitAudioContext;
  var actx = null;
  function tone(freqs, dur){
    if(!AudioCtx) return;
    if(!actx) actx = new AudioCtx();
    var t = actx.currentTime;
    freqs.forEach(function(f, i){
      var osc = actx.createOscillator();
      var gain = actx.createGain();
      osc.type = 'sine';
      osc.frequency.value = f;
      gain.gain.setValueAtTime(0.0001, t);
      gain.gain.exponentialRampToValueAtTime(0.15, t + 0.02 + i*dur);
      gain.gain.exponentialRampToValueAtTime(0.0001, t + dur + i*dur);
      osc.connect(gain).connect(actx.destination);
      osc.start(t + i*dur);
      osc.stop(t + i*dur + dur + 0.05);
    });
  }
  function soundCorrect(){ tone([523.25, 659.25], 0.14); }
  function soundIncorrect(){ tone([220], 0.28); }
  function soundBonus(){ tone([659.25, 783.99, 987.77], 0.12); }

  /* ---------------- Utilidades ---------------- */
  function shuffle(arr){
    var a = arr.slice();
    for(var i=a.length-1;i>0;i--){
      var j = Math.floor(Math.random()*(i+1));
      var tmp=a[i]; a[i]=a[j]; a[j]=tmp;
    }
    return a;
  }
  function unlock(key){
    if(!state.unlocked[key]){ state.unlocked[key] = true; return true; }
    return false;
  }

  /* ---------------- Render de diagramas de puntos ---------------- */
  function renderDiagram(container, pattern, sizeClass){
    container.innerHTML = '';
    container.className = sizeClass || 'cell-diagram';
    DOT_ORDER.forEach(function(n){
      var d = document.createElement('div');
      d.className = 'd' + (pattern.indexOf(n) !== -1 ? ' on' : '');
      container.appendChild(d);
    });
  }

  /* ---------------- Controles de accesibilidad ---------------- */
  $('btn-voice').addEventListener('click', function(){
    state.voiceOn = !state.voiceOn;
    this.setAttribute('aria-pressed', String(state.voiceOn));
    this.textContent = state.voiceOn ? '🔊 Voz: activada' : '🔇 Voz: desactivada';
    if(!state.voiceOn && speechSupported){ window.speechSynthesis.cancel(); }
  });
  $('btn-theme').addEventListener('click', function(){
    state.lightTheme = !state.lightTheme;
    document.body.classList.toggle('soft', state.lightTheme);
    this.setAttribute('aria-pressed', String(state.lightTheme));
    this.textContent = state.lightTheme ? '◑ Modo oscuro' : '◐ Modo claro';
  });
  var fontScale = 1.1;
  function applyFontScale(){ document.documentElement.style.setProperty('--scale', fontScale.toFixed(2)); }
  $('btn-font-plus').addEventListener('click', function(){
    fontScale = Math.min(1.7, fontScale + 0.1); applyFontScale();
  });
  $('btn-font-minus').addEventListener('click', function(){
    fontScale = Math.max(0.9, fontScale - 0.1); applyFontScale();
  });

  /* ---------------- Pantallas ---------------- */
  var screens = {
    start: $('screen-start'),
    explorer: $('screen-explorer'),
    game: $('screen-game'),
    win: $('screen-win'),
    lose: $('screen-lose')
  };
  function showScreen(name){
    Object.keys(screens).forEach(function(k){ screens[k].classList.add('hidden'); });
    screens[name].classList.remove('hidden');
    screens[name].setAttribute('tabindex','-1');
    screens[name].focus();
  }

  /* ---------------- Explorador del abecedario ---------------- */
  function renderExplorer(){
    var letter = ALPHABET[state.explorerIdx];
    state.explorerVisited[letter] = true;
    $('explorer-index').textContent = 'Letra ' + (state.explorerIdx+1) + ' de ' + ALPHABET.length;
    $('explorer-letter').textContent = letter.toUpperCase();
    renderDiagram($('explorer-diagram'), BRAILLE_MAP[letter], 'cell-diagram');
    $('explorer-caption').textContent = dotsCaption(BRAILLE_MAP[letter]);
    speak(letterDesc(letter));

    if(Object.keys(state.explorerVisited).length >= ALPHABET.length){
      unlock('explorer');
    }
  }
  $('btn-open-explorer').addEventListener('click', function(){
    state.explorerIdx = 0;
    showScreen('explorer');
    renderExplorer();
  });
  $('btn-explorer-next').addEventListener('click', function(){
    state.explorerIdx = (state.explorerIdx + 1) % ALPHABET.length;
    renderExplorer();
  });
  $('btn-explorer-prev').addEventListener('click', function(){
    state.explorerIdx = (state.explorerIdx - 1 + ALPHABET.length) % ALPHABET.length;
    renderExplorer();
  });
  $('btn-explorer-back').addEventListener('click', function(){ showScreen('start'); });

  /* ---------------- Logros ---------------- */
  function renderAchvList(){
    var list = $('achv-list');
    list.innerHTML = '';
    Object.keys(ACHIEVEMENTS).forEach(function(key){
      var a = ACHIEVEMENTS[key];
      var got = !!state.unlocked[key];
      var div = document.createElement('div');
      div.className = 'achv-item' + (got ? '' : ' locked');
      div.innerHTML = '<span class="a-icon" aria-hidden="true">' + (got ? a.icon : '🔒') + '</span>' +
        '<div><div class="a-name">' + a.name + (got ? '' : ' (bloqueado)') + '</div><div class="a-desc">' + a.desc + '</div></div>';
      list.appendChild(div);
    });
  }
  function openAchv(){
    renderAchvList();
    $('achv-overlay').classList.remove('hidden');
    $('btn-close-achv').focus();
    speak('Panel de logros abierto.');
  }
  function closeAchv(){
    $('achv-overlay').classList.add('hidden');
    speak('Panel de logros cerrado.');
  }
  $('btn-open-achv-start').addEventListener('click', openAchv);
  $('btn-open-achv-game').addEventListener('click', openAchv);
  $('btn-close-achv').addEventListener('click', closeAchv);
  document.addEventListener('keydown', function(e){
    if(e.key === 'Escape' && !$('achv-overlay').classList.contains('hidden')){ closeAchv(); }
  });

  /* ---------------- Estado visual ---------------- */
  function renderStatus(){
    $('lives-chip').textContent = 'Vidas: ' + state.lives + ' de ' + state.maxLives;
    $('stars-chip').textContent = 'Telarañas: ' + state.stars;
    $('progress-chip').textContent = 'Letra ' + (state.qIndex+1) + ' de ' + state.questions.length;
  }

  function renderBuildings(){
    var row = $('buildings-row');
    row.innerHTML = '';
    var total = state.questions.length;
    for(var i=0;i<total;i++){
      var b = document.createElement('div');
      b.className = 'building' + (i < state.qIndex ? ' done' : '');
      row.appendChild(b);
    }
    var hero = document.createElement('div');
    hero.className = 'hero-pos';
    hero.textContent = '🕷️';
    hero.style.left = (((state.qIndex + 0.5) / total) * 100) + '%';
    row.appendChild(hero);
  }

  /* ---------------- Construcción de preguntas ---------------- */
  function buildRoundQuestions(){
    var letters;
    if(state.roundsCompleted < 5){
      letters = BLOCKS[state.roundIndex % 5];
    } else {
      state.phase = 'review';
      letters = shuffle(ALPHABET).slice(0, 8);
    }
    var pool = shuffle(letters.concat(letters));
    for(var i=1;i<pool.length;i++){
      if(pool[i] === pool[i-1]){
        var swapWith = i+1 < pool.length ? i+1 : i-2;
        var tmp = pool[i]; pool[i] = pool[swapWith]; pool[swapWith] = tmp;
      }
    }
    return pool.map(function(letter){
      return { letter: letter, type: Math.random() < 0.5 ? 'toLetter' : 'toDiagram' };
    });
  }

  function currentBlockLabel(){
    if(state.roundsCompleted < 5){
      var b = BLOCKS[state.roundIndex % 5];
      return 'Bloque ' + ((state.roundIndex % 5) + 1) + ' de 5: letras ' + b[0].toUpperCase() + '-' + b[b.length-1].toUpperCase();
    }
    return 'Repaso general';
  }

  function startRound(){
    state.questions = buildRoundQuestions();
    state.qIndex = 0;
    state.lives = 3;
    state.streak = 0;
    state.roundHadError = false;

    $('start-round-badge').textContent = currentBlockLabel();

    showScreen('game');
    renderStatus();
    renderBuildings();
    showQuestion();
  }

  var firstCorrectEver = false;

  function showQuestion(){
    var q = state.questions[state.qIndex];
    renderStatus();
    renderBuildings();
    $('feedback').textContent = '';
    $('feedback').className = 'feedback-text';

    var visual = $('q-visual');
    visual.innerHTML = '';
    var ansRow = $('answers-row');
    ansRow.innerHTML = '';

    var distractPool = shuffle(ALPHABET.filter(function(l){ return l !== q.letter; })).slice(0,3);
    var options = shuffle(distractPool.concat([q.letter]));

    if(q.type === 'toDiagram'){
      // Se muestra la letra grande, hay que elegir el diagrama correcto
      var promptText = '¿Cuál cajetín es la letra ' + q.letter.toUpperCase() + '?';
      $('q-prompt').textContent = promptText;
      speak(promptText);

      var big = document.createElement('div');
      big.className = 'big-letter';
      big.textContent = q.letter.toUpperCase();
      visual.appendChild(big);

      options.forEach(function(letter){
        var b = document.createElement('button');
        b.className = 'ans-btn';
        b.setAttribute('aria-label', 'Opción: ' + dotsCaption(BRAILLE_MAP[letter]));
        var mini = document.createElement('div');
        renderDiagram(mini, BRAILLE_MAP[letter], 'mini-diagram');
        b.appendChild(mini);
        var cap = document.createElement('span');
        cap.className = 'mini-caption';
        cap.textContent = dotsCaption(BRAILLE_MAP[letter]);
        b.appendChild(cap);
        b.addEventListener('click', function(){ handleAnswer(b, letter, q.letter); });
        ansRow.appendChild(b);
      });

    } else {
      // Se muestra el diagrama, hay que elegir la letra correcta
      var promptText2 = '¿Qué letra es este cajetín?';
      $('q-prompt').textContent = promptText2;
      speak(promptText2 + ' ' + dotsCaption(BRAILLE_MAP[q.letter]));

      var diagWrap = document.createElement('div');
      renderDiagram(diagWrap, BRAILLE_MAP[q.letter], 'cell-diagram');
      visual.appendChild(diagWrap);
      var cap2 = document.createElement('p');
      cap2.className = 'caption';
      cap2.textContent = dotsCaption(BRAILLE_MAP[q.letter]);
      visual.appendChild(cap2);

      options.forEach(function(letter){
        var b = document.createElement('button');
        b.className = 'ans-btn';
        b.setAttribute('aria-label', 'Letra ' + letter.toUpperCase());
        var span = document.createElement('span');
        span.className = 'letter-opt';
        span.textContent = letter.toUpperCase();
        b.appendChild(span);
        b.addEventListener('click', function(){ handleAnswer(b, letter, q.letter); });
        ansRow.appendChild(b);
      });
    }
  }

  function handleAnswer(btnEl, chosen, correct){
    var allBtns = $('answers-row').querySelectorAll('.ans-btn');
    allBtns.forEach(function(b){ b.disabled = true; });
    var fb = $('feedback');

    if(chosen === correct){
      btnEl.classList.add('correct');
      fb.textContent = '¡Correcto! ' + letterDesc(correct);
      fb.className = 'feedback-text good';
      soundCorrect();

      state.stars++;
      state.streak++;
      if(!firstCorrectEver){ firstCorrectEver = true; unlock('firstStep'); }
      var bonusMsg = '';
      if(state.streak >= 3 && state.streak % 3 === 0){
        unlock('streak3');
        if(state.lives < state.maxLives){
          state.lives++;
          unlock('extraLife');
          soundBonus();
          bonusMsg = ' Telaraña extra conseguida.';
        }
      }
      speak('¡Correcto!' + bonusMsg);
      renderStatus();

      window.setTimeout(function(){
        state.qIndex++;
        if(state.qIndex >= state.questions.length){ roundComplete(); }
        else { showQuestion(); }
      }, 900);

    } else {
      btnEl.classList.add('incorrect');
      var correctBtn = null;
      allBtns.forEach(function(b){
        var label = b.getAttribute('aria-label') || '';
        if(label.indexOf(correct.toUpperCase()) !== -1 && (label.indexOf('Letra') === 0 || label.indexOf(dotsCaption(BRAILLE_MAP[correct])) !== -1)){
          correctBtn = b;
        }
      });
      if(correctBtn) correctBtn.classList.add('correct');

      state.streak = 0;
      state.lives--;
      state.roundHadError = true;
      renderStatus();
      soundIncorrect();

      var msg = 'No es esa. La correcta es: ' + letterDesc(correct);
      fb.textContent = msg;
      fb.className = 'feedback-text bad';
      speak(msg);

      window.setTimeout(function(){
        if(state.lives <= 0){ gameOver(); }
        else { showQuestion(); }
      }, 2400);
    }
  }

  function roundComplete(){
    state.roundsCompleted++;
    var newly = [];
    if(unlock('blockDone')) newly.push(ACHIEVEMENTS.blockDone);
    if(!state.roundHadError && unlock('noErrors')) newly.push(ACHIEVEMENTS.noErrors);
    if(state.roundsCompleted >= 5 && unlock('alphabetDone')) newly.push(ACHIEVEMENTS.alphabetDone);

    $('win-stars').textContent = 'Telarañas: ' + state.stars;
    $('win-round').textContent = currentBlockLabel() + ' completado';

    var box = $('win-new-achv');
    if(newly.length){
      box.classList.remove('hidden');
      var txt = 'Nuevo logro: ' + newly.map(function(a){ return a.name; }).join(', ');
      box.textContent = txt;
      speak('¡El héroe llegó al final! ' + txt);
    } else {
      box.classList.add('hidden');
      speak('¡El héroe llegó al final! Muy buen trabajo.');
    }
    showScreen('win');
  }

  function gameOver(){
    $('lose-progress').textContent = 'Llegaste a la letra ' + (state.qIndex+1) + ' de ' + state.questions.length;
    speak('Sigue practicando. Vamos a intentarlo de nuevo.');
    showScreen('lose');
  }

  /* ---------------- Navegación ---------------- */
  $('btn-play').addEventListener('click', startRound);

  $('btn-next-round').addEventListener('click', function(){
    if(state.roundsCompleted < 5){ state.roundIndex = (state.roundIndex + 1) % 5; }
    startRound();
  });

  $('btn-win-menu').addEventListener('click', function(){
    $('start-round-badge').textContent = currentBlockLabel();
    showScreen('start');
  });

  $('btn-retry').addEventListener('click', startRound);
  $('btn-lose-menu').addEventListener('click', function(){ showScreen('start'); });

  $('btn-full-reset').addEventListener('click', function(){
    state.roundIndex = 0;
    state.roundsCompleted = 0;
    state.phase = 'learn';
    state.stars = 0;
    state.unlocked = {};
    state.explorerVisited = {};
    $('start-round-badge').textContent = currentBlockLabel();
    speak('Todo el progreso fue reiniciado.');
    showScreen('start');
  });

})();
</script>
</body>
</html>
