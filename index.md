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
      <a href="/experiences/">Contact Me</a>
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
  </div>
</section>

<!-- ---------- INTERACTIVE VENN DIAGRAM ---------- -->
<section>
  <h2 style="text-align:center; color:var(--csu-green);">Interdisciplinary Focus</h2>
  <p style="text-align:center; max-width:700px; margin:0 auto;">
    My education bridges <strong>engineering, business, and human-centered design</strong>. I thrive at the intersection of analytical thinking, creative innovation, and real-world empathy — where technical expertise meets social impact.
  </p>

  <div class="venn-container">
    <div class="circle" id="circle1">Mechanical<br>Engineering</div>
    <div class="circle" id="circle2">Biomedical<br>Engineering</div>
    <div class="circle" id="circle3">Honors,<br>Business & Liberal Arts</div>
  </div>
</section>

<footer>
  <p><strong>Mia Chavez | Biomedical & Mechanical Engineer | CSU Class of 2027</strong></p>
</footer>

