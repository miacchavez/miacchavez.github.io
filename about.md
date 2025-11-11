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

/* ---------- HEADER (HEADSHOT + INTRO TEXT) ---------- */
.about-hero {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 2.5rem;
  margin-bottom: 2rem;
}

.about-headshot {
  flex: 0 0 auto;
}

.about-headshot img {
  width: 260px;
  height: 260px;
  object-fit: cover;
  border-radius: 50%;
  border: 6px solid var(--csu-gold);
  box-shadow: 0 4px 15px rgba(0,0,0,0.25);
}

.about-intro {
  flex: 1 1 auto;
  min-width: 280px;
}

.about-intro h1 {
  color: var(--csu-green);
  font-size: 2.2rem;
  margin-bottom: 0.75rem;
}

.about-intro p {
  font-size: 1.02rem;
  margin-bottom: 1rem;
}

/* ---------- QUOTE ---------- */
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
  margin-top: 3.5rem;
}

.about-section h2 {
  color: var(--csu-gold);
  font-size: 1.8rem;
  margin-bottom: 0.8rem;
}

.about-section p {
  font-size: 1.04rem;
  margin-bottom: 1rem;
}

/* ---------- IMAGES ---------- */
.about-image-full {
  text-align: center;
  margin-top: 1.8rem;
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
  font-size: 1.25rem;
  margin: 0.6rem 0 0.4rem;
}

/* ---------- RESPONSIVE ---------- */
@media (max-width: 768px) {
  .about-hero {
    flex-direction: column;
    text-align: left;
  }
  .about-intro h1 {
    font-size: 1.8rem;
  }
  .about-quote {
    font-size: 0.9rem;
  }
}
</style>

