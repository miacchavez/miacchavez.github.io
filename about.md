<!-- ---------- ABOUT HERO SECTION ---------- -->
<section class="hero about-hero">
  <div class="hero-image">
    <img src="/assets/images/headshot.jpg" alt="Headshot of Mia Chavez">
  </div>

  <div class="hero-text">
    <h1>Get to know me...</h1>
    <p>
      I’m <strong>Mia Chavez</strong> — a Biomedical and Mechanical Engineering student at 
      <strong>Colorado State University</strong> with a Business Minor and Entrepreneurship Certificate. 
      I’m deeply interested in the intersection of engineering, empathy, and impact — how design and 
      problem-solving can improve people’s lives in meaningful, sustainable ways.
    </p>

    <p>
      My journey has been shaped by curiosity and connection. Whether I’m working in a lab, leading a 
      nonprofit project, or collaborating with a team, I strive to approach challenges with both technical 
      precision and human understanding. Engineering, to me, is not just about building things — it’s about 
      building possibilities for others.
    </p>

    <p>
      Outside of academics, I find balance through basketball, mentorship, and travel. I’m passionate about 
      using innovation to make education, healthcare, and opportunity more accessible — especially in 
      underrepresented communities. These experiences have helped me grow into a thinker, leader, and learner 
      who values people as much as progress.
    </p>

    <div class="hero-buttons">
      <a href="/experiences/" class="gold">Experiences</a>
      <a href="/skills/">Skills</a>
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

.hero-buttons {
  margin-top: 1.5rem;
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
}

.hero-buttons a {
  padding: 0.6rem 1.2rem;
  border-radius: 30px;
  text-decoration: none;
  font-weight: 600;
  transition: 0.3s ease;
}

.hero-buttons a.gold {
  background-color: #c8b568;
  color: #fff;
}

.hero-buttons a:hover {
  opacity: 0.85;
}

/* Responsive */
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
