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

/* ---------- FOOTER ---------- */
footer {
  text-align: center;
  color: #555;
  margin-top: 4rem;
  padding-top: 2rem;
  border-top: 1px solid #eee;
  font-weight: 500;
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

<!-- ---------- INTERACTIVE CSU VENN DIAGRAM ---------- -->
<section>
  <h2 style="text-align:center; color:#1E4D2B; margin-top:4rem;">Interdisciplinary Engineering at CSU</h2>
  <p style="text-align:center; max-width:750px; margin:0 auto 1.5rem;">
    My studies in <strong>Mechanical Engineering</strong>, <strong>Biomedical Engineering</strong>, and 
    <strong>Honors, Business & Liberal Arts</strong> connect to form a foundation of technical skill, innovation, and human-centered leadership.
  </p>

  <h3 style="text-align:center; color:#555; font-style:italic; margin-bottom:2rem;">
    Click or hover on the diagram to explore key connections.
  </h3>

  <style>
    .venn-container {
      position: relative;
      width: 850px;
      height: 600px;
      margin: 0 auto;
    }

    .venn-circle {
      position: absolute;
      width: 340px;
      height: 340px;
      border-radius: 50%;
      mix-blend-mode: multiply;
      opacity: 0.75;
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: bold;
      text-align: center;
      color: white;
      cursor: pointer;
      transition: transform 0.3s, opacity 0.3s;
    }

    .venn-circle:hover {
      transform: scale(1.05);
      opacity: 0.9;
    }

    /* CSU Palette */
    #mech { background: #1E4D2B; left: 80px; top: 120px; }
    #bio { background: #C8B568; left: 400px; top: 120px; color: black; }
    #honors { background: #6B8E23; left: 240px; top: 280px; }

    /* Overlap Highlights */
    #mech-bio { background: #9AA556; left: 270px; top: 180px; width: 280px; height: 280px; opacity: 0.5; border-radius: 50%; }
    #bio-honors { background: #B3A55C; left: 330px; top: 220px; width: 280px; height: 280px; opacity: 0.45; border-radius: 50%; }
    #mech-honors { background: #5E7945; left: 200px; top: 230px; width: 280px; height: 280px; opacity: 0.45; border-radius: 50%; }

    /* Labels */
    .venn-label {
      position: absolute;
      width: 230px;
      text-align: center;
      font-size: 1rem;
      color: #222;
      font-weight: 500;
      line-height: 1.3;
    }

    #mech-label { left: 10px; top: 60px; }
    #bio-label { right: 0; top: 60px; }
    #honors-label { left: 300px; bottom: 10px; }

    #mech-bio-label { left: 320px; top: 150px; font-weight: 600; color: #234D2B; }
    #bio-honors-label { left: 360px; top: 320px; font-weight: 600; color: #7C6B22; }
    #mech-honors-label { left: 170px; top: 320px; font-weight: 600; color: #4D6A3A; }

    #center-label {
      left: 320px;
      top: 260px;
      font-weight: 700;
      font-size: 1.1rem;
      color: #1E4D2B;
      background: rgba(255, 255, 255, 0.9);
      padding: 8px 16px;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.15);
    }

    @media (max-width: 768px) {
      .venn-container {
        width: 95%;
        height: 500px;
      }
      .venn-circle {
        width: 260px;
        height: 260px;
        font-size: 0.85rem;
      }
    }
  </style>

  <div class="venn-container">
    <div class="venn-circle" id="mech" title="Mechanical Engineering: Prototyping, CAD, Testing"></div>
    <div class="venn-circle" id="bio" title="Biomedical Engineering: Human-Centered Design, Medical Devices"></div>
    <div class="venn-circle" id="honors" title="Honors, Business & Liberal Arts: Leadership, Strategy, Communication"></div>

    <div class="venn-circle" id="mech-bio" title="Biomechanics & Device Design"></div>
    <div class="venn-circle" id="bio-honors" title="Ethical Innovation & Healthcare Entrepreneurship"></div>
    <div class="venn-circle" id="mech-honors" title="Project Management & Technical Leadership"></div>

    <div class="venn-label" id="mech-label">Prototyping, CAD, and System Testing</div>
    <div class="venn-label" id="bio-label">Human-Centered Medical Design</div>
    <div class="venn-label" id="honors-label">Leadership, Strategy, and Communication</div>

    <div class="venn-label" id="mech-bio-label">Biomechanics & Device Design</div>
    <div class="venn-label" id="bio-honors-label">Ethical Innovation & Healthcare Entrepreneurship</div>
    <div class="venn-label" id="mech-honors-label">Project Management & Technical Leadership</div>
    <div class="venn-label" id="center-label">Interdisciplinary Problem Solving</div>
  </div>
</section>

<footer>
  <p><strong>Mia Chavez Portfolio</strong><br>Colorado State University</p>
</footer>
