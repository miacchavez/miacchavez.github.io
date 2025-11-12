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
<!-- ---------- MY ROOTS SECTION (TEXT + CENTER IMAGE + FAMILY GALLERY) ---------- -->
<section class="roots-section">
  <div class="roots-container">
    <div class="roots-text">
      <h2>My Roots</h2>

      <p>
        “Wow, really?” is typical for me to hear when people ask, “How many siblings do you have?”
        My response: seven. Yes, really. It’s chaotic at times — but it’s the kind of organized chaos
        that taught me teamwork, patience, and adaptability early on. Traveling cross-country in a
        14-passenger bus with eight kids meant constant motion, laughter, and improvisation. Whether
        it was carsickness, forgotten snacks, or emergency rest stops, I learned quickly how to stay
        calm under pressure, problem-solve, and keep a sense of humor along the way.
      </p>

      <div class="center-family-photo">
        <img src="/assets/images/family.jpg" alt="The Chavez family together">
      </div>

      <p>
        My parents, <strong>Denise and David Chavez</strong>, built a home full of energy, laughter,
        and faith. As the fourth of eight siblings — <strong>David (28)</strong>, <strong>Joey (26)</strong>,
        <strong>Matthew (24)</strong>, <strong>Hope (18)</strong>, <strong>Faith (18)</strong>,
        <strong>Micah (16)</strong>, and <strong>Sabrina (12)</strong> — I grew up surrounded by
        different personalities and perspectives. That environment taught me how to communicate,
        mediate, and connect with people who don’t always see things the same way.
      </p>

      <p>
        My life has always been a balance of movement and meaning — academics, leadership,
        basketball, and family. The “controlled chaos” of growing up Chavez shaped me into someone
        who thrives in collaboration and values empathy as much as efficiency. It’s where I learned
        that leadership isn’t about control — it’s about care, listening, and showing up when others
        need you most.
      </p>

      <p>
        My family is the foundation of everything I do. They’ve taught me how to listen before
        acting, how to step up when needed, and how to balance ambition with humility. I see echoes
        of those lessons every day — in engineering teams, nonprofit meetings, or basketball
        practices — where the same patience, adaptability, and humor I learned at home help me bring
        people together and get things done.
      </p>
    </div>
  </div>

<!-- ---------- FAMILY IMAGE GALLERY ---------- -->
<div class="family-gallery">
  <img src="/assets/images/family7.jpg" alt="Family photo 7">
  <img src="/assets/images/family8.jpg" alt="Family photo 8">
  <img src="/assets/images/family4.jpg" alt="Family photo 4">
  <img src="/assets/images/family5.jpg" alt="Family photo 5">
  <img src="/assets/images/family1.jpg" alt="Family photo 1">
  <img src="/assets/images/family2.jpg" alt="Family photo 2">
  <img src="/assets/images/family6.jpg" alt="Family photo 6">
  <img src="/assets/images/family9.jpg" alt="Family photo 9">
</div>
</section>

<style>
/* ---------- MY ROOTS SECTION ---------- */
.roots-section {
  margin: 6rem auto;
  padding: 2rem;
  max-width: 1200px;
  background: linear-gradient(to right, rgba(200,181,104,0.07), rgba(255,255,255,0.7));
  border-radius: 20px;
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.08);
}

.roots-text {
  color: #333;
  max-width: 850px;
  margin: 0 auto;
  text-align: left;
}

.roots-text h2 {
  color: #1e4d2b;
  font-size: 2rem;
  border-bottom: 3px solid #c8b568;
  display: inline-block;
  margin-bottom: 1.2rem;
}

.roots-text p {
  line-height: 1.8;
  font-size: 1.08rem;
  margin-bottom: 1.5rem;
}

/* ---------- CENTER FAMILY PHOTO ---------- */
.center-family-photo {
  text-align: center;
  margin: 2rem 0;
}

.center-family-photo img {
  width: 100%;
  max-width: 600px;
  height: auto;
  border-radius: 16px;
  border: 6px solid #1e4d2b;
  box-shadow: 0 8px 18px rgba(0, 0, 0, 0.25);
}

/* ---------- FAMILY GALLERY (TWO IMAGES PER ROW) ---------- */
.family-gallery {
  margin-top: 3rem;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 1.8rem;
  justify-items: center;
  max-width: 1100px;
  margin-left: auto;
  margin-right: auto;
}

.family-gallery img {
  width: 100%;
  max-width: 520px;
  height: auto;
  border-radius: 12px;
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.2);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.family-gallery img:hover {
  transform: scale(1.03);
  box-shadow: 0 8px 22px rgba(0, 0, 0, 0.3);
}

/* ---------- RESPONSIVE ---------- */
@media (max-width: 900px) {
  .roots-text {
    text-align: center;
  }

  .center-family-photo img {
    width: 90%;
  }

  .family-gallery {
    grid-template-columns: 1fr;
  }

  .family-gallery img {
    max-width: 90%;
  }
}
</style>

