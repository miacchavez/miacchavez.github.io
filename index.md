---
layout: page
title: Home
permalink: /
---

<link rel="stylesheet" href="/assets/css/style.css">

<style>
:root {
  --csu-green: #1e4d2b;
  --csu-gold: #c8b568;
}

/* ---------- MAIN LAYOUT ---------- */
.hero {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
  gap: 2rem;
  margin: 3rem auto;
  max-width: 1300px;
}

.hero-image img {
  width: 400px;
  height: 400px;
  object-fit: cover;
  border-radius: 50%;
  border: 6px solid var(--csu-gold);
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
}

.hero-text {
  flex: 1 1 600px;
}

.hero-text h1 {
  color: var(--csu-green);
  font-size: 2.3rem;
}

.hero-text span {
  color: var(--csu-gold);
}

.hero-text p {
  line-height: 1.6;
  font-size: 1.05rem;
}

/* ---------- BUTTONS ---------- */
.hero-buttons {
  margin-top: 1.5rem;
}

.hero-buttons a {
  background: var(--csu-green);
  color: white;
  padding: 0.7rem 1.4rem;
  border-radius: 6px;
  text-decoration: none;
  font-weight: 600;
  margin-right: 0.6rem;
  transition: 0.3s;
}

.hero-buttons a.gold {
  background: var(--csu-gold);
  color: black;
}

.hero-buttons a:hover {
  opacity: 0.9;
  transform: translateY(-2px);
}

/* ---------- IMAGE GALLERY ---------- */
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1rem;
  margin: 3rem auto;
  max-width: 1300px;
}

.gallery img {
  width: 100%;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.15);
}

.gallery figcaption {
  text-align: center;
  font-size: 0.9rem;
  color: #555;
  margin-top: 0.3rem;
}

/* ---------- FOOTER ---------- */
footer {
  text-align: center;
  color: #555;
  margin-top: 4rem;
  padding-top: 2rem;
  border-top: 1px solid #eee;
  font-weight: 500;
}
</style>

<section class="hero">
  <div class="hero-image">
    <img src="/assets/images/headshot.jpg" alt="Headshot of Mia Chavez">
  </div>

  <div class="hero-text">
    <h1>Hi, I’m <span>Mia Chavez</span>.</h1>
    <p>
      I’m a <strong>Biomedical and Mechanical Engineering</strong> student at
      <strong>Colorado State University</strong>, graduating in 2027 with a Business Minor and Entrepreneurship Certificate. My passion lies in combining technical engineering, design thinking, and social impact to create human-centered innovations.
    </p>

    <p>
      I value collaboration, curiosity, and creativity — qualities that shape my approach as a researcher, leader, and changemaker. Through hands-on experiences in labs, nonprofits, and leadership roles, I strive to design technology that empowers people and strengthens communities.
    </p>

    <div class="hero-buttons">
      <a href="/about/" class="gold">About Me</a>
      <a href="/experiences/">Experiences</a>
      <a href="/skills/" class="gold">Skills</a>
      <a href="/contact/">Contact Me</a>
    </div>
  </div>
</section>

<!-- ---------- IMAGE GALLERY ---------- -->
<section>
  <div class="gallery">
    <figure>
      <img src="/assets/images/lockheed.jpg" alt="Lockheed Martin Competition">
      <figcaption>Lockheed Martin Engineering Design Competition</figcaption>
    </figure>
    <figure>
      <img src="/assets/images/immaculateheart.jpg" alt="Crossover for Change in Uganda">
      <figcaption>Empowering young women at Immaculate Heart School, Uganda (CFC)</figcaption>
    </figure>
    <figure>
      <img src="/assets/images/stryker.jpg" alt="Stryker Shadow Day">
      <figcaption>Shadowing surgeons and med reps with Stryker</figcaption>
    </figure>
    <figure>
      <img src="/assets/images/or-shadow.jpg" alt="Operating Room Shadowing in Pueblo">
      <figcaption>Observing orthopedic surgery in the OR, Pueblo, CO</figcaption>
    </figure>
  </div>
</section>

