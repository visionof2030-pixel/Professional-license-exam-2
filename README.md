
<html lang="ar" dir="rtl">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>الملف المهني | فهد الخالدي</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
<style>
  :root{
    --primary:#1a365d;
    --accent:#2563eb;
    --green:#16a34a;
    --bg:#f5f7fa;
    --card:#ffffff;
  }
  *{box-sizing:border-box}
  body{
    margin:0;
    font-family:Tahoma, Arial, sans-serif;
    background:var(--bg);
    color:#0f172a;
    padding-right:88px;
    -webkit-font-smoothing:antialiased;
  }

  /* header */
  header{
    background:linear-gradient(135deg,var(--primary),#0f172a);
    color:white;
    padding:2.4rem 1rem;
    text-align:center;
    position:relative;
  }
  #title{margin:0;font-size:1.9rem}
  .lang-btn{
    position:fixed;
    left:18px;
    top:14px;
    background:#fff;
    color:var(--accent);
    border:0;
    padding:8px 12px;
    border-radius:8px;
    font-weight:700;
    cursor:pointer;
    z-index:1200;
    box-shadow:0 6px 18px rgba(37,99,235,.12);
  }

  /* side nav */
  nav{
    position:fixed;
    right:0;
    top:0;
    width:78px;
    height:100vh;
    background: #ffffff;
    border-left:1px solid #e6e6e6;
    z-index:1000;
  }
  .nav-container{
    display:flex;
    flex-direction:column;
    align-items:center;
    padding-top:86px;
    gap:14px;
  }
  .nav-link{
    width:64px;
    height:64px;
    display:flex;
    flex-direction:column;
    align-items:center;
    justify-content:center;
    color:var(--accent);
    text-decoration:none;
    border-radius:12px;
    font-size:12px;
    font-weight:700;
  }
  .nav-link i{font-size:16px;margin-bottom:4px}
  .nav-link.active, .nav-link:hover {
    background:var(--accent);
    color:white;
  }

  /* main layout */
  main{
    max-width:1180px;
    margin: 0 auto;
    padding: 2rem 1rem 4rem 1rem;
  }

  section{display:none;padding:28px 0}
  section.active{display:block}

  .section-title{
    text-align:center;
    color:var(--primary);
    font-size:1.7rem;
    margin-bottom:1.4rem;
  }

  .card{
    background:var(--card);
    border-radius:14px;
    box-shadow:0 10px 30px rgba(2,6,23,.06);
    padding:1.8rem;
    margin-bottom:1.6rem;
  }

  .profile-img{
    width:160px;
    height:160px;
    border-radius:50%;
    overflow:hidden;
    margin:0 auto 12px auto;
    border:4px solid var(--accent);
  }
  .profile-img img{width:100%;height:100%;object-fit:cover}

  .bio {text-align:justify;line-height:1.8;font-size:1rem}

  /* badge / band-aid style for 95 */
  .badge-wrap{display:flex;justify-content:center;margin:18px 0}
  .badge{
    display:inline-flex;
    align-items:center;
    gap:10px;
    padding:8px 28px;
    border-radius:999px;
    background:linear-gradient(90deg,#10b981,#059669);
    color:white;
    font-weight:700;
    box-shadow:0 8px 26px rgba(6,95,70,.18);
    font-size:15px;
    position:relative;
  }
  .badge::before, .badge::after{
    content:"";
    position:absolute;
    top:50%;
    width:12px;height:12px;border-radius:50%;
    background:rgba(255,255,255,.55);
    transform:translateY(-50%);
  }
  .badge::before{left:12px}
  .badge::after{right:12px}

  /* stats */
  .stats{display:grid;grid-template-columns:repeat(auto-fit,minmax(160px,1fr));gap:12px;margin-top:18px}
  .stat{background:#f8fafc;padding:14px;border-radius:10px;text-align:center;border:1px solid #e7eefc}
  .stat .num{font-size:20px;font-weight:800;color:var(--accent)}

  /* timeline (old -> new in data, visually displayed bottom-to-top) */
  .timeline{display:flex;flex-direction:column-reverse;position:relative;padding-right:40px;gap:18px}
  .timeline::before{
    content:"";
    position:absolute;
    right:14px;
    top:0;
    bottom:0;
    width:4px;background:var(--accent);border-radius:6px;
  }
  .timeline-item{
    position:relative;
    background:white;
    border-radius:12px;
    padding:14px 16px;
    margin-right:36px;
    box-shadow:0 6px 16px rgba(2,6,23,.06);
  }
  .timeline-item::after{
    content:"";
    position:absolute;
    right:-28px;
    top:20px;
    width:18px;height:18px;border-radius:50%;background:var(--accent);
  }
  .timeline-date{color:var(--accent);font-weight:700;margin-bottom:6px}

  ul{padding-inline-start:20px;margin:0}
  li{margin-bottom:8px;line-height:1.6}

  footer{background:var(--primary);color:#fff;padding:24px;text-align:center;margin-top:30px;border-top-left-radius:6px;border-top-right-radius:6px}

  /* responsive */
  @media (max-width:900px){
    body{padding-right:12px}
    nav{width:64px}
    .nav-link{width:56px;height:56px}
    main{padding-left:12px;padding-right:12px}
  }
</style>
</head>
<body>

<!-- language toggle -->
<button class="lang-btn" id="langBtn">EN</button>

<header>
  <h1 id="pageTitle">الملف المهني للمعلم فهد الخالدي</h1>
</header>

<nav aria-label="الشريط الجانبي">
  <div class="nav-container">
    <a class="nav-link active" data-section="about"><i class="fa-solid fa-user"></i><span class="nav-text">نبذة عني</span></a>
    <a class="nav-link" data-section="experience"><i class="fa-solid fa-briefcase"></i><span class="nav-text">خبراتي</span></a>
    <a class="nav-link" data-section="skills"><i class="fa-solid fa-star"></i><span class="nav-text">المهارات</span></a>
    <a class="nav-link" data-section="training"><i class="fa-solid fa-graduation-cap"></i><span class="nav-text">الدورات</span></a>
    <a class="nav-link" data-section="contact"><i class="fa-solid fa-envelope"></i><span class="nav-text">تواصل</span></a>
  </div>
</nav>

<main>

  <!-- ABOUT -->
  <section id="about" class="active" aria-labelledby="pageTitle">
    <h2 class="section-title" id="aboutTitle">نبذة عني</h2>
    <div class="card">
      <div class="profile-img"><img id="profilePic" src="https://i.ibb.co/k66psVmZ/20220817-151032.jpg" alt="فهد الخالدي"></div>
      <h3 id="name">فهد نغيمش حميد الخالدي</h3>
      <p id="jobTitle"><strong>معلم متقدم – تخصص اللغة الإنجليزية</strong></p>
      <p id="bio" class="bio">معلم لغة إنجليزية بخبرة تزيد عن 14 عامًا في التعليم العام، أعمل على تطوير الممارسات التعليمية الحديثة، وبناء بيئة صفية محفزة تنمّي التفكير النقدي والإبداعي لدى الطلاب وتخدم أهداف رؤية المملكة 2030.</p>

      <div class="badge-wrap"><div class="badge" id="badgeText">95% — حاصل على درجة 95 في التخصص</div></div>

      <div class="stats">
        <div class="stat"><div class="num" id="years">14+</div><div>سنوات خبرة</div></div>
        <div class="stat"><div class="num" id="trainHours">130+</div><div>ساعات تدريبية</div></div>
        <div class="stat"><div class="num" id="schools">3</div><div>مدن / مدارس</div></div>
      </div>
    </div>
  </section>

  <!-- EXPERIENCE -->
  <section id="experience">
    <h2 class="section-title" id="expTitle">الخبرات المهنية</h2>
    <div class="card">
      <div class="timeline" id="expTimeline">
        <!-- يتم تعبئتها بالـ JS -->
      </div>
    </div>
  </section>

  <!-- SKILLS -->
  <section id="skills">
    <h2 class="section-title" id="skillsTitle">المهارات</h2>
    <div class="card">
      <ul id="skillsList">
        <!-- JS -->
      </ul>
    </div>
  </section>

  <!-- TRAINING -->
  <section id="training">
    <h2 class="section-title" id="trainTitle">الدورات التدريبية</h2>
    <div class="card">
      <ul id="trainList">
        <!-- JS -->
      </ul>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact">
    <h2 class="section-title" id="contactTitle">تواصل</h2>
    <div class="card" style="text-align:center">
      <p id="contactEmail">📧 iFahadenglish@gmail.com</p>
    </div>
  </section>

</main>

<footer id="footerText">© جميع الحقوق محفوظة - فهد الخالدي</footer>

<script>
/* ===== البيانات بالعربية والإنجليزية ===== */
const contentAR = {
  pageTitle: "الملف المهني للمعلم فهد الخالدي",
  aboutTitle: "نبذة عني",
  name: "فهد نغيمش حميد الخالدي",
  jobTitle: "معلم متقدم – تخصص اللغة الإنجليزية",
  bio: "معلم لغة إنجليزية بخبرة تزيد عن 14 عامًا في التعليم العام. أسعى لتطوير الممارسات التعليمية الحديثة وبناء بيئة صفية محفزة تنمّي التفكير النقدي والإبداعي لدى الطلاب، كما أعمل على الارتقاء بجودة التعلم بما يتوافق مع رؤية المملكة 2030.",
  badge: "95% — حاصل على درجة 95 في التخصص",
  years: "14+",
  trainHours: "130+",
  schools: "3",
  expTitle: "الخبرات المهنية",
  experiences: [
    {date:"2012 - 2011", title:"مترجم - وزارة الحج والعمرة", place:"مكة المكرمة"},
    {date:"2014 - 2012", title:"معلم لغة إنجليزية - سعيد بن زيد", place:"عفيف"},
    {date:"2016 - 2015", title:"معلم لغة إنجليزية – ثانوية الأمير سعود بن عبدالمحسن", place:"الليث – تعليم الليث"},
    {date:"الآن - 2017", title:"معلم لغة إنجليزية - سعيد بن العاص", place:"مكة المكرمة – تعليم مكة"}
  ],
  skillsTitle: "المهارات",
  skills:[
    "إتقان اللغة الإنجليزية تحدثًا وكتابة",
    "تطوير وتنفيذ خطط تدريس محفزة ومبتكرة",
    "إدارة الصفوف بفاعلية وتشجيع التعلم الذاتي",
    "استخدام أدوات القياس والتقويم الإلكترونية بدقة",
    "دمج مهارات التفكير النقدي والإبداعي في التعليم",
    "شغف مستمر بتعلم اللغات واكتساب مهارات جديدة",
    "القدرة على التعليم في بيئات متعددة الثقافات مع استعداد لتعلم لغات إضافية مثل الصينية"
  ],
  trainTitle: "الدورات التدريبية",
  trainings:[
    "التفكير الناقد والإبداعي ودمجه في المواد الدراسية",
    "القياس والتقويم التربوي",
    "الاستراتيجية الحديثة في تدريس أساسيات اللغة الإنجليزية",
    "البيئة الصفية الجاذبة",
    "تحليل أداء الطلاب وتقديم التغذية الراجعة",
    "أساسيات الترجمة",
    "مهارات التعامل مع أدوات القياس والتقويم الإلكترونية",
    "التنمية المهنية لمعلمي اللغة الإنجليزية - المستوى الثالث",
    "العبقرية في العملية التعليمية",
    "بناء الاختيار الجيد",
    "توظيف استراتيجيات التعليم في البيئة التدريبية الجاذبة",
    "تدريس مهارتي التحدث والاستماع",
    "التوعية بقواعد السلوك والمواظبة المحدثة",
    "اللقاءات التخصصية لمادة اللغة الإنجليزية"
  ],
  contactTitle: "تواصل",
  contactEmail: "📧 iFahadenglish@gmail.com",
  footer: "© جميع الحقوق محفوظة - فهد الخالدي",
  nav: { about:"نبذة عني", experience:"خبراتي", skills:"المهارات", training:"الدورات", contact:"تواصل" }
};

const contentEN = {
  pageTitle: "Professional Portfolio - Fahad Al Khaldi",
  aboutTitle: "About Me",
  name: "Fahad Naghimish Hamid AlKhaldi",
  jobTitle: "Senior English Teacher",
  bio: "An English teacher with over 14 years of experience in public education. I work on developing modern teaching practices and building an engaging classroom environment that nurtures critical and creative thinking in students, in line with Saudi Vision 2030.",
  badge: "95% — Achieved a 95 score in specialization",
  years: "14+",
  trainHours: "130+",
  schools: "3",
  expTitle: "Professional Experience",
  experiences: [
    {date:"2011 - 2012", title:"Translator - Ministry of Hajj & Umrah", place:"Makkah"},
    {date:"2012 - 2014", title:"English Teacher - Saeed Bin Zaid", place:"Afif"},
    {date:"2015 - 2016", title:"English Teacher - Prince Saud Secondary School", place:"Al-Laith"},
    {date:"2017 - Present", title:"English Teacher - Saeed Bin Al-Aas", place:"Makkah - Makkah Education"}
  ],
  skillsTitle: "Skills",
  skills:[
    "Mastery of English (speaking & writing)",
    "Designing and implementing engaging lesson plans",
    "Classroom management and promoting autonomous learning",
    "Accurate use of digital assessment tools",
    "Integrating critical & creative thinking into instruction",
    "Continuous passion for learning languages and new skills",
    "Ability to teach in multicultural environments; willing to learn languages such as Chinese"
  ],
  trainTitle: "Training Courses",
  trainings:[
    "Critical & Creative Thinking and integration into subjects",
    "Educational Measurement & Assessment",
    "Modern strategies in teaching English fundamentals",
    "Attractive classroom environments",
    "Student performance analysis & feedback",
    "Basics of Translation",
    "Using digital assessment tools",
    "Professional development for English teachers - Level 3",
    "Genius in the educational process",
    "Building good multiple-choice items",
    "Using teaching strategies in attractive training environments",
    "Teaching speaking & listening skills",
    "Awareness of behavior & attendance rules",
    "Specialized English subject meetings"
  ],
  contactTitle: "Contact",
  contactEmail: "📧 iFahadenglish@gmail.com",
  footer: "© All rights reserved - Fahad Al Khaldi",
  nav: { about:"About", experience:"Experience", skills:"Skills", training:"Training", contact:"Contact" }
};

/* ===== العناصر الأساسية ===== */
const pageTitle = document.getElementById('pageTitle');
const aboutTitle = document.getElementById('aboutTitle');
const nameEl = document.getElementById('name');
const jobTitleEl = document.getElementById('jobTitle');
const bioEl = document.getElementById('bio');
const badgeEl = document.getElementById('badgeText');
const yearsEl = document.getElementById('years');
const trainHoursEl = document.getElementById('trainHours');
const schoolsEl = document.getElementById('schools');
const expTimeline = document.getElementById('expTimeline');
const skillsList = document.getElementById('skillsList');
const trainList = document.getElementById('trainList');
const expTitle = document.getElementById('expTitle');
const skillsTitle = document.getElementById('skillsTitle');
const trainTitle = document.getElementById('trainTitle');
const contactTitle = document.getElementById('contactTitle');
const contactEmail = document.getElementById('contactEmail');
const footerText = document.getElementById('footerText');
const langBtn = document.getElementById('langBtn');

/* الحالة الحالية */
let isArabic = true;

/* تحميل البيانات للغة المحددة */
function loadContent(data){
  pageTitle.textContent = data.pageTitle;
  aboutTitle.textContent = data.aboutTitle;
  nameEl.textContent = data.name;
  jobTitleEl.textContent = data.jobTitle;
  bioEl.textContent = data.bio;
  badgeEl.textContent = data.badge;
  yearsEl.textContent = data.years;
  trainHoursEl.textContent = data.trainHours;
  schoolsEl.textContent = data.schools;

  expTitle.textContent = data.expTitle;
  // experiences: render in chronological order (old -> new) so timeline column-reverse shows newest at top
  expTimeline.innerHTML = data.experiences.map(item => {
    return `<div class="timeline-item">
              <div class="timeline-date">${item.date}</div>
              <div class="timeline-title"><strong>${item.title}</strong></div>
              <div class="timeline-place">${item.place}</div>
            </div>`;
  }).join("");

  skillsTitle.textContent = data.skillsTitle;
  skillsList.innerHTML = data.skills.map(s=>`<li>${s}</li>`).join("");

  trainTitle.textContent = data.trainTitle;
  trainList.innerHTML = data.trainings.map(t=>`<li>${t}</li>`).join("");

  contactTitle.textContent = data.contactTitle;
  contactEmail.textContent = data.contactEmail;
  footerText.textContent = data.footer;

  // nav labels
  document.querySelectorAll('.nav-link').forEach(link=>{
    const key = link.getAttribute('data-section'); // about, experience, skills, training, contact
    link.querySelector('.nav-text').textContent = data.nav[key];
  });
}

/* initial load */
loadContent(contentAR);

/* toggle language */
langBtn.addEventListener('click', ()=>{
  isArabic = !isArabic;
  langBtn.textContent = isArabic ? 'EN' : 'AR';
  loadContent(isArabic?contentAR:contentEN);
  // also adjust dir and lang attributes
  document.documentElement.lang = isArabic ? 'ar':'en';
  document.documentElement.dir = isArabic ? 'rtl':'ltr';
  // for small UX: when switching to en, scroll to top to avoid layout shifts
  window.scrollTo({top:0,behavior:'smooth'});
});

/* ===== nav functionality fix (reliable) ===== */
document.querySelectorAll('.nav-link').forEach(link=>{
  link.addEventListener('click', function(e){
    e.preventDefault();
    // remove active
    document.querySelectorAll('.nav-link').forEach(l=>l.classList.remove('active'));
    document.querySelectorAll('section').forEach(s=>s.classList.remove('active'));

    // add to clicked
    this.classList.add('active');
    const target = this.getAttribute('data-section');
    const section = document.getElementById(target);
    if(section){ section.classList.add('active'); }
    window.scrollTo({top:0, behavior:'smooth'});
  });
});

/* Accessibility: show sections on load if none active (fallback) */
if(!document.querySelector('section.active')){
  document.getElementById('about').classList.add('active');
}
</script>
</body>
</html>
