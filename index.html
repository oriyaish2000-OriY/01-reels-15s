<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
<meta charset="UTF-8">
<title>Share-Pen | הדף הריק — Reel 15s</title>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,600;1,400;1,600&family=Heebo:wght@300;400;700;900&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box}
body{background:#0a0a0a;display:flex;justify-content:center;align-items:center;min-height:100vh;font-family:'Heebo',sans-serif}
#wrap{width:405px;height:720px;background:#060408;position:relative;overflow:hidden;border-radius:16px;box-shadow:0 0 80px rgba(212,165,53,.15)}
.scene{position:absolute;inset:0;display:flex;flex-direction:column;justify-content:center;align-items:center;padding:55px 38px;text-align:center;opacity:0;transition:opacity .55s ease;pointer-events:none}
.scene.active{opacity:1;pointer-events:auto}
.scene.active .t{animation:up .6s ease forwards}
.scene.active .t2{animation:up .6s ease .15s forwards;opacity:0}
.scene.active .t3{animation:up .6s ease .3s forwards;opacity:0}
@keyframes up{from{opacity:0;transform:translateY(28px)}to{opacity:1;transform:translateY(0)}}
.t{font-size:2.3rem;font-weight:900;color:#f0eae0;line-height:1.35;letter-spacing:-.5px}
.t.gold{color:#d4a535}
.t.serif{font-family:'Cormorant Garamond',serif;font-style:italic;font-size:2.8rem;font-weight:600;color:#d4a535}
.t.sm{font-size:1.5rem;font-weight:300;color:#f0eae0;opacity:.8}
.dot{width:3px;height:64px;background:#f0eae0;opacity:.75;animation:blink .85s infinite}
@keyframes blink{0%,100%{opacity:.75}50%{opacity:0}}
.logo{font-family:'Cormorant Garamond',serif;font-size:3rem;color:#d4a535;letter-spacing:4px;margin-bottom:10px}
.url{font-family:'Heebo',sans-serif;font-size:.95rem;color:#f0eae0;opacity:.65;letter-spacing:3px;margin-top:6px}
.line{width:36px;height:1px;background:#d4a535;opacity:.45;margin:14px auto}
#pb{position:absolute;bottom:0;left:0;height:3px;background:linear-gradient(90deg,#c9a227,#d4a535);transform-origin:left;transform:scaleX(0)}
.corner{position:absolute;top:18px;right:22px;font-size:.7rem;color:#d4a535;opacity:.5;letter-spacing:2px;font-family:'Heebo',sans-serif}
</style>
</head>
<body>
<div id="wrap">
  <div class="corner">15s · REEL</div>

  <!-- Scene 0: cursor -->
  <div class="scene" id="s0">
    <div class="dot"></div>
  </div>

  <!-- Scene 1 -->
  <div class="scene" id="s1">
    <p class="t">כמה פעמים<br>פתחת דף ריק...</p>
  </div>

  <!-- Scene 2 -->
  <div class="scene" id="s2">
    <p class="t">...וסגרת אותו<br>בלי לכתוב<br>מילה אחת?</p>
  </div>

  <!-- Scene 3 -->
  <div class="scene" id="s3">
    <p class="t serif">השאלה הזו<br>תיפסק היום.</p>
  </div>

  <!-- Scene 4: logo -->
  <div class="scene" id="s4">
    <p class="logo">Share-Pen</p>
    <div class="line"></div>
    <p class="t sm">✒ Write with Purpose</p>
    <p class="url">share-pen.com</p>
  </div>

    <div id="wm" style="position:absolute;bottom:14px;right:18px;display:flex;align-items:center;gap:8px;z-index:100;pointer-events:none;background:rgba(6,4,8,.55);padding:5px 12px;border-radius:7px;border:1px solid rgba(212,165,53,.22)">
    <span style="font-family:'Cormorant Garamond',serif;font-size:1rem;color:#d4a535;letter-spacing:3px;font-weight:700;text-shadow:0 0 16px rgba(212,165,53,.35)"><div id="pb">#9998; Share<div id="pb">#8209;Pen</span>
    <span style="width:1px;height:12px;background:#d4a535;opacity:.3;display:inline-block"></span>
    <span style="font-family:'Inter',sans-serif;font-size:.58rem;color:#d4a535;opacity:.55;letter-spacing:1.5px">share-pen.com</span>
  </div>
  <div id="pb"></div>
</div>

<script>
const TOTAL = 15000;
const scenes = [
  {id:'s0',start:0,end:2000},
  {id:'s1',start:2000,end:5500},
  {id:'s2',start:5500,end:10000},
  {id:'s3',start:10000,end:13200},
  {id:'s4',start:13200,end:15000},
];
let t0=null,cur=null;
function tick(ts){
  if(!t0)t0=ts;
  const el=ts-t0;
  document.getElementById('pb').style.transform=`scaleX(${Math.min(el/TOTAL,1)})`;
  const a=scenes.find(s=>el>=s.start&&el<s.end);
  if(a&&a.id!==cur){
    if(cur)document.getElementById(cur).classList.remove('active');
    document.getElementById(a.id).classList.add('active');
    cur=a.id;
  }
  if(el<TOTAL)requestAnimationFrame(tick);
  else setTimeout(()=>{t0=null;cur=null;document.querySelectorAll('.scene').forEach(s=>s.classList.remove('active'));requestAnimationFrame(tick);},3000);
}
requestAnimationFrame(tick);
</script>
</body>
</html>
