---
layout: page
title: About Me
permalink: /about/
---

<link rel="stylesheet" href="/assets/css/style.css">

<!-- ---------- ABOUT HERO SECTION ---------- -->
<section class="hero about-hero">
  <div class="hero-image">
    <img src="/assets/images/headshot.jpg" alt="Headshot of Mia Chavez">
  </div>

  <div class="hero-text">
    <h1>Get to know me...</h1>
    <p>
      I’m <strong>Mia Chavez</strong> — a Biomedical and Mechanical Engineering student at 
      <strong>Colorado State University</strong> with a Business Minor and Entrepreneurship Certificate. 
      My interests sit at the intersection of technology, human connection, and social impact. 
      I’m passionate about using engineering not just to design new systems, but to design opportunities.
    </p>

    <p>
      My curiosity and drive have led me through research, nonprofit work, and leadership roles that 
      challenged me to think beyond the technical side of engineering. I value collaboration, creativity, 
      and integrity — and I’ve learned that innovation happens when people from different backgrounds 
      and ideas come together around a shared purpose.
    </p>

    <p>
      Outside of the lab and classroom, I lead <strong>Crossover for Change</strong>, a nonprofit that 
      empowers young women in Uganda through basketball, education, and mentorship. I also serve as 
      President of CSU Women’s Club Basketball — balancing structure, teamwork, and joy in every role I take on.
    </p>

    <div class="hero-buttons">
      <a href="/experiences/" class="gold">Experiences</a>
      <a href="/skills/">Skills</a>
      <a href="/contact/">Contact Me</a>
    </div>
  </div>
</section>

<style>
/* ---------- ABOUT HERO SECTION STYLING ---------- */
.about-hero {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 3rem;
  flex-wrap: wrap;
  padding: 4rem 2rem;
  max-width: 1200px;
  margin: 0 auto;
}

.about-hero .hero-image img {
  width: 260px;
  height: 260px;
  object-fit: cover;
  border-radius: 50%;
  border: 6px solid #c8b568; /* CSU gold */
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.25);
}

.about-hero .hero-text {
  flex: 1 1 480px;
  max-width: 620px;
  text-align: left;
}

.about-hero h1 {
  color: #1e4d2b; /* CSU green */
  font-size: 2.2rem;
  margin-bottom: 1rem;
}

.about-hero p {
  margin-bottom: 1rem;
  line-height: 1.7;
  color: #333;
}

.hero-buttons {
  margin-top: 1.5rem;
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
}

.hero-buttons a {
  padding: 0.6rem 1.2rem;
  border-radius: 30px;
  text-decoration: none;
  font-weight: 600;
  transition: 0.3s ease;
}

.hero-buttons a.gold {
  background-color: #c8b568;
  color: #fff;
}

.hero-buttons a:hover {
  opacity: 0.85;
}

/* Responsive */
@media (max-width: 768px) {
  .about-hero {
    flex-direction: column;
    text-align: center;
  }

  .about-hero .hero-text {
    text-align: center;
  }

  .hero-buttons {
    justify-content: center;
  }
}
</style>
