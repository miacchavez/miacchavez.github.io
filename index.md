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
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 2rem;
  margin: 3rem auto;
  max-width: 1200px;
  padding: 0 3%;
}

/* ---------- IMAGE ROW (HEADSHOT + CFC IMAGE) ---------- */
.hero-images-horizontal {
  display: flex;
  justify-content: center;
  align-items: flex-start;
  flex-wrap: wrap;
  gap: 2.5rem;
  width: 100%;
}

.hero-images-horizontal figure {
  margin: 0;
  text-align: center;
}

/* Headshot - gold border, left-aligned */
.headshot img {
  width: 260px;
  height: 260px;
  object-fit: cover;
  border-radius: 50%;
  border: 6px solid var(--csu-gold);
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.25);
}

/* CFC Image - rectangular, green border, right-aligned */
.cfc-image img {
  width: 300px;
  height: auto;
  border-radius: 14px;
  border: 4px solid var(--csu-green);
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.25);
}

.cfc-image figcaption {
  font-size: 0.9rem;
  color: #333;
  max-width: 300px;
  margin-top: 0.4rem;
  line-height: 1.4;
  text-align: center;
}

/* Caption highlight for CFC name */
.cfc-highlight {
  color: var(--csu-green);
  border-bottom: 2px solid var(--csu-gold);
  padding-bottom: 2px;
}

/* ---------- TEXT SECTION ---------- */
.hero-text {
  flex: 1 1 500px;
  text-align: center;
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
  max-width: 800px;
  margin: 0 auto 1rem;
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
</style>

<section class="hero">
  <!-- HEADSHOT + CFC IMAGE ROW -->
  <div class="hero-images-horizontal">
    <figure class="headshot">
      <img src="/assets/images/headshot.jpg" alt="Headshot of Mia Chavez">
    </figure>
    <figure class="cfc-image">
      <img src="/assets/images/cfc.png" alt="Mia Chavez presenting with Crossover for Change in Uganda">
     <figcaption>
       Sharing interdisciplinary insights on engineering, leadership, and education with students in Uganda through
       <a href="https://crossoverforchange.org" target="_blank" rel="noopener noreferrer" class="cfc-link"> 
         Crossover for Change 
       </a>.
     </figcaption>
    </figure>
  </div>

  <!-- INTRO TEXT + BUTTONS -->
  <div class="hero-text">
    <h1>Hi, I’m <span>Mia Chavez</span>.</h1>
    <p>
      I’m a <strong>Biomedical and Mechanical Engineering</strong> student at
      <strong>Colorado State University</strong>, graduating in 2027 with a Business Administration Minor and Entrepreneurship Certificate in the Scott Scholars and Honors Programs. My passion lies in combining technical engineering, design thinking, and social impact to create human-centered innovations.
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


<!-- ---------- INTERDISCIPLINARY BUTTON SECTION ---------- -->
<section class="interdisciplinary-buttons">
  <h2 class="interdisciplinary-title">Interdisciplinary Focus Areas</h2>

  <!-- 🌟 Visual Overview FIRST -->
  <figure class="interdisciplinary-preview">
    <img src="/assets/images/1.png" alt="Interdisciplinary Overview Diagram">
  </figure>

  <div class="button-grid">
    <!-- Button 1 -->
    <button class="expand-btn gold-btn" data-target="img1">
      Honors and Business <span class="arrow">▶</span>
    </button>
    <img id="img1" class="expand-image" src="/assets/images/8.png" alt="Honors and Business Diagram">
    <!-- Button 2 -->
    <button class="expand-btn gold-btn" data-target="img2">
      Mechanical Engineering <span class="arrow">▶</span>
    </button>
    <img id="img2" class="expand-image" src="/assets/images/2.png" alt="Mechanical Engineering Diagram">
    <!-- Button 3 -->
    <button class="expand-btn gold-btn" data-target="img3">
      Biomedical Engineering <span class="arrow">▶</span>
    </button>
    <img id="img3" class="expand-image" src="/assets/images/3.png" alt="Biomedical Engineering Diagram">
    <!-- Button 4 -->
    <button class="expand-btn gold-btn" data-target="img4">
      Technical Leadership <span class="arrow">▶</span>
    </button>
    <img id="img4" class="expand-image" src="/assets/images/4.png" alt="Technical Leadership Diagram">
    <!-- Button 5 -->
    <button class="expand-btn gold-btn" data-target="img5">
      Human-Centered Design <span class="arrow">▶</span>
    </button>
    <img id="img5" class="expand-image" src="/assets/images/5.png" alt="Human-Centered Design Diagram">
    <!-- Button 6 -->
    <button class="expand-btn gold-btn" data-target="img6">
      Health Innovation & Ethics <span class="arrow">▶</span>
    </button>
    <img id="img6" class="expand-image" src="/assets/images/6.png" alt="Health Innovation & Ethics Diagram">
  </div>
</section>

<!-- ---------- FULL IMAGE UNDERNEATH ---------- -->
<section class="full-width-image">
  <img src="/assets/images/7.png" alt="Full interdisciplinary graphic">
</section>

<style>
/* ---------- INTERDISCIPLINARY IMAGES (NO BORDERS, NO CAPTIONS, CUSTOM SPACING) ---------- */
.interdisciplinary-images {
  margin: 4rem auto 6rem;
  max-width: 1200px;
  text-align: center;
  padding: 0 2rem;
}

.interdisciplinary-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 3rem; /* space between first and second image */
}

