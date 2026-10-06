<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>TEAM STX — اقرأ. اكتشف. استمتع</title>
<style>
:root{--bg:#111216;--bg2:#17181D;--card:#1C1D23;--ac:#E62F4F;--ac2:#FF405F;--tx:#fff;--mu:#A1A1AA;--bd:#292A30;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box;margin:0}
body{background:var(--bg);color:var(--tx);font-family:Tahoma,"Segoe UI",Arial,sans-serif;line-height:1.5}
a{color:inherit;text-decoration:none}
header{position:sticky;top:env(safe-area-inset-top,0px);z-index:10;background:var(--bg2);border-bottom:1px solid var(--bd);display:flex;align-items:center;gap:8px;padding:10px 14px}
.logo{display:flex;align-items:center;gap:8px;font-weight:800;font-size:18px;margin-inline-end:auto}
.logo i{background:linear-gradient(135deg,var(--ac),var(--ac2));border-radius:8px;padding:2px 8px;font-style:normal;letter-spacing:1px}
.ib{background:var(--card);border:1px solid var(--bd);color:var(--tx);border-radius:10px;width:38px;height:38px;font-size:16px;cursor:pointer;position:relative}
.ib b{position:absolute;top:-4px;left:-4px;background:var(--ac);border-radius:9px;font-size:10px;padding:0 5px}
.rw{background:var(--ac);border:0;color:#fff;border-radius:10px;padding:0 12px;height:38px;font-weight:700;cursor:pointer}
#search{display:none;padding:10px 14px;background:var(--bg2)}
#search input{width:100%;padding:12px;border-radius:10px;border:1px solid var(--bd);background:var(--card);color:#fff;font-size:15px}
#res{padding:6px 0}
#res a{display:flex;gap:10px;padding:8px;border-radius:8px}#res a:hover{background:var(--card)}
#res small{color:var(--mu)}
nav#menu{display:none;background:var(--bg2);padding:8px 14px;border-bottom:1px solid var(--bd);grid-template-columns:repeat(auto-fill,minmax(130px,1fr));gap:4px}
nav#menu a{padding:8px;border-radius:8px;color:var(--mu)}nav#menu a:hover{color:#fff;background:var(--card)}
main{max-width:1200px;margin:auto;padding:14px}
.hero{position:relative;border-radius:16px;overflow:hidden;height:320px}
.slide{position:absolute;inset:0;display:flex;flex-direction:column;justify-content:flex-end;gap:8px;padding:22px;opacity:0;transition:opacity .6s}
.slide.on{opacity:1}
.slide h2{font-size:26px}.slide p{color:#e4e4e7;max-width:520px;font-size:14px}
.st{display:inline-block;background:var(--ac);border-radius:6px;padding:1px 10px;font-size:12px;width:fit-content}
.btn{display:inline-block;background:var(--ac);padding:9px 20px;border-radius:10px;font-weight:700;font-size:14px}
.btn.o{background:rgba(255,255,255,.12)}
.dots{position:absolute;bottom:8px;inset-inline:0;display:flex;justify-content:center;gap:6px}
.dots span{width:8px;height:8px;border-radius:5px;background:#fff6;cursor:pointer}.dots .on{background:var(--ac);width:22px}
section{margin-top:28px}
h3{font-size:19px;border-inline-start:4px solid var(--ac);padding-inline-start:10px;margin-bottom:12px}
.row{display:flex;gap:12px;overflow-x:auto;padding-bottom:8px;scroll-snap-type:x proximity}
.card{flex:0 0 140px;background:var(--card);border:1px solid var(--bd);border-radius:12px;overflow:hidden;position:relative;scroll-snap-align:start;transition:transform .2s}
.card:hover{transform:translateY(-4px)}
.cv{aspect-ratio:3/4;display:flex;align-items:flex-end;padding:8px;font-weight:800;font-size:15px;position:relative}
.card .rd{position:absolute;inset:0 0 auto 0;aspect-ratio:3/4;background:#000a;display:none;align-items:center;justify-content:center;font-weight:700;color:#fff}
.card:hover .rd{display:flex}
.in{padding:8px;font-size:13px}.in b{display:block;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.in span{color:var(--mu)}.in em{color:#fbbf24;font-style:normal;float:left}
.list{display:grid;grid-template-columns:repeat(auto-fill,minmax(280px,1fr));gap:10px}
.li{display:flex;gap:10px;align-items:center;background:var(--card);border:1px solid var(--bd);border-radius:12px;padding:8px}
.li .cv{width:48px;aspect-ratio:3/4;border-radius:8px;padding:0}
.li div:nth-child(2){flex:1;font-size:14px}.li small{color:var(--mu);display:block}
.li a{background:var(--ac);padding:5px 12px;border-radius:8px;font-size:13px}
.cats{display:flex;flex-wrap:wrap;gap:8px}
.cats a{background:var(--card);border:1px solid var(--bd);padding:8px 16px;border-radius:20px;font-size:14px}
.cats a:hover{background:var(--ac);border-color:var(--ac)}
.soc{display:flex;gap:10px;justify-content:center;flex-wrap:wrap}
.soc a{background:var(--card);border:1px solid var(--bd);padding:8px 18px;border-radius:10px}
footer{margin-top:36px;background:var(--bg2);border-top:1px solid var(--bd);padding:26px 14px;text-align:center;color:var(--mu);font-size:14px}
footer b{color:#fff;font-size:20px;display:block}
footer nav{display:flex;gap:16px;justify-content:center;flex-wrap:wrap;margin-top:12px}
@media(min-width:760px){.card{flex-basis:170px}.hero{height:420px}.slide h2{font-size:38px}}
@media(prefers-color-scheme:light){:root{}}
</style>
</head>
<body>
<header>
<button class="ib" title="الحساب" onclick="tg('acc')">👤</button>
<button class="ib" title="الإشعارات">🔔<b>3</b></button>
<button class="ib" title="بحث" onclick="tg('search')">🔍</button>
<button class="rw">🎁 المكافآت</button>
<a class="logo" href="#"><i>STX</i>TEAM STX</a>
<button class="ib" title="القائمة" onclick="tg('menu','grid')">☰</button>
</header>
<div id="acc" style="display:none;background:var(--bg2);padding:8px 14px;border-bottom:1px solid var(--bd)">
<nav style="display:flex;flex-wrap:wrap;gap:6px 18px;color:var(--mu)"><a href="#">تسجيل الدخول</a><a href="#">إنشاء حساب</a><a href="#">الملف الشخصي</a><a href="#">المفضلة</a><a href="#">سجل القراءة</a><a href="#">الإعدادات</a><a href="#">تسجيل الخروج</a></nav></div>
<div id="search"><input id="q" placeholder="ابحث بالعربية أو الإنجليزية أو العنوان الأصلي أو المؤلف…" oninput="find(this.value)"><div id="res"></div></div>
<nav id="menu"><a href="#">الرئيسية</a><a href="#">المانهوا</a><a href="#">المانجا</a><a href="#">المانهوا الصينية</a><a href="#">الويب كومكس</a><a href="#">الأكثر مشاهدة</a><a href="#">آخر الإضافات</a><a href="#">آخر الفصول</a><a href="#">الأعمال المكتملة</a><a href="#">الأعمال المستمرة</a><a href="#">التصنيفات</a><a href="#">المفضلة</a><a href="#">سجل القراءة</a><a href="#">من نحن</a><a href="#">تواصل معنا</a><a href="#">سياسة الخصوصية</a><a href="#">حقوق النشر والإعلانات</a></nav>

<main>
<div class="hero" id="hero"></div>
<section><h3>متابعة القراءة</h3><div class="list" id="cont"></div></section>
<section><h3>الأكثر مشاهدة</h3><div class="row" id="s1"></div></section>
<section><h3>آخر الإضافات</h3><div class="row" id="s2"></div></section>
<section><h3>آخر الفصول</h3><div class="list" id="s3"></div></section>
<section><h3>الأعمال المستمرة</h3><div class="row" id="s4"></div></section>
<section><h3>الأعمال المكتملة</h3><div class="row" id="s5"></div></section>
<section><h3>الأعلى تقييمًا</h3><div class="row" id="s6"></div></section>
<section><h3>مقترحة لك</h3><div class="row" id="s7"></div></section>
<section><h3>التصنيفات</h3><div class="cats" id="cats"></div></section>
<section><div class="soc"><a href="#">Discord</a><a href="#">Facebook</a><a href="#">X / Twitter</a><a href="#">TikTok</a></div></section>
</main>
<footer><b>TEAM STX</b>STX — Read. Discover. Enjoy.
<nav><a href="#">الرئيسية</a><a href="#">About Us</a><a href="#">Contact Us</a><a href="#">Privacy Policy</a><a href="#">Copyrights and Ads</a></nav></footer>

<script>
// Sample data — replace with API/database (series, chapters tables)
var S=[
{ar:"الإمبراطور السحري",en:"Magic Emperor",orig:"魔皇大管家",ch:903,r:4.8,n:2310,st:"مستمر",c:["#E62F4F","#4c1d95"],d:"إمبراطور سابق يعود ليبدأ رحلة جديدة في عالم السحر."},
{ar:"قمة الفنون القتالية",en:"Martial Peak",orig:"武炼巅峰",ch:182,r:4.6,n:1890,st:"مستمر",c:["#0ea5e9","#1e1b4b"],d:"طريق طويل نحو قمة الفنون القتالية."},
{ar:"التأليه",en:"Apotheosis",orig:"元尊",ch:1200,r:4.7,n:2750,st:"مستمر",c:["#f59e0b","#7f1d1d"],d:"رحلة نحو الألوهية عبر عوالم لا حصر لها."},
{ar:"عودة المحارب",en:"Warrior Returns",orig:"전사의 귀환",ch:120,r:4.5,n:940,st:"مكتمل",c:["#10b981","#064e3b"],d:"محارب يعود بالزمن ليصلح أخطاء الماضي."},
{ar:"نظام الصياد",en:"Hunter System",orig:"헌터 시스템",ch:210,r:4.9,n:3300,st:"مكتمل",c:["#8b5cf6","#111827"],d:"نظام غامض يغيّر مصير صياد ضعيف."},
{ar:"زارع الخلود",en:"Immortal Farmer",orig:"仙农",ch:76,r:4.3,n:520,st:"مستمر",c:["#84cc16","#14532d"],d:"مزارع بسيط يجد طريقه إلى الخلود."}
];
var $=function(i){return document.getElementById(i)};
function tg(i,d){var e=$(i);e.style.display=e.style.display==='none'||!e.style.display?(d||'block'):'none'}
function cv(s){return 'background:linear-gradient(160deg,'+s.c[0]+','+s.c[1]+')'}
function card(s){return '<a class="card" href="#"><div class="cv" style="'+cv(s)+'">'+s.en+'</div><div class="rd">اقرأ الآن</div><div class="in"><b>'+s.ar+'</b><span>الفصل '+s.ch+'</span><em>★ '+s.r+'</em></div></a>'}
function fill(id,a){$(id).innerHTML=a.map(card).join('')}
fill('s1',S);fill('s2',S.slice().reverse());
fill('s4',S.filter(function(s){return s.st==='مستمر'}));
fill('s5',S.filter(function(s){return s.st==='مكتمل'}));
fill('s6',S.slice().sort(function(a,b){return b.r-a.r}));
fill('s7',S.slice(2).concat(S.slice(0,2)));
function row(s,t,btn){return '<div class="li"><div class="cv" style="'+cv(s)+'"></div><div><b>'+s.en+'</b><small>'+t+'</small></div><a href="#">'+btn+'</a></div>'}
$('s3').innerHTML=S.map(function(s,i){return row(s,'الفصل '+s.ch+' · منذ '+(i+1)+' ساعة','اقرأ')}).join('');
$('cont').innerHTML=row(S[0],'آخر قراءة: الفصل 903','متابعة القراءة');
$('cats').innerHTML="أكشن،مغامرة،فانتازيا،كوميديا،دراما،رومانسية،فنون قتالية،تناسخ،عودة بالزمن،نظام،زراعة،خيال علمي،غموض،رعب،تاريخي،شونين،شوجو،حياة مدرسية".split('،').map(function(c){return '<a href="#">'+c+'</a>'}).join('');
// hero
var h=$('hero'),cur=0;
h.innerHTML=S.slice(0,4).map(function(s,i){return '<div class="slide'+(i?'':' on')+'" style="'+cv(s)+'"><span class="st">'+s.st+'</span><h2>'+s.ar+'</h2><p>'+s.d+'</p><div><a class="btn" href="#">اقرأ الآن</a> <a class="btn o" href="#">التفاصيل</a></div></div>'}).join('')+'<div class="dots">'+[0,1,2,3].map(function(i){return '<span data-i="'+i+'"></span>'}).join('')+'</div>';
var sl=h.querySelectorAll('.slide'),dt=h.querySelectorAll('.dots span');
function go(i){cur=i;sl.forEach(function(e,k){e.classList.toggle('on',k===i)});dt.forEach(function(e,k){e.classList.toggle('on',k===i)})}
dt.forEach(function(e){e.onclick=function(){go(+e.dataset.i)}});go(0);
setInterval(function(){go((cur+1)%sl.length)},5000);
// search across ar/en/original titles
function norm(t){return t.toLowerCase().replace(/[\u064B-\u065F]/g,'')}
function find(v){v=norm(v.trim());$('res').innerHTML=!v?'':S.filter(function(s){return norm(s.ar+' '+s.en+' '+s.orig).indexOf(v)>-1}).map(function(s){return '<a href="#"><div class="cv" style="width:40px;height:54px;padding:0;border-radius:6px;'+cv(s)+'"></div><div>'+s.ar+'<br><small>'+s.en+' · '+s.orig+' · ★ '+s.r+' · '+s.st+'</small></div></a>'}).join('')||'<small>لا نتائج</small>'}
</script>
</body>
</html>
