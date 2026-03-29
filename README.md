# banbury-cross[banbury-cross (1).html](https://github.com/user-attachments/files/26335301/banbury-cross.1.html)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Banbury Cross Educational Academy – Lucknow</title>
<link href="https://fonts.googleapis.com/css2?family=Nunito:wght@400;600;700;800;900&family=Fredoka+One&display=swap" rel="stylesheet"/>
<style>
:root{--red:#e31b2e;--red-light:#ff4d5e;--red-pale:#fff0f1;--blue:#1a4fa0;--blue-light:#2d6fd6;--blue-pale:#eef4ff;--yellow:#ffc107;--green:#28b463;--white:#ffffff;--off-white:#fafbff;--gray:#555;--light-gray:#f4f6fb;}
*{margin:0;padding:0;box-sizing:border-box;}
html{scroll-behavior:smooth;}
body{font-family:'Nunito',sans-serif;background:var(--off-white);color:#222;overflow-x:hidden;}

/* NAV */
nav{background:var(--white);position:sticky;top:0;z-index:1000;box-shadow:0 2px 16px rgba(0,0,0,.10);}
.nav-inner{max-width:1200px;margin:0 auto;display:flex;align-items:center;justify-content:space-between;padding:10px 24px;flex-wrap:wrap;gap:12px;}
.logo-wrap img{height:62px;border-radius:8px;object-fit:contain;}
.nav-links{display:flex;gap:4px;flex-wrap:wrap;list-style:none;}
.nav-links a{text-decoration:none;font-weight:700;font-size:.88rem;color:var(--blue);padding:7px 13px;border-radius:30px;transition:background .2s,color .2s;}
.nav-links a:hover{background:var(--blue);color:var(--white);}
.nav-cta{background:var(--red)!important;color:var(--white)!important;}
.nav-cta:hover{background:var(--red-light)!important;color:var(--white)!important;}

/* HERO */
.hero{background:linear-gradient(135deg,var(--blue) 0%,var(--blue-light) 55%,#1e90ff 100%);padding:88px 24px 72px;text-align:center;position:relative;overflow:hidden;}
.hero-bubbles{position:absolute;top:0;left:0;right:0;bottom:0;pointer-events:none;overflow:hidden;}
.bubble{position:absolute;border-radius:50%;opacity:.14;animation:floatUp 6s ease-in-out infinite;}
.bubble:nth-child(1){width:70px;height:70px;background:#ffc107;top:8%;left:6%;animation-delay:0s;}
.bubble:nth-child(2){width:45px;height:45px;background:#e3002b;top:62%;left:4%;animation-delay:1.3s;}
.bubble:nth-child(3){width:90px;height:90px;background:#fff;top:20%;right:8%;animation-delay:.6s;}
.bubble:nth-child(4){width:32px;height:32px;background:#ffc107;top:72%;right:7%;animation-delay:2.1s;}
.bubble:nth-child(5){width:55px;height:55px;background:#28b463;top:82%;left:42%;animation-delay:.9s;}
.bubble:nth-child(6){width:38px;height:38px;background:#fff;top:40%;left:18%;animation-delay:1.8s;}
@keyframes floatUp{0%,100%{transform:translateY(0);}50%{transform:translateY(-20px);}}
.hero-content{position:relative;z-index:2;max-width:780px;margin:0 auto;}
.hero-badge{display:inline-block;background:rgba(255,255,255,.14);color:var(--yellow);font-size:.8rem;font-weight:800;padding:6px 18px;border-radius:30px;margin-bottom:20px;border:1.5px solid rgba(255,193,7,.45);letter-spacing:1.2px;text-transform:uppercase;}
.hero h1{font-family:'Fredoka One',sans-serif;font-size:clamp(2.4rem,6vw,4rem);color:var(--white);line-height:1.1;margin-bottom:14px;}
.hero h1 span{color:var(--yellow);}
.hero-motto{font-size:clamp(1rem,2.5vw,1.25rem);color:rgba(255,255,255,.88);font-weight:600;font-style:italic;margin-bottom:36px;}
.hero-btns{display:flex;gap:14px;justify-content:center;flex-wrap:wrap;}
.btn{padding:14px 34px;border-radius:50px;font-family:'Nunito',sans-serif;font-weight:800;font-size:1rem;cursor:pointer;border:none;text-decoration:none;display:inline-block;transition:transform .2s,box-shadow .2s;}
.btn:hover{transform:translateY(-3px);box-shadow:0 8px 24px rgba(0,0,0,.18);}
.btn-primary{background:var(--yellow);color:#1a1a1a;}
.btn-outline{background:transparent;color:var(--white);border:2.5px solid rgba(255,255,255,.7);}

/* STATS */
.stats-bar{background:var(--red);padding:22px 24px;}
.stats-inner{max-width:1200px;margin:0 auto;display:flex;justify-content:space-around;flex-wrap:wrap;gap:16px;}
.stat-item{text-align:center;color:var(--white);}
.stat-num{font-family:'Fredoka One',sans-serif;font-size:2.2rem;display:block;line-height:1;}
.stat-label{font-size:.78rem;font-weight:700;opacity:.85;letter-spacing:.5px;}

/* SECTIONS */
section{padding:76px 24px;}
section[id]{scroll-margin-top:90px;}
.section-inner{max-width:1160px;margin:0 auto;}
.section-tag{display:inline-block;font-size:.72rem;font-weight:800;text-transform:uppercase;letter-spacing:2px;padding:6px 16px;border-radius:30px;margin-bottom:12px;}
.tag-red{background:var(--red-pale);color:var(--red);}
.tag-blue{background:var(--blue-pale);color:var(--blue);}
.tag-green{background:#eafaf1;color:var(--green);}
.tag-yellow{background:#fff8e1;color:#e67e00;}
.section-title{font-family:'Fredoka One',sans-serif;font-size:clamp(1.9rem,4vw,2.7rem);margin-bottom:12px;color:#1a1a2e;}
.section-subtitle{color:var(--gray);font-size:1.05rem;max-width:640px;line-height:1.75;margin-bottom:48px;}

/* ABOUT */
#about{background:var(--white);}
.about-grid{display:grid;grid-template-columns:1fr 1fr;gap:60px;align-items:center;}
.about-visual{position:relative;}
.about-card{background:linear-gradient(135deg,var(--blue-pale),#ddeeff);border-radius:28px;padding:52px 40px;text-align:center;border:2px solid rgba(26,79,160,.12);}
.about-icon-big{font-size:5.5rem;margin-bottom:16px;display:block;}
.about-card h3{font-family:'Fredoka One',sans-serif;font-size:1.5rem;color:var(--blue);margin-bottom:8px;}
.about-card p{color:var(--gray);font-size:.95rem;}
.about-badge{position:absolute;top:-16px;right:-16px;background:var(--yellow);color:#1a1a1a;font-weight:800;font-size:.78rem;padding:10px 18px;border-radius:30px;box-shadow:0 4px 12px rgba(255,193,7,.4);}
.about-text p{color:var(--gray);font-size:1rem;line-height:1.8;margin-bottom:20px;}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin-top:24px;}
.chip{background:var(--blue-pale);color:var(--blue);font-weight:700;font-size:.85rem;padding:8px 16px;border-radius:30px;border:1.5px solid rgba(26,79,160,.15);}

/* ACADEMICS */
#academics{background:var(--light-gray);}
.academics-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:24px;}
.academic-card{background:var(--white);border-radius:20px;padding:32px 24px;text-align:center;box-shadow:0 4px 20px rgba(0,0,0,.06);border-top:5px solid var(--blue);transition:transform .25s,box-shadow .25s;}
.academic-card:hover{transform:translateY(-6px);box-shadow:0 12px 36px rgba(0,0,0,.1);}
.academic-card:nth-child(2){border-top-color:var(--red);}
.academic-card:nth-child(3){border-top-color:var(--green);}
.academic-card:nth-child(4){border-top-color:var(--yellow);}
.academic-icon{font-size:3rem;margin-bottom:16px;display:block;}
.academic-card h3{font-family:'Fredoka One',sans-serif;font-size:1.2rem;color:#1a1a2e;margin-bottom:10px;}
.academic-card p{font-size:.9rem;color:var(--gray);line-height:1.65;}

/* FACILITIES */
#facilities{background:var(--white);}
.facilities-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(195px,1fr));gap:24px;}
.facility-card{border-radius:24px;padding:38px 20px;text-align:center;transition:transform .25s,box-shadow .25s;border:2px solid transparent;cursor:default;}
.facility-card:hover{transform:translateY(-7px);box-shadow:0 14px 36px rgba(0,0,0,.12);}
.fc1{background:linear-gradient(135deg,var(--blue-pale),#c5dbff);}
.fc1:hover{border-color:var(--blue-light);}
.fc2{background:linear-gradient(135deg,#fff0f1,#ffd6da);}
.fc2:hover{border-color:var(--red-light);}
.fc3{background:linear-gradient(135deg,#eafaf1,#b8f0d0);}
.fc3:hover{border-color:var(--green);}
.fc4{background:linear-gradient(135deg,#fff8e1,#ffe09a);}
.fc4:hover{border-color:var(--yellow);}
.fc5{background:linear-gradient(135deg,#f3eaff,#d9bff5);}
.fc5:hover{border-color:#9b59b6;}
.facility-icon{font-size:3.6rem;display:block;margin-bottom:16px;}
.facility-card h3{font-family:'Fredoka One',sans-serif;font-size:1.15rem;color:#1a1a2e;margin-bottom:8px;}
.facility-card p{font-size:.875rem;color:var(--gray);line-height:1.6;}

/* ADMISSIONS */
#admissions{background:var(--light-gray);}
.admissions-layout{display:grid;grid-template-columns:1fr 1.2fr;gap:56px;align-items:start;}
.steps-list{list-style:none;}
.step-item{display:flex;gap:20px;margin-bottom:28px;align-items:flex-start;}
.step-num{flex-shrink:0;width:44px;height:44px;border-radius:50%;background:var(--red);color:var(--white);font-family:'Fredoka One',sans-serif;font-size:1.1rem;display:flex;align-items:center;justify-content:center;}
.step-body h4{font-weight:800;font-size:1rem;color:#1a1a2e;margin-bottom:4px;}
.step-body p{font-size:.9rem;color:var(--gray);line-height:1.6;}
.form-card{background:var(--white);border-radius:24px;padding:36px 32px;box-shadow:0 6px 30px rgba(0,0,0,.08);}
.form-card h3{font-family:'Fredoka One',sans-serif;font-size:1.5rem;color:#1a1a2e;margin-bottom:22px;}
.form-group{margin-bottom:18px;}
.form-group label{display:block;font-weight:700;font-size:.875rem;margin-bottom:6px;color:#444;}
.form-group input,.form-group select,.form-group textarea{width:100%;padding:12px 16px;border:2px solid #e0e6f0;border-radius:12px;font-family:'Nunito',sans-serif;font-size:.95rem;color:#333;transition:border-color .2s;outline:none;background:var(--off-white);}
.form-group input:focus,.form-group select:focus,.form-group textarea:focus{border-color:var(--blue-light);background:var(--white);}
.form-group textarea{resize:vertical;min-height:88px;}
.form-submit{width:100%;padding:15px;background:var(--red);color:var(--white);font-family:'Fredoka One',sans-serif;font-size:1.1rem;border:none;border-radius:50px;cursor:pointer;transition:background .2s,transform .2s;margin-top:4px;}
.form-submit:hover{background:var(--red-light);transform:translateY(-2px);}

/* GALLERY */
#gallery{background:var(--white);}
.gallery-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;}
.gallery-item{border-radius:18px;overflow:hidden;display:flex;flex-direction:column;align-items:center;justify-content:center;min-height:180px;font-size:3.5rem;transition:transform .25s;cursor:pointer;padding:20px;}
.gallery-item:hover{transform:scale(1.03);}
.g1{background:linear-gradient(135deg,#ffd6da,#ffaab5);grid-column:span 2;min-height:220px;}
.g2{background:linear-gradient(135deg,var(--blue-pale),#b3d0ff);}
.g3{background:linear-gradient(135deg,#eafaf1,#a9edc9);}
.g4{background:linear-gradient(135deg,#fff8e1,#ffe082);}
.g5{background:linear-gradient(135deg,#f3e5f5,#ce93d8);grid-column:span 2;min-height:220px;}
.gallery-label{font-family:'Fredoka One',sans-serif;font-size:.95rem;color:rgba(0,0,0,.45);margin-top:10px;}

/* CONTACT */
#contact{background:var(--blue);}
.contact-wrap{max-width:1160px;margin:0 auto;display:grid;grid-template-columns:1fr 1fr;gap:56px;align-items:start;}
.contact-info h2{font-family:'Fredoka One',sans-serif;font-size:clamp(1.9rem,4vw,2.5rem);color:var(--white);margin-bottom:14px;}
.contact-info p{color:rgba(255,255,255,.8);font-size:1rem;line-height:1.75;margin-bottom:32px;}
.cdetail{display:flex;align-items:flex-start;gap:16px;margin-bottom:22px;}
.cicon{flex-shrink:0;width:44px;height:44px;background:rgba(255,255,255,.14);border-radius:12px;display:flex;align-items:center;justify-content:center;font-size:1.2rem;}
.ctext strong{display:block;color:var(--yellow);font-size:.78rem;text-transform:uppercase;letter-spacing:1px;margin-bottom:3px;}
.ctext span{color:rgba(255,255,255,.88);font-size:.95rem;line-height:1.5;}
.contact-card{background:var(--white);border-radius:24px;padding:36px 32px;box-shadow:0 6px 30px rgba(0,0,0,.12);}
.contact-card h3{font-family:'Fredoka One',sans-serif;font-size:1.4rem;color:var(--blue);margin-bottom:22px;}
.map-box{background:linear-gradient(135deg,var(--blue-pale),#c5dbff);border-radius:16px;height:190px;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:12px;margin-top:20px;text-align:center;padding:20px;}
.map-box span:first-child{font-size:2.8rem;}
.map-box p{font-size:.88rem;color:var(--blue);font-weight:600;}
.map-box a{font-weight:700;font-size:.88rem;color:var(--blue);text-decoration:none;background:var(--white);padding:8px 22px;border-radius:30px;border:2px solid rgba(26,79,160,.2);transition:background .2s,color .2s;}
.map-box a:hover{background:var(--blue);color:var(--white);}

/* FOOTER */
footer{background:#0e2d6b;padding:36px 24px;text-align:center;}
.footer-links{display:flex;justify-content:center;gap:20px;flex-wrap:wrap;margin-bottom:16px;}
.footer-links a{color:rgba(255,255,255,.6);text-decoration:none;font-size:.88rem;font-weight:600;transition:color .2s;}
.footer-links a:hover{color:var(--yellow);}
footer p{color:rgba(255,255,255,.45);font-size:.85rem;}
footer strong{color:rgba(255,255,255,.75);}

/* RESPONSIVE */
@media(max-width:860px){
  .about-grid,.admissions-layout,.contact-wrap{grid-template-columns:1fr;}
  .gallery-grid{grid-template-columns:1fr 1fr;}
  .g1,.g5{grid-column:span 1;min-height:160px;}
  .about-badge{top:-12px;right:8px;}
}
@media(max-width:560px){
  .gallery-grid{grid-template-columns:1fr;}
  section{padding:52px 18px;}
}
</style>
</head>
<body>

<!-- NAV -->
<nav>
  <div class="nav-inner">
    <div class="logo-wrap">
      <img src="data:image/jpeg;base64,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" alt="Banbury Cross Educational Academy Logo"/>
    </div>
    <ul class="nav-links">
      <li><a href="#about">About</a></li>
      <li><a href="#academics">Academics</a></li>
      <li><a href="#facilities">Facilities</a></li>
      <li><a href="#gallery">Gallery</a></li>
      <li><a href="#contact">Contact</a></li>
      <li><a href="#admissions" class="nav-cta">Admissions</a></li>
    </ul>
  </div>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="hero-bubbles">
    <div class="bubble"></div><div class="bubble"></div><div class="bubble"></div>
    <div class="bubble"></div><div class="bubble"></div><div class="bubble"></div>
  </div>
  <div class="hero-content">
    <div class="hero-badge">⭐ Estd. 1990 · Lucknow's Trusted Preschool</div>
    <h1>Welcome to<br/><span>Banbury Cross</span><br/>Educational Academy</h1>
    <p class="hero-motto">"Creating Great Minds for a Great Future"</p>
    <div class="hero-btns">
      <a href="#admissions" class="btn btn-primary">🎒 Apply for Admission</a>
      <a href="#about" class="btn btn-outline">Discover Our School</a>
    </div>
  </div>
</section>

<!-- STATS -->
<div class="stats-bar">
  <div class="stats-inner">
    <div class="stat-item"><span class="stat-num">30+</span><span class="stat-label">Years of Excellence</span></div>
    <div class="stat-item"><span class="stat-num">🧠</span><span class="stat-label">Multiple Intelligence Theory</span></div>
    <div class="stat-item"><span class="stat-num">🌱</span><span class="stat-label">Preschool · Nursery · KG</span></div>
    <div class="stat-item"><span class="stat-num">🏆</span><span class="stat-label">Best Personality Development</span></div>
  </div>
</div>

<!-- ABOUT -->
<section id="about">
  <div class="section-inner">
    <div class="about-grid">
      <div class="about-visual">
        <div class="about-card">
          <span class="about-icon-big">🌟</span>
          <h3>Where Little Stars Shine</h3>
          <p>A nurturing home away from home for your little one's first big adventure in learning.</p>
        </div>
        <div class="about-badge">Estd. 1990</div>
      </div>
      <div class="about-text">
        <span class="section-tag tag-blue">Who We Are</span>
        <h2 class="section-title">About Banbury Cross</h2>
        <p>Banbury Cross Educational Academy is one of Lucknow's most trusted institutions for the holistic development of young scholars. Nestled in Mahanagar, we have been nurturing curious minds since 1990.</p>
        <p>We firmly believe in the <strong>Theory of Multiple Intelligences</strong> — recognising that every child is gifted in their own unique way. Our approach focuses on personality development, creativity, and building strong foundations for lifelong learning.</p>
        <p>Our warm, energetic environment ensures that children feel safe, loved, and inspired to explore the world around them every single day.</p>
        <div class="chips">
          <span class="chip">🧠 Multiple Intelligence</span>
          <span class="chip">🎨 Creative Learning</span>
          <span class="chip">🌱 Holistic Development</span>
          <span class="chip">💛 Caring Faculty</span>
          <span class="chip">🏅 Personality Building</span>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ACADEMICS -->
<section id="academics">
  <div class="section-inner">
    <span class="section-tag tag-red">What We Teach</span>
    <h2 class="section-title">Our Academic Approach</h2>
    <p class="section-subtitle">Rooted in the Theory of Multiple Intelligences, our curriculum helps every child discover and develop their natural strengths.</p>
    <div class="academics-grid">
      <div class="academic-card">
        <span class="academic-icon">🎵</span>
        <h3>Musical Intelligence</h3>
        <p>Rhythm, songs, and music-based learning to enhance memory, pattern recognition, and emotional expression in young learners.</p>
      </div>
      <div class="academic-card">
        <span class="academic-icon">🖼️</span>
        <h3>Visual &amp; Spatial Skills</h3>
        <p>Art, drawing, and creative activities that stimulate imagination and help children visualise and understand the world.</p>
      </div>
      <div class="academic-card">
        <span class="academic-icon">🏃</span>
        <h3>Bodily-Kinaesthetic</h3>
        <p>Movement-based play and physical activities designed to develop motor skills, coordination, and body awareness.</p>
      </div>
      <div class="academic-card">
        <span class="academic-icon">📖</span>
        <h3>Language &amp; Literacy</h3>
        <p>Storytelling, rhymes, and early reading programs that build communication skills and a lifelong love for language.</p>
      </div>
    </div>
  </div>
</section>

<!-- FACILITIES -->
<section id="facilities">
  <div class="section-inner">
    <span class="section-tag tag-green">Our Campus</span>
    <h2 class="section-title">World-Class Facilities</h2>
    <p class="section-subtitle">We have created a vibrant, safe, and stimulating environment where children can learn, play, and grow every day.</p>
    <div class="facilities-grid">
      <div class="facility-card fc1">
        <span class="facility-icon">🎠</span>
        <h3>Soft Play Area</h3>
        <p>A colourful, cushioned play zone where toddlers can explore, tumble, and build motor skills in a safe, padded environment.</p>
      </div>
      <div class="facility-card fc2">
        <span class="facility-icon">🖥️</span>
        <h3>Smart Classes</h3>
        <p>Interactive digital classrooms equipped with smart boards and audio-visual tools for engaging, technology-led learning sessions.</p>
      </div>
      <div class="facility-card fc3">
        <span class="facility-icon">🌳</span>
        <h3>Outdoor Play Area</h3>
        <p>Spacious, shaded outdoor grounds with swings, slides, and open space where children enjoy fresh air and active play.</p>
      </div>
      <div class="facility-card fc4">
        <span class="facility-icon">🎭</span>
        <h3>Amphitheatre</h3>
        <p>A dedicated performance space for annual days, skits, and cultural events — nurturing confidence and stage presence from an early age.</p>
      </div>
      <div class="facility-card fc5">
        <span class="facility-icon">🧩</span>
        <h3>Activity Rooms</h3>
        <p>Purpose-built rooms for arts &amp; crafts, music, and group activities designed to spark creativity and teamwork in little ones.</p>
      </div>
    </div>
  </div>
</section>

<!-- ADMISSIONS -->
<section id="admissions">
  <div class="section-inner">
    <div class="admissions-layout">
      <div>
        <span class="section-tag tag-red">Join Our Family</span>
        <h2 class="section-title">Admissions Open</h2>
        <p class="section-subtitle">Enrol your little one in an environment where they will be celebrated, challenged, and cheered on every step of the way.</p>
        <ul class="steps-list">
          <li class="step-item">
            <div class="step-num">1</div>
            <div class="step-body"><h4>Enquire &amp; Visit</h4><p>Call us or fill the form to schedule a campus tour. See our facilities and meet our faculty in person.</p></div>
          </li>
          <li class="step-item">
            <div class="step-num">2</div>
            <div class="step-body"><h4>Submit Application</h4><p>Complete the simple registration form with your child's details and required documents.</p></div>
          </li>
          <li class="step-item">
            <div class="step-num">3</div>
            <div class="step-body"><h4>Interaction Session</h4><p>A friendly, relaxed session where we get to know your child's interests and personality.</p></div>
          </li>
          <li class="step-item">
            <div class="step-num">4</div>
            <div class="step-body"><h4>Welcome Aboard! 🎉</h4><p>Complete enrolment formalities and prepare your little star for their exciting new adventure!</p></div>
          </li>
        </ul>
      </div>
      <div class="form-card">
        <h3>📋 Enquiry Form</h3>
        <div class="form-group"><label>Parent / Guardian Name</label><input id="enq-parent" type="text" placeholder="Your full name"/></div>
        <div class="form-group"><label>Child's Name</label><input id="enq-child" type="text" placeholder="Child's full name"/></div>
        <div class="form-group"><label>Phone Number</label><input id="enq-phone" type="tel" placeholder="+91 XXXXX XXXXX"/></div>
        <div class="form-group"><label>Email Address</label><input id="enq-email" type="email" placeholder="your@email.com"/></div>
        <div class="form-group">
          <label>Applying For</label>
          <select id="enq-programme">
            <option value="">Select programme</option>
            <option>Playgroup (1.5 – 2.5 yrs)</option>
            <option>Nursery (2.5 – 3.5 yrs)</option>
            <option>LKG (3.5 – 4.5 yrs)</option>
            <option>UKG (4.5 – 5.5 yrs)</option>
          </select>
        </div>
        <div class="form-group"><label>Message (optional)</label><textarea id="enq-msg" placeholder="Any questions or special requirements..."></textarea></div>
        <button class="form-submit" onclick="sendEnquiry()">Send Enquiry on WhatsApp 🚀</button>
      </div>
    </div>
  </div>
</section>

<!-- GALLERY -->
<section id="gallery">
  <div class="section-inner">
    <span class="section-tag tag-yellow">Life at Banbury Cross</span>
    <h2 class="section-title">Our Gallery</h2>
    <p class="section-subtitle">Glimpses of the joy, learning, and laughter that fills our school every single day.</p>
    <div class="gallery-grid">
      <div class="gallery-item g1">🎨<span class="gallery-label">Art & Craft Sessions</span></div>
      <div class="gallery-item g2">🎵<span class="gallery-label">Music Time</span></div>
      <div class="gallery-item g3">🌿<span class="gallery-label">Outdoor Play</span></div>
      <div class="gallery-item g4">📚<span class="gallery-label">Story Time</span></div>
      <div class="gallery-item g5">🎭<span class="gallery-label">Annual Day Performances</span></div>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <div class="contact-wrap">
    <div class="contact-info">
      <h2>Come Find Us 📍</h2>
      <p>We'd love to meet you and show you around our beautiful campus. Reach out any time — our doors and hearts are always open!</p>
      <div class="cdetail">
        <div class="cicon">📍</div>
        <div class="ctext"><strong>Address</strong><span>B-86, Sector-C, Mahanagar,<br/>Lucknow – 226006, Uttar Pradesh</span></div>
      </div>
      <div class="cdetail">
        <div class="cicon">📞</div>
        <div class="ctext"><strong>Phone</strong><span><a href="tel:+917565887777" style="color:rgba(255,255,255,.88);text-decoration:none;font-weight:700;">+91 7565887777</a></span></div>
      </div>
      <div class="cdetail">
        <div class="cicon">🕐</div>
        <div class="ctext"><strong>School Hours</strong><span>Monday – Saturday<br/>8:00 AM – 1:00 PM</span></div>
      </div>
      <div class="cdetail">
        <div class="cicon">📧</div>
        <div class="ctext"><strong>Admissions Enquiry</strong><span>Visit us or call directly for fastest response</span></div>
      </div>
    </div>
    <div class="contact-card">
      <h3>Quick Contact</h3>
      <div class="form-group"><label>Your Name</label><input id="ct-name" type="text" placeholder="Full name"/></div>
      <div class="form-group"><label>Phone Number</label><input id="ct-phone" type="tel" placeholder="+91 XXXXX XXXXX"/></div>
      <div class="form-group"><label>Message</label><textarea id="ct-msg" placeholder="How can we help you?"></textarea></div>
      <button class="form-submit" onclick="sendContact()">Send on WhatsApp 💬</button>
      <div class="map-box">
        <span>🗺️</span>
        <p>B-86, Sector-C, Mahanagar, Lucknow</p>
        <a href="https://maps.google.com/?q=B-86,Sector-C,Mahanagar,Lucknow-226006" target="_blank">Open in Google Maps →</a>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-links">
    <a href="#about">About</a>
    <a href="#academics">Academics</a>
    <a href="#facilities">Facilities</a>
    <a href="#gallery">Gallery</a>
    <a href="#admissions">Admissions</a>
    <a href="#contact">Contact</a>
  </div>
  <p><strong>Banbury Cross Educational Academy</strong> · B-86, Sector-C, Mahanagar, Lucknow – 226006<br/>
  📞 7565887777 &nbsp;|&nbsp; "Creating Great Minds for a Great Future"<br/><br/>
  © 2025 Banbury Cross Educational Academy. All rights reserved.</p>
</footer>

<script>
// Smooth scroll for all anchor links with offset for sticky nav
document.querySelectorAll('a[href^="#"]').forEach(function(link) {
  link.addEventListener('click', function(e) {
    var targetId = this.getAttribute('href').slice(1);
    var target = document.getElementById(targetId);
    if (target) {
      e.preventDefault();
      var navHeight = document.querySelector('nav').offsetHeight;
      var top = target.getBoundingClientRect().top + window.pageYOffset - navHeight - 12;
      window.scrollTo({ top: top, behavior: 'smooth' });
    }
  });
});

const WA_NUMBER = '917565887777';

function sendEnquiry() {
  const parent   = document.getElementById('enq-parent').value.trim();
  const child    = document.getElementById('enq-child').value.trim();
  const phone    = document.getElementById('enq-phone').value.trim();
  const email    = document.getElementById('enq-email').value.trim();
  const prog     = document.getElementById('enq-programme').value.trim();
  const msg      = document.getElementById('enq-msg').value.trim();

  if (!parent || !child || !phone) {
    alert('Please fill in Parent Name, Child Name, and Phone Number before sending.');
    return;
  }

  const text =
    `*📋 New Admission Enquiry – Banbury Cross*\n\n` +
    `👤 *Parent Name:* ${parent}\n` +
    `👶 *Child Name:* ${child}\n` +
    `📞 *Phone:* ${phone}\n` +
    (email    ? `📧 *Email:* ${email}\n`         : '') +
    (prog     ? `🎒 *Programme:* ${prog}\n`      : '') +
    (msg      ? `💬 *Message:* ${msg}\n`         : '') +
    `\n_Sent via Banbury Cross website_`;

  window.open('https://wa.me/' + WA_NUMBER + '?text=' + encodeURIComponent(text), '_blank');
}

function sendContact() {
  const name  = document.getElementById('ct-name').value.trim();
  const phone = document.getElementById('ct-phone').value.trim();
  const msg   = document.getElementById('ct-msg').value.trim();

  if (!name || !phone) {
    alert('Please fill in your Name and Phone Number before sending.');
    return;
  }

  const text =
    `*💬 Quick Contact – Banbury Cross*\n\n` +
    `👤 *Name:* ${name}\n` +
    `📞 *Phone:* ${phone}\n` +
    (msg ? `💬 *Message:* ${msg}\n` : '') +
    `\n_Sent via Banbury Cross website_`;

  window.open('https://wa.me/' + WA_NUMBER + '?text=' + encodeURIComponent(text), '_blank');
}
</script>
</body>
</html>
