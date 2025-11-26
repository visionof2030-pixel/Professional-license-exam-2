<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<title>الملف المهني للمعلم فهد الخالدي</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
:root{
--main:#2563eb;
--dark:#0f172a;
--bg:#f5f7fa;
}

body{
margin:0;
font-family:Tahomaly,Arial;
background:var(--bg);
padding-right:80px;
}

header{
background:linear-gradient(135deg,#1a365d,#0f172a);
color:white;
padding:2.5rem;
text-align:center;
}

nav{
position:fixed;
top:0;
right:0;
width:78px;
height:100vh;
background:white;
border-left:1px solid #ddd;
z-index:999;
}

.nav-container{
display:flex;
flex-direction:column;
align-items:center;
padding-top:90px;
gap:20px;
}

.nav-link{
width:65px;
height:64px;
font-size:13px;
font-weight:bold;
border-radius:16px;
color:#2563eb;
display:flex;
align-items:center;
justify-content:center;
flex-direction:column;
text-decoration:none;
}

.nav-link.active,.nav-link:hover{
background:#2563eb;
color:white;
}

main{
width:95%;
max-width:1200px;
margin:auto;
}

section{
display:none;
padding:4rem 0;
}

section.active{
display:block;
}

.section-title{
text-align:center;
font-size:2rem;
margin-bottom:2rem;
color:#1a365d;
}

.card{
background:white;
border-radius:18px;
padding:2rem;
box-shadow:0 8px 18px rgba(0,0,0,.1);
}

.profile-img{
width:160px;
height:160px;
border-radius:50%;
overflow:hidden;
margin:auto;
border:4px solid var(--main);
}

.profile-img img{
width:100%;
height:100%;
object-fit:cover;
}

.stats{
margin-top:25px;
display:grid;
grid-template-columns:repeat(3,1fr);
gap:15px;
}

.stat-box{
background:#f8fafc;
padding:15px;
text-align:center;
border-radius:14px;
border:1px solid #ddd;
}

.stat-number{
font-size:26px;
color:#2563eb;
font-weight:bold;
}

.badge{
margin:25px auto;
width:140px;
height:60px;
border-radius:40px;
border:5px solid #16a34a;
display:flex;
align-items:center;
justify-content:center;
font-weight:bold;
font-size:22px;
color:#16a34a;
}

/* ✅ الخط الزمني من أسفل إلى أعلى */
.timeline{
position:relative;
margin-top:30px;
padding-right:40px;
}

.timeline::before{
content:'';
position:absolute;
right:10px;
top:0;
width:4px;
height:100%;
background:#2563eb;
}

.timeline-item{
background:white;
border-radius:18px;
padding:20px;
margin-bottom:30px;
margin-right:30px;
box-shadow:0 5px 15px rgba(0,0,0,.1);
}

.timeline-item::before{
content:'';
position:absolute;
right:-34px;
top:35px;
width:22px;
height:22px;
background:#2563eb;
border-radius:50%;
}

ul{padding-right:20px;}

footer{
background:#1a365d;
color:white;
padding:2rem;
text-align:center;
margin-top:3rem;
}

/* ✅ زر اللغة */
.lang-btn{
position:fixed;
top:15px;
left:15px;
background:#2563eb;
color:white;
border:none;
padding:10px 16px;
border-radius:10px;
font-weight:bold;
cursor:pointer;
}
</style>
</head>

<body>

<button class="lang-btn" onclick="toggleLang()">EN</button>

<header>
<h1 id="title">الملف المهني للمعلم فهد الخالدي</h1>
</header>

<nav>
<div class="nav-container">
<a class="nav-link active" data-section="about"><i class="fa-solid fa-user"></i>نبذة عني</a>
<a class="nav-link" data-section="experience"><i class="fa-solid fa-briefcase"></i>خبراتي</a>
<a class="nav-link" data-section="skills"><i class="fa-solid fa-star"></i>المهارات</a>
<a class="nav-link" data-section="training"><i class="fa-solid fa-graduation-cap"></i>الدورات</a>
<a class="nav-link" data-section="contact"><i class="fa-solid fa-envelope"></i>تواصل</a>
</div>
</nav>

<main>

<section id="about" class="active">
<h2 class="section-title">نبذة عني</h2>
<div class="card" style="text-align:center">

<div class="profile-img">
<img src="https://i.ibb.co/k66psVmZ/20220817-151032.jpg">
</div>

<h3>فهد نغيمش حميد الخالدي</h3>
<p><b>معلم متقدم – لغة إنجليزية</b></p>

<p>
معلم لغة إنجليزية بخبرة تزيد عن 14 عامًا في التعليم العام، أعمل على تطوير الممارسات التعليمية الحديثة، وربط التعليم برؤية المملكة 2030، وأسعى باستمرار للتميز والابتكار في أساليب التدريس، وتحقيق تعلم عميق وفعّال للطلاب.
</p>

<div class="badge">95%</div>

<div class="stats">
<div class="stat-box"><div class="stat-number">14+</div>سنوات خبرة</div>
<div class="stat-box"><div class="stat-number">130+</div>ساعات تدريبية</div>
<div class="stat-box"><div class="stat-number">3</div>مناطق تعليم</div>
</div>

</div>
</section>

<section id="experience">
<h2 class="section-title">الخبرات المهنية</h2>

<div class="timeline">

<div class="timeline-item">
الآن – 2017<br>
معلم لغة إنجليزية - سعيد بن العاص<br>
مكة المكرمة – تعليم مكة
</div>

<div class="timeline-item">
2016 – 2015<br>
معلم لغة إنجليزية – ثانوية الأمير سعود بن عبدالمحسن<br>
الليث – تعليم الليث
</div>

<div class="timeline-item">
2014 – 2012<br>
معلم لغة إنجليزية – سعيد بن زيد<br>
عفيف
</div>

<div class="timeline-item">
2012 – 2011<br>
مترجم – وزارة الحج والعمرة<br>
مكة المكرمة
</div>

</div>
</section>

<section id="skills">
<h2 class="section-title">المهارات</h2>
<div class="card">
<ul>
<li>إتقان اللغة الإنجليزية تحدثًا وكتابة</li>
<li>التخطيط التدريسي الإبداعي</li>
<li>إدارة الصف بفاعلية</li>
<li>التقويم الإلكتروني</li>
<li>دمج التفكير النقدي</li>
<li>العمل في بيئات متعددة الثقافات</li>
</ul>
</div>
</section>

<section id="training">
<h2 class="section-title">الدورات</h2>
<div class="card">
<ul>
<li>التفكير الناقد والإبداعي</li>
<li>القياس والتقويم التربوي</li>
<li>أساسيات الترجمة</li>
<li>البيئة الصفية الجاذبة</li>
<li>اللقاءات التخصصية لمادة اللغة الإنجليزية</li>
</ul>
</div>
</section>

<section id="contact">
<h2 class="section-title">تواصل</h2>
<div class="card" style="text-align:center">
📧 iFahadenglish@gmail.com
</div>
</section>

</main>

<footer>
© جميع الحقوق محفوظة - فهد الخالدي
</footer>

<script>

/* ✅ التنقل بين الأقسام */
document.querySelectorAll('.nav-link').forEach(link=>{
link.onclick=()=>{
document.querySelectorAll('.nav-link').forEach(l=>l.classList.remove('active'));
document.querySelectorAll('section').forEach(s=>s.classList.remove('active'));
link.classList.add('active');
document.getElementById(link.dataset.section).classList.add('active');
window.scrollTo({top:0,behavior:"smooth"});
};
});

/* ✅ زر اللغة */
let ar=true;
function toggleLang(){
const btn=document.querySelector('.lang-btn');
ar=!ar;
btn.innerText=ar?'EN':'AR';
}

</script>

</body>
</html>
