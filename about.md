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
      <strong>Colorado State University</strong> pursuing a Business Minor and Entrepreneurship Certificate. 
      My studies combine creativity, precision, and purpose, reflecting my belief that innovation 
      should serve people as much as progress.
    </p>

    <p>
      I’m currently an <strong>Honors Ambassador</strong> for the CSU Honors Program, a 
      <strong>Manager at NOCO Sports Center</strong> in Windsor, and the <strong>Treasurer and Co-Founder 
      of Crossover for Change</strong>, a nonprofit that empowers young women in Uganda through 
      basketball, education, and mentorship. Each of these roles challenges me to lead with empathy, 
      stay organized under pressure, and communicate across diverse teams.
    </p>

    <p>
      Through engineering, leadership, and service, I’ve learned that every system — whether mechanical 
      or human — depends on connection. My goal is to keep building those connections through 
      technology, collaboration, and creativity to design solutions that make a tangible difference 
      in people’s lives.
    </p>

    <div class="hero-buttons">
      <a href="/experiences/">Experiences</a>
      <a href="/skills/" class="gold">Skills</a>
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

/* ---------- BUTTON STYLING (MATCHES HOMEPAGE) ---------- */
.hero-buttons {
  margin-top: 1.5rem;
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
}

.hero-buttons a {
  background-color: #1e4d2b; /* CSU green */
  color: white;
  font-weight: 600;
  text-decoration: none;
  padding: 0.7rem 2rem;
  border-radius: 8px;
  font-size: 1rem;
  transition: 0.3s ease;
}

.hero-buttons a.gold {
  background-color: #c8b568; /* CSU gold */
  color: black;
}

.hero-buttons a:hover {
  opacity: 0.9;
  transform: translateY(-2px);
}

/* ---------- RESPONSIVE ---------- */
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
