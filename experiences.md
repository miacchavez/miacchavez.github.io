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

  <!-- Engineering Experience Dropdown -->
  <div class="dropdown">
    <button class="dropbtn">Engineering Experience ▾</button>
    <div class="dropdown-content">
      <a href="#engineering-experience">Stryker Industry Day & Cadaver Lab</a>
      <a href="#clinical-rotations">Clinical Rotations at UCHealth</a>
      <a href="#lockheed">Lockheed Martin Ethics in Engineering Case Competition</a>
      <a href="#empirical">Engineering Capstone: Empirical Technologies Corp.</a>
    </div>
  </div>

  <!-- Engineering Projects & Research Dropdown -->
  <div class="dropdown">
    <button class="dropbtn">Engineering Projects & Research ▾</button>
    <div class="dropdown-content">
      <a href="#led-battery-tester">LED Battery Tester Project</a>
      <a href="#turtle-feeder">Turtle Feeder Mechanical System</a>
      <a href="#mri-case">MRI-Safe Protective Case Proposal</a>
      <a href="#extremity-normothermia">Extremity Normothermia Support Proposal</a>
      <a href="#spur-research">Scott Undergraduate Research – CSU Spur</a>
    </div>
  </div>

  <!-- Business & Nonprofit Work Dropdown -->
  <div class="dropdown">
    <button class="dropbtn">Business & Nonprofit Work ▾</button>
    <div class="dropdown-content">
      <a href="#cfc-cofounder">Crossover for Change – Co-Founder</a>
      <a href="#pro-sports-mvp">Pro Sports MVP – Intern</a>
      <a href="#noco-supervisor">NoCo Sports Center – Supervisor</a>
    </div>
  </div>

  <!-- Leadership Dropdown -->
  <div class="dropdown">
    <button class="dropbtn">Leadership ▾</button>
    <div class="dropdown-content">
      <a href="#hsa-president">CSU Honors Student Association – President</a>
      <a href="#honors-ambassador">CSU Honors Ambassador</a>
      <a href="#bio-la">CSU Biology Learning Assistant</a>
      <a href="#wcb-president">CSU Women’s Club Basketball – President</a>
    </div>
  </div>

  <!-- Athletics & Coaching Dropdown -->
  <div class="dropdown">
    <button class="dropbtn">Athletics &amp; Coaching ▾</button>
    <div class="dropdown-content">
      <a href="#wcb-coach-player">CSU Women’s Club Basketball – Coach/Player</a>
      <a href="#crusaders-coach">Youth Coaching – Colorado Springs Crusaders</a>
      <a href="#css-camps">Basketball Camps – The Colorado Springs School</a>
    </div>
  </div>

  <!-- Service Industry Dropdown -->
  <div class="dropdown">
    <button class="dropbtn">Service Industry ▾</button>
    <div class="dropdown-content">
      <a href="#broadmoor">The Broadmoor – Server/Food Runner</a>
      <a href="#skyline-nails">Skyline Nails &amp; Spa – Receptionist</a>
    </div>
  </div>

  <!-- Awards & Honors Dropdown -->
  <div class="dropdown">
    <button class="dropbtn">Awards &amp; Honors ▾</button>
    <div class="dropdown-content">
      <a href="#scott-scholarship">CSU Walter Scott Jr. Undergraduate Scholarship</a>
      <a href="#gazette-brightest">Gazette Charities Best &amp; Brightest</a>
      <a href="#innovator-merit">CSS Innovator Merit Scholarship</a>
      <a href="#faculty-cup">CSS Faculty Cup Award</a>
    </div>
  </div>

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
/* ---------- DROPDOWN MENUS FOR CATEGORY BUTTONS ---------- */
.dropdown {
  position: relative;
  display: inline-block;
}

.dropbtn {
  border: none;
  cursor: pointer;
  padding: 0.8rem 1.4rem;
  border-radius: 10px;
  font-weight: 600;
  font-size: 1rem;
  transition: 0.3s ease;
  border: 2px solid transparent;
}

