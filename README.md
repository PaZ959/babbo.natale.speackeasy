[index.html](https://github.com/user-attachments/files/34699722/index.html)
# babbo.natale.speackeasy
babbo.natale.speackeasy
<!DOCTYPE html>
<html lang="it"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Babbo Natale Speakeasy – Trova la chiave</title>
<style>
:root{--bg:#0b1220;--bg2:#141c33;--gold:#e8b84a;--gold2:#ffd97a;--txt:#f4efe3;--red:#e0524a;--ok:#5fcf8a;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
html,body{margin:0;min-height:100%;background:var(--bg);color:var(--txt);font-family:system-ui,-apple-system,"Segoe UI",Roboto,Arial,sans-serif;font-size:20px;line-height:1.5;color-scheme:dark;overflow-x:hidden}
body{background:radial-gradient(ellipse at top,#1b2747 0%,var(--bg) 70%) fixed}
*{box-sizing:border-box}
#snow{position:fixed;inset:0;width:100%;height:100%;pointer-events:none;z-index:0}
main{position:relative;z-index:1;max-width:520px;margin:0 auto;padding:24px 18px 40px}
.screen{display:none;animation:in .6s ease both}.screen.on{display:block}
@keyframes in{from{opacity:0;transform:translateY(18px)}to{opacity:1;transform:none}}
h1{font-size:2.6rem;line-height:1.15;text-align:center;color:var(--gold);margin:.3em 0;text-shadow:0 0 18px #e8b84a55;letter-spacing:.02em}
h1 small{display:block;font-size:1.7rem;color:var(--gold2);font-style:italic;font-weight:normal;margin-top:.3em}
.sub{text-align:center;font-size:1.45rem;line-height:1.55;margin:1.2em 0 1.6em}
.deco{text-align:center;font-size:2.6rem;letter-spacing:.2em;margin:.4em 0}
.btn{display:block;width:100%;padding:22px 16px;font-size:1.5rem;font-weight:bold;font-family:inherit;letter-spacing:.06em;color:#2a1a00;background:linear-gradient(180deg,var(--gold2),var(--gold));border:0;border-radius:14px;box-shadow:0 6px 22px #e8b84a40;cursor:pointer}
.btn:active{transform:scale(.98)}
.card{background:linear-gradient(180deg,#18223e,#111a30);border:1px solid #e8b84a55;border-radius:16px;padding:16px;margin:0 0 14px}
.card.bad{border-color:var(--red);box-shadow:0 0 0 2px #e0524a66;animation:shake .4s}
@keyframes shake{25%{transform:translateX(-6px)}75%{transform:translateX(6px)}}
.lab{color:var(--gold);font-weight:bold;letter-spacing:.08em;text-transform:uppercase;font-size:1.1rem}
.card p{font-size:1.4rem;line-height:1.5;margin:.5em 0 .8em}
input{width:100%;padding:16px;font-size:1.7rem;font-family:inherit;color:var(--txt);background:#0b1220;border:1px solid #e8b84a88;border-radius:10px;text-align:center}
input:focus{outline:2px solid var(--gold2)}
#msg{display:none;margin:14px 0;padding:14px;border-radius:12px;background:#3a1618;border:1px solid var(--red);text-align:center;font-size:1.35rem;line-height:1.5}
.gift{position:relative;width:240px;height:240px;margin:10px auto 0}
.gift svg{position:absolute;inset:0;width:100%;height:100%;overflow:visible}
.gwrap{position:absolute;inset:0;transform-origin:50% 90%;animation:drop .9s cubic-bezier(.3,1.5,.5,1) both,wig .8s 1.1s ease-in-out forwards}
@keyframes drop{from{transform:translateY(-90px);opacity:0}to{transform:none;opacity:1}}
@keyframes wig{0%{transform:rotate(0)}20%{transform:rotate(-5deg)}40%{transform:rotate(5deg)}60%{transform:rotate(-3deg)}80%{transform:rotate(2deg)}100%{transform:rotate(0)}}
.lid{transform-box:fill-box;transform-origin:center;animation:lidoff 1.3s 2s cubic-bezier(.4,0,.2,1) forwards}
@keyframes lidoff{0%{transform:none}35%{transform:translate(-4px,-62px) rotate(-7deg)}100%{transform:translate(54px,74px) rotate(22deg)}}
.glowin{animation:glowin 1s 2s both}
@keyframes glowin{from{opacity:0}to{opacity:1}}
.rays{position:absolute;left:50%;top:50%;width:360px;height:360px;margin:-180px 0 0 -180px;background:repeating-conic-gradient(rgba(255,217,122,.5) 0 7deg,transparent 7deg 18deg);-webkit-mask-image:radial-gradient(circle,#000 0,transparent 68%);mask-image:radial-gradient(circle,#000 0,transparent 68%);opacity:0;animation:raysin 5s 2.2s ease-out forwards,spin 14s linear infinite}
@keyframes raysin{0%{opacity:0}20%{opacity:.9}100%{opacity:.55}}
@keyframes spin{to{transform:rotate(360deg)}}
.cf{position:absolute;left:50%;top:46%;width:8px;height:14px;border-radius:2px;background:var(--c);opacity:0;animation:burst 2.2s cubic-bezier(.15,.7,.35,1) var(--d) both}
@keyframes burst{0%{opacity:0;transform:translate(0,0) rotate(0)}8%{opacity:1}50%{opacity:1;transform:translate(var(--x),var(--y)) rotate(var(--r))}100%{opacity:0;transform:translate(calc(var(--x)*1.15),calc(var(--y) + 170px)) rotate(calc(var(--r)*1.5))}}
.star{position:absolute;left:50%;top:38%;width:56px;margin-left:-28px;text-align:center;font-size:3.4rem;line-height:1;opacity:0;animation:rise 1.6s 2.4s ease-out forwards;filter:drop-shadow(0 0 14px #ffd97a)}
@keyframes rise{0%{opacity:0;transform:translateY(25px) scale(.3)}60%{opacity:1;transform:translateY(-95px) scale(1.3)}100%{opacity:1;transform:translateY(-85px) scale(1.1)}}
#s3 h1,#s3 .fin,#s3 #go{animation:in .8s 2.8s backwards}







.fin{text-align:center;font-size:1.45rem;line-height:1.55;margin:1.5em 0}
a.btn{text-decoration:none;text-align:center}
</style></head><body>
<canvas id="snow"></canvas>
<main>
<section class="screen on" id="s1">
<div class="deco">🎄🎁🔑</div>
<h1>BABBO NATALE SPEAKEASY<small>Trova la chiave</small></h1>
<p class="sub">Sei piccoli enigmi ti separano dalla destinazione. Risolvi tutti gli indovinelli per guadagnarti l'accesso!</p>
<button class="btn" id="start">INIZIA LA SFIDA</button>
<div class="deco">⭐🔔🎅</div>
</section>
<section class="screen" id="s2">
<h1 style="font-size:2.1rem">Risolvi gli enigmi</h1>
<div class="card" id="c0"><div class="lab">🎄 Indovinello 1</div><p>Sono i giorni di una settimana moltiplicati per sette, poi togli sei.</p><input id="a0" type="text" inputmode="decimal" autocomplete="off" placeholder="La tua risposta" aria-label="Risposta 1"></div><div class="card" id="c1"><div class="lab">🎄 Indovinello 2</div><p>Sono il numero delle zampe di un ragno moltiplicato per sette.</p><input id="a1" type="text" inputmode="decimal" autocomplete="off" placeholder="La tua risposta" aria-label="Risposta 2"></div><div class="card" id="c2"><div class="lab">🎄 Indovinello 3</div><p>Sono i secondi che mancano a mezzo minuto dopo averne già trascorsi 15,9.</p><input id="a2" type="text" inputmode="decimal" autocomplete="off" placeholder="La tua risposta" aria-label="Risposta 3"></div><div class="card" id="c3"><div class="lab">🎄 Indovinello 4</div><p>Sono il doppio delle stagioni dell’anno, moltiplicato per tre.</p><input id="a3" type="text" inputmode="decimal" autocomplete="off" placeholder="La tua risposta" aria-label="Risposta 4"></div><div class="card" id="c4"><div class="lab">🎄 Indovinello 5</div><p>Sono i giorni di un mese di febbraio non bisestile meno due.</p><input id="a4" type="text" inputmode="decimal" autocomplete="off" placeholder="La tua risposta" aria-label="Risposta 5"></div><div class="card" id="c5"><div class="lab">🎄 Indovinello 6</div><p>Sono il doppio delle dita di una mano moltiplicato per due, poi aggiungi 2,7.</p><input id="a5" type="text" inputmode="decimal" autocomplete="off" placeholder="La tua risposta" aria-label="Risposta 6"></div>
<div id="msg">Non ci siamo ancora! Alcuni enigmi nascondono ancora il loro segreto. Riprova!</div>
<button class="btn" id="check">VERIFICA LE RISPOSTE</button>
</section>
<section class="screen" id="s3">
<div class="gift"><div class="rays"></div><div class="gwrap"><svg viewBox="0 0 240 240" aria-hidden="true"><defs><linearGradient id="gb" x1="0" x2="1"><stop offset="0" stop-color="#8f2620"/><stop offset=".45" stop-color="#d8443b"/><stop offset="1" stop-color="#9a2a23"/></linearGradient><linearGradient id="gl" x1="0" x2="1"><stop offset="0" stop-color="#a82d26"/><stop offset=".5" stop-color="#ea5a50"/><stop offset="1" stop-color="#a82d26"/></linearGradient><linearGradient id="gr" x1="0" x2="1"><stop offset="0" stop-color="#b88a1f"/><stop offset=".5" stop-color="#ffe08a"/><stop offset="1" stop-color="#b88a1f"/></linearGradient><radialGradient id="gi"><stop offset="0" stop-color="#fff3b0"/><stop offset="1" stop-color="#e8a23a"/></radialGradient></defs><ellipse cx="120" cy="214" rx="82" ry="9" fill="#000" opacity=".45"/><rect x="50" y="120" width="140" height="92" rx="4" fill="url(#gb)"/><rect x="108" y="120" width="24" height="92" fill="url(#gr)"/><rect x="50" y="120" width="140" height="10" fill="#000" opacity=".18"/><ellipse cx="120" cy="120" rx="68" ry="11" fill="#2b0b09" stroke="#7a1f1a" stroke-width="2"/><ellipse class="glowin" cx="120" cy="120" rx="66" ry="9" fill="url(#gi)"/><g class="lid"><rect x="44" y="98" width="152" height="36" rx="5" fill="url(#gl)"/><rect x="44" y="126" width="152" height="8" rx="3" fill="#000" opacity=".2"/><rect x="108" y="98" width="24" height="36" fill="url(#gr)"/><ellipse cx="98" cy="88" rx="24" ry="13" transform="rotate(-24 98 88)" fill="url(#gr)" stroke="#8a6414"/><ellipse cx="142" cy="88" rx="24" ry="13" transform="rotate(24 142 88)" fill="url(#gr)" stroke="#8a6414"/><path d="M112 96L100 120L112 113ZM128 96L140 120L128 113Z" fill="#d4a63a" stroke="#8a6414"/><circle cx="120" cy="94" r="10" fill="url(#gr)" stroke="#8a6414"/></g></svg></div><div class="star">⭐</div></div>
<h1 style="font-size:2.3rem">COMPLIMENTI!<br>HAI TROVATO LA STRADA!</h1>
<p class="fin">Sei riuscito a risolvere tutti gli enigmi. Il Babbo Natale Segreto Speakeasy ti aspetta!</p>
<a class="btn" id="go" href="#" target="_blank" rel="noopener">SCOPRI LA DESTINAZIONE</a>
</section>
</main>
<script>
const HASHES=[["79308777eb73b346ac2ae3511cb741371c5e9c2be023441475792aaf4ab5d52c"], ["e56983a2be6ddffed3b0b0ebd82cd74e8258ffa15429fd483054ba9cebca773e"], ["016c01730b178b4912ffc4f2b0de2b9391a6a7980b98d0fe850861431a263fd6", "4308afeffbd6980122d68b9267af11f24c7b056db49acb18ca7f2bca75a86420"], ["090f03a0c6436f3d0d46285fa2461627616e236bd25ce496de362f7e72c30315", "b815a8c19f32acfb16e4201d7f1d290ef2f88a011c4316141c84f1c4c9091ee6"], ["0e216524c91b5c6ec5ec321faf7ad360886697c0c0a59433cb622b83751921a2"], ["f8c1735ad3fd9fe80d16256fa1d0dc36380c745af8e2da78499d522f273c1ffe"]];
// 43°56'09.1"N 12°26'22.7"E -> 43.935861, 12.439639
const DEST=atob("aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS9tYXBzL3NlYXJjaC8/YXBpPTEmcXVlcnk9NDMuOTM1ODYxLDEyLjQzOTYzOQ==");
const $=id=>document.getElementById(id);
const gf=document.querySelector('.gift'),cols=['#e8b84a','#e0524a','#5fcf8a','#ffd97a','#f4efe3','#6ab7ff'];
for(let i=0;i<28;i++){const s=document.createElement('span');s.className='cf';const a=(Math.random()*160-80)*Math.PI/180,d=90+Math.random()*110;s.style.cssText=`--x:${Math.sin(a)*d*1.2|0}px;--y:${-Math.cos(a)*d-30|0}px;--r:${Math.random()*720-360|0}deg;--c:${cols[i%6]};--d:${(2.3+Math.random()*.3).toFixed(2)}s`;gf.appendChild(s)}
function show(id){document.querySelectorAll('.screen').forEach(s=>s.classList.remove('on'));$(id).classList.add('on');window.scrollTo({top:0,behavior:'smooth'})}
async function sha(t){const b=await crypto.subtle.digest('SHA-256',new TextEncoder().encode(t));return[...new Uint8Array(b)].map(x=>x.toString(16).padStart(2,'0')).join('')}
function canon(v){v=v.replace(/\s+/g,'').replace(',','.');if(!/^\d+(\.\d+)?$/.test(v))return null;return String(parseFloat(v))}
$('start').onclick=()=>show('s2');
$('check').onclick=async()=>{
  let ok=true;
  for(let i=0;i<HASHES.length;i++){
    const c=canon($('a'+i).value);
    const good=c!==null&&HASHES[i].includes(await sha('gg:'+i+':'+c));
    $('c'+i).classList.remove('bad');
    if(!good){ok=false;void $('c'+i).offsetWidth;$('c'+i).classList.add('bad')}
  }
  if(ok){$('go').href=DEST;$('msg').style.display='none';show('s3')}
  else $('msg').style.display='block';
};
// nevischio di sfondo
const cv=$('snow'),cx=cv.getContext('2d');let W,Hh,fl=[];
function rs(){W=cv.width=innerWidth;Hh=cv.height=innerHeight}rs();addEventListener('resize',rs);
for(let i=0;i<60;i++)fl.push({x:Math.random()*W,y:Math.random()*Hh,r:Math.random()*2.2+.6,s:Math.random()*.8+.3,d:Math.random()*Math.PI});
(function f(){cx.clearRect(0,0,W,Hh);cx.fillStyle='rgba(255,255,255,.75)';
fl.forEach(p=>{p.y+=p.s;p.d+=.01;p.x+=Math.sin(p.d)*.4;if(p.y>Hh){p.y=-5;p.x=Math.random()*W}cx.beginPath();cx.arc(p.x,p.y,p.r,0,7);cx.fill()});requestAnimationFrame(f)})();
</script></body></html>
