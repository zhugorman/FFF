<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Колебания давления подземных вод</title>
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,400;9..144,500;9..144,600;9..144,700&family=IBM+Plex+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{
  box-sizing:border-box;
  padding-top:env(safe-area-inset-top,0px);
  padding-bottom:env(safe-area-inset-bottom,0px);

  --bg:#e9e0c8;
  --panel:#f7f1e0;
  --panel-2:#eee3c6;
  --ink:#20302a;
  --muted:#726a51;
  --line:#b7a473;
  --water:#215f83;
  --water-soft:#9cc0d4;
  --sand:#b07f3c;
  --clay:#8a7250;
  --accent:#1b6b62;
  --hot:#9c3d21;
  --grid:#ddcf9f;
  --shadow:0 1px 0 rgba(40,28,4,.06);
  --serif:"Fraunces","Iowan Old Style","Georgia",serif;
  --sans:"IBM Plex Sans","Segoe UI",Roboto,Arial,sans-serif;
}
@media (prefers-color-scheme: dark){
  :root:not([data-theme="light"]){
    --bg:#0d1a17;
    --panel:#122622;
    --panel-2:#173029;
    --ink:#e9efe3;
    --muted:#93a695;
    --line:#2c463d;
    --water:#5eb4d8;
    --water-soft:#1f4a5c;
    --sand:#c99a55;
    --clay:#7a6a4b;
    --accent:#4fc2ab;
    --hot:#e17f52;
    --grid:#1a322b;
    --shadow:0 1px 0 rgba(0,0,0,.45);
  }
}
:root[data-theme="dark"]{
  --bg:#0d1a17;--panel:#122622;--panel-2:#173029;--ink:#e9efe3;--muted:#93a695;
  --line:#2c463d;--water:#5eb4d8;--water-soft:#1f4a5c;--sand:#c99a55;--clay:#7a6a4b;
  --accent:#4fc2ab;--hot:#e17f52;--grid:#1a322b;
  --shadow:0 1px 0 rgba(0,0,0,.45);
}
*,*::before,*::after{box-sizing:inherit}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
body{
  margin:0;
  background:
    linear-gradient(var(--bg),var(--bg)) fixed,
    repeating-linear-gradient(0deg, rgba(120,105,60,.05) 0 1px, transparent 1px 34px),
    repeating-linear-gradient(90deg, rgba(120,105,60,.05) 0 1px, transparent 1px 34px);
  background-color:var(--bg);
  color:var(--ink);
  font:400 16px/1.55 var(--sans);
  -webkit-text-size-adjust:100%;
}
@media (prefers-color-scheme: dark){
  body{background:
    linear-gradient(var(--bg),var(--bg)) fixed,
    repeating-linear-gradient(0deg, rgba(180,220,200,.035) 0 1px, transparent 1px 34px),
    repeating-linear-gradient(90deg, rgba(180,220,200,.035) 0 1px, transparent 1px 34px);
    background-color:var(--bg);}
}
.wrap{max-width:1180px;margin:0 auto;padding:26px 18px 60px}

header.top{
  display:grid;grid-template-columns:1fr auto;gap:8px 22px;align-items:end;
  padding-bottom:16px;margin-bottom:8px;
}
.title-block{grid-column:1/2}
h1{
  margin:0 0 8px;font-family:var(--serif);font-weight:600;font-optical-sizing:auto;
  font-size:clamp(24px,3.6vw,36px);line-height:1.08;letter-spacing:-.01em;color:var(--ink);
}
.sub{margin:0;color:var(--muted);font-size:14.5px;max-width:64ch}
.plate{
  grid-column:2/3;justify-self:end;text-align:right;font-size:12px;color:var(--muted);
  border:1px solid var(--line);padding:8px 12px;line-height:1.5;background:var(--panel);
}
.plate b{display:block;color:var(--ink);font-weight:600;font-size:13px}
.eq{
  font-family:var(--serif);font-style:italic;font-size:14.5px;color:var(--accent);margin-top:3px;
}

.ruler{
  height:14px;margin-bottom:22px;
  background-image:repeating-linear-gradient(90deg, var(--line) 0 1px, transparent 1px calc(100%/60));
  background-position:bottom left;background-size:100% 100%;
  background-repeat:no-repeat;
  position:relative;border-bottom:1.5px solid var(--line);
}
.ruler::before{
  content:"";position:absolute;inset:0;
  background-image:repeating-linear-gradient(90deg, var(--line) 0 1.5px, transparent 1.5px calc(100%/12));
  background-size:100% 60%;background-position:bottom left;background-repeat:no-repeat;
  opacity:.85;
}

.grid{display:grid;grid-template-columns:minmax(0,1.45fr) minmax(280px,1fr);gap:18px}
@media (max-width:900px){.grid{grid-template-columns:1fr}}