/* Alternate green and gold by position */
.experience-buttons.alt-color .dropdown:nth-child(odd) .dropbtn {
  background-color: var(--csu-green);
  color: white;
}
.experience-buttons.alt-color .dropdown:nth-child(even) .dropbtn {
  background-color: var(--csu-gold);
  color: black;
}

/* Hover effects for dropdown buttons */
.dropdown:hover .dropbtn {
  transform: translateY(-2px);
  border-color: #00000025;
  box-shadow: 0 4px 10px rgba(0,0,0,0.15);
}

/* Dropdown content panel */
.dropdown-content {
  display: none;
  position: absolute;
  background-color: white;
  min-width: 260px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.15);
  border-radius: 10px;
  z-index: 50;
  overflow: hidden;
}

/* Links inside dropdown */
.dropdown-content a {
  color: var(--csu-green);
  padding: 0.6rem 1rem;
  text-decoration: none;
  display: block;
  font-weight: 500;
  border-bottom: 1px solid #eee;
  background-color: white;
}

.dropdown-content a:last-child {
  border-bottom: none;
}

/* Hover on dropdown items */
.dropdown-content a:hover {
  background-color: var(--csu-gold);
  color: black;
}

/* Show dropdown on hover or focus (better for keyboard/mobiles) */
.dropdown:hover .dropdown-content,
.dropdown:focus-within .dropdown-content {
  display: block;
}

/* Small screens: stack dropdowns nicely */
@media (max-width: 768px) {
  .experience-buttons {
    flex-direction: column;
    align-items: stretch;
  }

  .dropdown {
    width: 100%;
  }

  .dropbtn {
    width: 100%;
    text-align: center;
  }

  .dropdown-content {
    position: static;
    box-shadow: none;
    border-radius: 0 0 10px 10px;
    border: 1px solid #ddd;
    border-top: none;
  }
}

/* ----- FIX BANNER IMAGES FROM GETTING CUT OFF ----- */
.experience-banner img {
  width: 100%;
  height: auto !important;
  max-height: none !important;
  object-fit: contain !important;
  border-radius: 12px;
  border: 3px solid var(--csu-green);
  box-shadow: 0 4px 10px rgba(0,0,0,0.15);
  margin: 1.5rem 0;
}

/* Subheader Enhancement (Clinical section) */
.experience-section h4 {
  margin-top: 1.8rem;
  font-size: 1.15rem;
  font-weight: 700;
  color: var(--csu-gold);
  letter-spacing: 0.3px;
}

.pdf-link {
  margin-top: 1.5rem;
}

.pdf-link a {
  display: inline-block;
  padding: 0.7rem 1.4rem;
  border-radius: 8px;
  background-color: var(--csu-green);
  color: #fff;
  text-decoration: none;
  font-weight: 600;
  transition: 0.25s ease;
}

.pdf-link a:hover {
  background-color: var(--csu-gold);
  color: #000;
  box-shadow: 0 4px 10px rgba(0,0,0,0.15);
  transform: translateY(-1px);
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
/* other existing styles... */

/* ----- FIX BANNER IMAGES FROM GETTING CUT OFF ----- */
.experience-banner img {
  width: 100%;
  height: auto !important;
  max-height: none !important;
  object-fit: contain !important;
  border-radius: 12px;
  border: 3px solid var(--csu-green);
  box-shadow: 0 4px 10px rgba(0,0,0,0.15);
  margin: 1.5rem 0;
}

/* ----- FIX SUB-IMAGE SIZING (SECOND IMAGE IN A SECTION) ----- */
.experience-subimage img {
  width: 100%;
  max-width: 650px;
  height: auto !important;
  object-fit: contain;
  display: block;
  margin: 1.2rem auto;
  border-radius: 12px;
  border: 3px solid var(--csu-gold);
  box-shadow: 0 4px 10px rgba(0,0,0,0.15);
}
</style>

<style>
/* ---------- FEATURED EXPERIENCE BANNER ---------- */
.experience-featured img {
  width: 100%;
  height: auto;            /* keep full proportions */
  object-fit: contain;     /* prevent cropping */
  border-bottom: 6px solid var(--csu-gold);
  display: block;
  margin: 0 0 2.5rem 0;
}

/* Featured Image */
.card-image img {
  width: 100%;
  height: auto;
  border-radius: 12px;
  border: 4px solid var(--csu-green);
  box-shadow: 0 4px 10px rgba(0,0,0,0.15);
}

/* Caption Button Under Image */
.card-title {
  text-align: center;
  margin-top: 0.6rem;
}

.expand-btn {
  background: none;
  border: none;
  font-weight: 700;
  font-size: 1.15rem;
  cursor: pointer;
  color: var(--csu-green);
}

.expand-btn:hover {
  color: var(--csu-gold);
}

.expand-btn .arrow {
  font-size: 1rem;
  margin-left: 0.3rem;
  color: #777;
  transition: transform .3s ease;
}

/* Hidden Content */
.card-content {
  display: none;
  margin-top: 1rem;
  animation: fadein .3s ease-in-out;
}

@keyframes fadein {
  from { opacity: 0; transform: translateY(-4px); }
  to { opacity: 1; transform: translateY(0); }
}
/* ---------- EXPERIENCE GRID LAYOUT ---------- */
.experience-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2rem;
  max-width: 1100px;
  margin: 0 auto;
}