<div class="about-wrapper">

  <!-- HEADER -->
  <section class="about-hero">
    <div class="about-headshot">
      <img src="/assets/images/headshot.jpg" alt="Headshot of Mia Chavez">
    </div>
    <div class="about-intro">
      <h1>Get to know me…</h1>
      <p>
        I’m <strong>Mia Chavez</strong> — a Biomedical and Mechanical Engineering student at 
        <strong>Colorado State University</strong> with a Business Minor and Entrepreneurship Certificate. 
        My passion lies in designing technology that strengthens human connection and creates equitable access 
        to opportunity. I approach engineering not just as a technical pursuit, but as a way to listen, 
        collaborate, and serve.
      </p>
      <p>
        Whether I’m calibrating sensors, developing medical prototypes, or leading community programs, I’m drawn 
        to the space where structure meets empathy — where engineering becomes a tool for understanding and 
        improving lives.
      </p>
    </div>
  </section>

  <div class="about-quote">
    “Engineering with empathy. Leading with purpose.”
  </div>

  <!-- MY FAMILY & ROOTS -->
  <section class="about-section">
    <h2>My Family & Roots</h2>
    <p>
      I grew up in Colorado Springs as one of eight kids — a beautiful, chaotic, and character-building 
      experience that shaped who I am today. My parents, <strong>Jeff and Rachel</strong>, have always modeled 
      what it means to work hard while caring deeply for others. My siblings — <strong>Andrew, Matt, Abby, 
      Josh, Lizzy, Julia, and Grace</strong> — have been my greatest teachers in patience, teamwork, and humor. 
      With that many voices in one house, life was never quiet — but it was always full.
    </p>
    <p>
      Our home was a mix of <em>controlled chaos</em> — color-coded calendars on the fridge, basketball games in 
      the driveway, group dinners where stories collided. Growing up in that environment taught me how to thrive 
      under pressure, mediate conflict, and find focus amid noise. Those lessons show up daily in my work — in labs, 
      team projects, and leadership roles — as I navigate complex systems with calm and creativity.
    </p>
    <div class="about-image-full">
      <img src="/assets/images/family.jpg" alt="Mia with her family">
    </div>
  </section>

  <!-- EDUCATION -->
  <section class="about-section">
    <h2>Educational Journey</h2>
    <p>
      My education has been a journey of transformation — from mastering the fundamentals to applying them in ways 
      that make an impact. Each school I attended built on the last, shaping how I think, communicate, and serve.
    </p>

    <div class="education-split">
      <div class="education-card">
        <img src="/assets/images/vanguard_school.jpg" alt="The Vanguard School">
        <h3>The Vanguard School (K–8)</h3>
        <p>
          Vanguard provided me with a classical education rooted in critical thinking, memorization, and logic. 
          The structured environment and content-rich curriculum established a foundation of discipline, clarity, 
          and academic confidence. It’s where I learned how to study rigorously, articulate ideas effectively, and 
          value integrity as much as intelligence. These early lessons in structure and diligence remain the 
          backbone of how I approach engineering challenges today.
        </p>
      </div>

      <div class="education-card">
        <img src="/assets/images/css_school.jpg" alt="The Colorado Springs School">
        <h3>The Colorado Springs School (9–12)</h3>
        <p>
          At CSS, I earned the <strong>Innovator Merit Scholarship</strong> — an opportunity that transformed how I 
          viewed education. Moving from Vanguard’s classical foundation into CSS’s experiential model allowed me 
          to expand beyond memorization and immerse myself in real-world problem-solving. Through outdoor education, 
          field research, and interdisciplinary projects, I learned how creativity, teamwork, and reflection could 
          drive innovation. CSS taught me how to learn by doing — to connect technical skill with empathy, and 
          intellect with impact.
        </p>
      </div>
    </div>
  </section>

  <!-- CFC IMPACT SECTION -->
  <section class="about-section">
    <h2>Impact & Leadership</h2>
    <p>
      In 2020, I co-founded <strong>Crossover for Change</strong>, a nonprofit that empowers girls in Uganda through 
      basketball, education, and mentorship. What began as a simple idea — combining athletics and academics to 
      promote confidence — grew into an international initiative that now provides leadership camps, technology 
      access, and scholarships for students across several schools.
    </p>
    <p>
      As Co-Founder and Board Treasurer, I oversee finances, partnerships, and programming while collaborating with 
      educators in Uganda and the U.S. to ensure sustainability. Through this work, I’ve learned that leadership 
      isn’t about control — it’s about connection. It’s about bringing together people, ideas, and passion to 
      create something bigger than any one person could build alone.
    </p>
    <div class="about-image-full">
      <img src="/assets/images/cfc_uganda.jpg" alt="Mia presenting with Crossover for Change in Uganda">
    </div>
  </section>

  <!-- WHAT DRIVES ME -->
  <section class="about-section">
    <h2>What Drives Me</h2>
    <p>
      I’m drawn to the intersection of <strong>engineering, empathy, and impact</strong>. My goal is to design 
      solutions that are not only innovative but also inclusive — medical devices, prosthetics, and tools that 
      improve access to healthcare and quality of life. I love analyzing complex systems, understanding how 
      components interact, and reimagining them with human needs at the center.
    </p>
    <p>
      To me, engineering is about people. It’s a language of connection — translating challenges into 
      opportunities and data into dignity. Whether in a lab or a nonprofit boardroom, I’m most alive when I’m 
      collaborating to create something that helps others thrive.
    </p>
    <div class="about-image-full">
      <img src="/assets/images/engineering_lab.jpg" alt="Mia working in the engineering lab">
    </div>
  </section>

  <!-- BEYOND THE CLASSROOM -->
  <section class="about-section">
    <h2>Beyond the Classroom</h2>
    <p>
      As President of <strong>CSU Women’s Club Basketball</strong>, I lead three teams, coordinate tournaments, 
      and mentor younger players. Basketball has been my constant — the balance between the technical and the 
      emotional. On the court, I’ve learned how to communicate clearly, respond quickly, and lead with empathy. 
      Off the court, those same lessons guide how I lead projects, manage time, and support others.
    </p>
    <p>
      Sports have shown me that leadership isn’t about hierarchy — it’s about presence, humility, and teamwork. 
      The resilience I’ve built through athletics strengthens every other part of my life, from my engineering 
      labs to my nonprofit work.
    </p>
    <div class="about-image-full">
      <img src="/assets/images/basketball.jpg" alt="Mia playing basketball">
    </div>
  </section>

</div>
