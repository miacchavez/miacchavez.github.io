<div class="hero-buttons">
  <a href="/experiences/">Experiences</a>
  <a href="/skills/" class="gold">Skills</a>
  <a href="/contact/">Contact Me</a>
</div>

<style>
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

/* Responsive layout for small screens */
@media (max-width: 768px) {
  .hero-buttons {
    justify-content: center;
  }
}
</style>
