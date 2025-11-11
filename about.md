---
layout: page
title: About Me
permalink: /about/
---

<link rel="stylesheet" href="/assets/css/style.css">

<style>
:root {
  --csu-green: #1e4d2b;
  --csu-gold: #c8b568;
}

.about-wrapper {
  max-width: 1150px;
  margin: 3rem auto 4rem;
  padding: 0 3%;
  color: #333;
  line-height: 1.7;
}

/* ---------- HEADER (HEADSHOT + CFC IMAGE) ---------- */
.about-hero {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 2.5rem;
  align-items: flex-start;
  margin-bottom: 2rem;
}

.about-hero-images {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 1.2rem;
}

.about-headshot img {
  width: 250px;
  height: 250px;
  object-fit: cover;
  border-radius: 50%;
  border: 6px solid var(--csu-gold);
  box-shadow: 0 4px 15px rgba(0,0,0,0.25);
}

.about-cfc img {
  width: 320px;
  height: auto;
  border-radius: 14px;
  border: 4px solid var(--csu-green);
  box-shadow: 0 4px 15px rgba(0,0,0,0.25);
}

.about-hero-text {
  flex: 1 1 380px;
  min-width: 280px;
}

.about-hero-text h1 {
  color: var(--csu-green);
  font-size: 2.2rem;
  margin-bottom: 0.75rem;
}

.about-quote {
  margin: 1.5rem auto 2rem;
  padding: 0.9rem 1.4rem;
  border-radius: 999px;
  background: linear-gradient(to right, rgba(30,77,43,0.07), rgba(200,181,104,0.3));
  text-align: center;
  font-style: italic;
  font-size: 1rem;
  max-width: 680px;
  color: #223322;
}

/* ---------- SECTION HEADERS ---------- */
.about-section {
  margin-top: 3rem;
}

.about-section h2 {
  color: var(--csu-gold);
  font-size: 1.7rem;
  margin-bottom: 0.7rem;
}

/* ---------- SINGLE IMAGE SECTIONS ---------- */
.about-image-full {
  text-align: center;
  margin-top: 1.5rem;
}

.about-image-full img {
  width: 100%;
  max-width: 950px;
  height: auto;
  border-radius: 16px;
  box-shadow: 0 6px 14px rgba(0,0,0,0.15);
}

/* ---------- EDUCATION SPLIT ---------- */
.education-split {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(360px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.education-card img {
  width: 100%;
  max-width: 500px;
  border-radius: 14px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.12);
}

.education-card h3 {
  color: var(--csu-green);
  font-size: 1.2rem;
  margin: 0.6rem 0 0.3rem;
}

/* ---------- LARGE IMAGE SECTIONS ---------- */
.about-gallery {
  display: flex;
  justify-content: center;
  gap: 1.5rem;
  flex-wrap: wrap;
  margin-top: 2rem;
}

.about-gallery img {
  width: 100%;
  max-width: 950px;
  border-radius: 16px;
  box-shadow: 0 6px 14px rgba(0,0,0,0.15);
}

/* ---------- RESPONSIVE ---------- */
@media (max-width: 768px) {
  .about-hero {
    flex-direction: column;
    align-items: center;
  }
}
</style>

<div class="about-wrapper">

  <!-- HEADER -->
  <section class="about-hero">
    <div class="about-hero-images">
      <figure class="about-headshot">
        <img src="/assets/images/headshot.jpg" alt="Headshot of Mia Chavez">
      </figure>
      <figure class="about-cfc">
        <img src="/assets/images/cfc_uganda.jpg" alt="Mia presenting with Crossover for Change in Uganda">
      </figure>
    </div>

    <div class="about-hero-text">
      <h1>Hi, I’m Mia.</h1>
      <p>
        I’m a <strong>Biomedical and Mechanical Engineering</strong> student at 
        <strong>Colorado State University</strong>, graduating in May 2027 with a Minor in Business Administration 
        and an Entrepreneurship Certificate. I’m passionate about designing solutions that sit at the intersection 
        of engineering, human connection, and social impact.
      </p>
      <p>
        Whether I’m developing medical devices, leading nonprofit initiatives, or mentoring others, I aim to create 
        work that blends precision, empathy, and purpose.
      </p>
    </div>
  </section>

  <div class="about-quote">
    “Engineering with empathy. Leading with purpose.”
  </div>

  <!-- MY JOURNEY -->
  <section class="about-section">
    <h2>My Journey</h2>
    <p>
      I grew up in Colorado Springs as one of eight kids in a close-knit, chaotic, and loving family. Those experiences 
      taught me to adapt quickly, collaborate with others, and lead with empathy. My family has been the foundation for 
      how I approach teamwork, service, and creativity today.
    </p>
    <div class="about-image-full">
      <img src="/assets/images/family.jpg" alt="Mia with her family">
    </div>
  </section>

  <!-- EDUCATION -->
  <section class="about-section">
    <h2>Educational Journey</h2>
    <p>
      My education reflects a shift from memorization to application — learning not just what to think, but how to think. 
      These two schools helped shape both my intellect and my values.
    </p>
    <div class="education-split">
      <div class="education-card">
        <img src="/assets/images/vanguard_school.jpg" alt="The Vanguard School">
        <h3>The Vanguard School</h3>
        <p>
          A foundation built on discipline, structure, and academic excellence that fueled my curiosity and drive for precision.
        </p>
      </div>
      <div class="education-card">
        <img src="/assets/images/css_school.jpg" alt="The Colorado Springs School">
        <h3>The Colorado Springs School</h3>
        <p>
          A space where I grew into a creative thinker, community leader, and advocate for real-world learning through service.
        </p>
      </div>
    </div>
  </section>

  <!-- WHAT DRIVES ME -->
  <section class="about-section">
    <h2>What Drives Me</h2>
    <p>
      I believe engineering is most powerful when it serves people. My goal is to design accessible, human-centered 
      technologies that improve health, mobility, and equity. This mindset inspires both my work in biomedical engineering 
      and my leadership with Crossover for Change.
    </p>
    <div class="about-gallery">
      <img src="/assets/images/engineering_lab.jpg" alt="Mia working in the engineering lab">
    </div>
  </section>

  <!-- BEYOND THE CLASSROOM -->
  <section class="about-section">
    <h2>Beyond the Classroom</h2>
    <p>
      On the court and in leadership roles, I’ve learned lessons in communication, resilience, and trust that extend 
      far beyond sports. As President of CSU Women’s Club Basketball, I build community, foster confidence, and help others grow.
    </p>
    <div class="about-gallery">
      <img src="/assets/images/basketball.jpg" alt="Mia playing basketball">
    </div>
  </section>

</div>