.interdisciplinary-container img {
  width: 100%;
  max-width: 950px;
  height: auto;
  border: none;
  border-radius: 0;
  box-shadow: none;
  margin: 0 auto;
  display: block;
}

/* Remove space between 2nd and 3rd image */
.interdisciplinary-container img:nth-child(3) {
  margin-top: -3rem;
}

/* Ensure no captions or automatic text appear */
.interdisciplinary-container img + br,
.interdisciplinary-container img + small,
.interdisciplinary-container img + figcaption {
  display: none !important;
}
</style>

<!-- ---------- IMAGE GALLERY ---------- -->
<style>
/* ---------- IMAGE GALLERY (2x2 GRID) ---------- */
.gallery {
  display: grid;
  grid-template-columns: repeat(2, 1fr); /* Two images per row */
  gap: 1.5rem;
  justify-items: center;
  align-items: start;
  margin: 3rem auto;
  max-width: 1000px;
}

/* Make it mobile-friendly (1 per row below 768px) */
@media (max-width: 768px) {
  .gallery {
    grid-template-columns: 1fr;
  }
}

.gallery figure {
  text-align: center;
  margin: 0;
}

.gallery img {
  width: 100%;
  max-width: 450px;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.15);
}

.gallery figcaption {
  font-size: 0.9rem;
  color: #555;
  margin-top: 0.4rem;
  line-height: 1.3;
}
</style>
<style>
.interdisciplinary-title {
  text-align: center;
  color: var(--csu-green);
  font-size: 2rem;
  margin-bottom: 1rem;
  border-bottom: 3px solid var(--csu-gold);
  display: inline-block;
  padding-bottom: 0.4rem;
}

.button-grid {
  max-width: 900px;
  margin: 2rem auto;
  display: flex;
  flex-direction: column;
  gap: 0.8rem;
}

.gold-btn {
  background-color: var(--csu-gold);
  color: black;
  border: none;
  padding: 0.8rem 1.2rem;
  font-weight: 700;
  cursor: pointer;
  border-radius: 8px;
  font-size: 1.1rem;
  text-align: left;
  transition: 0.3s ease;
}

.gold-btn:hover {
  background-color: #e0d39a;
  transform: translateY(-2px);
}

.expand-image {
  display: none;
  width: 100%;
  max-width: 950px;
  margin: 0.5rem auto 1.5rem;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.15);
}

.arrow {
  float: right;
  transition: transform .3s ease;
  color: #333;
}

.full-width-image img {
  width: 100%;
  max-width: 950px;
  margin: 3rem auto;
  display: block;
}
</style>
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
<script>
document.querySelectorAll(".expand-btn").forEach(btn => {
  btn.addEventListener("click", () => {
    const img = document.getElementById(btn.dataset.target);
    const arrow = btn.querySelector(".arrow");
    const isOpen = img.style.display === "block";

    img.style.display = isOpen ? "none" : "block";
    arrow.style.transform = isOpen ? "rotate(0deg)" : "rotate(90deg)";
  });
});
</script>
