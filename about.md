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

/* ---------- PAGE WRAPPER ---------- */
.about-wrapper {
  max-width: 1100px;
  margin: 3rem auto 4rem;
  padding: 0 3%;
  color: #333;
  line-height: 1.7;
}

/* ---------- HEAD SECTION (IMAGES + INTRO) ---------- */
.about-hero {
  display: flex;
  flex-wrap: wrap;
  gap: 2rem;
  align-items: flex-start;
  justify-content: center;
  margin-bottom: 2rem;
}

.about-hero-images {
  display: flex;
  flex-direction: column;
  gap: 1.2rem;
  align-items: center;
}

/* Headshot */
.about-headshot img {
  width: 230px;
  height: 230px;
  object-fit: cover;
  border-radius: 50%;
  border: 5px solid var(--csu-gold);
  box-shadow: 0 4px 14px rgba(0,0,0,0.22);
}

/* CFC image */
.about-cfc img {
  width: 260px;
  height: auto;
  border-radius: 14px;
  border: 4px solid var(--csu-green);
  box-shadow: 0 4px 14px rgba(0,0,0,0.22);
}

/* Intro text */
.about-hero-text {
  flex: 1 1 320px;
  min-width: 280px;
}

.about-hero-text h1 {
  color: var(--csu-green);
  font-size: 2.2rem;
  margin-bottom: 0.75rem;
}

.about-hero-text p {
  margin-bottom: 1rem;
  font-size: 1.02rem;
}

/* Quote banner */
.about-quote {
  margin: 1.5rem auto 0;
  padding: 0.9rem 1.4rem;
  border-radius: 999px;
  background: linear-gradient(to right, rgba(30,77,43,0.07), rgba(200,181,104,0.3));
  text-align: center;
  font-style: italic;
  font-size: 0.98rem;
  max-width: 650px;
  color: #223322;
}

/* ---------- SECTION HEADERS ---------- */
.about-section {
  margin-top: 2.5rem;
}

.about-section h2 {
  color: var(--csu-gold);
  font-size: 1.6rem;
  margin-bottom: 0.6rem;
}

.about-section p {
  font-size: 1.02rem;
}

/* ---------- EDUCATION SPLIT ---------- */
.education-split {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 1.5rem;
  margin-top: 1.2rem;
}

.education-card {
  background: #fafafa;
  border-radius: 16px;
  padding: 1rem 1.3rem;
  box-shadow: 0 3px 10px rgba(0,0,0,0.06);
}

.education-card h3 {
  margin-top: 0;
  margin-bottom: 0.4rem;
  color: var(--csu-green);
  font-size: 1.1rem;
}

.education-card p {
  margin-bottom: 0;
  font-size: 0.96rem;
}

/* ---------- IMAGE GALLERY ---------- */
.about-gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 1.5rem;
  margin-top: 1.8rem;
}

.about-gallery img {
  width: 280px;
  height: auto;
  border-radius: 12px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.15);
  object-fit: cover;
}

/* ---------- RESPONSIVE ---------- */
@media (max-width: 768px) {
  .about-hero {
    align-items: center;
    text-align: left;
  }
  .about-quote {
    font-size: 0.9rem;
  }
}
</style>

