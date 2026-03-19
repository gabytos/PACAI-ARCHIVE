<!DOCTYPE html>

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="PACAI">
<meta name="theme-color" content="#f2f2f7">
<title>PACAI — Opinamang Gabriel</title>
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@300;400;500;600;700&family=DM+Serif+Display:ital@0;1&display=swap" rel="stylesheet">
<style>
*, *::before, *::after { margin:0; padding:0; box-sizing:border-box; -webkit-tap-highlight-color:transparent; -webkit-font-smoothing:antialiased; }
:root {
  --bg:#f2f2f7; --white:#ffffff; --g1:#e5e5ea; --g2:#d1d1d6; --g3:#aeaeb2; --g4:#636366;
  --text:#1c1c1e; --text2:#3a3a3c; --accent:#007aff; --green:#34c759; --orange:#ff9500;
  --red:#ff3b30; --purple:#af52de; --gold:#d4a017; --r:14px; --rsm:10px;
}
html { background:var(--bg); font-family:'DM Sans',-apple-system,sans-serif; color:var(--text); }
body { min-height:100vh; background:var(--bg); overflow-y:auto; -webkit-overflow-scrolling:touch; }
body::before { content:''; position:fixed; inset:0; z-index:-1;
  background: radial-gradient(ellipse 80% 40% at 20% 0%,rgba(200,210,235,0.5) 0%,transparent 60%),
              radial-gradient(ellipse 60% 50% at 80% 100%,rgba(180,195,225,0.3) 0%,transparent 60%);
  pointer-events:none; }

