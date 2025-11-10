---
layout: page
title: Home
permalink: /
---

<link rel="stylesheet" href="/assets/css/style.css">

<style>
:root {
  --csu-green: #1e4d2b;
  --csu-gold: #c8b568;
}

/* ---------- MAIN LAYOUT ---------- */
.hero {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
  gap: 2rem;
  margin: 3rem auto;
  max-width: 1100px;
}

.hero-image img {
  width: 260px;
  height: 260px;
  object-fit: cover;
  border-radius: 50%;
  border: 6px solid var(--csu-gold);
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
}

.hero-text {
  flex: 1 1 500px;
}

.hero-text h1 {
  color: var(--csu-green);
  font-size: 2.3rem;
}

.hero-text span {
  color: var(--csu-gold);
}

.hero-text p {
  line-height: 1.6;
  font-size: 1.05rem;
}

/* ---------- BUTTONS ---------- */
.hero-buttons {
  margin-top: 1.5rem;
}

.hero-buttons a {
  background: var(--csu-green);
  color: white;
  padding: 0.7rem 1.4rem;
  border-radius: 6px;
  text-decoration: none;
  font-weight: 500;
  margin-right: 0.6rem;
  transition: 0.3s;
}

.hero-buttons a.gold {
  background: var(--csu-gold);
  color: black;
}

.hero-buttons a:hover {
  opacity: 0.9;
  transform: translateY(-2px);
}

/* ---------- IMAGE GALLERY ---------- */
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1rem;
  margin: 3rem auto;
  max-width: 1100px;
}

.gallery img {
  width: 100%;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.15);
}

.gallery figcaption {
  text-align: center;
  font-size: 0.9rem;
  color: #555;
  margin-top: 0.3rem;
}

/* ---------- VENN DIAGRAM ---------- */
.venn-container {
  position: relative;
  width: 400px;
  height: 300px;
  margin: 3rem auto;
}

.circle {
  position: absolute;
  width: 220px;
  height: 220px;
  border-radius: 50%;
  opacity: 0.7;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  text-align: center;
  font-weight: bold;
  transition: transform 0.3s;
}

.circle:hover {
  transform: scale(1.05);
}

#circle1 {
  background: var(--csu-green);
  left: 30px;
  top: 40px;
}

#circle2 {
  background: var(--csu-gold);
  left: 150px;
  top: 40px;
  color: black;
}

#circle3 {
  background: #6b8e23;
  left: 90px;
  top: 130px;
}

/* ---------- FOOTER ---------- */
footer {
  text-align: center;
  color: #777;
  margin-top: 3rem;
  padding-top: 2rem;
  border-top: 1px solid #eee;
}
</style>

<section class="hero">
  <div class="hero-image">
    <img src="/assets/images/headshot.jpg" alt="Headshot of Mia Chavez">
  </div>

  <div class="hero-text">
    <h1>Hi, I’m <span>Mia Chavez</span>.</h1>
    <p>
      I’m a <strong>Biomedical and Mechanical Engineering</strong> student at
      <strong>Colorado State University</strong>, graduating in 2027 with a Business Minor and Entrepreneurship Certificate. My passion lies in combining technical engineering, design thinking, and social impact to create human-centered innovations.
    </p>

    <p>
      I value collaboration, curiosity, and creativity — qualities that shape my approach as a researcher, leader, and changemaker. Through hands-on experiences in labs, nonprofits, and leadership roles, I strive to design technology that empowers people and strengthens communities.
    </p>

    <div class="hero-buttons">
      <a href="/about/" class="gold">About Me</a>
      <a href="/experiences/">Experiences</a>
      <a href="/skills/" class="gold">Skills</a>
      <a href="/contact/">Contact Me</a>
    </div>
  </div>
</section>

<!-- ---------- IMAGE GALLERY ---------- -->
<section>
  <div class="gallery">
    <figure>
      <img src="/assets/images/lockheed.jpg" alt="Lockheed Martin Competition">
      <figcaption>Lockheed Martin Engineering Design Competition</figcaption>
    </figure>
    <figure>
      <img src="/assets/images/immaculateheart.jpg" alt="Crossover for Change in Uganda">
      <figcaption>Empowering young women at Immaculate Heart School, Uganda (CFC)</figcaption>
    </figure>
    <figure>
      <img src="/assets/images/stryker.jpg" alt="Stryker Shadow Day">
      <figcaption>Shadowing surgeons and med reps with Stryker</figcaption>
    </figure>
    <figure>
      <img src="/assets/images/or-shadow.jpg" alt="Operating Room Shadowing in Pueblo">
      <figcaption>Observing orthopedic surgery in the OR, Pueblo, CO</figcaption>
    </figure>
  </div>
</section>