<!-- ---------- MY EDUCATIONAL JOURNEY SECTION ---------- -->
<section class="education-section">
  <div class="education-container">
    <h2>My Educational Journey</h2>
    <p class="intro">
      My academic path has been one of steady growth — from classical rigor to creative exploration and, finally, to interdisciplinary innovation. 
      Each stage shaped how I learn, lead, and approach challenges, blending discipline with curiosity and purpose.
    </p>

    <!-- Vanguard School -->
    <div class="education-block">
      <h3>The Vanguard School (K–8)</h3>
      <p>
        My journey began at <strong>The Vanguard School</strong>, where I spent nine formative years immersed in a rigorous classical education. 
        The curriculum emphasized structure, memorization, logic, and rhetoric — teaching me not only how to retain information, 
        but how to think critically and articulate ideas clearly. From daily recitations to Latin roots and Socratic discussions, 
        Vanguard instilled in me the discipline to study deeply and the confidence to participate fully.
      </p>
      <p>
        These years built my academic foundation and taught me perseverance, focus, and attention to detail — skills that continue to guide me 
        in the lab, on the court, and in leadership.
      </p>
      <p class="takeaways">
        <strong>Key Takeaways:</strong> Structured thinking, strong academic discipline, logical reasoning, and intellectual curiosity.
      </p>
      <img src="/assets/images/vanguard_school.jpg" alt="The Vanguard School campus in Colorado Springs" class="education-photo">
    </div>

    <div class="timeline-divider"></div>

    <!-- Colorado Springs School -->
    <div class="education-block">
      <h3>The Colorado Springs School (9–12)</h3>
      <p>
        In high school, I attended <strong>The Colorado Springs School</strong> as an <strong>Innovator Merit Scholar</strong>, where I shifted from memorization 
        to exploration. CSS encouraged independent inquiry, creativity, and leadership — blending classroom learning with outdoor education, 
        community projects, and global engagement.
      </p>
      <p>
        I found my voice as a leader, an athlete, and a learner who valued perspective over perfection. 
        Through interdisciplinary projects and real-world problem-solving, I discovered how collaboration and empathy 
        can transform education into experience. CSS gave me the confidence to ask “why,” to take risks, and to value the process as much as the result.
      </p>
      <p class="takeaways">
        <strong>Key Takeaways:</strong> Leadership through experience, creative and analytical balance, global awareness, and curiosity-driven learning.
      </p>
      <img src="/assets/images/css_school.jpg" alt="The Colorado Springs School campus" class="education-photo">
    </div>

    <div class="timeline-divider"></div>

    <!-- Colorado State University -->
    <div class="education-block">
      <h3>Colorado State University (Undergraduate – Present)</h3>
      <p>
        Today, at <strong>Colorado State University</strong>, I’m pursuing dual degrees in <strong>Biomedical and Mechanical Engineering</strong>, 
        alongside a <strong>Business Administration Minor</strong> and <strong>Entrepreneurship Certificate</strong>. CSU has become the place where 
        my ideas come alive — where I can merge the precision of engineering with the empathy of design and the strategy of business.
      </p>
      <p>
        Beyond academics, I’ve built communities that reflect my values. As an <strong>Honors Ambassador</strong>, I support other students navigating 
        academic and personal growth; as <strong>Treasurer of Crossover for Change</strong>, I lead initiatives empowering girls through education in Uganda; 
        and as a <strong>Manager at NOCO Sports Center</strong>, I apply leadership and communication skills in a fast-paced, team-centered environment.
      </p>
      <p>
        CSU has taught me that engineering isn’t just about innovation — it’s about impact. 
        Every design choice, equation, and collaboration can create ripple effects that change lives.
      </p>
      <p class="takeaways">
        <strong>Key Takeaways:</strong> Interdisciplinary innovation, ethical and human-centered design, teamwork, and community-driven leadership.
      </p>
      <img src="/assets/images/engineering_lab.png" alt="Engineering lab at Colorado State University" class="education-photo">
    </div>
  </div>
</section>

<style>
/* ---------- EDUCATIONAL JOURNEY STYLING ---------- */
.education-section {
  margin: 6rem auto;
  padding: 2rem;
  max-width: 1200px;
  background: linear-gradient(to bottom, rgba(200,181,104,0.08), rgba(255,255,255,0.9));
  border-radius: 20px;
  box-shadow: 0 6px 18px rgba(0,0,0,0.08);
}

.education-container {
  text-align: left;
  color: #333;
  max-width: 950px;
  margin: 0 auto;
}

.education-container h2 {
  color: #1e4d2b;
  font-size: 2rem;
  border-bottom: 3px solid #c8b568;
  display: inline-block;
  margin-bottom: 1.5rem;
}

.education-container .intro {
  font-size: 1.1rem;
  margin-bottom: 2.5rem;
  line-height: 1.7;
  color: #444;
}

.education-block {
  margin-bottom: 3rem;
}

.education-block h3 {
  color: #1e4d2b;
  font-size: 1.5rem;
  margin-bottom: 1rem;
}

.education-block p {
  line-height: 1.75;
  font-size: 1.05rem;
  margin-bottom: 1rem;
}

.education-block .takeaways {
  color: #1e4d2b;
  font-weight: 600;
}

.education-photo {
  width: 100%;
  max-width: 900px;
  height: auto;
  border-radius: 16px;
  box-shadow: 0 6px 16px rgba(0,0,0,0.18);
  margin-top: 1rem;
  margin-bottom: 2.5rem;
  display: block;
}

.timeline-divider {
  height: 3px;
  width: 80px;
  background: #c8b568;
  margin: 2rem auto 3rem;
  border-radius: 2px;
}

/* ---------- RESPONSIVE DESIGN ---------- */
@media (max-width: 900px) {
  .education-container {
    text-align: center;
  }
  .education-photo {
    max-width: 95%;
  }
  .timeline-divider {
    width: 60px;
  }
}
</style>