<div class="about-wrapper">

  <!-- TOP: IMAGES + INTRO -->
  <section class="about-hero">
    <div class="about-hero-images">
      <figure class="about-headshot">
        <img src="/assets/images/headshot.jpg" alt="Headshot of Mia Chavez">
      </figure>
      <figure class="about-cfc">
        <img src="/assets/images/cfc.png" alt="Mia presenting with Crossover for Change in Uganda">
      </figure>
    </div>

    <div class="about-hero-text">
      <h1>Hi, I’m Mia.</h1>
      <p>
        I’m a <strong>Biomedical and Mechanical Engineering</strong> student at 
        <strong>Colorado State University</strong>, graduating in May 2027 with a Minor in Business Administration 
        and an Entrepreneurship Certificate. I’m passionate about designing solutions that sit at the intersection of 
        engineering, human connection, and social impact.
      </p>
      <p>
        I care deeply about how technology can empower people, especially through access to education, healthcare, and 
        community. Whether I’m in the lab, on the court, or working with girls in Uganda through 
        <strong>Crossover for Change</strong>, I show up as a teammate, problem-solver, and listener first.
      </p>
    </div>
  </section>

  <div class="about-quote">
    “Engineering with empathy. Leading with purpose.”
  </div>

  <!-- MY STORY -->
  <section class="about-section">
    <h2>My Story</h2>
    <p>
      I grew up in Colorado Springs as the fourth of eight children to my parents, Denise and David. 
      With siblings David, Joey, Matthew, Hope, Faith, Micah, and Sabrina, our house has always been full of energy, 
      noise, and what I like to call “organized chaos.” From long road trips in a 14-passenger van to solving 
      small crises together, my family taught me how to be a teammate, a role model, and an older sister who leads 
      with compassion and flexibility.
    </p>
    <p>
      Those early experiences shaped how I approach challenges today. When things get messy, I naturally shift into 
      problem-solving mode: listen, coordinate, and take the next right step. That mindset carries into my work in 
      engineering, nonprofit leadership, and athletics, where I’m constantly balancing structure with empathy.
    </p>

    <div class="about-gallery">
      <img src="/assets/images/family.jpg" alt="Mia with her family">
    </div>
  </section>

  <!-- EDUCATION -->
  <section class="about-section">
    <h2>Educational Journey</h2>
    <p>
      My education has combined rigor, character development, and hands-on learning. Each school I attended pushed me 
      to see learning not just as information, but as a way to serve others.
    </p>

    <div class="education-split">
      <div class="education-card">
        <h3>The Vanguard School</h3>
        <p>
          At Vanguard (K–8), I was immersed in a content-rich, classical education that emphasized character, discipline, 
          and academic excellence. It gave me a strong foundation in critical thinking and a deep appreciation for hard work 
          and integrity.
        </p>
      </div>

      <div class="education-card">
        <h3>The Colorado Springs School</h3>
        <p>
          At CSS, I experienced experiential learning—education that extends beyond the classroom. Through programs like 
          my homelessness-focused ECS and community service, I learned to connect issues like equity, belonging, and access 
          to the work I want to do in the world. CSS helped me see leadership as service.
        </p>
      </div>
    </div>
  </section>

  <!-- WHAT DRIVES ME -->
  <section class="about-section">
    <h2>What Drives Me</h2>
    <p>
      At the heart of everything I do is a belief that <strong>engineering is about people</strong>. I’m motivated by the 
      relationships I build, the communities I serve, and the chance to create tools that make life safer, more accessible, 
      and more empowering for others.
    </p>
    <p>
      This belief shows up in my work with <strong>Crossover for Change</strong>, which I co-founded to foster confidence, 
      empowerment, and leadership for young women in Uganda through basketball and education. It also shapes how I think 
      about biomedical engineering, particularly in orthopedics, prosthetics, and assistive technologies that restore motion 
      and independence.
    </p>

    <div class="about-gallery">
      <img src="/assets/images/basketball.jpg" alt="Mia playing or leading basketball">
      <img src="/assets/images/engineering_lab.jpg" alt="Mia working in an engineering or research setting">
    </div>
  </section>

  <!-- BEYOND THE CLASSROOM -->
  <section class="about-section">
    <h2>Beyond the Classroom</h2>
    <p>
      Outside of coursework, I’ve led and served in roles that have stretched me as a communicator, organizer, and mentor. 
      As President of CSU Women’s Club Basketball and the Honors Student Association, and as Board Treasurer and Co-Founder 
      of Crossover for Change, I’ve learned how to build communities where people feel seen, included, and supported.
    </p>
    <p>
      Basketball, especially, has been a constant thread in my life—from playing in my backyard with siblings to traveling 
      with teams and coaching younger players. It’s taught me resilience, communication, and what it means to trust the people 
      beside you. Those lessons follow me everywhere: into classrooms, into labs, and into the nonprofit spaces where I hope to 
      make long-term impact.
    </p>
  </section>

</div>