<!-- ---------- INTERACTIVE VENN DIAGRAM 2.0 ---------- -->
<section>
  <h2 style="text-align:center; color:var(--csu-green); margin-top:4rem;">Interdisciplinary Focus</h2>
  <p style="text-align:center; max-width:750px; margin:0 auto 1rem;">
    My education bridges <strong>engineering, business, and human-centered design</strong>.
    Click on any circle or overlap to explore how my studies intersect across disciplines.
  </p>

  <div style="text-align:center; margin-bottom:2rem; color:#555;">
    🖱️ <em>Click each area to reveal the related skills</em>
  </div>

  <style>
    .venn-wrapper {
      position: relative;
      width: 600px;
      height: 450px;
      margin: 0 auto;
    }

    .circle {
      position: absolute;
      width: 300px;
      height: 300px;
      border-radius: 50%;
      opacity: 0.7;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-weight: bold;
      text-align: center;
      cursor: pointer;
      transition: transform 0.3s, opacity 0.3s;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }

    .circle:hover {
      transform: scale(1.05);
      opacity: 0.9;
    }

    #mech { background: var(--csu-green); left: 50px; top: 80px; }
    #bio { background: var(--csu-gold); left: 250px; top: 80px; color:black; }
    #honors { background: #6b8e23; left: 150px; top: 200px; }

    /* Overlap clickable areas */
    .overlap {
      position: absolute;
      width: 150px;
      height: 100px;
      border-radius: 50%;
      cursor: pointer;
      z-index: 10;
      opacity: 0;
    }

    #overlap-mech-bio { left: 200px; top: 120px; }
    #overlap-bio-honors { left: 240px; top: 210px; }
    #overlap-mech-honors { left: 120px; top: 210px; }
    #overlap-center { left: 200px; top: 180px; width: 160px; height: 120px; }

    /* Info boxes */
    .info-box {
      display: none;
      background: #f9f9f9;
      border-left: 6px solid var(--csu-green);
      padding: 1.2rem;
      margin: 1rem auto;
      max-width: 750px;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      animation: fadeIn 0.4s ease-in-out;
    }

    .info-box.active {
      display: block;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(10px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @media (max-width: 768px) {
      .venn-wrapper { width: 100%; height: 400px; }
      .circle { width: 200px; height: 200px; font-size: 0.8rem; }
    }
  </style>

  <div class="venn-wrapper">
    <!-- Main Circles -->
    <div class="circle" id="mech" onclick="showInfo('mechBox')">Mechanical<br>Engineering</div>
    <div class="circle" id="bio" onclick="showInfo('bioBox')">Biomedical<br>Engineering</div>
    <div class="circle" id="honors" onclick="showInfo('honorsBox')">Honors,<br>Business &<br>Liberal Arts</div>

    <!-- Invisible overlap areas -->
    <div class="overlap" id="overlap-mech-bio" onclick="showInfo('mechBioBox')"></div>
    <div class="overlap" id="overlap-bio-honors" onclick="showInfo('bioHonorsBox')"></div>
    <div class="overlap" id="overlap-mech-honors" onclick="showInfo('mechHonorsBox')"></div>
    <div class="overlap" id="overlap-center" onclick="showInfo('centerBox')"></div>
  </div>

  <!-- Info boxes below -->
  <div id="mechBox" class="info-box">
    <h3 style="color:var(--csu-green);">Mechanical Engineering</h3>
    <ul>
      <li>SolidWorks & CAD modeling</li>
      <li>Prototyping & fabrication</li>
      <li>Circuit design (LabVIEW, Arduino)</li>
      <li>Materials testing & data analysis</li>
      <li>Mechanical systems optimization</li>
    </ul>
  </div>

  <div id="bioBox" class="info-box">
    <h3 style="color:#a88b00;">Biomedical Engineering</h3>
    <ul>
      <li>Medical device design & testing</li>
      <li>Anatomy & biomechanics</li>
      <li>Orthopedic implant research (Empirical Technologies)</li>
      <li>Human factors & usability</li>
      <li>Healthcare innovation & empathy-driven design</li>
    </ul>
  </div>

  <div id="honorsBox" class="info-box">
    <h3 style="color:#6b8e23;">Honors, Business & Liberal Arts</h3>
    <ul>
      <li>Project management & fundraising</li>
      <li>Communication & public speaking</li>
      <li>Strategic planning & leadership</li>
      <li>Ethical decision-making</li>
      <li>Community engagement & mentorship</li>
    </ul>
  </div>

  <!-- Overlap info -->
  <div id="mechBioBox" class="info-box">
    <h3 style="color:var(--csu-green);">Mechanical + Biomedical</h3>
    <ul>
      <li>Biomechanics modeling</li>
      <li>CAD design for prosthetics</li>
      <li>Testing & validation of medical tools</li>
      <li>Reliability engineering for human use</li>
    </ul>
  </div>

  <div id="bioHonorsBox" class="info-box">
    <h3 style="color:#b5a200;">Biomedical + Business</h3>
    <ul>
      <li>Human-centered innovation</li>
      <li>Medical entrepreneurship</li>
      <li>Ethical product development</li>
      <li>Social impact design</li>
    </ul>
  </div>

  <div id="mechHonorsBox" class="info-box">
    <h3 style="color:#4d6b3b;">Mechanical + Business</h3>
    <ul>
      <li>Engineering project management</li>
      <li>Technical communication</li>
      <li>Product development strategy</li>
      <li>Team coordination</li>
    </ul>
  </div>

  <div id="centerBox" class="info-box">
    <h3 style="color:var(--csu-green);">Intersection of All Three</h3>
    <ul>
      <li>Interdisciplinary problem-solving</li>
      <li>Leadership through empathy</li>
      <li>Sustainable design for human impact</li>
      <li>Real-world innovation</li>
    </ul>
  </div>

  <script>
    function showInfo(boxId) {
      const boxes = document.querySelectorAll('.info-box');
      boxes.forEach(box => box.classList.remove('active'));
      document.getElementById(boxId).classList.add('active');
      window.scrollTo({ top: document.getElementById(boxId).offsetTop - 100, behavior: 'smooth' });
    }
  </script>
</section>



<footer>
  <p><strong>Mia Chavez | Biomedical & Mechanical Engineer | CSU Class of 2027</strong></p>
