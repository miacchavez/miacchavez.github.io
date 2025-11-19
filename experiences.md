---
layout: page
title: Experiences
permalink: /experiences/
---

<link rel="stylesheet" href="/assets/css/style.css">

<!-- ---------- EXPERIENCE HERO ---------- -->
<section class="experience-hero">
  <h1>My Experiences</h1>
  <p class="intro">
    A look into where I’ve learned by doing — from observing complex medical systems to building solutions that serve real needs.
  </p>

  <div class="experience-buttons alt-color">
    <a href="#engineering-experience">Engineering Experience</a>
    <a href="#engineering-projects-research">Engineering Projects & Research</a>
    <a href="#business-nonprofit">Business & Nonprofit Work</a>
    <a href="#leadership">Leadership</a>
    <a href="#athletics">Athletics & Coaching</a>
    <a href="#service">Service Industry</a>
    <a href="#awards">Awards & Honors</a>
  </div>
</section>

<style>
:root {
  --csu-green: #1e4d2b;
  --csu-gold: #c8b568;
}

/* ---------- HERO SECTION ---------- */
.experience-hero {
  text-align: center;
  margin: 4rem auto 2rem;
  max-width: 900px;
}
.experience-hero h1 {
  color: var(--csu-green);
  font-size: 2.5rem;
  border-bottom: 3px solid var(--csu-gold);
  display: inline-block;
  padding-bottom: 0.5rem;
}
.experience-hero .intro {
  margin-top: 1rem;
  font-size: 1.1rem;
  color: #444;
}

/* ---------- BUTTONS ---------- */
.experience-buttons {
  margin-top: 2rem;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 1rem;
}

.experience-buttons.alt-color a {
  padding: 0.8rem 1.4rem;
  border-radius: 10px;
  text-decoration: none;
  font-weight: 600;
  transition: 0.3s ease;
  border: 2px solid transparent;
}

/* Alternating green and gold */
.experience-buttons.alt-color a:nth-child(odd) {
  background-color: var(--csu-green);
  color: white;
}
.experience-buttons.alt-color a:nth-child(even) {
  background-color: var(--csu-gold);
  color: black;
}

/* Hover Effects */
.experience-buttons.alt-color a:hover {
  transform: translateY(-2px);
  border-color: #00000025;
  box-shadow: 0 4px 10px rgba(0,0,0,0.15);
}

/* ---------- SECTION STYLING (used for all subsections) ---------- */
.experience-section {
  margin: 4rem auto;
  max-width: 1000px;
  padding: 0 2rem;
  line-height: 1.8;
  color: #333;
}
.experience-section h2 {
  color: var(--csu-green);
  font-size: 2rem;
  border-bottom: 3px solid var(--csu-gold);
  display: inline-block;
  margin-bottom: 1rem;
}
.experience-section .tagline {
  color: #666;
  font-size: 1.1rem;
  margin-bottom: 1.5rem;
}
.experience-section h3 {
  color: var(--csu-green);
  margin-top: 1.5rem;
  font-size: 1.25rem;
}
.experience-section ul {
  list-style-type: disc;
  margin-left: 1.5rem;
  margin-bottom: 0.5rem;
}
.experience-section p strong {
  color: var(--csu-green);
}

/* Smooth Scroll */
html {
  scroll-behavior: smooth;
}
</style>

<!-- ---------- STRYKER INDUSTRY DAY & CADAVER LAB ---------- -->
<section id="stryker" class="experience-section">
  <h2>Engineering Experience</h2>
  <p class="tagline"><em>Learning from regulated industry, clinical environments, and real medical systems.</em></p>

  <h3>Stryker Industry Day & Cadaver Lab Shadowing (2024)</h3>
  <p class="experience-intro">
    I attended Stryker’s Sports Medicine Industry Day, an immersive mentorship and training experience focused on how engineering, business strategy, and clinical needs intersect in the medical device industry. I shadowed a project management mentor, explored product development workflows, and learned how engineering roles support the commercialization of surgical tools.
  </p>

  <!-- Banner Image -->
  <figure class="experience-banner">
    <img src="/assets/images/strykerfullgroup.jpg" alt="Stryker Industry Day group photo">
  </figure>

  <ul>
    <li>Shadowed a project management mentor to understand cross-functional decision-making across design, testing, marketing, and clinical use.</li>
    <li>Participated in networking and mock career development sessions including technical resume building, LinkedIn review, and interview strategy.</li>
    <li>Learned how diverse engineering roles (R&D, test engineering, quality, regulatory) contribute to surgeon success and patient outcomes.</li>
  </ul>

  <h4>Hands-On Cadaver Lab: ACL, Meniscus & Rotator Cuff Repair</h4>
  <p>
    In the cadaver lab, I used real Stryker surgical instruments to assist in ACL reconstruction, meniscus repair, and rotator cuff procedures. Having undergone ACL and meniscus reconstruction on both knees, this experience was especially meaningful. Although I once planned to become an orthopedic surgeon, it reinforced that I can still contribute to surgical impact through engineering design.
  </p>

  <figure class="experience-subimage">
    <img src="/assets/images/stryker.png" alt="Stryker sports medicine tools and cadaver lab instruments">
  </figure>

  <ul>
    <li>Used surgical instrumentation for ACL, meniscus, and rotator cuff repair on cadaver tissue.</li>
    <li>Evaluated tool ergonomics and workflow from a surgeon’s perspective to understand design requirements.</li>
    <li>Observed how surgical feedback informs design iteration for improved usability and outcomes.</li>
    <li>Connected engineering with patient recovery, especially for athletic injuries.</li>
  </ul>

  <p><strong>Summary:</strong> Strengthened my interest in designing surgical tools that support athletes, surgeons, and patient recovery through usability and engineering innovation.</p>
</section>
/* ---------- IMAGE STYLING FOR EXPERIENCES ---------- */
.experience-banner img {
  width: 100%;
  max-height: 380px;
  object-fit: cover;
  border-radius: 12px;
  border: 3px solid var(--csu-green);
  box-shadow: 0 4px 10px rgba(0,0,0,0.15);
  margin: 1.5rem 0;
}

.experience-subimage img {
  width: 100%;
  max-width: 650px;
  display: block;
  margin: 1.2rem auto;
  border-radius: 12px;
  border: 3px solid var(--csu-gold);
  box-shadow: 0 4px 10px rgba(0,0,0,0.15);
}