.card{
  background:var(--panel);border:1px solid var(--line);border-radius:2px;
  box-shadow:var(--shadow);overflow:hidden;
}
.card h2{
  margin:0;padding:12px 15px;font-size:14px;font-weight:600;color:var(--ink);
  border-bottom:1px solid var(--line);font-family:var(--sans);letter-spacing:.01em;
}
.canvas-box{padding:10px}
canvas{display:block;width:100%;touch-action:manipulation}
#scene{height:clamp(360px,52vh,560px)}
#graph{height:250px}
@media (max-width:640px){#graph{height:210px}}

.ctl{padding:14px 15px 18px}
.field{margin-bottom:14px}
.field .lab{display:flex;justify-content:space-between;align-items:baseline;gap:8px;font-size:13.5px}
.field .lab span{color:var(--muted)}
.field .lab b{font-weight:600;font-variant-numeric:tabular-nums;color:var(--ink)}
input[type=range]{
  width:100%;margin:6px 0 0;accent-color:var(--water);height:22px;
}
input[type=range]:focus-visible{outline:2px solid var(--accent);outline-offset:3px}

.seg{display:flex;gap:1px;margin-bottom:16px;border:1px solid var(--line);background:var(--line)}
.seg button{flex:1;border-radius:0;border:none}
button{
  font:500 13.5px var(--sans);padding:9px 10px;border-radius:2px;cursor:pointer;
  border:1px solid var(--line);background:var(--panel-2);color:var(--ink);
}
button:hover{border-color:var(--accent);color:var(--accent)}
button:focus-visible{outline:2px solid var(--accent);outline-offset:2px}
button[aria-pressed="true"]{background:var(--water);border-color:var(--water);color:#fdf9ee}
.btns{display:flex;gap:6px;flex-wrap:wrap;margin-top:8px}
.chk{display:flex;align-items:center;gap:8px;font-size:13.5px;color:var(--muted);margin-top:12px}

.readout{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:1px;background:var(--line);border-top:1px solid var(--line)}
.readout div{background:var(--panel);padding:10px 13px}
.readout small{display:block;color:var(--muted);font-size:11.5px;line-height:1.3}
.readout b{font-weight:600;font-size:16.5px;font-variant-numeric:tabular-nums;font-family:var(--sans)}
.readout b i{font-style:normal;font-size:12px;color:var(--muted);font-weight:400}

.bars{padding:12px 15px 15px;border-top:1px solid var(--line)}
.bar{height:8px;background:var(--panel-2);overflow:hidden;margin:4px 0 10px;border:1px solid var(--line)}
.bar i{display:block;height:100%;background:var(--water)}
.bar.pot i{background:var(--sand)}
.bars .lab{display:flex;justify-content:space-between;font-size:12.5px;color:var(--muted)}

.note{padding:11px 15px;font-size:13px;color:var(--muted);border-top:1px solid var(--line);background:var(--panel-2)}
.note.warn{color:var(--hot)}

.full{margin-top:18px}
details.theory{margin-top:18px;background:var(--panel);border:1px solid var(--line);border-radius:2px;box-shadow:var(--shadow)}
details.theory>summary{padding:13px 15px;cursor:pointer;font-weight:600;font-size:15.5px;font-family:var(--serif)}
details.theory .body{padding:0 17px 20px;max-width:78ch}
details.theory h3{font-size:15px;margin:18px 0 7px;font-family:var(--sans);font-weight:600}
details.theory p,details.theory li{font-size:14.5px;color:var(--ink)}
details.theory .fml{
  font-family:var(--serif);font-style:italic;font-size:16.5px;
  background:var(--panel-2);border-left:3px solid var(--water);padding:9px 13px;margin:9px 0;
  overflow-x:auto;
}
code{font-family:ui-monospace,Menlo,Consolas,monospace;font-size:13px}
footer.foot{margin-top:22px;padding-top:14px;border-top:1px solid var(--line);font-size:12px;color:var(--muted);display:flex;justify-content:space-between;flex-wrap:wrap;gap:6px}
</style>
</head>
<body>
<div class="wrap">

<header class="top">
  <div class="title-block">
    <h1>Колебания давления подземных вод</h1>
    <p class="sub">Модель наблюдательной скважины, вскрывшей напорный водоносный горизонт. Уровень воды в стволе ведёт себя как инерционный осциллятор: меняйте параметры — период, затухание и давление пересчитываются по формулам.</p>
  </div>
  <div class="plate">
    <b>Схема колебаний напора</b>
    модель Купера — Бредехофта — Папададопулоса
    <div class="eq">d²h/dt² + 2β·dh/dt + ω₀²h = f(t)</div>
  </div>
</header>
<div class="ruler" aria-hidden="true"></div>

<div class="grid">

  <section class="card">
    <h2>Разрез: скважина и напорный горизонт</h2>
    <div class="canvas-box"><canvas id="scene" aria-label="Анимация колебаний уровня воды в скважине"></canvas></div>
    <div class="note" id="sceneNote">Вектор справа — фазор: его проекция на вертикаль задаёт смещение уровня h(t).</div>
  </section>

  <aside class="card">
    <h2>Параметры</h2>
    <div class="ctl">
      <div class="seg" role="group" aria-label="Режим колебаний">
        <button id="mFree" aria-pressed="true">Свободные</button>
        <button id="mForced" aria-pressed="false">Вынужденные</button>
      </div>

      <div class="field">
        <div class="lab"><span>Длина столба воды L<sub>э</sub></span><b id="oLe">60 м</b></div>
        <input type="range" id="Le" min="5" max="300" step="1" value="60">
      </div>

      <div class="field">
        <div class="lab"><span>Коэффициент затухания ζ</span><b id="oZ">0.08</b></div>
        <input type="range" id="zeta" min="0" max="1.4" step="0.01" value="0.08">
      </div>

      <div class="field" data-mode="free">
        <div class="lab"><span>Начальная амплитуда A₀</span><b id="oA">1.5 м</b></div>
        <input type="range" id="A0" min="0.1" max="5" step="0.1" value="1.5">
      </div>

      <div class="field" data-mode="free">
        <div class="lab"><span>Начальная фаза φ₀</span><b id="oP">0°</b></div>
        <input type="range" id="phi0" min="0" max="360" step="5" value="0">
      </div>

      <div class="field" data-mode="forced" hidden>
        <div class="lab"><span>Период воздействия T<sub>в</sub></span><b id="oTf">20.0 с</b></div>
        <input type="range" id="Tf" min="2" max="120" step="0.5" value="20">
      </div>

      <div class="field" data-mode="forced" hidden>
        <div class="lab"><span>Амплитуда воздействия a₀</span><b id="oa0">0.5 м</b></div>
        <input type="range" id="a0" min="0.05" max="2" step="0.05" value="0.5">
      </div>

      <div class="field">
        <div class="lab"><span>Скорость времени</span><b id="oS">1.0×</b></div>
        <input type="range" id="speed" min="0.1" max="4" step="0.1" value="1">
      </div>

      <div class="btns">
        <button id="play" aria-pressed="true">Пауза</button>
        <button id="reset">Сброс</button>
        <button id="pr1">Слаг-тест</button>
        <button id="pr2">Резонанс</button>
        <button id="pr3">Вязкая скважина</button>
      </div>

      <label class="chk"><input type="checkbox" id="env" checked> показывать огибающую e<sup>−βt</sup></label>
    </div>

    <div class="readout">
      <div><small>Собственный период T₀</small><b id="rT0">—</b></div>
      <div><small>Период колебаний T<sub>d</sub></small><b id="rTd">—</b></div>
      <div><small>Частота ω₀</small><b id="rW0">—</b></div>
      <div><small>Показатель затухания β</small><b id="rB">—</b></div>
      <div><small>Смещение уровня h(t)</small><b id="rH">—</b></div>
      <div><small>Скорость v(t)</small><b id="rV">—</b></div>
      <div><small>Избыточное давление Δp</small><b id="rP">—</b></div>
      <div><small id="lK">Логарифм. декремент</small><b id="rK">—</b></div>
    </div>

    <div class="bars">
      <div class="lab"><span>Кинетическая энергия</span><span id="bk">0%</span></div>
      <div class="bar"><i id="barK" style="width:0%"></i></div>
      <div class="lab"><span>Потенциальная энергия</span><span id="bp">0%</span></div>
      <div class="bar pot"><i id="barP" style="width:0%"></i></div>
    </div>

    <div class="note" id="regime">—</div>
  </aside>
</div>

<section class="card full">
  <h2>График: смещение напорного уровня h(t) и давление Δp(t)</h2>
  <div class="canvas-box"><canvas id="graph" aria-label="График колебаний уровня во времени"></canvas></div>
</section>

<details class="theory">
  <summary>Теория: откуда берутся колебания давления подземных вод</summary>
  <div class="body">
    <p>В напорном (артезианском) горизонте вода зажата между водоупорами. Скважина, вскрывшая такой горизонт, работает как гигантский U-образный манометр: столб воды в стволе обладает инерцией, а перепад напора — возвращающей силой. Поэтому уровень не просто «садится» на новое положение, а колеблется около него.</p>

    <h3>Уравнение движения</h3>
    <p>Для столба воды эффективной длины <i>L</i><sub>э</sub> баланс инерции, трения и веса даёт уравнение затухающих колебаний (модель Купера—Бредехофта—Папададопулоса, 1965):</p>
    <div class="fml">L<sub>э</sub>·d²h/dt² + c·dh/dt + g·h = L<sub>э</sub>·f(t)&nbsp;&nbsp;⟹&nbsp;&nbsp;d²h/dt² + 2β·dh/dt + ω₀²·h = f(t)</div>
    <p>Собственная круговая частота и период не зависят от амплитуды — это и есть «закон физики», по которому пересчитывается модель при движении ползунка <i>L</i><sub>э</sub>:</p>
    <div class="fml">ω₀ = √(g / L<sub>э</sub>),&nbsp;&nbsp; T₀ = 2π·√(L<sub>э</sub> / g),&nbsp;&nbsp; β = ζ·ω₀</div>
    <p>Чем длиннее столб воды, тем больше инерция и тем медленнее колебания: при L<sub>э</sub> = 10 м период ≈ 6,3 с, при L<sub>э</sub> = 200 м уже ≈ 28 с.</p>

    <h3>Давление</h3>
    <p>Колебание уровня — это колебание давления на кровле горизонта по гидростатическому закону:</p>
    <div class="fml">Δp(t) = ρ·g·h(t),&nbsp;&nbsp; ρ = 1000 кг/м³,&nbsp;&nbsp; 1 м вод. ст. ≈ 9,81 кПа</div>

    <h3>Три режима затухания</h3>
    <ul>
      <li><b>ζ &lt; 1 — колебательный.</b> h(t) = A₀·e<sup>−βt</sup>·cos(ω<sub>d</sub>t + φ₀), где ω<sub>d</sub> = ω₀√(1 − ζ²). Характерен для скважин большого диаметра в хорошо проницаемых породах.</li>
      <li><b>ζ = 1 — критический.</b> Возврат к равновесию за минимальное время без перехода через ноль.</li>
      <li><b>ζ &gt; 1 — апериодический (переторможенный).</b> Вязкое трение в узком стволе и слабопроницаемые породы гасят импульс: уровень «ползёт» к равновесию. По форме этой кривой в слаг-тесте определяют водопроводимость пласта.</li>
    </ul>

    <h3>Что раскачивает пласт в природе</h3>
    <ul>
      <li><b>Сейсмические волны.</b> Поверхностные волны с периодами 10–30 с деформируют пласт — скважина работает как гидросейсмограф. Если T<sub>в</sub> ≈ T₀, наступает резонанс и размах уровня вырастает в 1/(2ζ) раз.</li>
      <li><b>Земные приливы.</b> Лунно-солнечные волны (главная M₂, период 12 ч 25 мин) сжимают породу и дают колебания уровня в единицы сантиметров.</li>
      <li><b>Атмосферное давление.</b> Рост барометрического давления прижимает кровлю и опускает уровень; отношение называют барометрической эффективностью.</li>
      <li><b>Откачка, слаг-тест, забивка обсадной трубы</b> — импульсное возмущение, после которого идут свободные затухающие колебания.</li>
    </ul>

    <h3>Вынужденные колебания</h3>
    <p>При гармоническом воздействии с частотой ω установившийся отклик имеет амплитуду a₀·K и отстаёт по фазе на δ:</p>
    <div class="fml">K = 1 / √((1 − r²)² + (2ζr)²),&nbsp;&nbsp; tg δ = 2ζr / (1 − r²),&nbsp;&nbsp; r = ω / ω₀</div>
    <p>При r ≪ 1 (приливы, барометр) отклик квазистатический: K ≈ 1, фазовый сдвиг почти нулевой. При r ≈ 1 — резонанс. При r ≫ 1 инерция столба не успевает за воздействием, и колебания уровня почти не передаются.</p>
  </div>
</details>

<footer class="foot">
  <span>Модель Купера — Бредехофта — Папададопулоса, 1965</span>
  <span>ρ = 1000 кг/м³ · g = 9,81 м/с²</span>
</footer>

</div>

<script>
(function(){
"use strict";
var G=9.81, RHO=1000;

var S={mode:"free",Le:60,zeta:0.08,A0:1.5,phi0:0,Tf:20,a0:0.5,speed:1,
       t:0,running:true,env:true};

/* ---------- физика ---------- */
function der(){
  var w0=Math.sqrt(G/S.Le), T0=2*Math.PI/w0, beta=S.zeta*w0;
  var d={w0:w0,T0:T0,beta:beta,zeta:S.zeta};
  if(S.zeta<1){ d.wd=w0*Math.sqrt(1-S.zeta*S.zeta); d.Td=2*Math.PI/d.wd; }
  else { d.wd=0; d.Td=Infinity; }
  if(S.mode==="forced"){
    var w=2*Math.PI/S.Tf, r=w/w0;
    d.w=w; d.r=r;
    d.K=1/Math.sqrt(Math.pow(1-r*r,2)+Math.pow(2*S.zeta*r,2));
    d.H=S.a0*d.K;
    d.delta=Math.atan2(2*S.zeta*r,1-r*r);
  }
  return d;
}
function state(t,d){
  var h,v;
  if(S.mode==="forced"){
    var ph=d.w*t-d.delta;
    h=d.H*Math.cos(ph); v=-d.H*d.w*Math.sin(ph);
    return {h:h,v:v,drive:S.a0*Math.cos(d.w*t),env:d.H,ang:d.w*t-d.delta};
  }
  var e=Math.exp(-d.beta*t), f=S.phi0*Math.PI/180;
  if(S.zeta<1){
    var a=d.wd*t+f;
    h=S.A0*e*Math.cos(a);
    v=S.A0*e*(-d.beta*Math.cos(a)-d.wd*Math.sin(a));
    return {h:h,v:v,drive:null,env:S.A0*e,ang:a};
  }
  if(Math.abs(S.zeta-1)<1e-6){
    h=S.A0*e*(1+d.w0*t);
    v=-S.A0*d.w0*d.w0*t*e;
    return {h:h,v:v,drive:null,env:Math.abs(h),ang:0};
  }
  var s=d.w0*Math.sqrt(S.zeta*S.zeta-1);
  h=S.A0*e*(Math.cosh(s*t)+(d.beta/s)*Math.sinh(s*t));
  v=-S.A0*d.w0*d.w0*e*Math.sinh(s*t)/s;
  return {h:h,v:v,drive:null,env:Math.abs(h),ang:0};
}
function scaleAmp(d){
  if(S.mode==="forced") return Math.min(Math.max(d.H,S.a0),8);
  return S.A0;
}

/* ---------- палитра ---------- */
var C={};
function readTheme(){
  var cs=getComputedStyle(document.documentElement);
  ["ink","muted","line","water","water-soft","sand","clay","accent","hot","grid","panel","panel-2"]
    .forEach(function(k){ C[k]=cs.getPropertyValue("--"+k).trim(); });
}
readTheme();
if(window.matchMedia) try{ window.matchMedia("(prefers-color-scheme: dark)").addEventListener("change",readTheme); }catch(e){}

/* ---------- canvas ---------- */
var scene=document.getElementById("scene"), sx=scene.getContext("2d");
var graph=document.getElementById("graph"), gx=graph.getContext("2d");
function fit(cv,ctx){
  var r=cv.getBoundingClientRect();
  var dpr=Math.min(window.devicePixelRatio||1,2);
  var w=Math.max(1,Math.round(r.width)), h=Math.max(1,Math.round(r.height));
  if(cv.width!==w*dpr||cv.height!==h*dpr){cv.width=w*dpr;cv.height=h*dpr;}
  ctx.setTransform(dpr,0,0,dpr,0,0);
  ctx.clearRect(0,0,w,h);
  return {w:w,h:h};
}
function fnt(ctx,size,weight){ ctx.font=(weight||400)+" "+size+'px "Segoe UI",Roboto,Arial,sans-serif'; }
function line(ctx,x1,y1,x2,y2){ctx.beginPath();ctx.moveTo(x1,y1);ctx.lineTo(x2,y2);ctx.stroke();}

/* ---------- разрез ---------- */
function drawScene(st,d){
  var m=fit(scene,sx), w0=m.w, h=m.h;
  var axisW=Math.max(34,Math.min(0.075*w0,50));
  var w=w0-axisW, ox=axisW;
  var yG=0.11*h, yAdT=0.30*h, yAdB=0.44*h, yAqT=0.44*h, yAqB=0.70*h;
  var wellW=Math.max(24,Math.min(0.07*w,40));
  var wx=Math.max(50,0.20*w), wl=ox+wx-wellW/2, wr=ox+wx+wellW/2;
  var y0=0.205*h;
  var amp=scaleAmp(d);
  var mScale=(0.075*h)/Math.max(amp,1e-3);
  var hy=y0-st.h*mScale;
  hy=Math.max(yG-0.05*h,Math.min(hy,yAdT-6));

  /* глубины слоёв (масштаб зависит от Le — геология "дышит" вместе со столбом) */
  var dVad=3+0.07*S.Le, dConf=dVad+4+0.10*S.Le, dAq=dConf+6+0.20*S.Le;

  /* --- пласты --- */
  sx.fillStyle=C["panel-2"]; sx.fillRect(ox,0,w,yG);
  sx.fillStyle=C.sand; sx.globalAlpha=.26; sx.fillRect(ox,yG,w,yAdT-yG); sx.globalAlpha=1;
  sx.save(); sx.beginPath(); sx.rect(ox,yG,w,yAdT-yG); sx.clip();
  sx.fillStyle=C.clay; sx.globalAlpha=.5;
  for(var vy=yG+7;vy<yAdT;vy+=10) for(var vx=ox+6+((vy%20<10)?5:0);vx<ox+w;vx+=15){
    sx.beginPath(); sx.arc(vx,vy,1,0,7); sx.fill();
  }
  sx.globalAlpha=1; sx.restore();
  sx.strokeStyle=C.line; sx.lineWidth=1.5; line(sx,ox,yG,ox+w,yG);

  sx.fillStyle=C.clay; sx.globalAlpha=.55; sx.fillRect(ox,yAdT,w,yAdB-yAdT); sx.globalAlpha=1;
  sx.save(); sx.beginPath(); sx.rect(ox,yAdT,w,yAdB-yAdT); sx.clip();
  sx.strokeStyle=C.line; sx.lineWidth=1; sx.globalAlpha=.65;
  for(var i=-h;i<w+h;i+=10) line(sx,ox+i,yAdB,ox+i+(yAdB-yAdT),yAdT);
  sx.globalAlpha=1; sx.restore();
  sx.strokeStyle=C.line; sx.lineWidth=1; line(sx,ox,yAdT,ox+w,yAdT); line(sx,ox,yAdB,ox+w,yAdB);

  sx.fillStyle=C["water-soft"]; sx.globalAlpha=.4; sx.fillRect(ox,yAqT,w,yAqB-yAqT); sx.globalAlpha=1;
  sx.fillStyle=C.sand;
  for(var yy=yAqT+7;yy<yAqB-3;yy+=11) for(var xx=ox+7+((yy%22<11)?5:0);xx<ox+w;xx+=14){
    sx.globalAlpha=.8; sx.beginPath(); sx.arc(xx,yy,1.6,0,7); sx.fill();
  }
  sx.globalAlpha=1;
  sx.strokeStyle=C.line; sx.lineWidth=1; sx.setLineDash([2,3]); line(sx,ox,yAqT,ox+w,yAqT); sx.setLineDash([]);

  sx.fillStyle=C.clay; sx.globalAlpha=.55; sx.fillRect(ox,yAqB,w,h-yAqB); sx.globalAlpha=1;
  sx.save(); sx.beginPath(); sx.rect(ox,yAqB,w,h-yAqB); sx.clip();
  sx.strokeStyle=C.line; sx.globalAlpha=.65;
  for(var j=-h;j<w+h;j+=10) line(sx,ox+j,h,ox+j+(h-yAqB),yAqB);
  sx.globalAlpha=1; sx.restore();
  sx.strokeStyle=C.line; sx.lineWidth=1; line(sx,ox,yAqB,ox+w,yAqB);

  /* --- шкала глубин --- */
  sx.strokeStyle=C.ink; sx.globalAlpha=.7; sx.lineWidth=1; line(sx,ox-1,yG-0.05*h,ox-1,h);
  var ticks=[[yG,0],[yAdT,dVad],[yAdB,dConf],[yAqB,dAq]];
  fnt(sx,10.5); sx.globalAlpha=1; sx.fillStyle=C.muted; sx.textAlign="right"; sx.textBaseline="middle";
  ticks.forEach(function(tk){
    sx.strokeStyle=C.ink; sx.globalAlpha=.7; sx.lineWidth=1;
    line(sx,ox-6,tk[0],ox-1,tk[0]);
    sx.globalAlpha=1; sx.fillText(Math.round(tk[1])+" м",ox-9,tk[0]);
  });
  fnt(sx,10,600); sx.save(); sx.translate(11,(yG+yAqB)/2); sx.rotate(-Math.PI/2);
  sx.textAlign="center"; sx.fillStyle=C.muted; sx.fillText("глубина",0,0); sx.restore();

  /* --- скважина: обвязка, обсадка, фильтр, гравийная обсыпка --- */
  var wellTop=yG-0.06*h;
  /* гравийная обсыпка вокруг фильтра */
  sx.fillStyle=C.sand; sx.globalAlpha=.5;
  for(var gy=yAqT+3;gy<yAqB-3;gy+=6) for(var side=-1;side<=1;side+=2){
    var gx=side>0?wr+3+((gy%12<6)?3:0):wl-3-((gy%12<6)?3:0);
    sx.beginPath(); sx.arc(gx,gy,1.4,0,7); sx.fill();
  }
  sx.globalAlpha=1;
  /* обсадная колонна (фон под водой) */
  sx.fillStyle=C.panel; sx.fillRect(wl,wellTop,wellW,yAqT-wellTop);
  /* вода в стволе */
  var grd=sx.createLinearGradient(0,hy,0,yAqB);
  grd.addColorStop(0,C.water); grd.addColorStop(1,C["water-soft"]);
  sx.fillStyle=grd; sx.fillRect(wl+2,hy,wellW-4,yAqB-hy);
  /* лёгкая штриховка толщи воды для объёма */
  sx.save(); sx.beginPath(); sx.rect(wl+2,hy,wellW-4,yAqB-hy); sx.clip();
  sx.strokeStyle="#ffffff"; sx.globalAlpha=.12; sx.lineWidth=1;
  for(var wv=-40;wv<wellW+40;wv+=6) line(sx,wl+wv,hy,wl+wv-30,yAqB);
  sx.globalAlpha=1; sx.restore();
  /* обсадные трубы (двойная линия — реалистичная толщина стенки) */
  sx.strokeStyle=C.ink; sx.globalAlpha=.75; sx.lineWidth=2;
  line(sx,wl,wellTop,wl,yAqT); line(sx,wr,wellTop,wr,yAqT);
  sx.lineWidth=1; sx.globalAlpha=.35;
  line(sx,wl-2.5,wellTop,wl-2.5,yAqT); line(sx,wr+2.5,wellTop,wr+2.5,yAqT);
  sx.globalAlpha=1;
  /* оголовок скважины (колонка + крышка) */
  sx.fillStyle=C.ink; sx.globalAlpha=.85;
  sx.fillRect(wl-5,wellTop-8,wellW+10,8);
  sx.globalAlpha=1;
  sx.strokeStyle=C.ink; sx.lineWidth=1; sx.strokeRect(wl-5,wellTop-8,wellW+10,8);
  fnt(sx,10.5,600); sx.fillStyle=C.muted; sx.textAlign="left"; sx.textBaseline="bottom";
  sx.fillText("скв. Р-1",wl-5,wellTop-11);
  /* щелевой фильтр — короткие прорези в трубе против пласта */
  sx.strokeStyle=C.ink; sx.globalAlpha=.55; sx.lineWidth=1.3;
  for(var f=yAqT+4;f<yAqB-2;f+=6){ line(sx,wl,f,wl+6,f); line(sx,wr,f,wr-6,f); }
  sx.globalAlpha=1;
  sx.strokeStyle=C.ink; sx.globalAlpha=.75; sx.lineWidth=2;
  line(sx,wl,yAqT,wl,yAqB); line(sx,wr,yAqT,wr,yAqB); sx.globalAlpha=1;
  /* мениск */
  sx.strokeStyle="#ffffff"; sx.globalAlpha=.9; sx.lineWidth=2;
  line(sx,wl+2,hy,wr-2,hy); sx.globalAlpha=1;

  /* статический уровень */
  sx.strokeStyle=C.muted; sx.lineWidth=1.2; sx.setLineDash([6,5]);
  line(sx,ox+6,y0,ox+w-6,y0); sx.setLineDash([]);
  fnt(sx,11.5); sx.fillStyle=C.muted; sx.textAlign="left"; sx.textBaseline="bottom";
  sx.fillText("статический напорный уровень",wr+10,y0-4);

  /* стрелка смещения */
  if(Math.abs(hy-y0)>3){
    var ax=wl-16;
    sx.strokeStyle=C.hot; sx.fillStyle=C.hot; sx.lineWidth=1.8;
    line(sx,ax,y0,ax,hy);
    var dir=hy<y0?-1:1;
    sx.beginPath(); sx.moveTo(ax,hy); sx.lineTo(ax-4,hy-dir*7); sx.lineTo(ax+4,hy-dir*7); sx.closePath(); sx.fill();
    fnt(sx,12,600); sx.textAlign="right"; sx.textBaseline="middle";
    sx.fillText("h = "+st.h.toFixed(2)+" м",ax-6,(y0+hy)/2);
  }

  /* фазор */
  var cx=Math.min(w-0.10*w,wx+0.42*w), R=0.075*h;
  if(cx-R>wr+70){
    sx.strokeStyle=C.line; sx.lineWidth=1;
    sx.beginPath(); sx.arc(cx,y0,R,0,7); sx.stroke();
    sx.setLineDash([3,4]); sx.strokeStyle=C.muted;
    line(sx,cx-R-6,y0,cx+R+6,y0); line(sx,cx,y0-R-6,cx,y0+R+6); sx.setLineDash([]);
    if(S.mode==="forced"){
      var rr=Math.min(S.a0,scaleAmp(d))*mScale, ad=d.w*S.t;
      sx.strokeStyle=C.sand; sx.lineWidth=1.6;
      line(sx,cx,y0,cx+rr*Math.sin(ad),y0-rr*Math.cos(ad));
    }
    var rC=Math.min(st.env,scaleAmp(d))*mScale;
    var px=cx+rC*Math.sin(st.ang), py=y0-rC*Math.cos(st.ang);
    if(S.zeta<1||S.mode==="forced"){
      sx.strokeStyle=C.water; sx.lineWidth=2.2; line(sx,cx,y0,px,py);
      sx.fillStyle=C.water; sx.beginPath(); sx.arc(px,py,4.5,0,7); sx.fill();
      sx.strokeStyle=C.water; sx.globalAlpha=.55; sx.lineWidth=1; sx.setLineDash([4,4]);
      line(sx,px,py,wr,py); sx.setLineDash([]); sx.globalAlpha=1;
    }
  }

  /* манометр */
  var dp=RHO*G*st.h/1000;
  var bx=wr+14, by=yAqT+(yAqB-yAqT)/2, bw=Math.min(150,w-bx-16);
  if(bw>90){
    sx.fillStyle=C.panel; sx.strokeStyle=C.line; sx.lineWidth=1;
    sx.beginPath(); sx.rect(bx,by-26,bw,52); sx.fill(); sx.stroke();
    fnt(sx,11); sx.fillStyle=C.muted; sx.textAlign="left"; sx.textBaseline="top";
    sx.fillText("давление на кровле, Δp",bx+9,by-21);
    fnt(sx,16,600); sx.fillStyle=dp>=0?C.water:C.hot;
    sx.fillText((dp>=0?"+":"")+dp.toFixed(1)+" кПа",bx+9,by-5);
    var mid=bx+bw/2, half=bw/2-10, fr=Math.max(-1,Math.min(1,st.h/Math.max(scaleAmp(d),1e-3)));
    sx.strokeStyle=C.line; line(sx,bx+9,by+20,bx+bw-9,by+20);
    sx.strokeStyle=dp>=0?C.water:C.hot; sx.lineWidth=4;
    line(sx,mid,by+20,mid+fr*half,by+20);
  }

  /* подписи слоёв */
  fnt(sx,11.5); sx.fillStyle=C.muted; sx.textAlign="left"; sx.textBaseline="middle";
  sx.fillText("зона аэрации",10,(yG+yAdT)/2);
  sx.fillText("водоупор",10,(yAdT+yAdB)/2);
  sx.fillStyle=C.ink;
  sx.fillText("напорный водоносный горизонт",10,yAqB-12);
}

/* ---------- график ---------- */
var trace=[];
function drawGraph(d){
  var m=fit(graph,gx), w=m.w, h=m.h;
  var L=48, R=54, T=14, B=26;
  var pw=w-L-R, ph=h-T-B;
  var Tvis=S.mode==="forced"?S.Tf:(S.zeta<1?d.Td:d.T0);
  var win=Math.max(12,Math.min(6*Tvis,400));
  var t1=S.t, t0=t1-win;
  var amp=scaleAmp(d);
  var yMax=amp*1.18;
  var X=function(t){return L+(t-t0)/win*pw;};
  var Y=function(v){return T+ph/2-v/yMax*(ph/2);};

  gx.strokeStyle=C.grid; gx.lineWidth=1;
  for(var k=0;k<=6;k++){var xx=L+pw*k/6; line(gx,xx,T,xx,T+ph);}
  for(var q=-2;q<=2;q++){var yy=Y(yMax*q/2.4); line(gx,L,yy,L+pw,yy);}
  gx.strokeStyle=C.muted; gx.lineWidth=1.3; line(gx,L,Y(0),L+pw,Y(0));

  /* огибающая */
  if(S.env&&S.mode==="free"&&S.zeta<1){
    gx.strokeStyle=C.hot; gx.globalAlpha=.55; gx.lineWidth=1.2; gx.setLineDash([5,4]);
    for(var sgn=-1;sgn<=1;sgn+=2){
      gx.beginPath();
      for(var t=Math.max(0,t0);t<=t1;t+=win/220){
        var e=sgn*S.A0*Math.exp(-d.beta*t);
        var yv=Y(e); if(t===Math.max(0,t0)) gx.moveTo(X(t),yv); else gx.lineTo(X(t),yv);
      }
      gx.stroke();
    }
    gx.setLineDash([]); gx.globalAlpha=1;
  }

  /* воздействие */
  if(S.mode==="forced"){
    gx.strokeStyle=C.sand; gx.lineWidth=1.6; gx.globalAlpha=.85; gx.beginPath();
    var first=true;
    for(var i=0;i<trace.length;i++){var p=trace[i]; if(p.t<t0)continue;
      if(first){gx.moveTo(X(p.t),Y(p.drive));first=false;} else gx.lineTo(X(p.t),Y(p.drive));}
    gx.stroke(); gx.globalAlpha=1;
  }

  /* h(t) */
  gx.strokeStyle=C.water; gx.lineWidth=2.2; gx.beginPath();
  var f2=true;
  for(var n=0;n<trace.length;n++){var pt=trace[n]; if(pt.t<t0)continue;
    var yv2=Y(Math.max(-yMax,Math.min(yMax,pt.h)));
    if(f2){gx.moveTo(X(pt.t),yv2);f2=false;} else gx.lineTo(X(pt.t),yv2);}
  gx.stroke();

  if(trace.length){
    var last=trace[trace.length-1];
    gx.fillStyle=C.water; gx.beginPath();
    gx.arc(X(last.t),Y(Math.max(-yMax,Math.min(yMax,last.h))),4,0,7); gx.fill();
  }

  /* рамка и подписи */
  gx.strokeStyle=C.line; gx.lineWidth=1; gx.strokeRect(L,T,pw,ph);
  fnt(gx,11); gx.fillStyle=C.muted;
  gx.textAlign="right"; gx.textBaseline="middle";
  for(var a=-2;a<=2;a++){var vv=yMax*a/2.4; gx.fillText(vv.toFixed(2),L-6,Y(vv));}
  gx.textAlign="left";
  for(var b=-2;b<=2;b++){var v2=yMax*b/2.4; gx.fillText((RHO*G*v2/1000).toFixed(1),L+pw+6,Y(v2));}
  gx.textAlign="center"; gx.textBaseline="top";
  for(var c=0;c<=6;c++){var tt=t0+win*c/6; gx.fillText(tt.toFixed(0)+" с",L+pw*c/6,T+ph+6);}
  gx.textAlign="left"; gx.fillText("h, м",6,2);
  gx.textAlign="right"; gx.fillText("Δp, кПа",w-4,2);
}

/* ---------- UI ---------- */
var el=function(id){return document.getElementById(id);};
function fmt(x,n){return x.toFixed(n===undefined?2:n);}

function syncLabels(){
  el("oLe").textContent=S.Le+" м";
  el("oZ").textContent=S.zeta.toFixed(2);
  el("oA").textContent=fmt(S.A0,1)+" м";
  el("oP").textContent=S.phi0+"°";
  el("oTf").textContent=fmt(S.Tf,1)+" с";
  el("oa0").textContent=fmt(S.a0,2)+" м";
  el("oS").textContent=fmt(S.speed,1)+"×";
}
function syncMode(){
  el("mFree").setAttribute("aria-pressed",S.mode==="free");
  el("mForced").setAttribute("aria-pressed",S.mode==="forced");
  Array.prototype.forEach.call(document.querySelectorAll('[data-mode]'),function(n){
    n.hidden=(n.getAttribute("data-mode")!==S.mode);
  });
  el("lK").textContent=S.mode==="forced"?"Усиление K / сдвиг δ":"Логарифм. декремент";
  el("sceneNote").textContent=S.mode==="forced"
    ? "Синий вектор — отклик пласта, песочный — внешнее воздействие. Угол между ними равен фазовому сдвигу δ."
    : "Вектор справа — фазор: его проекция на вертикаль задаёт смещение уровня h(t).";
}
function restart(){ S.t=0; trace.length=0; }

var sliders=[["Le","Le",1],["zeta","zeta",0],["A0","A0",0],["phi0","phi0",1],["Tf","Tf",0],["a0","a0",0],["speed","speed",0]];
sliders.forEach(function(s){
  var node=el(s[0]);
  node.addEventListener("input",function(){
    S[s[1]]=parseFloat(node.value);
    syncLabels();
    if(s[1]!=="speed") restart();
    if(!S.running) frame(0);
  });
});
el("mFree").addEventListener("click",function(){S.mode="free";syncMode();restart();});
el("mForced").addEventListener("click",function(){S.mode="forced";syncMode();restart();});
el("play").addEventListener("click",function(){
  S.running=!S.running;
  this.textContent=S.running?"Пауза":"Продолжить";
  this.setAttribute("aria-pressed",S.running);
  if(S.running){last=0;requestAnimationFrame(frame);}
});
el("reset").addEventListener("click",restart);
el("env").addEventListener("change",function(){S.env=this.checked;});

function preset(o){
  Object.keys(o).forEach(function(k){
    S[k]=o[k];
    var n=el(k); if(n) n.value=o[k];
  });
  syncLabels(); syncMode(); restart();
}
el("pr1").addEventListener("click",function(){preset({mode:"free",Le:40,zeta:0.06,A0:2.5,phi0:0});});
el("pr2").addEventListener("click",function(){
  var Tres=2*Math.PI*Math.sqrt(120/G);
  preset({mode:"forced",Le:120,zeta:0.05,Tf:Math.round(Tres*2)/2,a0:0.3});
});
el("pr3").addEventListener("click",function(){preset({mode:"free",Le:25,zeta:1.2,A0:2.0,phi0:0});});

/* ---------- цикл ---------- */
var last=0;
function frame(ts){
  var d=der();
  if(S.running){
    if(last) S.t+=Math.min((ts-last)/1000,0.05)*S.speed;
    last=ts;
  }
  var st=state(S.t,d);
  trace.push({t:S.t,h:st.h,drive:st.drive});
  var Tvis=S.mode==="forced"?S.Tf:(S.zeta<1?d.Td:d.T0);
  var win=Math.max(12,Math.min(6*Tvis,400));
  while(trace.length&&trace[0].t<S.t-win-1) trace.shift();

  drawScene(st,d);
  drawGraph(d);

  el("rT0").innerHTML=fmt(d.T0,2)+" <i>с</i>";
  el("rTd").innerHTML=S.zeta<1?fmt(d.Td,2)+" <i>с</i>":"—";
  el("rW0").innerHTML=fmt(d.w0,3)+" <i>рад/с</i>";
  el("rB").innerHTML=fmt(d.beta,3)+" <i>1/с</i>";
  el("rH").innerHTML=fmt(st.h,3)+" <i>м</i>";
  el("rV").innerHTML=fmt(st.v,3)+" <i>м/с</i>";
  el("rP").innerHTML=fmt(RHO*G*st.h/1000,2)+" <i>кПа</i>";
  if(S.mode==="forced") el("rK").innerHTML=fmt(d.K,2)+"× <i>/ "+fmt(d.delta*180/Math.PI,0)+"°</i>";
  else el("rK").innerHTML=S.zeta<1?fmt(2*Math.PI*S.zeta/Math.sqrt(1-S.zeta*S.zeta),3):"—";

  var Ek=0.5*RHO*S.Le*st.v*st.v, Ep=0.5*RHO*G*st.h*st.h, Et=Ek+Ep;
  var fk=Et>1e-9?Ek/Et*100:0;
  el("barK").style.width=fk.toFixed(1)+"%";
  el("barP").style.width=(100-fk).toFixed(1)+"%";
  el("bk").textContent=fk.toFixed(0)+"%";
  el("bp").textContent=(100-fk).toFixed(0)+"%";

  var note=el("regime");
  if(S.mode==="forced"){
    var r=d.r;
    if(Math.abs(r-1)<0.12&&S.zeta<0.3){note.className="note warn";note.textContent="Резонанс: T_в ≈ T₀, амплитуда отклика больше воздействия в "+fmt(d.K,1)+" раза.";}
    else if(r<0.2){note.className="note";note.textContent="Квазистатический режим (r = "+fmt(r,3)+"): пласт успевает за воздействием — так отзываются приливы и барометр.";}
    else if(r>3){note.className="note";note.textContent="Инерционный режим (r = "+fmt(r,2)+"): столб воды не успевает за быстрым воздействием, колебания подавлены.";}
    else {note.className="note";note.textContent="Отношение частот r = "+fmt(r,2)+", усиление K = "+fmt(d.K,2)+", отставание по фазе "+fmt(d.delta*180/Math.PI,0)+"°.";}
  } else {
    if(S.zeta<1) note.className="note", note.textContent="Колебательный режим (ζ < 1): амплитуда падает в e раз за "+fmt(1/d.beta,1)+" с.";
    else if(Math.abs(S.zeta-1)<0.02) note.className="note", note.textContent="Критическое затухание (ζ = 1): возврат к равновесию без колебаний за минимальное время.";
    else note.className="note", note.textContent="Апериодический режим (ζ > 1): вязкое трение гасит импульс, уровень плавно ползёт к равновесию.";
  }

  if(S.running) requestAnimationFrame(frame);
}

window.addEventListener("resize",function(){ if(!S.running) frame(0); });
syncLabels(); syncMode();
requestAnimationFrame(frame);
})();
</script>
</body>
</html>