/* Each card */
.experience-card {
  border: 1px solid #ddd;
  border-radius: 10px;
  padding-bottom: 1rem;
  background: #fff;
  box-shadow: 0 3px 8px rgba(0,0,0,0.08);
}
.experience-card {
  overflow: visible;
  padding-bottom: 1.2rem;
}

/* Ensure banner always looks clickable */
.experience-card .experience-banner img {
  cursor: pointer;
}

/* Card title button */
.experience-card .expand-btn {
  width: 100%;
  text-align: left;
  background: none;
  border: none;
  cursor: pointer;
  padding: 1rem 1rem 0.5rem;
  font-size: 1.15rem;
  font-weight: 700;
  color: var(--csu-green);
}

.experience-card .expand-btn:hover {
  color: var(--csu-gold);
}

.experience-card .arrow {
  float: right;
  transition: transform .3s ease;
  color: #777;
}

/* Hide content until clicked */
.experience-card .card-content {
  display: none;
  padding: 0 1rem 0.5rem 1rem;
}

/* ---------- Responsive (Mobile: 1 Column) ---------- */
@media (max-width: 900px) {
  .experience-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<!-- ===================================================================== -->
<!-- ======================== ENGINEERING EXPERIENCE ===================== -->
<!-- ===================================================================== -->

<section id="engineering-experience" class="experience-section">
  <h2>Engineering Experience</h2>
  <p class="tagline"><em>Learning from regulated industry, clinical environments, and real medical systems.</em></p>

  <div class="experience-grid">

<!-- STRYKER EXPERIENCE CARD -->
<section id="stryker" class="experience-card">

  <figure class="card-image">
    <img src="/assets/images/strykerfullgroup.jpg" alt="Stryker Industry Day group photo">
    <figcaption class="card-title">
      <button class="expand-btn">
         Stryker Industry Day & Cadaver Lab (2024)
        <span class="arrow">▶</span>
      </button>
    </figcaption>
  </figure>

  <div class="card-content">
    <p>
      I attended Stryker’s Sports Medicine Industry Day, an immersive mentorship and training experience focused on how engineering, business strategy, and clinical needs intersect in the medical device industry. I shadowed a project management mentor, explored product development workflows, and learned how engineering roles support the commercialization of surgical tools.
    </p>
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
  </div>
</section>

<!-- LOCKHEED MARTIN EXPERIENCE CARD -->
<section id="lockheed" class="experience-card">

  <figure class="card-image">
    <img src="/assets/images/lockheed.jpg" alt="Lockheed Martin Ethics Case Competition banquet">
    <figcaption class="card-title">
      <button class="expand-btn">
        Lockheed Martin Ethics in Engineering Case Competition (2025)
        <span class="arrow">▶</span>
      </button>
    </figcaption>
  </figure>
  <div class="card-content">
    <p class="experience-intro">
      Representing Colorado State University with my teammate, D’Andre Rogers, I competed in the Lockheed Martin Ethics in Engineering Case Competition. We analyzed a complex case about <strong>HotShotAI</strong>—a fictional company integrating artificial intelligence into wildfire response—and were challenged to balance safety, profit, and public trust while making recommendations under real-time pressure.
    </p>
    <h4>Case Focus: HotShotAI & Wildfire Response</h4>
    <ul class="experience-list">
      <li>Evaluated how AI systems should prioritize limited resources during high-risk wildfire events.</li>
      <li>Identified stakeholder tensions between government agencies, local communities, firefighters, and investors.</li>
      <li>Developed recommendations prioritizing safety, transparency, and long-term credibility over short-term profit.</li>
      <li>Presented final decisions to judges in a role-play format simulating a real executive meeting.</li>
    </ul>
    <h4>What I Practiced & Learned</h4>
    <ul class="experience-list">
      <li>Communicating technical and ethical trade-offs clearly under time pressure and judge questioning.</li>
      <li>Strategic planning: identifying key arguments and dividing roles with a teammate.</li>
      <li>Translating abstract ethical frameworks into real-world engineering business decisions.</li>
      <li>Reflecting on competitor strategies to strengthen future CSU team performance.</li>
    </ul>
    <h4>Professional Development & Networking</h4>
    <ul class="experience-list">
      <li>Toured key sites in Washington, D.C., connecting policy, national security, and ethics.</li>
      <li>Joined a live call with NASA astronaut Sunita “Suni” Williams discussing reliability in life-critical decision-making.</li>
      <li>Received resume, recruiting, and career guidance from Lockheed engineers and hiring managers.</li>
      <li>Built a national network of engineering students with shared interests in responsible innovation.</li>
    </ul>
    <p class="summary">
      <strong>Summary:</strong> This competition challenged me to think critically under pressure, evaluate ethical trade-offs in engineering design, and communicate clearly in high-stakes conversations. It strengthened my commitment to working on technologies where safety and public trust matter as much as performance.
    </p>
    <p class="pdf-link">
      <a href="/assets/docs/EIEC.pdf" target="_blank" rel="noopener noreferrer">
        View Full Case Study Work
      </a>
    </p>
  </div> <!-- closes card-content -->
</section>

<!--  CLINICAL ROTATIONS EXPERIENCE CARD -->
<section id="clinical-rotations" class="experience-card">

  <figure class="card-image">
    <img src="/assets/images/or-shadow.jpg" alt="Observing orthopedic surgery and clinical workflows">
    <figcaption class="card-title">
      <button class="expand-btn">
         Clinical Rotations — BIOM 480: Clinical Experience for Bio-Innovation (2025)
        <span class="arrow">▶</span>
      </button>
    </figcaption>
  </figure>
  <div class="card-content">
    <p>
      Before this immersion course, I shadowed <strong>Dr. Eric Richter</strong> and <strong>Christin Hungerford</strong> (medical device representative), where I observed orthopedic trauma workflows and how surgeons collaborate with industry to improve patient outcomes. That experience sparked my interest in clinical innovation — leading me to pursue BIOM 480, a selective course that connects engineering students with medical environments to identify unmet clinical needs and opportunities for device development.
    </p>
    <p>
      Through this program, I completed rotations at <strong>Poudre Valley Hospital (PVH)</strong>, <strong>Medical Center of the Rockies (MCR)</strong>, and the <strong>CSU Veterinary Teaching Hospital</strong> — exploring how devices, human factors, and workflow design influence patient safety and care.
    </p>
    <h4>Surgical & Procedure Observations</h4>
    <ul>
      <li>Orthopedic trauma, thoracic surgery, vascular, and robotic-assisted procedures</li>
      <li>Observed surgeon–nurse–rep dynamics and device setup workflows</li>
      <li>Studied error prevention strategies and sterile field design</li>
    </ul>
    <h4>Medical Device & Imaging Exposure</h4>
    <ul>
      <li>Interventional radiology, cardiovascular imaging, and catheter-based procedures</li>
      <li>Learned the physics and human factors behind imaging interpretation</li>
      <li>Studied trade-offs in device selection based on patient anatomy and risk</li>
    </ul>
    <h4>Veterinary Medicine Rotations</h4>
    <ul>
      <li>Orthopedic, emergency, and interventional procedures for small animals</li>
      <li>Compared constraints in human vs. veterinary device needs</li>
      <li>Explored opportunities for cross-species medical innovation</li>
    </ul>
    <p class="summary"><strong>Summary:</strong> These rotations deepened my understanding of how device usability, workflow design, and human factors shape real-world clinical impact. They reinforced my interest in creating medical technologies driven by safety, efficiency, and human-centered engineering.</p>
  </div>
</section>

<!-- EMPIRICAL TECHNOLOGIES CORP. EXPERIENCE CARD -->
<section id="empirical" class="experience-card">

  <figure class="card-image">
    <img src="/assets/images/engineering_lab.png" alt="Mechanical testing lab at Empirical Technologies Corp.">
    <figcaption class="card-title">
      <button class="expand-btn">
        Engineering Capstone: Implant Testing & Biomechanics at Empirical Technologies Corp. (2022)
        <span class="arrow">▶</span>
      </button>
    </figcaption>
  </figure>
  <div class="card-content">
    <p class="experience-intro">
      For my senior Capstone, I spent fifty hours shadowing engineers at Empirical Technologies Corp., a contract testing lab for orthopedic and other biomedical implants. I entered with three guiding questions: how biomedical engineers design testing methods, how test results lead to product improvements, and which education pathways lead to this kind of work.
    </p>
    <h4>Testing Orthopedic Implants</h4>
    <ul class="experience-list">
      <li>Observed how engineers design test setups to meet ASTM and ISO standards for spinal and joint implants.</li>
      <li>Watched full workflows: building fixtures, software setup, test alignment, and documenting final results.</li>
      <li>Assisted with operational tasks such as photographing samples, organizing post-test hardware, and labeling components.</li>
      <li>Learned how failure modes provide design feedback that manufacturers use to improve product durability and safety.</li>
    </ul>
    <h4>Example Project: Spinal Implant Fatigue + Static Testing</h4>
    <p>
      A highlight of my experience was observing three spinal implant designs undergoing saline soak and mechanical testing to mimic how implants behave in the body. After timed soak periods, the implants were tested in horizontal and vertical orientations. Once I understood the protocol, I assisted with fixture setup, software control, recording failure loads, and organizing fractured components into labeled sample bags.
    </p>
    <h4>Engineering Paths & Career Insight</h4>
    <ul class="experience-list">
      <li>Interviewed engineers with backgrounds in biomedical, mechanical, and electrical engineering.</li>
      <li>One engineer held the same CSU biomedical–mechanical dual degree I am now pursuing.</li>
      <li>Saw how engineers contribute to patient care indirectly by ensuring implant reliability and regulatory compliance.</li>
    </ul>
    <h4>Independent Research & Reflection</h4>
    <p>
      Due to schedule conflicts with AP exams and then COVID-19, half of my Capstone involved independent research into the history of knee implants and biomechanics. My physics and calculus background helped me understand forces, stresses, and loading conditions that define implant performance. I realized how essential software, documentation, and data analysis are to regulated engineering work.
    </p>
    <p class="summary">
      <strong>Summary:</strong> This experience showed how biomechanics, standards, and data-driven testing protect patients and guide safer implant design. It strengthened my interest in biomedical and mechanical engineering as a bridge between surgery and lab-based testing — where engineering decisions directly influence patient safety and long-term mobility.
    </p>
  </div> <!-- closes card-content -->
</section>
</div> <!-- closes experience-grid for Engineering Experience -->
</section> <!-- closes #engineering-experience section -->
<!-- ===================================================================== -->
<!-- ================== ENGINEERING PROJECTS & RESEARCH ================== -->
<!-- ===================================================================== -->

<section id="engineering-projects-research" class="experience-section">
  <h2>Engineering Projects & Research</h2>
  <p class="tagline"><em>Hands-on builds, testing, and design work that strengthened my process + data mindset.</em></p>

  <div class="experience-grid">
    <!-- LED BATTERY TESTER / MECH 207 CARD -->
    <section id="led-battery-tester" class="experience-card">
      <figure class="card-image">
        <img src="/assets/images/LEDBatterTester.png" alt="LED Bar Graph Voltage Meter prototype">
        <figcaption class="card-title">
          <button class="expand-btn">
            LED Bar Graph Voltage Meter
            <span class="arrow">▶</span>
          </button>
        </figcaption>
      </figure>
      <div class="card-content">
        <p>
          Built a low-cost battery tester that converts a 9V battery’s voltage into a clear 5-step LED “charge level” indicator
          using Zener-diode thresholds and current-limited LED stages. The project emphasized voltage threshold design,
          verification testing, and iterative troubleshooting to improve reliability and accuracy.
        </p>
        <ul>
          <li><strong>Designed & built</strong> a 5-stage LED bar-graph meter using Zener diodes as voltage thresholds and resistors for safe current limiting.</li>
          <li><strong>Verified performance</strong> by testing single-stage thresholds, then validating full-chain sequential LED activation with increasing input voltage.</li>
          <li><strong>Troubleshot & improved accuracy</strong> by recalculating trigger points, updating Zener/resistor values, and refining thresholds for more consistent behavior.</li>
          <li><strong>Packaged the prototype</strong> with a custom 3D-printed enclosure for safer handling and a cleaner battery connection interface.</li>
        </ul>
        <p class="summary">
          <strong>Summary:</strong> Strengthened my circuit design, testing/verification, troubleshooting, and documentation skills through an end-to-end build.
        </p>
        <p class="pdf-link">
          <a href="/assets/docs/Project207.pdf" target="_blank" rel="noopener noreferrer">
            View Full Report (PDF)
          </a>
        </p>
      </div>
    </section>
<!-- TURTLE FEEDER / MECH 103 CARD -->
<section id="turtle-feeder" class="experience-card">
  <figure class="card-image">
    <img src="/assets/images/TurtleFeeder.png" alt="Automatic Turtle Feeder prototype">
    <figcaption class="card-title">
      <button class="expand-btn">
        Automatic Turtle Feeder
        <span class="arrow">▶</span>
      </button>
    </figcaption>
  </figure>
  <div class="card-content">
    <p>
      Designed and built an automatic turtle feeder to dispense food <strong>once per day for up to four days</strong>
      while the owner is away, using an Arduino-controlled servo and a rotating “ferris wheel” compartment design.
    </p>
    <ul>
      <li><strong>Built a compartment wheel</strong> (4 sections) that rotates to drop one serving per day.</li>
      <li><strong>Integrated Arduino + micro servo control</strong> using timed rotation (24-hour delay between feedings).</li>
      <li><strong>Iterated the design</strong> from an initial conveyor concept to a more reliable rotating wheel mechanism.</li>
      <li><strong>Troubleshot premature dispensing</strong> by adding a thin hot-glue lip to hold pellets until release.</li>
      <li><strong>Validated performance</strong>: dispensed the correct amount of food for four consecutive days.</li>
    </ul>
    <p class="summary">
      <strong>Summary:</strong> Strengthened my mechanical design + prototyping skills while integrating basic embedded control to solve a real user need.
    </p>
    <p class="pdf-link">
      <a href="/assets/docs/MECH103ProjectReport.pdf" target="_blank" rel="noopener noreferrer">
        View Full Report (PDF)
      </a>
    </p>
  </div>
</section>
<script>
document.addEventListener("DOMContentLoaded", () => {
  document.querySelectorAll(".expand-btn").forEach(btn => {
    btn.addEventListener("click", () => {
      const content = btn.closest("section").querySelector(".card-content");
      const arrow = btn.querySelector(".arrow");
      const isOpen = content.style.display === "block";
      // Toggle content visibility
      content.style.display = isOpen ? "none" : "block";
      // Rotate arrow
      arrow.style.transform = isOpen ? "rotate(0deg)" : "rotate(90deg)";
    });
  });
});
</script>
<!-- MRI-SAFE PROTECTIVE CASE PROJECT CARD -->
<section id="mri-case" class="experience-card">

  <figure class="card-image">
    <img src="/assets/images/philips.png" alt="Protective case concept for Philips Expression MR Wireless SpO₂ Module">
    <figcaption class="card-title">
      <button class="expand-btn">
        MRI-Safe Protective Case Design — Philips Expression MR SpO₂ Module
        <span class="arrow">▶</span>
      </button>
    </figcaption>
  </figure>

  <div class="card-content">
    <p>
      Designed a medical-grade, MRI-safe protective enclosure for the
      <strong>Philips Expression MR Wireless SpO₂ Module</strong>, a critical yet fragile device
      used during MRI procedures. The project was informed by direct clinical observation,
      technician interviews, and workflow analysis in radiology suites.
    </p>
    <ul>
      <li>
        <strong>Identified a real clinical pain point:</strong> modules costing $3,000+ are frequently
        damaged during transport and cleaning, causing workflow delays and costly downtime.
      </li>
      <li>
        <strong>Developed a standards-aware design</strong> using non-ferromagnetic,
        biocompatible polymers (PEEK + Lexan) compatible with MRI environments.
      </li>
      <li>
        <strong>Engineered for usability:</strong> maintained full access to ports, LEDs, and the
        battery compartment while improving drop resistance and chemical durability.
      </li>
      <li>
        <strong>Integrated regulatory thinking</strong> by aligning material and geometry choices
        with ASTM MR-safety standards and ISO biocompatibility considerations.
      </li>
    </ul>
    <p class="summary">
      <strong>Summary:</strong> This project combined clinical insight, materials engineering,
      workflow analysis, and business awareness to propose a cost-effective solution that
      protects hospital assets while improving reliability and patient care in MRI environments.
    </p>
    <p class="pdf-link">
      <a href="/assets/docs/Proposal_ProtectiveCaseDesignforthePhilipsExpressionMR WirelessSpO₂Module.pdf"
         target="_blank" rel="noopener noreferrer">
        View Full Design Proposal (PDF)
      </a>
    </p>
  </div>
</section>
<!-- EXTREMITY NORMOTHERMIA SUPPORT PROPOSAL CARD -->
<section id="extremity-normothermia" class="experience-card">
  <figure class="card-image">
    <img src="/assets/images/support.png" alt="Extremity Normothermia Support proposal visual">
    <figcaption class="card-title">
      <button class="expand-btn">
        Extremity Normothermia Support Proposal
        <span class="arrow">▶</span>
      </button>
    </figcaption>
  </figure>

  <div class="card-content">
    <p>
      Proposed a clinical solution to support extremity normothermia (hands/feet) in surgical and ICU settings, with a focus on
      reducing heat loss while maintaining visibility, access, and workflow compatibility for clinicians.
    </p>
    <ul>
      <li><strong>Problem focus:</strong> Prevent heat loss in extremities without blocking IV access, monitoring, or patient assessment.</li>
      <li><strong>Design priorities:</strong> Safe, regulated warming; clinically realistic materials/cleaning; minimal workflow disruption.</li>
      <li><strong>Human factors:</strong> Designed around line access, quick checks (color/perfusion), and ease of use for staff.</li>
    </ul>
    <p class="summary">
      <strong>Summary:</strong> Strengthened my ability to translate a clinical need into clear design requirements and a proposal-ready concept.
    </p>
    <p class="pdf-link">
      <a href="/assets/docs/Proposal_ExtremityNormothermiaSupport.pdf" target="_blank" rel="noopener noreferrer">
        View Full Proposal (PDF)
      </a>
    </p>
  </div>
</section>
<style>
/* ---------- EXPERIENCE CARD IMAGES: NATURAL SIZE ---------- */
.card-image img {
  width: 100%;
  height: auto;              /* let image define height */
  display: block;
  border-radius: 12px;
  border: 4px solid var(--csu-green);
  box-shadow: 0 4px 10px rgba(0,0,0,0.15);
  object-fit: unset;         /* remove forced fitting */
}
<style>
