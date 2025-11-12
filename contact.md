---
layout: page
title: Contact Me
permalink: /contact/
---

<link rel="stylesheet" href="/assets/css/style.css">

<!-- ---------- CONTACT SECTION ---------- -->
<section class="contact-section">
  <div class="overlay"></div>
  <div class="contact-content">
    <h1>Let’s Connect and Build Something Meaningful</h1>
    <p>
      I’d love to hear from you — whether it’s about engineering, leadership, nonprofit work, or collaboration opportunities.
    </p>

    <div class="contact-info">
      <p><strong>Email:</strong> <a href="mailto:miacchavez10@gmail.com">miacchavez10@gmail.com</a></p>
      <p><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/mia-c-chavez" target="_blank">linkedin.com/in/mia-c-chavez</a></p>
      <p><strong>Phone:</strong> <a href="tel:7199302125">(719) 930-2125</a></p>
    </div>

    <div class="hero-buttons">
      <a href="/about/" class="gold">About Me</a>
      <a href="/skills/">Skills</a>
      <a href="/experiences/" class="gold">Experiences</a>
    </div>
  </div>
</section>

<style>
/* ---------- CONTACT SECTION ---------- */
.contact-section {
  position: relative;
  background: url("/assets/images/connecting.jpg") center center / cover no-repeat;
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 4rem 2rem;
  text-align: center;
  color: white;
  overflow: hidden;
}

/* Semi-transparent overlay for readability */
.contact-section .overlay {
  position: absolute;
  inset: 0;
  background: rgba(30, 77, 43, 0.7); /* CSU green overlay, 70% opacity */
  z-index: 1;
}

/* Content styling */
.contact-content {
  position: relative;
  z-index: 2;
  max-width: 700px;
  background: rgba(255, 255, 255, 0.08);
  padding: 3rem 2rem;
  border-radius: 16px;
  backdrop-filter: blur(6px);
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.25);
}

/* Text */
.contact-content h1 {
  font-size: 2.3rem;
  color: #c8b568;
  margin-bottom: 1rem;
}

.contact-content p {
  font-size: 1.1rem;
  line-height: 1.7;
  margin-bottom: 1.2rem;
  color: #f0f0f0;
}

/* Contact info */
.contact-info p {
  margin: 0.5rem 0;
  font-size: 1.05rem;
}

.contact-info a {
  color: #c8b568;
  text-decoration: none;
  font-weight: 500;
}

.contact-info a:hover {
  text-decoration: underline;
}

/* Buttons (match homepage) */
.hero-buttons {
  margin-top: 2rem;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 1rem;
}

.hero-buttons a {
  background-color: #1e4d2b;
  color: white;
  font-weight: 600;
  text-decoration: none;
  padding: 0.7rem 1.8rem;
  border-radius: 8px;
  transition: 0.3s ease;
}

.hero-buttons a.gold {
  background-color: #c8b568;
  color: black;
}

.hero-buttons a:hover {
  opacity: 0.9;
  transform: translateY(-2px);
}

/* ---------- RESPONSIVE ---------- */
@media (max-width: 768px) {
  .contact-content {
    padding: 2rem 1.5rem;
  }

  .contact-content h1 {
    font-size: 2rem;
  }

  .contact-info p {
    font-size: 1rem;
  }
}
</style>
