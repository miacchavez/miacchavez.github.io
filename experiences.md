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
/* Subheader Enhancement (Clinical section) */
.experience-section h4 {
  margin-top: 1.8rem;
  font-size: 1.15rem;
  font-weight: 700;
  color: var(--csu-gold);
  letter-spacing: 0.3px;
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

/* ---------- SECTION STYLING ---------- */
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
.experience-section h4 {
  margin-top: 1.8rem;
  font-size: 1.15rem;
  font-weight: 600;
  color: var(--csu-gold);
}
.experience-section ul {
  list-style-type: disc;
  margin-left: 1.5rem;
  margin-bottom: 0.5rem;
}
.summary strong {
  color: var(--csu-green);
}

/* ---------- IMAGE STYLING FOR EXPERIENCES ---------- */
.experience-banner img {
  width: 100%;
  height: auto; /* natural proportions */
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

/* Smooth Scroll */
html {
  scroll-behavior: smooth;
}
</style>

<!-- ===================================================================== -->
<!-- ======================== ENGINEERING EXPERIENCE ===================== -->
<!-- ===================================================================== -->

<section id="engineering-experience" class="experience-section">
  <h2>Engineering Experience</h2>
  <p class="tagline"><em>Learning from regulated industry, clinical environments, and real medical systems.</em></p>

  <!-- 🏥 STRYKER -->
  <h3>Stryker Industry Day & Cadaver Lab Shadowing (2024)</h3>
  <p class="experience-intro">
    I attended Stryker’s Sports Medicine Industry Day, an immersive mentorship and training experience focused on how engineering, business strategy, and clinical needs intersect in the medical device industry. I shadowed a project management mentor, explored product development workflows, and learned how engineering roles support the commercialization of surgical tools.
  </p>

  <figure class="experience-banner">
    <img src="/assets/images/strykerfullgroup.jpg" alt="Stryker Industry Day group photo">
  </figure>

  <ul>
    <li>Shadowed a project management mentor to understand cross-functional decision-making across design, testing, marketing, and clinical use.</li>
    <li>Participated in mock career development sessions including resume building, LinkedIn review, and interview strategy.</li>
    <li>Explored how engineering teams collaborate with surgeons to develop tools that support patient outcomes.</li>
  </ul>

  <h4>Hands-On Cadaver Lab: ACL, Meniscus & Rotator Cuff Repair</h4>
  <p>
    In the cadaver lab, I used real orthopedic surgical instruments to assist in ACL reconstruction, meniscus repair, and rotator cuff procedures. As someone who has undergone double ACL and meniscus surgery, working with the same tools used in my own operations was a full-circle moment. Though I shifted away from pre-med, the experience showed how engineering directly supports surgical impact.
  </p>

  <figure class="experience-subimage">
    <img src="/assets/images/stryker.jpg" alt="Stryker sports medicine tools and cadaver lab instruments">
  </figure>

  <ul>
    <li>Assisted in orthopedic procedures using industry-standard instruments.</li>
    <li>Evaluated ergonomic design considerations for surgeons in high-stress environments.</li>
    <li>Observed how surgical feedback drives iteration for safety, usability, and efficiency.</li>
    <li>Connected device usability with long-term patient recovery and athletic performance.</li>
  </ul>

  <p class="summary"><strong>Summary:</strong> Strengthened my interest in designing orthopedic tools that support athletes, surgeons, and patient recovery through usability-focused engineering.</p>
</section>

<!-- 🏥 ======================= CLINICAL ROTATIONS ======================= -->
<section id="clinical-rotations" class="experience-section">
  <h3>Clinical Rotations — BIOM 480: Clinical Experience for Bio-Innovation (2025)</h3>
  <p class="experience-intro">
    Before this immersion course, I shadowed <strong>Dr. Eric Richter</strong> and <strong>Christin Hungerford</strong> (medical device representative), where I observed orthopedic trauma workflows and how surgeons collaborate with industry to improve patient outcomes. That experience sparked my interest in clinical innovation — leading me to pursue BIOM 480, a selective course that connects engineering students with medical environments to identify unmet clinical needs and opportunities for device development.
  </p>

  <!-- Banner Image -->
  <figure class="experience-banner">
    <img src="/assets/images/or-shadow.jpg" alt="Observing orthopedic surgery and clinical workflows">
  </figure>

  <p>
    Through this program, I completed rotations at <strong>Poudre Valley Hospital (PVH)</strong>, <strong>Medical Center of the Rockies (MCR)</strong>, and the <strong>CSU Veterinary Teaching Hospital</strong> — exploring how devices, human factors, and workflow design influence patient safety and care.
  </p>

  <h4>📌 Surgical & Procedure Observations</h4>
  <ul>
    <li>Orthopedic trauma, thoracic surgery, vascular, and robotic-assisted procedures</li>
    <li>Observed surgeon–nurse–rep dynamics and device setup workflows</li>
    <li>Studied error prevention strategies and sterile field design</li>
  </ul>

  <h4>💡 Medical Device & Imaging Exposure</h4>
  <ul>
    <li>Interventional radiology, cardiovascular imaging, and catheter-based procedures</li>
    <li>Learned the physics and human factors behind imaging interpretation</li>
    <li>Studied trade-offs in device selection based on patient anatomy and risk</li>
  </ul>

  <h4>🐾 Veterinary Medicine Rotations</h4>
  <ul>
    <li>Orthopedic, emergency, and interventional procedures for small animals</li>
    <li>Compared constraints in human vs. veterinary device needs</li>
    <li>Explored opportunities for cross-species medical innovation</li>
  </ul>

  <p class="summary"><strong>Summary:</strong> These rotations deepened my understanding of how device usability, workflow design, and human factors shape real-world clinical impact. They reinforced my interest in creating medical technologies driven by safety, efficiency, and human-centered engineering.</p>
</section>

