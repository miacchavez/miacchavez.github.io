---
layout: page
title: Skills
permalink: /skills/
---

<link rel="stylesheet" href="/assets/css/style.css">
<!-- ==================== TOP INTERDISCIPLINARY IMAGE ==================== -->
<section class="skills-banner">
  <img src="/assets/images/1.png" alt="Interdisciplinary Skills Diagram">
</section>

<!-- ==================== GOLD EXPANDABLE SKILL BUTTONS ==================== -->
<section class="skills-expansion">
  <div class="skills-buttons">
    <!-- Honors & Business -->
    <button class="skill-toggle">
      Honors & Business <span class="arrow">▶</span>
    </button>
    <div class="skill-content">
      <img src="/assets/images/8.png" alt="Honors and Business Skills">
    </div>
    <!-- Mechanical Engineering -->
    <button class="skill-toggle">
      Mechanical Engineering <span class="arrow">▶</span>
    </button>
    <div class="skill-content">
      <img src="/assets/images/2.png" alt="Mechanical Engineering Skills">
    </div>
    <!-- Biomedical Engineering -->
    <button class="skill-toggle">
      Biomedical Engineering <span class="arrow">▶</span>
    </button>
    <div class="skill-content">
      <img src="/assets/images/3.png" alt="Biomedical Engineering Skills">
    </div>
    <!-- Technical Leadership -->
    <button class="skill-toggle">
      Technical Leadership <span class="arrow">▶</span>
    </button>
    <div class="skill-content">
      <img src="/assets/images/4.png" alt="Technical Leadership Skills">
    </div>
    <!-- Human-Centered Design -->
    <button class="skill-toggle">
      Human-Centered Design <span class="arrow">▶</span>
    </button>
    <div class="skill-content">
      <img src="/assets/images/5.png" alt="Human-Centered Design Skills">
    </div>
    <!-- Health Innovation & Ethics -->
    <button class="skill-toggle">
      Health Innovation & Ethics <span class="arrow">▶</span>
    </button>
    <div class="skill-content">
      <img src="/assets/images/6.png" alt="Health Innovation & Ethics Diagram">
    </div>
  </div>
</section>

<!-- ==================== BOTTOM LARGE IMAGE ==================== -->
<section class="skills-banner">
  <img src="/assets/images/7.png" alt="Future Engineering Vision Graphic">
</section>

<section class="skills-section">
  <h1>Explore More Skills Below</h1>

  <div class="accordion">
    <!-- Engineering & Technical Skills -->
    <div class="accordion-item">
      <button class="accordion-header">Engineering & Technical Skills</button>
      <div class="accordion-content">
        <p>
          Hands-on experience designing, testing, and fabricating mechanical and biomedical systems, guided by safety, precision, and creativity.
        </p>
        <ul>
          <li>SolidWorks Certified; proficient in 3D modeling & simulation</li>
          <li>HAAS CNC Mill & Lathe Certified; capable on manual mill, lathe, belt grinder, laser, and engraver</li>
          <li>Medical device design and evaluation</li>
          <li>Circuit design, soldering, and prototyping</li>
          <li>Data analysis, MATLAB, and LabVIEW</li>
        </ul>
      </div>
    </div>
    <!-- Research, Leadership & Communication -->
    <div class="accordion-item">
      <button class="accordion-header">Research, Leadership & Communication</button>
      <div class="accordion-content">
        <p>
          Proven ability to lead teams, communicate across disciplines, and foster mentorship through research, service, and athletics.
        </p>
        <ul>
          <li>Public speaking and presentation skills</li>
          <li>Mentorship, coaching, and student engagement</li>
          <li>Conflict resolution and collaboration under pressure</li>
          <li>Travel and event coordination</li>
          <li>Independent research and analytical writing</li>
        </ul>
      </div>
    </div>
    <!-- Innovation, Business & Design Thinking -->
    <div class="accordion-item">
      <button class="accordion-header">Innovation, Business & Design Thinking</button>
      <div class="accordion-content">
        <p>
          Entrepreneurial mindset with a focus on creative problem-solving, strategic planning, and user-centered design across technical and social contexts.
        </p>
        <ul>
          <li>Entrepreneurship and project development</li>
          <li>Graphic design and visual storytelling</li>
          <li>Marketing, outreach, and stakeholder communication</li>
          <li>Program development and systems innovation</li>
          <li>Leadership in nonprofit and organizational management</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<style>
