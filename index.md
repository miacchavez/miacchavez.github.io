---
layout: default
title: Home
---

<style>
body {
  font-family: "Helvetica Neue", Arial, sans-serif;
  margin: 0;
  padding: 0;
  color: #222;
}

.container {
  max-width: 1100px;
  margin: 0 auto;
  padding: 2rem 2rem 4rem 2rem;
}

header {
  text-align: center;
  margin-bottom: 2.5rem;
}

header img {
  width: 240px;
  height: 240px;
  border-radius: 50%;
  border: 5px solid #c8b568; /* CSU gold */
  object-fit: cover;
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.15);
}

header h1 {
  color: #1e4d2b; /* CSU green */
  font-size: 2rem;
  margin-top: 1rem;
}

header h2 {
  color: #555;
  font-weight: 400;
  font-size: 1.1rem;
}

header p {
  max-width: 700px;
  margin: 1rem auto;
  line-height: 1.6;
}

.buttons {
  margin-top: 1.2rem;
}

.buttons a {
  text-decoration: none;
  padding: 0.6rem 1.2rem;
  border-radius: 6px;
  margin: 0.3rem;
  font-weight: 600;
  transition: 0.2s;
}

.btn-primary {
  background-color: #1e4d2b;
  color: #fff;
}

.btn-primary:hover {
  background-color: #236538;
}

.btn-secondary {
  background-color: #c8b568;
  color: #000;
}

.btn-secondary:hover {
  background-color: #d1c06d;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.2rem;
  margin-top: 3rem;
}

.gallery img {
  width: 100%;
  height: 240px;
  object-fit: cover;
  border-radius: 12px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.12);
}

.caption {
  text-align: center;
  font-size: 0.9rem;
  color: #444;
  margin-top: 0.3rem;
}

.venn {
  margin-top: 4rem;
  text-align: center;
}

.venn h2 {
  color: #1e4d2b;
  margin-bottom: 1rem;
}

iframe {
  border: none;
  width: 100%;
  max-width: 600px;
  height: 450px;
}
</style>

<div class="container">

  <header>
    <img src="/assets/images/headshot.jpg" alt="Mia Chavez Headshot">
    <h1>Hi, I’m Mia Chavez — Biomedical & Mechanical Engineer.</h1>
    <h2>CSU Class of 2027 | Fort Collins, Colorado</h2>
    <p>
      I design innovative medical and mechanical systems that improve quality of life and expand access to healthcare technology.
      Through hands-on research, nonprofit leadership, and interdisciplinary teamwork, I combine engineering precision with a
      human-centered approach to solve real-world problems.
    </p>

    <div class="buttons">
      <a href="/about/" class="btn-primary">About Me</a>
      <a href="/experiences/" class="btn-primary">Experiences</a>
      <a href="/skills/" class="btn-primary">Skills</a>
      <a href="/contact/" class="btn-secondary">Contact Me</a>
    </div>
  </header>

  <section class="gallery">
    <div>
      <img src="/assets/images/immaculateheart.jpg" alt="Crossover for Change in Uganda">
      <p class="caption">Leading a Crossover for Change camp at Immaculate Heart Girls’ School, Uganda (June 2025).</p>
    </div>

    <div>
      <img src="/assets/images/stryker.jpg" alt="Stryker Shadow Day">
      <p class="caption">Performing mock ACL & meniscus repairs using real surgical tools at a Stryker shadow day.</p>
    </div>

    <div>
      <img src="/assets/images/lockheed.jpg" alt="Lockheed Martin Ethics Competition">
      <p class="caption">Competing at the Lockheed Martin Engineering in Ethics Competition (March 2025).</p>
    </div>

    <div>
      <img src="/assets/images/or-shadow.jpg" alt="Operating Room Shadowing in Pueblo">
      <p class="caption">Observing orthopedic surgery and medical device use during OR shadowing in Pueblo, Colorado.</p>
    </div>
  </section>

  <section class="venn">
    <h2>Where My Interests Intersect</h2>
    <p>Hover over each circle to explore how my studies in Mechanical Engineering, Biomedical Engineering, and Honors/Business/Liberal Arts overlap.</p>
    <iframe src="https://www.venngage.com/viewer/intersecting-venn-diagram-example"></iframe>
  </section>

</div>