<!-- ---------- CSU 3-CIRCLE VENN SECTION ---------- -->
<section class="venn-section">
  <h2 style="text-align:center; color:#1E4D2B; margin-top:4rem;">Interdisciplinary Engineering at CSU</h2>
  <p style="text-align:center; max-width:750px; margin:0 auto 2rem;">
    This diagram illustrates how my studies in <strong>Honors, Business & Liberal Arts</strong>, 
    <strong>Mechanical Engineering</strong>, and <strong>Biomedical Engineering</strong> come together to shape how I learn, lead, and design.
  </p>

  <style>
    /* ===== VENN LAYOUT WRAPPER ===== */
    .venn-section {
      max-width: 1400px;
      margin: 0 auto 3rem;
      padding: 0 1.5rem;
    }

    .venn-layout {
      display: grid;
      grid-template-columns: 1.1fr 1fr 1.1fr;
      gap: 2.5rem;
      align-items: center;
    }

    .venn-column {
      display: flex;
      flex-direction: column;
      gap: 1.5rem;
    }

    /* ===== INFO CARDS (LEFT + RIGHT) ===== */
    .venn-card {
      position: relative;
      border-radius: 28px;
      padding: 1.1rem 1.4rem;
      background: #ffffff;
      box-shadow: 0 4px 12px rgba(0,0,0,0.06);
      font-size: 0.95rem;
      line-height: 1.4;
    }

    .venn-card h4 {
      margin: 0 0 0.2rem;
      font-size: 1.05rem;
    }

    .venn-card .subtitle {
      font-style: italic;
      font-size: 0.9rem;
      margin-bottom: 0.35rem;
      color: #555;
    }

    .venn-card p {
      margin: 0 0 0.35rem;
    }

    .venn-card ul {
      margin: 0;
      padding-left: 1.1rem;
    }

    .venn-card li {
      margin: 0.1rem 0;
    }

    .venn-icon-tag {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      width: 1.8rem;
      height: 1.8rem;
      border-radius: 0.6rem;
      font-size: 1.1rem;
      margin-right: 0.4rem;
      background: rgba(0,0,0,0.04);
    }

    /* Gradient accent and connector knobs */
    .venn-card.left {
      background: linear-gradient(to right, rgba(200,181,104,0.15), #ffffff);
    }

    .venn-card.right {
      background: linear-gradient(to left, rgba(200,181,104,0.08), #ffffff);
    }

    .venn-card.left::after,
    .venn-card.right::after {
      content: "";
      position: absolute;
      top: 50%;
      transform: translateY(-50%);
      width: 18px;
      height: 18px;
      border-radius: 6px;
      border: 2px solid rgba(0,0,0,0.15);
      background: #fff;
    }

    .venn-card.left::after {  /* knob on right side */
      right: -9px;
    }

    .venn-card.right::after { /* knob on left side */
      left: -9px;
    }

    /* Color accents for different sections */
    .card-honors h4 { color: #C8B568; }
    .card-mech h4 { color: #1E4D2B; }
    .card-bme h4 { color: #6B8E23; }
    .card-techlead h4 { color: #66754D; }
    .card-hcd h4 { color: #4A6530; }
    .card-ethics h4 { color: #BFAE77; }

    /* ===== VENN DIAGRAM ITSELF ===== */
    .venn-diagram {
      position: relative;
      width: 500px;
      height: 500px;
      margin: 0 auto;
    }

    .vd-circle {
      position: absolute;
      width: 500px;
      height: 500px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 2rem;
      color: #1E4D2B;
      box-shadow: 0 6px 14px rgba(0,0,0,0.12);
      background: #eee;
      opacity: 0.96;
    }

    .vd-circle span {
      background: rgba(255,255,255,0.8);
      width: 64px;
      height: 64px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    /* Top: Honors / Business / Liberal Arts */
    .vd-top {
      left: 50%;
      top: -5px;
      transform: translateX(-50%);
      background: radial-gradient(circle at 30% 20%, #fff, #C8B568);
    }

    /* Bottom-left: Mechanical */
    .vd-left {
      left: 35px;
      bottom: 5px;
      background: radial-gradient(circle at 30% 20%, #fff, #1E4D2B);
      color: #ffffff;
    }

    /* Bottom-right: Biomedical */
    .vd-right {
      right: 35px;
      bottom: 5px;
      background: radial-gradient(circle at 30% 20%, #fff, #6B8E23);
      color: #ffffff;
    }

    /* Center overlap circle */
    .vd-center {
      position: absolute;
      left: 50%;
      top: 52%;
      transform: translate(-50%, -50%);
      width: 130px;
      height: 130px;
      border-radius: 50%;
      background: #E8E4D0;
      box-shadow: 0 4px 10px rgba(0,0,0,0.18);
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      text-align: center;
      font-size: 0.8rem;
      color: #1E4D2B;
      font-weight: 600;
    }

    .vd-center span.icon {
      font-size: 1.5rem;
      margin-bottom: 0.2rem;
    }

    /* ===== BOTTOM SUMMARY CARD ===== */
    .venn-summary {
      max-width: 700px;
      margin: 3rem auto 0;
      border-radius: 26px;
      padding: 1.2rem 1.6rem;
      background: linear-gradient(to right, rgba(30,77,43,0.06), rgba(200,181,104,0.12));
      box-shadow: 0 4px 12px rgba(0,0,0,0.06);
      text-align: center;
      font-size: 0.97rem;
    }

    .venn-summary-title {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      margin-bottom: 0.2rem;
      font-weight: 600;
      color: #1E4D2B;
    }

    .venn-summary-title span.icon {
      width: 1.8rem;
      height: 1.8rem;
      border-radius: 0.6rem;
      display: flex;
      align-items: center;
      justify-content: center;
      margin-right: 0.4rem;
      background: rgba(255,255,255,0.7);
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    /* ===== RESPONSIVE ===== */
    @media (max-width: 900px) {
      .venn-layout {
        grid-template-columns: 1fr;
      }
      .venn-column {
        order: 2;
      }
      .venn-center-column {
        order: 1;
      }
      .venn-card.left::after,
      .venn-card.right::after {
        display: none;
      }
    }

  </style>

  <div class="venn-layout">
    <!-- LEFT COLUMN: three main disciplines -->
    <div class="venn-column">
      <!-- Honors / Business / Liberal Arts -->
      <div class="venn-card left card-honors">
        <h4><span class="venn-icon-tag">💼</span>Honors, Business & Liberal Arts</h4>
        <div class="subtitle">Leadership through interdisciplinary thinking</div>
        <p>
          Developing communication, ethics, and entrepreneurship skills that support thoughtful, people-centered engineering decisions.
        </p>
        <ul>
          <li>Ethical decision-making</li>
          <li>Leadership and project management</li>
          <li>Public speaking and collaboration</li>
          <li>Strategic and analytical thinking</li>
          <li>Entrepreneurial and innovative mindset</li>
        </ul>
      </div>

      <!-- Mechanical Engineering -->
      <div class="venn-card left card-mech">
        <h4><span class="venn-icon-tag">⚙️</span>Mechanical Engineering</h4>
        <div class="subtitle">Designing with precision and purpose</div>
        <p>
          Applying mechanics and materials science to prototype and optimize systems that balance function, safety, and performance.
        </p>
        <ul>
          <li>CAD and mechanical design (SolidWorks)</li>
          <li>Prototyping and hands-on fabrication</li>
          <li>Materials analysis and stress testing</li>
          <li>Experimental data collection and calibration</li>
          <li>Iterative design and system optimization</li>
        </ul>
      </div>

      <!-- Biomedical Engineering -->
      <div class="venn-card left card-bme">
        <h4><span class="venn-icon-tag">🩺</span>Biomedical Engineering</h4>
        <div class="subtitle">Engineering solutions that improve lives</div>
        <p>
          Integrating engineering with human biology to create accessible medical tools and technologies that support health and recovery.
        </p>
        <ul>
          <li>Human-centered medical device design</li>
          <li>Biomechanics and physiology awareness</li>
          <li>Device usability and safety testing</li>
          <li>Research in orthopedic and assistive technologies</li>
          <li>Healthcare-focused data analysis</li>
        </ul>
      </div>
    </div>

    <!-- CENTER COLUMN: Venn diagram -->
    <div class="venn-center-column">
      <div class="venn-diagram" aria-label="Venn diagram of Mia Chavez's interdisciplinary skills">
        <div class="vd-circle vd-top"><span>💼</span></div>
        <div class="vd-circle vd-left"><span>⚙️</span></div>
        <div class="vd-circle vd-right"><span>🩺</span></div>

        <div class="vd-center">
          <span class="icon">🔗</span>
          Interdisciplinary<br>Problem-Solving
        </div>
      </div>
    </div>

    <!-- RIGHT COLUMN: overlaps -->
    <div class="venn-column">
      <!-- Technical Leadership (Honors + Mechanical) -->
      <div class="venn-card right card-techlead">
        <h4><span class="venn-icon-tag">🧠</span>Technical Leadership</h4>
        <div class="subtitle">Where leadership and engineering meet</div>
        <p>
          Guiding teams and projects by combining clear communication with strong technical understanding.
        </p>
        <ul>
          <li>Cross-disciplinary teamwork</li>
          <li>Strategic project coordination</li>
          <li>Decision-making under constraints</li>
          <li>Translating engineering ideas to stakeholders</li>
          <li>Systems-level planning</li>
        </ul>
      </div>

      <!-- Human-Centered Design (Mechanical + Biomedical) -->
      <div class="venn-card right card-hcd">
        <h4><span class="venn-icon-tag">🦾</span>Human-Centered Design</h4>
        <div class="subtitle">Where design meets empathy</div>
        <p>
          Creating tools and devices that are functional, intuitive, and responsive to real human needs.
        </p>
        <ul>
          <li>Prototyping assistive and medical devices</li>
          <li>Comfort, safety, and usability focus</li>
          <li>Collecting feedback from users & teams</li>
          <li>Iterative testing and refinement</li>
          <li>Designing for real-world environments</li>
        </ul>
      </div>

      <!-- Healthcare Innovation & Ethics (Honors + Biomedical) -->
      <div class="venn-card right card-ethics">
        <h4><span class="venn-icon-tag">💡</span>Healthcare Innovation & Ethics</h4>
        <div class="subtitle">Innovation grounded in responsibility</div>
        <p>
          Ensuring that biomedical technologies are developed with equity, access, and long-term impact in mind.
        </p>
        <ul>
          <li>Ethical and global health perspectives</li>
          <li>Awareness of regulatory pathways</li>
          <li>Translating research to real communities</li>
          <li>Evaluating impact and accessibility</li>
          <li>Designing sustainable solutions</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- Bottom center summary box -->
  <div class="venn-summary">
    <div class="venn-summary-title">
      <span class="icon">🌱</span>
      Interdisciplinary Engineering Identity
    </div>
    <p>
      At the intersection of these three fields, I approach engineering as a way to connect people, solve meaningful problems,
      and design solutions that are both technically sound and deeply human.
    </p>
  </div>
</section>