/* ---------- SKILLS SECTION ---------- */
.skills-section {
  max-width: 900px;
  margin: 4rem auto;
  padding: 2rem;
  text-align: center;
}

.skills-section h1 {
  color: #1e4d2b;
  font-size: 2.2rem;
  margin-bottom: 2rem;
}

/* ---------- ACCORDION ---------- */
.accordion {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.accordion-item {
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

.accordion-header {
  background-color: #1e4d2b;
  color: white;
  cursor: pointer;
  padding: 1rem 1.2rem;
  width: 100%;
  border: none;
  outline: none;
  text-align: left;
  font-size: 1.1rem;
  font-weight: 600;
  transition: background-color 0.3s ease;
}

.accordion-header:hover {
  background-color: #2a633b;
}

.accordion-header.active {
  background-color: #c8b568;
  color: black;
}

.accordion-content {
  max-height: 0;
  overflow: hidden;
  background: #fffdf7;
  padding: 0 1.5rem;
  text-align: left;
  line-height: 1.6;
  transition: max-height 0.5s ease, padding 0.3s ease;
}

.accordion-content p {
  margin: 1rem 0 0.5rem;
  color: #333;
}

.accordion-content ul {
  margin: 0 0 1rem 1.2rem;
}

.accordion-content li {
  margin-bottom: 0.5rem;
}

/* ---------- RESPONSIVE ---------- */
@media (max-width: 768px) {
  .skills-section {
    padding: 1rem;
  }
  .accordion-header {
    font-size: 1rem;
  }
}
</style>
<style>
.skills-banner img {
  width: 100%;
  max-height: 420px;
  object-fit: contain;
  display: block;
  margin: 0 auto 2rem;
  border-bottom: 6px solid var(--csu-gold);
}

/* ---------- GOLD EXPANDABLE BUTTONS ---------- */
.skills-expansion {
  text-align: center;
  max-width: 950px;
  margin: 0 auto 4rem;
}

.skills-buttons {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.skill-toggle {
  background: var(--csu-gold);
  color: black;
  font-weight: 700;
  border: none;
  padding: 0.8rem 1.2rem;
  border-radius: 8px;
  font-size: 1.1rem;
  cursor: pointer;
  transition: 0.3s;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.skill-toggle:hover {
  background: #bfa65d;
}

.skill-toggle .arrow {
  margin-left: 0.8rem;
  transition: transform 0.3s ease;
  color: #333;
}

.skill-content {
  display: none;
  margin-top: 0.5rem;
  animation: fadein .35s ease-in-out;
}

.skill-content img {
  width: 100%;
  max-width: 950px;
  border-radius: 12px;
  border: 4px solid var(--csu-green);
  box-shadow: 0 4px 10px rgba(0,0,0,0.15);
}

@keyframes fadein {
  from { opacity: 0; transform: translateY(-4px); }
  to { opacity: 1; transform: translateY(0); }
}
</style>

<script>
document.querySelectorAll(".accordion-header").forEach(button => {
  button.addEventListener("click", () => {
    const accordion = button.parentElement.parentElement;
    const openItem = accordion.querySelector(".accordion-header.active");

    if (openItem && openItem !== button) {
      openItem.classList.remove("active");
      openItem.nextElementSibling.style.maxHeight = null;
      openItem.nextElementSibling.style.padding = "0 1.5rem";
    }

    button.classList.toggle("active");
    const content = button.nextElementSibling;

    if (button.classList.contains("active")) {
      content.style.maxHeight = content.scrollHeight + "px";
      content.style.padding = "1rem 1.5rem";
    } else {
      content.style.maxHeight = null;
      content.style.padding = "0 1.5rem";
    }
  });
});
</script>
<script>
document.querySelectorAll(".skill-toggle").forEach(btn => {
  btn.addEventListener("click", () => {
    const content = btn.nextElementSibling;
    const arrow = btn.querySelector(".arrow");
    const isOpen = content.style.display === "block";
    content.style.display = isOpen ? "none" : "block";
    arrow.style.transform = isOpen ? "rotate(0deg)" : "rotate(90deg)";
  });
});
</script>