/* PIN */
#pinScreen { min-height:100vh; display:flex; flex-direction:column; align-items:center; justify-content:space-between; padding:80px 24px 60px; background:linear-gradient(160deg,#e8eaf0 0%,#efeff4 50%,#e4e6ed 100%); }
.pin-top { display:flex; flex-direction:column; align-items:center; gap:8px; }
.pin-av { width:82px; height:82px; border-radius:50%; background:linear-gradient(135deg,#d0d5e0,#b8bfd0); display:flex; align-items:center; justify-content:center; font-size:36px; margin-bottom:10px; box-shadow:0 4px 20px rgba(0,0,0,0.1),inset 0 1px 0 rgba(255,255,255,0.6); }
.pin-name { font-family:‘DM Serif Display’,serif; font-size:24px; color:var(–text); }
.pin-email { font-size:13px; color:var(–g4); }
.pin-lbl { font-size:14px; color:var(–g4); font-weight:500; margin-top:28px; }
.pin-dots { display:flex; gap:18px; margin:18px 0 6px; }
.pin-dot { width:15px; height:15px; border-radius:50%; background:var(–g2); border:1.5px solid rgba(0,0,0,0.12); transition:all 0.2s cubic-bezier(0.34,1.56,0.64,1); }
.pin-dot.on { background:var(–text); border-color:var(–text); transform:scale(1.2); box-shadow:0 2px 8px rgba(0,0,0,0.2); }
.pin-dot.shake { animation:shake 0.35s ease; }
@keyframes shake { 0%,100%{transform:translateX(0)} 20%{transform:translateX(-6px)} 60%{transform:translateX(6px)} 80%{transform:translateX(-3px)} }
.pin-err { font-size:13px; color:var(–red); font-weight:500; min-height:18px; text-align:center; }
.numpad { display:grid; grid-template-columns:repeat(3,1fr); gap:14px; width:min(290px,86vw); }
.nbtn { height:74px; border-radius:50%; background:rgba(255,255,255,0.75); border:1px solid rgba(255,255,255,0.85); box-shadow:0 2px 14px rgba(0,0,0,0.07),inset 0 1px 0 rgba(255,255,255,0.95); display:flex; flex-direction:column; align-items:center; justify-content:center; cursor:pointer; transition:all 0.12s; -webkit-user-select:none; user-select:none; }
.nbtn:active { transform:scale(0.9); background:rgba(255,255,255,0.45); }
.nm { font-size:26px; font-weight:300; color:var(–text); line-height:1; }
.ns { font-size:8px; font-weight:600; color:var(–g3); letter-spacing:1.5px; margin-top:1px; }
.nsp { background:transparent!important; border:none!important; box-shadow:none!important; }
.nsp:active { background:rgba(0,0,0,0.05)!important; }
.nsp .nm { font-size:20px; font-weight:400; color:var(–g4); }

/* APP */
#app { display:none; min-height:100vh; padding-bottom:40px; }

/* NAVBAR */
.navbar { position:sticky; top:0; z-index:50; background:rgba(242,242,247,0.92); backdrop-filter:blur(20px); -webkit-backdrop-filter:blur(20px); border-bottom:1px solid rgba(0,0,0,0.06); padding:52px 20px 0; }
.nav-row { display:flex; align-items:center; justify-content:space-between; padding-bottom:12px; }
.nav-user { display:flex; align-items:center; gap:10px; }
.nav-av { width:36px; height:36px; border-radius:50%; background:linear-gradient(135deg,#c8cdd8,#a8b0c4); display:flex; align-items:center; justify-content:center; font-size:13px; font-weight:700; color:#fff; box-shadow:0 1px 4px rgba(0,0,0,0.1); flex-shrink:0; }
.nav-name { font-size:15px; font-weight:700; color:var(–text); }
.nav-sub { font-size:11px; color:var(–g4); }
.nav-lock { background:var(–g1); border:none; border-radius:20px; padding:6px 16px; font-size:13px; font-weight:500; color:var(–g4); cursor:pointer; font-family:‘DM Sans’,sans-serif; }
.nav-lock:active { background:var(–g2); }
.stats { display:flex; gap:8px; padding-bottom:14px; overflow-x:auto; -webkit-overflow-scrolling:touch; }
.stats::-webkit-scrollbar { display:none; }
.stat { background:rgba(255,255,255,0.8); border-radius:12px; padding:10px 16px; flex-shrink:0; border:1px solid rgba(255,255,255,0.9); box-shadow:0 1px 4px rgba(0,0,0,0.05); }
.stat-n { font-size:22px; font-weight:700; color:var(–text); line-height:1; }
.stat-l { font-size:11px; color:var(–g4); font-weight:500; margin-top:1px; }

/* CONTENT */
.content { padding:14px 16px 0; }
.search-box { display:flex; align-items:center; gap:8px; background:rgba(255,255,255,0.85); border:1px solid rgba(255,255,255,0.9); border-radius:12px; padding:11px 14px; box-shadow:0 1px 4px rgba(0,0,0,0.05); margin-bottom:12px; }
.search-icon { font-size:15px; color:var(–g3); flex-shrink:0; }
.search-in { flex:1; background:none; border:none; outline:none; font-family:‘DM Sans’,sans-serif; font-size:15px; color:var(–text); }
.search-in::placeholder { color:var(–g3); }
.filters { display:flex; gap:8px; margin-bottom:16px; overflow-x:auto; -webkit-overflow-scrolling:touch; padding-bottom:4px; }
.filters::-webkit-scrollbar { display:none; }
.chip { background:rgba(255,255,255,0.8); border:1px solid rgba(255,255,255,0.9); border-radius:20px; padding:7px 16px; font-size:13px; font-weight:500; color:var(–g4); cursor:pointer; white-space:nowrap; flex-shrink:0; box-shadow:0 1px 3px rgba(0,0,0,0.04); font-family:‘DM Sans’,sans-serif; }
.chip.active { background:var(–text); color:#fff; border-color:var(–text); box-shadow:0 2px 10px rgba(0,0,0,0.15); }
.sec-title { font-size:13px; font-weight:600; color:var(–g4); margin-bottom:10px; padding-left:2px; }
.ideas { display:flex; flex-direction:column; gap:10px; padding-bottom:120px; }

/* CARDS */
.card { background:rgba(255,255,255,0.88); border:1px solid rgba(255,255,255,0.95); border-radius:var(–r); padding:15px 16px; box-shadow:0 1px 6px rgba(0,0,0,0.06); cursor:pointer; position:relative; overflow:hidden; animation:cardIn 0.25s ease both; }
@keyframes cardIn { from{opacity:0;transform:translateY(6px)} to{opacity:1;transform:translateY(0)} }
.card:active { opacity:0.85; }
.card-bar { position:absolute; left:0; top:0; bottom:0; width:3px; border-radius:14px 0 0 14px; }
.card-top { display:flex; align-items:flex-start; justify-content:space-between; gap:10px; margin-bottom:6px; }
.card-claim { font-size:10px; font-weight:600; color:var(–g3); letter-spacing:0.8px; margin-bottom:3px; }
.card-title { font-size:15px; font-weight:600; color:var(–text); line-height:1.3; }
.card-badges { display:flex; align-items:center; gap:6px; flex-shrink:0; margin-top:2px; }
.badge { font-size:9px; font-weight:700; letter-spacing:0.5px; padding:3px 8px; border-radius:20px; text-transform:uppercase; }
.pip { width:7px; height:7px; border-radius:50%; flex-shrink:0; }
.card-preview { font-size:13px; font-weight:400; color:var(–g4); line-height:1.55; display:-webkit-box; -webkit-line-clamp:2; -webkit-box-orient:vertical; overflow:hidden; margin-bottom:10px; }
.card-foot { display:flex; align-items:center; justify-content:space-between; padding-top:8px; border-top:1px solid rgba(0,0,0,0.05); }
.card-date { font-size:11px; color:var(–g3); }
.card-btns { display:flex; gap:6px; }
.cbtn { background:rgba(0,0,0,0.04); border:none; color:var(–g4); font-family:‘DM Sans’,sans-serif; font-size:12px; font-weight:500; padding:5px 11px; border-radius:7px; cursor:pointer; }
.cbtn.del { color:var(–red); }
.cbtn:active { background:rgba(0,0,0,0.08); }

/* EMPTY */
.empty { display:flex; flex-direction:column; align-items:center; gap:10px; padding:70px 20px; text-align:center; }
.empty-icon { font-size:50px; opacity:0.2; margin-bottom:4px; }
.empty-title { font-size:18px; font-weight:600; color:var(–text2); }
.empty-sub { font-size:14px; color:var(–g3); line-height:1.6; max-width:220px; }

/* FAB */
.fab { position:fixed; right:20px; bottom:36px; z-index:100; width:56px; height:56px; border-radius:50%; background:var(–text); border:none; color:#fff; font-size:30px; font-weight:200; box-shadow:0 4px 20px rgba(0,0,0,0.22); display:flex; align-items:center; justify-content:center; cursor:pointer; font-family:‘DM Sans’,sans-serif; }
.fab:active { transform:scale(0.9); }

/* OVERLAY + SHEET */
.overlay { position:fixed; inset:0; z-index:200; background:rgba(0,0,0,0.28); backdrop-filter:blur(6px); -webkit-backdrop-filter:blur(6px); display:flex; align-items:flex-end; opacity:0; pointer-events:none; transition:opacity 0.3s; }
.overlay.open { opacity:1; pointer-events:all; }
.overlay.open .sheet { transform:translateY(0); }
.sheet { width:100%; max-height:92vh; background:rgba(248,248,252,0.97); backdrop-filter:blur(40px); -webkit-backdrop-filter:blur(40px); border-radius:22px 22px 0 0; border:1px solid rgba(255,255,255,0.85); border-bottom:none; box-shadow:0 -6px 40px rgba(0,0,0,0.1); display:flex; flex-direction:column; transform:translateY(100%); transition:transform 0.38s cubic-bezier(0.34,1.05,0.64,1); overflow:hidden; }
.sheet-handle { width:38px; height:4px; border-radius:2px; background:var(–g2); margin:10px auto; flex-shrink:0; }
.sheet-hdr { display:flex; align-items:center; justify-content:space-between; padding:4px 20px 14px; border-bottom:1px solid rgba(0,0,0,0.06); flex-shrink:0; }
.sheet-ttl { font-size:16px; font-weight:600; color:var(–text); }
.sheet-x { width:28px; height:28px; border-radius:50%; background:var(–g1); border:none; cursor:pointer; display:flex; align-items:center; justify-content:center; font-size:13px; color:var(–g4); font-family:‘DM Sans’,sans-serif; }
.sheet-body { flex:1; overflow-y:auto; padding:16px 20px 20px; display:flex; flex-direction:column; gap:14px; -webkit-overflow-scrolling:touch; }
.sheet-body::-webkit-scrollbar { display:none; }
.field { display:flex; flex-direction:column; gap:5px; }
.flbl { font-size:12px; font-weight:600; color:var(–g4); padding-left:2px; }
.fin,.fsel,.fta { background:var(–white); border:1.5px solid var(–g1); border-radius:var(–rsm); color:var(–text); font-family:‘DM Sans’,sans-serif; font-size:15px; padding:12px 14px; outline:none; width:100%; -webkit-appearance:none; appearance:none; }
.fin:focus,.fsel:focus,.fta:focus { border-color:var(–accent); box-shadow:0 0 0 3px rgba(0,122,255,0.08); }
.fin::placeholder,.fta::placeholder { color:var(–g3); }
.fsel { cursor:pointer; }
.fsel option { background:#fff; }
.fta { resize:none; min-height:110px; line-height:1.6; font-size:14px; }
.row2 { display:grid; grid-template-columns:1fr 1fr; gap:10px; }
.sheet-ftr { display:flex; gap:10px; padding:12px 20px 36px; border-top:1px solid rgba(0,0,0,0.06); flex-shrink:0; }
.bcancel { flex:1; background:var(–g1); border:none; color:var(–text2); font-family:‘DM Sans’,sans-serif; font-size:14px; font-weight:500; padding:14px; border-radius:var(–rsm); cursor:pointer; }
.bsave { flex:2; background:var(–text); border:none; color:#fff; font-family:‘DM Sans’,sans-serif; font-size:14px; font-weight:600; padding:14px; border-radius:var(–rsm); cursor:pointer; box-shadow:0 2px 10px rgba(0,0,0,0.15); }
.bsave:active { opacity:0.85; }
.dblock { background:var(–white); border:1.5px solid var(–g1); border-radius:var(–rsm); padding:14px; }
.dlbl { font-size:11px; font-weight:600; color:var(–g3); letter-spacing:0.8px; text-transform:uppercase; margin-bottom:6px; }
.dval { font-size:14px; color:var(–text2); line-height:1.7; white-space:pre-wrap; word-break:break-word; }
</style>

</head>
<body>

<div id="pinScreen">
  <div class="pin-top">
    <div class="pin-av">🔐</div>
    <div class="pin-name">Opinamang Gabriel</div>
    <div class="pin-email">opinamangabriel30@gmail.com</div>
    <div class="pin-lbl" id="pinLbl">Create your passcode</div>
    <div class="pin-dots">
      <div class="pin-dot" id="pd0"></div><div class="pin-dot" id="pd1"></div>
      <div class="pin-dot" id="pd2"></div><div class="pin-dot" id="pd3"></div>
    </div>
    <div class="pin-err" id="pinErr"></div>
  </div>
  <div class="numpad">
    <button class="nbtn" onclick="pp('1')"><span class="nm">1</span></button>
    <button class="nbtn" onclick="pp('2')"><span class="nm">2</span><span class="ns">ABC</span></button>
    <button class="nbtn" onclick="pp('3')"><span class="nm">3</span><span class="ns">DEF</span></button>
    <button class="nbtn" onclick="pp('4')"><span class="nm">4</span><span class="ns">GHI</span></button>
    <button class="nbtn" onclick="pp('5')"><span class="nm">5</span><span class="ns">JKL</span></button>
    <button class="nbtn" onclick="pp('6')"><span class="nm">6</span><span class="ns">MNO</span></button>
    <button class="nbtn" onclick="pp('7')"><span class="nm">7</span><span class="ns">PQRS</span></button>
    <button class="nbtn" onclick="pp('8')"><span class="nm">8</span><span class="ns">TUV</span></button>
    <button class="nbtn" onclick="pp('9')"><span class="nm">9</span><span class="ns">WXYZ</span></button>
    <div></div>
    <button class="nbtn" onclick="pp('0')"><span class="nm">0</span></button>
    <button class="nbtn nsp" onclick="pd()"><span class="nm">⌫</span></button>
  </div>
</div>

<div id="app">
  <div class="navbar">
    <div class="nav-row">
      <div class="nav-user">
        <div class="nav-av">OG</div>
        <div><div class="nav-name">Opinamang Gabriel</div><div class="nav-sub">PACAI Private Archive</div></div>
      </div>
      <button class="nav-lock" onclick="lockApp()">Lock</button>
    </div>
    <div class="stats">
      <div class="stat"><div class="stat-n" id="sT">0</div><div class="stat-l">Total</div></div>
      <div class="stat"><div class="stat-n" id="sD">0</div><div class="stat-l">Draft</div></div>
      <div class="stat"><div class="stat-n" id="sDv">0</div><div class="stat-l">Developing</div></div>
      <div class="stat"><div class="stat-n" id="sP">0</div><div class="stat-l">Protected</div></div>
    </div>
  </div>
  <div class="content">
    <div class="search-box">
      <span class="search-icon">🔍</span>
      <input class="search-in" id="si" type="search" placeholder="Search your ideas..." oninput="render()">
    </div>
    <div class="filters">
      <div class="chip active" data-f="all" onclick="setF('all')">All</div>
      <div class="chip" data-f="hardware" onclick="setF('hardware')">Hardware</div>
      <div class="chip" data-f="software" onclick="setF('software')">Software</div>
      <div class="chip" data-f="biotech" onclick="setF('biotech')">Biotech</div>
      <div class="chip" data-f="energy" onclick="setF('energy')">Energy</div>
      <div class="chip" data-f="transport" onclick="setF('transport')">Transport</div>
      <div class="chip" data-f="general" onclick="setF('general')">General</div>
    </div>
    <div class="sec-title" id="secT">All Ideas</div>
    <div class="ideas" id="list"></div>
  </div>
  <button class="fab" onclick="openAdd()">+</button>
</div>

<div class="overlay" id="eOv" onclick="bc(event,'eOv')">
  <div class="sheet">
    <div class="sheet-handle"></div>
    <div class="sheet-hdr"><div class="sheet-ttl" id="eTtl">New Idea</div><button class="sheet-x" onclick="cs('eOv')">✕</button></div>
    <div class="sheet-body">
      <div class="field"><div class="flbl">Claim Title / Code Name</div><input class="fin" id="fT" type="text" placeholder="e.g. Solemn Engagement Protocol"></div>
      <div class="row2">
        <div class="field"><div class="flbl">Category</div><select class="fsel" id="fC"><option value="general">General</option><option value="hardware">Hardware</option><option value="software">Software</option><option value="biotech">Biotech</option><option value="energy">Energy</option><option value="transport">Transport</option></select></div>
        <div class="field"><div class="flbl">Status</div><select class="fsel" id="fS"><option value="draft">Draft</option><option value="developing">Developing</option><option value="pending">Pending</option><option value="protected">Protected</option></select></div>
      </div>
      <div class="field"><div class="flbl">Core Description</div><textarea class="fta" id="fD" placeholder="Describe the concept, mechanism or breakthrough..."></textarea></div>
      <div class="field"><div class="flbl">Technical Notes & Claims</div><textarea class="fta" id="fN" placeholder="Specifications, prior art, unique claims..."></textarea></div>
      <div class="field"><div class="flbl">Next Action</div><input class="fin" id="fX" type="text" placeholder="e.g. Research WIPO patent landscape"></div>
    </div>
    <div class="sheet-ftr"><button class="bcancel" onclick="cs('eOv')">Cancel</button><button class="bsave" onclick="saveI()">Secure Entry</button></div>
  </div>
</div>

<div class="overlay" id="dOv" onclick="bc(event,'dOv')">
  <div class="sheet">
    <div class="sheet-handle"></div>
    <div class="sheet-hdr"><div class="sheet-ttl" id="dTtl">Detail</div><button class="sheet-x" onclick="cs('dOv')">✕</button></div>
    <div class="sheet-body" id="dBody"></div>
    <div class="sheet-ftr"><button class="bcancel" onclick="cs('dOv')">Close</button><button class="bsave" id="dEdit">Edit Entry</button></div>
  </div>
</div>

<script>
const PK='pacai_pin_v4',DK='pacai_data_v4';
const CC={general:{c:'#636366',bg:'rgba(99,99,102,0.1)',bar:'#8e8e93'},hardware:{c:'#c96000',bg:'rgba(255,149,0,0.12)',bar:'#ff9500'},software:{c:'#248a3d',bg:'rgba(52,199,89,0.12)',bar:'#34c759'},biotech:{c:'#8944ab',bg:'rgba(175,82,222,0.12)',bar:'#af52de'},energy:{c:'#9a6c00',bg:'rgba(212,160,23,0.12)',bar:'#d4a017'},transport:{c:'#d70015',bg:'rgba(255,59,48,0.12)',bar:'#ff3b30'}};
const SC={draft:{c:'#aeaeb2',l:'Draft'},developing:{c:'#ff9500',l:'Developing'},pending:{c:'#d4a017',l:'Pending'},protected:{c:'#34c759',l:'Protected'}};
let ideas=[],filt='all',eId=null,pin='',tmp=null;
function pp(d){if(pin.length>=4)return;pin+=d;dots();document.getElementById('pinErr').textContent='';if(pin.length===4)setTimeout(sub,150);}
function pd(){pin=pin.slice(0,-1);dots();document.getElementById('pinErr').textContent='';}
function dots(){for(let i=0;i<4;i++)document.getElementById('pd'+i).classList.toggle('on',i<pin.length);}
function errP(m){document.getElementById('pinErr').textContent=m;document.querySelectorAll('.pin-dot').forEach(d=>{d.classList.add('shake');setTimeout(()=>d.classList.remove('shake'),400);});pin='';setTimeout(dots,10);}
function sub(){const s=localStorage.getItem(PK);if(!s){if(!tmp){tmp=pin;pin='';dots();document.getElementById('pinLbl').textContent='Confirm your passcode';}else if(pin===tmp){localStorage.setItem(PK,pin);unlock();}else{errP('Passcodes did not match. Try again.');tmp=null;document.getElementById('pinLbl').textContent='Create your passcode';}}else{if(pin===s)unlock();else errP('Incorrect passcode. Try again.');}}
function unlock(){try{ideas=JSON.parse(localStorage.getItem(DK))||[];}catch{ideas=[];}document.getElementById('pinScreen').style.display='none';document.getElementById('app').style.display='block';render();sts();}
function lockApp(){ideas=[];pin='';tmp=null;dots();document.getElementById('pinErr').textContent='';document.getElementById('pinLbl').textContent=localStorage.getItem(PK)?'Enter your passcode':'Create your passcode';document.getElementById('app').style.display='none';document.getElementById('pinScreen').style.display='flex';cs('eOv');cs('dOv');window.scrollTo(0,0);}
function sv(){localStorage.setItem(DK,JSON.stringify(ideas));}
function uid(){return'I'+Date.now()+Math.random().toString(36).substr(2,4).toUpperCase();}
function td(){return new Date().toLocaleDateString('en-GB',{day:'numeric',month:'short',year:'numeric'});}
function esc(s){return String(s||'').replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;');}
function setF(f){filt=f;document.querySelectorAll('.chip').forEach(c=>c.classList.toggle('active',c.dataset.f===f));const lb={all:'All Ideas',hardware:'Hardware',software:'Software',biotech:'Biotech',energy:'Energy',transport:'Transport',general:'General'};document.getElementById('secT').textContent=lb[f]||'All Ideas';render();}
function render(){const q=(document.getElementById('si').value||'').toLowerCase();const list=document.getElementById('list');const items=ideas.filter(x=>{const mf=filt==='all'||x.cat===filt;const ms=!q||(x.title||'').toLowerCase().includes(q)||(x.desc||'').toLowerCase().includes(q)||(x.notes||'').toLowerCase().includes(q);return mf&&ms;});if(!items.length){list.innerHTML=`<div class="empty"><div class="empty-icon">📝</div><div class="empty-title">No ideas yet</div><div class="empty-sub">Tap + to log your first secret idea.</div></div>`;return;}list.innerHTML=items.map(x=>{const n=String(ideas.indexOf(x)+1).padStart(2,'0');const cc=CC[x.cat]||CC.general;const sc=SC[x.status]||SC.draft;return`<div class="card" onclick="openD('${x.id}')"><div class="card-bar" style="background:${cc.bar}"></div><div class="card-top"><div><div class="card-claim">CLAIM #${n}</div><div class="card-title">${esc(x.title)}</div></div><div class="card-badges"><div class="badge" style="background:${cc.bg};color:${cc.c}">${(x.cat||'GEN').toUpperCase()}</div><div class="pip" style="background:${sc.c};box-shadow:0 0 5px ${sc.c}"></div></div></div>${x.desc?`<div class="card-preview">${esc(x.desc)}</div>`:''}<div class="card-foot"><div class="card-date">${x.date||''} · ${sc.l}</div><div class="card-btns"><button class="cbtn" onclick="event.stopPropagation();openE('${x.id}')">Edit</button><button class="cbtn del" onclick="event.stopPropagation();delI('${x.id}')">Delete</button></div></div></div>`;}).join('');}
function sts(){document.getElementById('sT').textContent=ideas.length;document.getElementById('sD').textContent=ideas.filter(i=>i.status==='draft').length;document.getElementById('sDv').textContent=ideas.filter(i=>i.status==='developing').length;document.getElementById('sP').textContent=ideas.filter(i=>i.status==='protected').length;}
function openAdd(){eId=null;document.getElementById('eTtl').textContent='New Idea';['fT','fD','fN','fX'].forEach(id=>document.getElementById(id).value='');document.getElementById('fC').value='general';document.getElementById('fS').value='draft';os('eOv');}
function openE(id){const x=ideas.find(i=>i.id===id);if(!x)return;eId=id;document.getElementById('eTtl').textContent='Edit Idea';document.getElementById('fT').value=x.title||'';document.getElementById('fC').value=x.cat||'general';document.getElementById('fS').value=x.status||'draft';document.getElementById('fD').value=x.desc||'';document.getElementById('fN').value=x.notes||'';document.getElementById('fX').value=x.next||'';os('eOv');}
function saveI(){const title=document.getElementById('fT').value.trim();if(!title){alert('Please add a title.');return;}const d={title,cat:document.getElementById('fC').value,status:document.getElementById('fS').value,desc:document.getElementById('fD').value.trim(),notes:document.getElementById('fN').value.trim(),next:document.getElementById('fX').value.trim(),date:td()};if(eId){const i=ideas.findIndex(x=>x.id===eId);if(i>-1)ideas[i]={...ideas[i],...d};}else ideas.unshift({id:uid(),...d});sv();render();sts();cs('eOv');}
function delI(id){if(!confirm('Delete this idea?'))return;ideas=ideas.filter(i=>i.id!==id);sv();render();sts();}
function openD(id){const x=ideas.find(i=>i.id===id);if(!x)return;const n=String(ideas.indexOf(x)+1).padStart(2,'0');const cc=CC[x.cat]||CC.general;const sc=SC[x.status]||SC.draft;document.getElementById('dTtl').textContent=`Claim #${n}`;document.getElementById('dBody').innerHTML=`<div style="display:flex;flex-direction:column;gap:12px;"><div><div style="font-size:19px;font-weight:700;color:#1c1c1e;line-height:1.3;margin-bottom:8px;">${esc(x.title)}</div><div style="display:flex;gap:8px;align-items:center;flex-wrap:wrap;"><div class="badge" style="background:${cc.bg};color:${cc.c}">${(x.cat||'general').toUpperCase()}</div><div style="font-size:12px;font-weight:600;color:${sc.c};">${sc.l}</div><div style="font-size:12px;color:#aeaeb2;">${x.date||''}</div></div></div>${x.desc?`<div class="dblock"><div class="dlbl">Core Description</div><div class="dval">${esc(x.desc)}</div></div>`:''}${x.notes?`<div class="dblock"><div class="dlbl">Technical Notes & Claims</div><div class="dval">${esc(x.notes)}</div></div>`:''}${x.next?`<div class="dblock"><div class="dlbl">Next Action</div><div class="dval">${esc(x.next)}</div></div>`:''}</div>`;document.getElementById('dEdit').onclick=()=>{cs('dOv');openE(id);};os('dOv');}
function os(id){document.getElementById(id).classList.add('open');}
function cs(id){document.getElementById(id).classList.remove('open');}
function bc(e,id){if(e.target===document.getElementById(id))cs(id);}
window.addEventListener('load',()=>{const s=localStorage.getItem(PK);if(s)document.getElementById('pinLbl').textContent='Enter your passcode';document.getElementById('app').style.display='none';});
</script>

</body>
</html>
