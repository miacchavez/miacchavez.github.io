---
layout: page
title: Contact Me
permalink: /contact/
---

<link rel="stylesheet" href="/assets/css/style.css">

<!-- ---------- CONTACT SECTION ---------- -->
<section class="contact-section">
  <h1>Let’s Connect</h1>
  <p class="tagline">
    Always open to new opportunities, collaborations, and conversations that spark innovation and impact.
  </p>

  <p class="intro">
    Let’s connect and build something meaningful together. Whether you’d like to collaborate, ask questions, or learn more about my work — I’d love to hear from you.
  </p>

  <div class="contact-info">
    <p><strong>Email:</strong> <a href="mailto:miacchavez10@gmail.com">miacchavez10@gmail.com</a></p>
    <p><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/mia-c-chavez" target="_blank">www.linkedin.com/in/mia-c-chavez</a></p>
    <p><strong>Phone:</strong> <a href="tel:+17199302125">(719) 930-2125</a></p>
  </div>

  <div class="contact-buttons">
    <a href="mailto:miacchavez10@gmail.com" class="gold">Email Me</a>
    <a href="https://www.linkedin.com/in/mia-c-chavez" target="_blank">Visit LinkedIn</a>
  </div>
</section>

<style>
/* ---------- CONTACT SECTION ---------- */
.contact-section {
  max-width: 800px;
  margin: 6rem auto;
  padding: 3rem 2rem;
  text-align: center;
  background: linear-gradient(to right, rgba(200,181,104,0.07), rgba(255,255,255,0.9));
  border-radius: 20px;
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.08);
}

.contact-section h1 {
  color: #1e4d2b; /* CSU green */
  font-size: 2.3rem;
  margin-bottom: 0.5rem;
}

.contact-section .tagline {
  color: #444;
  font-size: 1.1rem;
  font-style: italic;
  margin-bottom: 1.8rem;
}

.contact-section .intro {
  font-size: 1.1rem;
  line-height: 1.7;
  color: #333;
  margin-bottom: 2rem;
}

.contact-info p {
  font-size: 1.05rem;
  color: #1e4d2b;
  margin: 0.6rem 0;
}

.contact-info a {
  color: #1e4d2b;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.3s ease;
}

.contact-info a:hover {
  color: #c8b568; /* CSU gold */
}

/* ---------- CONTACT BUTTONS ---------- */
.contact-buttons {
  margin-top: 2.5rem;
  display: flex;
  justify-content: center;
  gap: 1.2rem;
  flex-wrap: wrap;
}

.contact-buttons a {
  background-color: #1e4d2b;
  color: white;
  font-weight: 600;
  text-decoration: none;
  padding: 0.9rem 2rem;
  border-radius: 8px;
  font-size: 1rem;
  transition: 0.3s ease;
}

.contact-buttons a.gold {
  background-color: #c8b568;
  color: black;
}

.contact-buttons a:hover {
  opacity: 0.9;
  transform: translateY(-2px);
}

/* ---------- RESPONSIVE ---------- */
@media (max-width: 768px) {
  .contact-section {
    padding: 2rem 1.5rem;
  }

  .contact-buttons {
    flex-direction: column;
    align-items: center;
  }

  .contact-buttons a {
    width: 80%;
    max-width: 300px;
  }
}
</style>
