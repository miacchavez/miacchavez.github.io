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
    <a href="#engineering-projects">Engineering Projects</a>
    <a href="#business">Business & Nonprofit</a>
    <a href="#athletics">Athletic Experience</a>
    <a href="#service">Service Industry</a>
    <a href="#leadership">Research & Leadership</a>
    <a href="#honors">Honors & Recognition</a>
  </div>
</section>

<style>
.experience-hero {
  text-align: center;
  margin: 4rem auto 2rem;
  max-width: 900px;
}
.experience-hero h1 {
  color: #1e4d2b;
  font-size: 2.5rem;
  border-bottom: 3px solid #c8b568;
  display: inline-block;
  padding-bottom: 0.5rem;
}
.experience-hero .intro {
  margin-top: 1rem;
  font-size: 1.1rem;
  color: #444;
}

/* ----- EXPERIENCE BUTTONS ----- */
.experience-buttons {
  margin-top: 2rem;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 1rem;
}

/* Alternating button colors */
.experience-buttons.alt-color a {
  padding: 0.8rem 1.4rem;
  border-radius: 10px;
  text-decoration: none;
  font-weight: 600;
  color: white;
  transition: 0.3s ease;
  border: 2px solid transparent;
}

/* Alternate Green and Gold Colors */
.experience-buttons.alt-color a:nth-child(odd) {
  background-color: #1e4d2b;   /* Deep CSU Green */
}

.experience-buttons.alt-color a:nth-child(even) {
  background-color: #c8b568;   /* Gold */
  color: black;
}

/* Hover Styling */
.experience-buttons.alt-color a:hover {
  transform: translateY(-2px);
  border-color: #00000025;
  box-shadow: 0 4px 10px rgba(0,0,0,0.15);
}

/* ---------- SECTION STYLES ---------- */
.experience-section {
  margin: 4rem auto;
  max-width: 1000px;
  padding: 0 2rem;
  line-height: 1.8;
  color: #333;
}
.experience-section h2 {
  color: #1e4d2b;
  font-size: 2rem;
  border-bottom: 3px solid #c8b568;
  display: inline-block;
  margin-bottom: 1rem;
}
.experience-section .tagline {
  color: #666;
  font-size: 1.1rem;
  margin-bottom: 1.5rem;
}
.experience-section h3 {
  color: #1e4d2b;
  margin-top: 1.5rem;
  font-size: 1.25rem;
}
.experience-section ul {
  list-style-type: disc;
  margin-left: 1.5rem;
  margin-bottom: 0.5rem;
}
.experience-section p strong {
  color: #1e4d2b;
}
html {
  scroll-behavior: smooth;
}
</style>
