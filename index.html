<!DOCTYPE html>
<html lang="it">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Portfolio Builder — Trade Republic 2026</title>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=DM+Mono:wght@300;400;500&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #07090f;
    --surface: #0e1018;
    --surface2: #161820;
    --border: #232535;
    --accent: #4fffb0;
    --accent2: #7c6fff;
    --accent3: #ff9f43;
    --text: #eef0fa;
    --muted: #5a5c7a;
    --danger: #ff5c5c;
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'DM Mono', monospace;
    min-height: 100vh;
    overflow-x: hidden;
  }
  body::before {
    content: '';
    position: fixed; inset: 0;
    background-image:
      linear-gradient(rgba(79,255,176,0.025) 1px, transparent 1px),
      linear-gradient(90deg, rgba(79,255,176,0.025) 1px, transparent 1px);
    background-size: 48px 48px;
    pointer-events: none; z-index: 0;
  }
  body::after {
    content: '';
    position: fixed;
    width: 600px; height: 600px;
    background: radial-gradient(circle, rgba(79,255,176,0.04) 0%, transparent 70%);
    top: -200px; right: -200px;
    pointer-events: none; z-index: 0;
  }
  .container {
    max-width: 780px;
    margin: 0 auto;
    padding: 48px 24px 100px;
    position: relative; z-index: 1;
  }
  .header {
    text-align: center;
    margin-bottom: 60px;
    animation: fadeDown 0.7s cubic-bezier(0.22,1,0.36,1) both;
  }
  .header .eyebrow {
    display: inline-flex; align-items: center; gap: 8px;
    background: rgba(79,255,176,0.07);
    border: 1px solid rgba(79,255,176,0.2);
    color: var(--accent);
    font-size: 10px; letter-spacing: 3px;
    text-transform: uppercase; padding: 7px 18px;
    border-radius: 2px; margin-bottom: 24px;
  }
  .header .eyebrow::before {
    content: ''; width: 6px; height: 6px;
    background: var(--accent); border-radius: 50%;
    animation: pulse 2s infinite;
  }
  .header h1 {
    font-family: 'Syne', sans-serif;
    font-size: clamp(36px, 7vw, 64px);
    font-weight: 800; line-height: 1.0;
    letter-spacing: -2px; margin-bottom: 16px;
  }
  .header h1 em { color: var(--accent); font-style: normal; }
  .header p { color: var(--muted); font-size: 13px; line-height: 1.8; max-width: 440px; margin: 0 auto; }

  .context-banner {
    background: linear-gradient(135deg, rgba(255,159,67,0.06), rgba(124,111,255,0.06));
    border: 1px solid rgba(255,159,67,0.2);
    border-radius: 4px; padding: 16px 20px;
    margin-bottom: 40px;
    display: flex; gap: 14px; align-items: flex-start;
    animation: fadeUp 0.7s 0.15s cubic-bezier(0.22,1,0.36,1) both;
  }
  .context-banner .icon { font-size: 18px; flex-shrink: 0; margin-top: 1px; }
  .context-banner p { font-size: 11px; color: #c8a06a; line-height: 1.7; }
  .context-banner strong { color: var(--accent3); }

  .progress-wrap {
    margin-bottom: 44px;
    animation: fadeUp 0.7s 0.2s cubic-bezier(0.22,1,0.36,1) both;
  }
  .progress-header { display: flex; justify-content: space-between; margin-bottom: 10px; }
  .progress-label { font-size: 10px; color: var(--muted); letter-spacing: 2.5px; text-transform: uppercase; }
  .progress-count { font-size: 10px; color: var(--accent); font-weight: 500; }
  .progress-bar { height: 2px; background: var(--border); border-radius: 2px; overflow: hidden; }
  .progress-fill {
    height: 100%;
    background: linear-gradient(90deg, var(--accent), var(--accent2));
    border-radius: 2px;
    transition: width 0.6s cubic-bezier(0.4,0,0.2,1);
    box-shadow: 0 0 12px rgba(79,255,176,0.4);
  }

  .section-label {
    font-size: 9px; letter-spacing: 3px; text-transform: uppercase;
    color: var(--accent2); margin-bottom: 14px;
    display: flex; align-items: center; gap: 10px;
  }
  .section-label::after { content: ''; flex: 1; height: 1px; background: var(--border); }

  .question-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 6px; padding: 32px 36px;
    margin-bottom: 16px;
    position: relative; overflow: hidden;
    transition: border-color 0.3s;
  }
  .question-card::before {
    content: ''; position: absolute;
    top: 0; left: 0; right: 0; height: 2px;
    background: linear-gradient(90deg, var(--accent), var(--accent2));
    opacity: 0; transition: opacity 0.4s;
  }
  .question-card.answered { border-color: rgba(79,255,176,0.2); }
  .question-card.answered::before { opacity: 1; }

  .q-meta { display: flex; align-items: center; justify-content: space-between; margin-bottom: 16px; }
  .q-number { font-size: 10px; color: var(--accent); letter-spacing: 2.5px; text-transform: uppercase; }
  .q-tag {
    font-size: 9px; letter-spacing: 1.5px; text-transform: uppercase;
    color: var(--muted); background: var(--surface2);
    border: 1px solid var(--border); padding: 3px 10px; border-radius: 2px;
  }
  .q-text {
    font-family: 'Syne', sans-serif;
    font-size: 16px; font-weight: 600; line-height: 1.45;
    margin-bottom: 22px; color: var(--text);
  }
  .q-hint { font-size: 10px; color: var(--accent3); margin-bottom: 14px; }

  .options { display: flex; flex-direction: column; gap: 8px; }
  .option {
    display: flex; align-items: flex-start; gap: 12px;
    padding: 12px 16px;
    background: var(--surface2); border: 1px solid var(--border);
    border-radius: 4px; cursor: pointer;
    transition: all 0.18s; text-align: left;
    width: 100%; font-family: 'DM Mono', monospace; color: var(--text);
  }
  .option:hover { border-color: rgba(79,255,176,0.35); background: rgba(79,255,176,0.04); transform: translateX(2px); }
  .option.selected { border-color: var(--accent); background: rgba(79,255,176,0.07); color: var(--accent); }
  .option-key {
    min-width: 20px; height: 20px;
    border: 1px solid currentColor; border-radius: 2px;
    display: flex; align-items: center; justify-content: center;
    font-size: 10px; font-weight: 600; opacity: 0.5; flex-shrink: 0; margin-top: 1px;
  }
  .option.selected .option-key { opacity: 1; }
  .option-text { font-size: 12px; line-height: 1.55; }

  .nav { display: flex; justify-content: space-between; align-items: center; margin-top: 28px; }
  .btn {
    padding: 13px 28px; border: none; border-radius: 3px;
    font-family: 'DM Mono', monospace; font-size: 11px;
    letter-spacing: 2px; text-transform: uppercase;
    cursor: pointer; transition: all 0.2s; font-weight: 500;
  }
  .btn-primary { background: var(--accent); color: #07090f; }
  .btn-primary:hover { background: #6fffbe; transform: translateY(-1px); box-shadow: 0 6px 24px rgba(79,255,176,0.3); }
  .btn-primary:disabled { opacity: 0.25; cursor: not-allowed; transform: none; box-shadow: none; }
  .btn-ghost { background: transparent; color: var(--muted); border: 1px solid var(--border); }
  .btn-ghost:hover { color: var(--text); border-color: var(--muted); }

  .error-msg {
    background: rgba(255,92,92,0.07); border: 1px solid rgba(255,92,92,0.25);
    color: var(--danger); padding: 10px 16px; border-radius: 3px;
    font-size: 11px; margin-top: 14px; display: none;
  }
  .error-msg.show { display: block; }

  .loading-screen { display: none; text-align: center; padding: 80px 24px; }
  .loading-screen.active { display: block; animation: fadeUp 0.5s ease both; }
  .loader-ring { width: 52px; height: 52px; margin: 0 auto 36px; position: relative; }
  .loader-ring::before, .loader-ring::after {
    content: ''; position: absolute; inset: 0; border-radius: 50%; border: 2px solid transparent;
  }
  .loader-ring::before { border-top-color: var(--accent); animation: spin 0.9s linear infinite; }
  .loader-ring::after { border-bottom-color: var(--accent2); animation: spin 1.4s linear infinite reverse; inset: 6px; }
  .loading-title { font-family: 'Syne', sans-serif; font-size: 24px; font-weight: 700; margin-bottom: 8px; }
  .loading-sub { color: var(--muted); font-size: 11px; letter-spacing: 1px; }
  .loading-steps { margin-top: 44px; display: flex; flex-direction: column; gap: 10px; max-width: 300px; margin-left: auto; margin-right: auto; }
  .loading-step { display: flex; align-items: center; gap: 12px; font-size: 11px; color: var(--muted); opacity: 0; transition: all 0.5s; transform: translateX(-8px); }
  .loading-step.show { opacity: 1; color: var(--accent); transform: translateX(0); }
  .step-dot { width: 5px; height: 5px; border-radius: 50%; background: currentColor; flex-shrink: 0; }

  .result-screen { display: none; }
  .result-screen.active { display: block; animation: fadeUp 0.6s cubic-bezier(0.22,1,0.36,1) both; }
  .result-header { text-align: center; margin-bottom: 48px; }
  .result-header .eyebrow {
    display: inline-block;
    background: rgba(79,255,176,0.07); border: 1px solid rgba(79,255,176,0.2);
    color: var(--accent); font-size: 10px; letter-spacing: 3px;
    text-transform: uppercase; padding: 7px 18px; border-radius: 2px; margin-bottom: 20px;
  }
  .result-header h2 {
    font-family: 'Syne', sans-serif;
    font-size: clamp(28px, 5vw, 48px); font-weight: 800; letter-spacing: -1px; line-height: 1.1;
  }

  .result-content {
    background: var(--surface); border: 1px solid var(--border);
    border-radius: 6px; padding: 40px;
    font-size: 13px; line-height: 1.9; color: #ccd0ee;
  }
  .result-content h2 {
    font-family: 'Syne', sans-serif; font-size: 20px; font-weight: 700;
    color: var(--text); margin: 36px 0 14px; padding-bottom: 10px;
    border-bottom: 1px solid var(--border);
  }
  .result-content h2:first-child { margin-top: 0; }
  .result-content h3 {
    font-family: 'Syne', sans-serif; font-size: 15px; font-weight: 600;
    color: var(--accent); margin: 22px 0 10px;
  }
  .result-content h4 {
    font-size: 10px; font-weight: 600; color: var(--accent2);
    text-transform: uppercase; letter-spacing: 2px; margin: 18px 0 8px;
  }
  .result-content table { width: 100%; border-collapse: collapse; margin: 16px 0; font-size: 12px; }
  .result-content th {
    background: var(--surface2); padding: 10px 14px; text-align: left;
    font-weight: 500; color: var(--muted); font-size: 9px;
    letter-spacing: 2px; text-transform: uppercase; border-bottom: 1px solid var(--border);
  }
  .result-content td { padding: 11px 14px; border-bottom: 1px solid rgba(35,37,53,0.7); vertical-align: middle; }
  .result-content tr:last-child td { border-bottom: none; }
  .result-content tr:hover td { background: rgba(79,255,176,0.02); }
  .result-content strong { color: var(--accent); font-weight: 500; }
  .result-content em { color: var(--accent3); font-style: normal; }
  .result-content ul, .result-content ol { padding-left: 18px; margin: 10px 0; }
  .result-content li { margin-bottom: 7px; }
  .result-content p { margin-bottom: 14px; }
  .result-content blockquote {
    border-left: 3px solid var(--accent); padding: 14px 20px; margin: 18px 0;
    background: rgba(79,255,176,0.04); border-radius: 0 4px 4px 0; color: var(--text);
  }
  .result-content hr { border: none; border-top: 1px solid var(--border); margin: 24px 0; }

  .restart-btn {
    display: block; margin: 36px auto 0; padding: 14px 44px;
    background: transparent; border: 1px solid var(--border);
    border-radius: 3px; color: var(--muted);
    font-family: 'DM Mono', monospace; font-size: 10px;
    letter-spacing: 2.5px; text-transform: uppercase;
    cursor: pointer; transition: all 0.2s;
  }
  .restart-btn:hover { color: var(--text); border-color: var(--muted); }
  .number-input {
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: 4px;
    padding: 14px 18px;
    color: var(--accent);
    font-family: 'Syne', sans-serif;
    font-size: 22px;
    font-weight: 700;
    width: 100%;
    outline: none;
    transition: border-color 0.2s;
    -moz-appearance: textfield;
  }
  .number-input::-webkit-outer-spin-button,
  .number-input::-webkit-inner-spin-button { -webkit-appearance: none; margin: 0; }
  .number-input:focus { border-color: var(--accent); box-shadow: 0 0 0 3px rgba(79,255,176,0.08); }
  .number-input::placeholder { color: var(--muted); font-size: 16px; font-weight: 400; }
  .freetext-input {
    width: 100%;
    min-height: 160px;
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: 4px;
    padding: 16px 18px;
    color: var(--text);
    font-family: 'DM Mono', monospace;
    font-size: 13px;
    line-height: 1.7;
    resize: vertical;
    outline: none;
    transition: border-color 0.2s;
  }
  .freetext-input:focus { border-color: var(--accent); box-shadow: 0 0 0 3px rgba(79,255,176,0.06); }
  .freetext-input::placeholder { color: var(--muted); font-size: 12px; line-height: 1.8; }
  .char-count {
    text-align: right;
    font-size: 10px;
    color: var(--muted);
    margin-top: 8px;
    letter-spacing: 1px;
  }

  @keyframes fadeDown { from { opacity: 0; transform: translateY(-24px); } to { opacity: 1; transform: translateY(0); } }
  @keyframes fadeUp { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }
  @keyframes spin { to { transform: rotate(360deg); } }
  @keyframes pulse { 0%, 100% { opacity: 1; transform: scale(1); } 50% { opacity: 0.4; transform: scale(0.7); } }

  @media (max-width: 600px) {
    .question-card { padding: 24px 20px; }
    .result-content { padding: 24px 20px; }
    .result-content table { font-size: 11px; }
    .result-content th, .result-content td { padding: 8px 10px; }
  }
</style>
</head>
<body>
<div class="container">

  <div class="header" id="mainHeader">
    <div class="eyebrow">Trade Republic · AI Portfolio Builder</div>
    <h1>Costruisci il tuo<br><em>portafoglio ottimale</em></h1>
    <p>20 domande sul tuo profilo. L'AI analizzerà il contesto macro 2026 e genererà un portafoglio diversificato su misura per settore e geografia.</p>
  </div>

  <div class="context-banner" id="contextBanner">
    <div class="icon">⚡</div>
    <p><strong>Contesto 2026 integrato:</strong> guerra Russia-Ucraina, tensioni Medio Oriente, riarmo NATO, ciclo BCE in discesa, dazi USA al 18%, boom AI e semiconduttori, transizione energetica. Il portafoglio terrà conto di tutti questi fattori.</p>
  </div>

  <div class="progress-wrap" id="progressWrap">
    <div class="progress-header">
      <span class="progress-label">Completamento profilo</span>
      <span class="progress-count" id="progressCount">0 / 20</span>
    </div>
    <div class="progress-bar"><div class="progress-fill" id="progressFill" style="width:0%"></div></div>
  </div>

  <div id="questionSection">
    <div class="section-label" id="sectionLabel">Profilo Personale</div>
    <div class="question-card" id="questionCard">
      <div class="q-meta">
        <div class="q-number" id="qNumber">01 / 20</div>
        <div class="q-tag" id="qTag">PROFILO</div>
      </div>
      <div class="q-text" id="qText"></div>
      <div class="q-hint" id="qHint" style="display:none"></div>
      <div class="options" id="optionsContainer"></div>
    </div>
    <div class="error-msg" id="errorMsg">↑ Seleziona almeno una risposta per continuare.</div>
    <div class="nav">
      <button class="btn btn-ghost" id="prevBtn" onclick="prevQuestion()">← Indietro</button>
      <button class="btn btn-primary" id="nextBtn" onclick="nextQuestion()">Avanti →</button>
    </div>
  </div>

  <div class="loading-screen" id="loadingScreen">
    <div class="loader-ring"></div>
    <div class="loading-title">Analisi in corso...</div>
    <div class="loading-sub">L'AI sta costruendo il tuo portafoglio</div>
    <div class="loading-steps">
      <div class="loading-step" id="step1"><div class="step-dot"></div>Analisi profilo e tolleranza al rischio</div>
      <div class="loading-step" id="step2"><div class="step-dot"></div>Valutazione contesto macro 2026</div>
      <div class="loading-step" id="step3"><div class="step-dot"></div>Screening settori globali</div>
      <div class="loading-step" id="step4"><div class="step-dot"></div>Selezione ETF e azioni per settore</div>
      <div class="loading-step" id="step5"><div class="step-dot"></div>Ottimizzazione allocazioni e rischi</div>
      <div class="loading-step" id="step6"><div class="step-dot"></div>Generazione portafoglio personalizzato</div>
    </div>
  </div>

  <div class="result-screen" id="resultScreen">
    <div class="result-header">
      <div class="eyebrow">Portafoglio Personalizzato · 2026</div>
      <h2>Il tuo portafoglio<br>ottimale</h2>
    </div>
    <div class="result-content" id="resultContent"></div>
    <button class="restart-btn" onclick="restart()">↺ Rifai il questionario</button>
  </div>

</div>
<script>
const TOTAL = 26;
const questions = [
  { id:1, section:"Profilo Personale", tag:"ANAGRAFICA", text:"Quanti anni hai?", type:"single", options:["Meno di 25 anni","25–34 anni","35–44 anni","45–54 anni","55 anni o più"] },
  { id:2, section:"Profilo Personale", tag:"LAVORO", text:"Qual è la tua situazione lavorativa?", type:"single", options:["Studente","Dipendente (contratto fisso)","Dipendente (contratto precario)","Libero professionista / P.IVA","Imprenditore","Disoccupato"] },
  { id:3, section:"Profilo Personale", tag:"ESPERIENZA", text:"Che esperienza hai con gli investimenti finanziari?", type:"single", options:["Zero — è la prima volta","Principiante — ho qualche nozione base","Intermedio — investo da 1–3 anni","Avanzato — investo da oltre 3 anni","Esperto — gestisco portafogli complessi"] },
  { id:4, section:"Capitale & Obiettivi", tag:"CAPITALE", text:"Qual è il capitale che vuoi investire?", type:"capital", hint:"Inserisci la cifra esatta oppure scegli una fascia", options:["Meno di 500€","500€ – 2.000€","2.000€ – 5.000€","5.000€ – 20.000€","Oltre 20.000€"] },
  { id:5, section:"Capitale & Obiettivi", tag:"LIQUIDITÀ", text:"Hai già un fondo di emergenza separato (3–6 mesi di spese)?", type:"single", options:["No — questi sono tutti i miei risparmi","No — ma ho entrate stabili mensili","Sì — piccolo cuscinetto","Sì — fondo di emergenza adeguato"] },
  { id:6, section:"Capitale & Obiettivi", tag:"OBIETTIVO", text:"Qual è il tuo obiettivo principale?", type:"single", options:["Proteggere i risparmi dall'inflazione","Accumulare capitale nel lungo periodo","Generare rendita e dividendi passivi","Crescita aggressiva con rischio elevato","Imparare investendo con somme piccole"] },
  { id:7, section:"Capitale & Obiettivi", tag:"ORIZZONTE", text:"Per quanto tempo puoi lasciare il denaro investito senza toccarlo?", type:"single", options:["Meno di 1 anno","1–2 anni","3–5 anni","5–10 anni","Oltre 10 anni"] },
  { id:8, section:"Tolleranza al Rischio", tag:"VOLATILITÀ", text:"Se il tuo portafoglio perdesse il 25% in un mese, cosa faresti?", type:"single", options:["Venderei tutto subito per limitare i danni","Sarei preoccupato ma aspetterei","Aspetterei con calma il recupero","Comprerei altri titoli a prezzi scontati","Raddoppierei la posizione senza esitare"] },
  { id:9, section:"Tolleranza al Rischio", tag:"PERDITA MAX", text:"Qual è la perdita massima tollerabile in un anno?", type:"single", options:["0% — non posso permettermi perdite","Fino al 5%","Fino al 10–15%","Fino al 25–30%","Oltre il 30% — accetto alta volatilità"] },
  { id:10, section:"Strategia", tag:"STRUMENTI", text:"Preferisci ETF o azioni singole?", type:"single", options:["Solo ETF — massima diversificazione e semplicità","Prevalentemente ETF + poche azioni singole","Mix equilibrato (50/50)","Prevalentemente azioni singole","Solo azioni singole"] },
  { id:11, section:"Strategia", tag:"PAC", text:"Vuoi impostare un Piano di Accumulo mensile (PAC) oltre al capitale iniziale?", type:"single", options:["No — solo investimento iniziale","Sì — 20–50€/mese","Sì — 50–150€/mese","Sì — oltre 150€/mese"] },
  { id:12, section:"Strategia", tag:"DIVIDENDI", text:"Preferisci ETF ad accumulazione (reinvestono dividendi) o distribuzione (pagano cedole)?", type:"single", options:["Accumulazione — voglio far crescere il capitale","Distribuzione — voglio incassare dividendi periodici","Misto — un po' di entrambi","Non so — mi fido dell'AI"] },
  { id:13, section:"Diversificazione Settoriale", tag:"SETTORI", text:"Quali macro-settori ti interessano di più? (fino a 3)", type:"multi", hint:"Seleziona fino a 3 settori", maxSelect:3, options:["🤖 Tecnologia & AI (chip, cloud, software)","🏦 Finanza & Banche (europee e globali)","⚡ Energia & Rinnovabili (solare, eolico, idrogeno)","🛡️ Difesa & Sicurezza (riarmo NATO, cybersecurity)","💊 Healthcare & Biotech (farmaci, diagnostica)","🛍️ Lusso & Consumer (LVMH, Ferrari, Nike)","🏗️ Infrastrutture & Utilities (reti, acqua, energia)"] },
  { id:14, section:"Diversificazione Settoriale", tag:"ESCLUSIONI", text:"Vuoi escludere settori per motivi etici? (opzionale)", type:"multi", hint:"Opzionale — lascia vuoto se nessuno", maxSelect:5, optional:true, options:["🚫 Armamenti e difesa","🚫 Combustibili fossili","🚫 Tabacco e alcol","🚫 Gioco d'azzardo","✅ Nessuna esclusione — massimizza il rendimento"] },
  { id:15, section:"Diversificazione Geografica", tag:"GEOGRAFIE", text:"Quali aree geografiche vuoi includere?", type:"multi", hint:"Puoi selezionare più opzioni", maxSelect:4, options:["🇺🇸 USA (S&P 500, tech, mercati profondi)","🇪🇺 Europa (banche italiane, difesa, utilities)","🌏 Mercati Emergenti (India, Cina, Brasile)","🌍 Globale diversificato (tutto il mondo)","🇮🇹 Solo Italia / Eurozona"] },
  { id:16, section:"Visione Macro 2026", tag:"RISCHIO MACRO", text:"Quali scenari ti preoccupano per il 2026? (puoi sceglierne più di uno)", type:"multi", hint:"Seleziona tutti gli scenari che ti preoccupano", maxSelect:5, options:["Escalation militare in Europa o Medio Oriente","Recessione da dazi USA e deglobalizzazione","Inflazione alta e tassi BCE elevati a lungo","Bolla speculativa nell'AI che scoppia","Nessuno — ho fiducia nei mercati a lungo termine"] },
  { id:17, section:"Visione Macro 2026", tag:"TEMA 2026", text:"Su quale grande tema strutturale vuoi puntare di più?", type:"single", options:["Intelligenza Artificiale e semiconduttori","Riarmo europeo e sicurezza (NATO)","Transizione energetica e rinnovabili","Sanità globale e invecchiamento demografico","Nessun tema — diversificazione pura"] },
  { id:18, section:"Aspetti Pratici", tag:"MONITORAGGIO", text:"Quanto spesso vuoi monitorare e ribilanciare il portafoglio?", type:"single", options:["Mai — compro e dimentico (buy & hold)","Una volta l'anno","Ogni trimestre","Ogni mese","Ogni settimana"] },
  { id:19, section:"Aspetti Pratici", tag:"TASSAZIONE", text:"Sei a conoscenza della tassazione italiana sugli investimenti?", type:"single", options:["No — spiegami nel portafoglio come funziona","Sì, so che le plusvalenze sono tassate al 26%","Sì, e voglio ottimizzare la fiscalità (timing, minusvalenze)"] },
  { id:20, section:"Aspetti Pratici", tag:"PREOCCUPAZIONI", text:"Cosa ti spaventa di più negli investimenti?", type:"single", options:["Perdere una parte significativa del capitale","Non capire cosa sto comprando","Pagare troppe commissioni o tasse","Fare scelte sbagliate nei momenti cruciali","La volatilità emotiva — vendere per panico"] },
  { id:21, section:"Profilo Avanzato", tag:"REDDITO", text:"Qual è la tua fascia di reddito annuo netto?", type:"single", options:["Meno di 15.000€ / anno","15.000€ – 30.000€ / anno","30.000€ – 60.000€ / anno","60.000€ – 100.000€ / anno","Oltre 100.000€ / anno","Preferisco non rispondere"] },
  { id:22, section:"Profilo Avanzato", tag:"DEBITI", text:"Hai attualmente mutui, prestiti o debiti significativi in corso?", type:"single", options:["No — sono finanziariamente libero","Sì — mutuo casa (rata sostenibile)","Sì — prestito personale o auto","Sì — debiti significativi che pesano sul budget","Preferisco non rispondere"] },
  { id:23, section:"Profilo Avanzato", tag:"ALTRI INVESTIMENTI", text:"Hai già altri investimenti o risparmi attivi oltre a questo?", type:"multi", hint:"Puoi selezionare più opzioni", maxSelect:6, options:["Conto deposito o buoni fruttiferi postali","Fondi pensione o TFR investito","Immobili o investimento immobiliare","Altri ETF o azioni (broker diverso)","Criptovalute","No — questo sarà il mio unico investimento"] },
  { id:24, section:"Profilo Avanzato", tag:"VITA FINANZIARIA", text:"Nei prossimi 2 anni, prevedi spese importanti che potrebbero ridurre il tuo capitale investito?", type:"single", options:["No — la situazione è stabile","Forse — acquisto auto o elettrodomestici","Sì — affitto / trasferimento / università","Sì — matrimonio o figli in programma","Sì — acquisto casa o immobile"] },
  { id:25, section:"Profilo Avanzato", tag:"COMPORTAMENTO", text:"Come hai reagito emotivamente all'ultima grande crisi finanziaria che hai vissuto (es. Covid 2020, 2022)?", type:"single", options:["Non investivo ancora — non ho esperienza diretta","Ho venduto tutto per paura","Ho resistito senza fare nulla","Ho comprato di più approfittando dei prezzi bassi","Ho aumentato significativamente la posizione"] },
  { id:26, section:"Richieste Personalizzate", tag:"NOTE LIBERE", text:"C'è qualcosa di specifico che vuoi includere, escludere o comunicare all'AI per costruire il tuo portafoglio ideale?", type:"freetext", optional:true, hint:"Campo libero — scrivi qualsiasi preferenza, vincolo o idea (es. 'voglio almeno una small cap europea', 'evita aziende cinesi', 'interessato alle materie prime')" }
];

const sectionColors = {
  "Profilo Personale":"#7c6fff","Capitale & Obiettivi":"#4fffb0","Tolleranza al Rischio":"#ff9f43",
  "Strategia":"#4fffb0","Diversificazione Settoriale":"#ff6b9d","Diversificazione Geografica":"#48dbfb",
  "Visione Macro 2026":"#ff9f43","Aspetti Pratici":"#a29bfe",
  "Profilo Avanzato":"#26de81","Richieste Personalizzate":"#fd9644"
};

let current = 0, answers = {};

function renderQuestion() {
  const q = questions[current];
  const card = document.getElementById('questionCard');
  card.style.animation = 'none'; void card.offsetWidth;
  card.style.animation = 'fadeUp 0.35s cubic-bezier(0.22,1,0.36,1) both';
  card.classList.remove('answered');

  const sl = document.getElementById('sectionLabel');
  sl.textContent = q.section;
  sl.style.color = sectionColors[q.section] || 'var(--accent2)';
  document.getElementById('qNumber').textContent = `${String(q.id).padStart(2,'0')} / ${TOTAL}`;
  document.getElementById('qTag').textContent = q.tag;
  document.getElementById('qText').textContent = q.text;

  const hint = document.getElementById('qHint');
  if (q.hint) { hint.textContent = q.hint; hint.style.display = 'block'; } else hint.style.display = 'none';

  const container = document.getElementById('optionsContainer');
  container.innerHTML = '';
  const keys = ['A','B','C','D','E','F','G'];
  const saved = answers[q.id] || (q.type === 'multi' || q.type === 'capital' ? [] : null);

  if (q.type === 'capital') {
    // Manual number input
    const inputWrap = document.createElement('div');
    inputWrap.style.cssText = 'margin-bottom:16px;';
    const inputRow = document.createElement('div');
    inputRow.style.cssText = 'display:flex;gap:10px;align-items:center;';
    const inp = document.createElement('input');
    inp.type = 'number'; inp.min = '1'; inp.placeholder = 'Es. 800';
    inp.className = 'number-input';
    inp.style.cssText = 'flex:1;font-size:15px;padding:14px 18px;';
    const euroLabel = document.createElement('span');
    euroLabel.textContent = '€';
    euroLabel.style.cssText = 'color:var(--accent);font-size:18px;font-family:Syne,sans-serif;font-weight:700;';
    inputRow.appendChild(inp); inputRow.appendChild(euroLabel);
    inputWrap.appendChild(inputRow);
    // Restore saved manual value if any
    if (answers[q.id] && answers[q.id].manual) inp.value = answers[q.id].manual;
    inp.oninput = () => {
      const v = inp.value.trim();
      if (!answers[q.id]) answers[q.id] = { manual: '', range: '' };
      answers[q.id].manual = v;
      // Deselect range buttons
      container.querySelectorAll('.option').forEach(b => b.classList.remove('selected'));
      answers[q.id].range = '';
      const hasVal = v.length > 0;
      document.getElementById('questionCard').classList.toggle('answered', hasVal);
      document.getElementById('errorMsg').classList.remove('show');
      updateProgress();
    };
    container.appendChild(inputWrap);

    // Divider
    const div = document.createElement('div');
    div.style.cssText = 'display:flex;align-items:center;gap:12px;margin-bottom:14px;';
    div.innerHTML = '<div style="flex:1;height:1px;background:var(--border)"></div><span style="font-size:10px;color:var(--muted);letter-spacing:2px">OPPURE SCEGLI FASCIA</span><div style="flex:1;height:1px;background:var(--border)"></div>';
    container.appendChild(div);

    // Range buttons
    q.options.forEach((opt, i) => {
      const btn = document.createElement('button');
      const selRange = answers[q.id] && answers[q.id].range === opt;
      btn.className = 'option' + (selRange ? ' selected' : '');
      btn.innerHTML = `<span class="option-key">${keys[i]}</span><span class="option-text">${opt}</span>`;
      btn.onclick = () => {
        if (!answers[q.id]) answers[q.id] = { manual: '', range: '' };
        answers[q.id].range = opt;
        answers[q.id].manual = '';
        inp.value = '';
        container.querySelectorAll('.option').forEach(b => b.classList.remove('selected'));
        btn.classList.add('selected');
        document.getElementById('questionCard').classList.add('answered');
        document.getElementById('errorMsg').classList.remove('show');
        updateProgress();
      };
      container.appendChild(btn);
    });
  } else if (q.type === 'freetext') {
    const textarea = document.createElement('textarea');
    textarea.className = 'freetext-input';
    textarea.placeholder = 'Scrivi qui le tue preferenze, vincoli o idee specifiche...\n\nEsempi:\n— "Voglio almeno una small cap europea"\n— "Evita aziende con sede in Cina"\n— "Interessato alle materie prime (oro, rame)"\n— "Voglio un titolo con dividendo sopra il 4%"';
    textarea.value = answers[q.id] || '';
    textarea.oninput = () => {
      answers[q.id] = textarea.value.trim();
      document.getElementById('questionCard').classList.toggle('answered', textarea.value.trim().length > 0);
      updateProgress();
    };
    container.appendChild(textarea);

    const charCount = document.createElement('div');
    charCount.className = 'char-count';
    charCount.textContent = '0 / 500 caratteri';
    container.appendChild(charCount);

    textarea.addEventListener('input', () => {
      const len = textarea.value.length;
      if (len > 500) textarea.value = textarea.value.slice(0, 500);
      charCount.textContent = `${Math.min(len,500)} / 500 caratteri`;
    });
  } else {
    q.options.forEach((opt, i) => {
      const btn = document.createElement('button');
      const sel = q.type === 'multi' ? (Array.isArray(saved) && saved.includes(opt)) : saved === opt;
      btn.className = 'option' + (sel ? ' selected' : '');
      btn.innerHTML = `<span class="option-key">${keys[i]}</span><span class="option-text">${opt}</span>`;
      btn.onclick = () => selectOption(q, opt);
      container.appendChild(btn);
    });
  }

  const hasAnswer = q.type === 'capital'
    ? !!(answers[q.id] && (answers[q.id].manual || answers[q.id].range))
    : q.type === 'freetext' ? true  // always allow continue (optional)
    : q.type === 'multi' ? (Array.isArray(saved) && saved.length > 0) : !!saved;
  if (hasAnswer) card.classList.add('answered');

  document.getElementById('prevBtn').style.visibility = current === 0 ? 'hidden' : 'visible';
  document.getElementById('nextBtn').textContent = current === questions.length - 1 ? 'Genera Portafoglio →' : 'Avanti →';
  updateProgress();
  document.getElementById('errorMsg').classList.remove('show');
}

function selectOption(q, value) {
  if (q.type === 'capital') return; // handled inline
  if (q.type === 'multi') {
    if (!answers[q.id]) answers[q.id] = [];
    const arr = answers[q.id];
    const idx = arr.indexOf(value);
    if (idx > -1) arr.splice(idx, 1);
    else { if (arr.length >= (q.maxSelect || 99)) arr.shift(); arr.push(value); }
  } else {
    answers[q.id] = value;
  }
  document.querySelectorAll('.option').forEach((btn, i) => {
    const opt = q.options[i];
    const sel = q.type === 'multi' ? (answers[q.id] || []).includes(opt) : answers[q.id] === opt;
    btn.classList.toggle('selected', sel);
  });
  const hasAnswer = q.type === 'multi' ? (answers[q.id] || []).length > 0 : !!answers[q.id];
  document.getElementById('questionCard').classList.toggle('answered', hasAnswer);
  document.getElementById('errorMsg').classList.remove('show');
  updateProgress();
}

function nextQuestion() {
  const q = questions[current];
  let hasAnswer;
  if (q.type === 'capital') hasAnswer = !!(answers[q.id] && (answers[q.id].manual || answers[q.id].range));
  else if (q.type === 'freetext') hasAnswer = true; // always optional
  else if (q.type === 'multi') hasAnswer = (answers[q.id] || []).length > 0;
  else hasAnswer = !!answers[q.id];
  if (!hasAnswer && !q.optional) { document.getElementById('errorMsg').classList.add('show'); return; }
  if (current < questions.length - 1) { current++; renderQuestion(); window.scrollTo({top:0,behavior:'smooth'}); }
  else generatePortfolio();
}

function prevQuestion() {
  if (current > 0) { current--; renderQuestion(); window.scrollTo({top:0,behavior:'smooth'}); }
}

function updateProgress() {
  const answered = Object.keys(answers).filter(k => {
    const v = answers[k];
    if (Array.isArray(v)) return v.length > 0;
    if (v && typeof v === 'object') return !!(v.manual || v.range);
    return !!v;
  }).length;
  const pct = (answered / TOTAL) * 100;
  document.getElementById('progressFill').style.width = pct + '%';
  document.getElementById('progressCount').textContent = `${answered} / ${TOTAL}`;
}

async function generatePortfolio() {
  ['questionSection','progressWrap','mainHeader','contextBanner'].forEach(id => document.getElementById(id).style.display = 'none');
  document.getElementById('loadingScreen').classList.add('active');
  const steps = ['step1','step2','step3','step4','step5','step6'];
  for (let i = 0; i < steps.length; i++) { await new Promise(r => setTimeout(r, 600 + i*100)); document.getElementById(steps[i]).classList.add('show'); }

  const summary = questions.map(q => {
    const ans = answers[q.id];
    let ansStr;
    if (q.type === 'freetext') {
      ansStr = ans ? ans : 'Nessuna preferenza specifica indicata';
    } else if (q.type === 'capital' && ans && typeof ans === 'object') {
      ansStr = ans.manual ? ans.manual + '€ (importo esatto)' : (ans.range || 'N/A');
    } else if (Array.isArray(ans)) {
      ansStr = ans.length ? ans.join(' | ') : 'Nessuna esclusione indicata';
    } else {
      ansStr = ans || 'N/A';
    }
    return `[${q.tag}] ${q.text}\n→ ${ansStr}`;
  }).join('\n\n');

  const prompt = `Sei un consulente finanziario senior specializzato in portafogli diversificati per investitori retail italiani su Trade Republic.

Il tuo compito è costruire un portafoglio OBBLIGATORIAMENTE distribuito su PIÙ SETTORI dell'economia globale — non concentrato su uno o due. Ogni settore deve avere almeno un titolo rappresentativo. Questo è il requisito più importante.

════════════════════════════
PROFILO INVESTITORE
════════════════════════════
${summary}

════════════════════════════
CONTESTO MACRO GLOBALE — MARZO 2026
════════════════════════════
GEOPOLITICA:
- Guerra Russia-Ucraina attiva → riarmo UE, obiettivo NATO 2% PIL, boom ordini difesa (Leonardo, Rheinmetall, BAE Systems)
- Tensioni USA-Iran/Medio Oriente → petrolio Brent ~80$, rischio supply shock energia
- Dazi USA al 18% (massimo anni '30) → reshoring manifatturiero in Europa e India, penalizza export cinese

MACRO & BANCHE CENTRALI:
- BCE in ciclo di tagli graduali → favorevole per azioni growth, real estate, utilities
- Fed ferma o taglia lentamente → dollaro indebolito, vantaggio competitivo per esportatori europei
- Inflazione in discesa ma non sconfitta → materie prime e energia rimangono hedge

SETTORI IN FORTE CRESCITA 2026:
- 🤖 TECH & AI: capex hyperscaler >570 mld$ (Microsoft Azure, Google Cloud, AWS). Nvidia domina chip AI. ASML monopolio litografia. Tema strutturale decennale.
- 🛡️ DIFESA: bilanci NATO in aumento ovunque. ETF difesa (DFNS, NATO) e titoli come Leonardo, Rheinmetall, Thales
- ⚡ ENERGIA & RINNOVABILI: transizione accelerata. Enel, Vestas, Brookfield Renewable, First Solar. Petrolio ancora necessario (Eni, Shell)
- 💊 HEALTHCARE: invecchiamento demografico globale. Novo Nordisk (GLP-1/obesità), Roche, ETF iShares Healthcare
- 🏦 BANCHE EUROPEE: FTSE Italia Banks +47% nel 2025. UniCredit target +23%, BPER ancora upside. Tassi BCE favorevoli ancora per 12-18 mesi
- 🛍️ LUSSO & CONSUMER: LVMH, Ferrari, Hermès. Domanda Asia e Middle East resiliente nonostante macro debole
- 🏗️ INFRASTRUTTURE: utilities, reti elettriche smart, acqua. Difensive in scenari di recessione. Terna, Snam, NextEra
- 🌏 EMERGENTI: India (+7% PIL, demografia positiva), Brasile (commodity), Cina (incerta per dazi USA)

════════════════════════════
REGOLE FERREE — NON DEROGABILI
════════════════════════════
⛔ VIETATO costruire un portafoglio concentrato su 1-2 settori soli (es. solo banche, solo tech)
✅ OBBLIGATORIO: almeno 6 settori distinti rappresentati nel portafoglio finale
✅ OBBLIGATORIO: almeno 3 aree geografiche (USA, Europa, Resto del mondo/Emergenti) salvo esplicita richiesta contraria
✅ Ogni settore deve avere peso minimo del 5% e massimo del 30%
✅ Ticker esatti disponibili su Trade Republic per ogni posizione
✅ Percentuali che sommano esattamente al 100%
✅ Importo in euro calcolato sul capitale dichiarato
✅ ETF e azioni bilanciate secondo la preferenza espressa
✅ Motivazione di 1-2 righe per ogni posizione, ancorata al contesto macro 2026
✅ Se l'utente ha indicato settori preferiti, sovrappesali ma NON escludere gli altri
✅ Rispetta le esclusioni etiche indicate

LOGICA DI COSTRUZIONE DA SEGUIRE:
1. Definisci prima la struttura macro (% per ETF core + % per azioni singole)
2. Dividi le azioni singole su almeno 6 settori diversi
3. Seleziona 1-2 titoli per settore (qualità > quantità)
4. Assegna i pesi in base a: preferenze utente + momentum macro 2026 + tolleranza al rischio
5. Verifica che nessun settore superi il 30% del totale

════════════════════════════
STRUTTURA RISPOSTA OBBLIGATORIA
════════════════════════════

## 📊 Profilo Sintetico
[3-4 righe: chi è, profilo di rischio, approccio scelto]

## 🗂️ Portafoglio Completo
[Tabella con colonne: Strumento | Ticker | Settore | Area Geo | % | Importo €]
[Prima blocco ETF Core, poi Azioni Singole raggruppate per settore]
[Riga TOTALE finale con 100% e importo totale]

## 🌍 Mappa della Diversificazione
Tabella 1 → Settore | Peso % | Titoli inclusi
Tabella 2 → Area Geografica | Peso % | Motivazione

## 🧠 Razionale per Settore (contesto 2026)
[Per ogni settore presente: 2-3 righe che spiegano perché è incluso e quale catalizzatore macro lo supporta]

## ⚠️ Rischi Specifici del Portafoglio
[4-5 rischi concreti, non generici, legati a questo portafoglio e al 2026]

## 📅 Come Procedere su Trade Republic
[Ordine degli acquisti, cost averaging su 2-3 mesi, impostazione PAC se richiesto, ribilanciamento]

## 💡 Tassazione Italia
[26% plusvalenze, compensazione minusvalenze, consigli pratici sul timing]

════════════════════════════
ISTRUZIONI SUL PROFILO AVANZATO E RICHIESTE PERSONALIZZATE
════════════════════════════
- Tieni conto del reddito e dei debiti per valutare la sostenibilità dell'investimento
- Se l'utente ha altri investimenti attivi, evita sovrapposizioni e complementa il portafoglio esistente
- Se prevede spese importanti nei prossimi 2 anni, aumenta la componente difensiva o liquida
- Il comportamento durante le crisi passate è il predittore più affidabile della tolleranza al rischio reale: usalo per calibrare la volatilità del portafoglio
- Se l'utente ha fornito RICHIESTE PERSONALIZZATE (domanda 26), queste hanno PRIORITÀ ASSOLUTA: rispettale integralmente nel portafoglio finale
- COSTO TRANSAZIONI: Trade Republic addebita 1 euro fisso per ogni ordine eseguito. Tienine conto:
  * Calcola il costo totale delle transazioni iniziali (1 euro x numero posizioni) e indicalo esplicitamente
  * Con capitali piccoli sotto i 2000 euro, limita le posizioni a 6-8 per non sprecare piu del 1-2% in commissioni
  * Suggerisci un ordine di acquisto ottimale (prima ETF core, poi azioni singole per importanza)
  * Per il PAC mensile, raggruppa gli acquisti in 1-2 ordini mensili per minimizzare i costi
  * Nella sezione Prossimi Passi includi sempre: Costo commissioni stimato: X euro (X ordini x 1 euro)

Rispondi in italiano. Usa tabelle markdown pulite. Massima precisione sui ticker.`;

  try {
    const resp = await fetch("https://api.anthropic.com/v1/messages", {
      method: "POST",
      headers: { "Content-Type": "application/json", "x-api-key": "sk-ant-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", "anthropic-version": "2023-06-01" },
      body: JSON.stringify({ model: "claude-sonnet-4-20250514", max_tokens: 3000, messages: [{ role: "user", content: prompt }] })
    });
    const data = await resp.json();
    const text = data.content?.map(b => b.text || '').join('') || 'Errore nella generazione.';
    document.getElementById('loadingScreen').classList.remove('active');
    document.getElementById('resultScreen').classList.add('active');
    document.getElementById('resultContent').innerHTML = renderMarkdown(text);
    window.scrollTo({top:0,behavior:'smooth'});
  } catch(e) {
    document.getElementById('loadingScreen').classList.remove('active');
    document.getElementById('resultScreen').classList.add('active');
    document.getElementById('resultContent').innerHTML = `<p style="color:var(--danger)">⚠ Errore nella connessione. Riprova più tardi.<br><small>${e.message}</small></p>`;
  }
}

function renderMarkdown(md) {
  const lines = md.split('\n');
  const result = [];
  let tableBuffer = [];
  let inTable = false;
  let firstRow = true;

  for (const raw of lines) {
    const line = raw.trim();
    if (/^\|.+\|$/.test(line)) {
      inTable = true;
      const cells = line.split('|').slice(1,-1).map(c => c.trim());
      if (cells.every(c => /^[-:]+$/.test(c))) { firstRow = false; continue; }
      const tag = firstRow ? 'th' : 'td';
      tableBuffer.push('<tr>' + cells.map(c => `<${tag}>${c}</${tag}>`).join('') + '</tr>');
      if (firstRow) firstRow = false;
    } else {
      if (inTable) {
        const thead = tableBuffer[0];
        const tbody = tableBuffer.slice(1).join('');
        result.push(`<table><thead>${thead}</thead><tbody>${tbody}</tbody></table>`);
        tableBuffer = []; inTable = false; firstRow = true;
      }
      result.push(raw);
    }
  }
  if (inTable && tableBuffer.length) {
    result.push(`<table><thead>${tableBuffer[0]}</thead><tbody>${tableBuffer.slice(1).join('')}</tbody></table>`);
  }

  return result.join('\n')
    .replace(/^## (.+)$/gm, '<h2>$1</h2>')
    .replace(/^### (.+)$/gm, '<h3>$1</h3>')
    .replace(/^#### (.+)$/gm, '<h4>$1</h4>')
    .replace(/\*\*(.+?)\*\*/g, '<strong>$1</strong>')
    .replace(/\*(.+?)\*/g, '<em>$1</em>')
    .replace(/^> (.+)$/gm, '<blockquote>$1</blockquote>')
    .replace(/^---$/gm, '<hr>')
    .replace(/^[-*] (.+)$/gm, '<li>$1</li>')
    .replace(/^\d+\. (.+)$/gm, '<li>$1</li>')
    .replace(/(<li>.*<\/li>\n?)+/g, m => `<ul>${m}</ul>`)
    .replace(/\n\n+/g, '</p><p>')
    .replace(/<p><\/p>/g, '');
}

function restart() {
  current = 0; answers = {};
  ['mainHeader','contextBanner','progressWrap','questionSection'].forEach(id => document.getElementById(id).style.display = '');
  document.getElementById('resultScreen').classList.remove('active');
  renderQuestion();
  window.scrollTo({top:0,behavior:'smooth'});
}

renderQuestion();
</script>
</body>
</html>
