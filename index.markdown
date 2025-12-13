---
layout: default
title: Home
---

<div class="container">

  <!-- Sidebar Section -->
  <aside class="sidebar">
    <div class="headshot">
      <img src="assets/images/headshot.jpg" alt="Naing Htet's Professional Headshot" class="headshot-image">
    </div>
    <div class="sidebar-content">
      <p>
        <svg class="svg-icon"><use xlink:href="assets/minima-social-icons.svg#marker"></use></svg>
        <span>Daly City, CA</span>
      </p>
      <p>
        <a href="https://codingjackking.github.io" aria-label="Website" target="_blank" rel="noopener">
          <svg class="svg-icon"><use xlink:href="/assets/minima-social-icons.svg#link"></use></svg>
          <span>codingjackking.github.io</span>
        </a>
      </p>
      <p>
        <a href="mailto:{{ site.email }}" aria-label="Email">
          <svg class="svg-icon"><use xlink:href="/assets/minima-social-icons.svg#email"></use></svg>
          <span>{{ site.email }}</span>
        </a>
      </p>
      <p>
        <a href="https://twitter.com/{{ site.twitter_username }}" aria-label="Twitter" target="_blank" rel="noopener">
          <svg class="svg-icon"><use xlink:href="/assets/minima-social-icons.svg#twitter"></use></svg>
          <span>Twitter</span>
        </a>
      </p>
      <p>
        <a href="https://linkedin.com/in/nainghtet" aria-label="LinkedIn" target="_blank" rel="noopener">
          <svg class="svg-icon"><use xlink:href="/assets/minima-social-icons.svg#linkedin"></use></svg>
          <span>LinkedIn</span>
        </a>
      </p>
      <p>
        <a href="https://github.com/{{ site.github_username }}" aria-label="GitHub" target="_blank" rel="noopener">
          <svg class="svg-icon"><use xlink:href="/assets/minima-social-icons.svg#github"></use></svg>
          <span>GitHub</span>
        </a>
      </p>
    </div>
  </aside>

  <!-- Main Content Section -->
  <div class="content">
    <!-- About Me Section -->
    <section id="about">
      <h2>About Me</h2>
      <p>I'm a 1st year master candidate at <a href="https://sjsu.edu" target="_blank" rel="noopener">San Jose State University</a>, aspiring to apply to Ph.D. programs. My interests are in artificial intelligence, data science, healthcare, education, and frontend development. I am a Cal Bridge Scholar and a member of the prestigious Phi Beta Kappa.</p>
      
      <p>During the summer of 2025, I worked with amazing labs under Dr. Marti Hearst and her first year Ph.D. student Jasmine Shih. I had the pleasure of using Large Language Models like Gemini and ChatGPT to explore <a href="https://docs.google.com/presentation/d/1bU3xe6_hLMNiUrq-qHdxUTDrM6_bi_rPq5mPyJ8OvEs/edit?usp=sharing" target="_blank" rel="noopener">data visualization</a>.</p>
      
      <p>Summer of 2024, I had the opportunity to work under Dr. Yu Zhang, an Assistant Professor in Electrical and Computer Engineering. This experience was invaluable, as it allowed me to immerse myself in the field of data analysis and machine learning, specifically focusing on <a href="https://docs.google.com/presentation/d/16D892MRAqM3MTbQpsdQFwY0wZFAPFKzs47PcMVS2vh4/edit?usp=sharing" target="_blank" rel="noopener">load forecasting</a>.</p>
      
      <p>I think that Artificial Intelligence is the future, whether it be through robotics, data processing, or autonomous cars. AI has the potential to transform nearly every industry, from enhancing operational efficiency to creating entirely new ways for humans to interact with technology. My interest is in the application of AI in healthcare, where it can revolutionize diagnostics, personalize treatment plans, and improve patient outcomes. I am particularly fascinated by how machine learning algorithms can help identify patterns in complex medical data, leading to early detection of diseases and more accurate prognoses. In the long run, I believe that AI-driven healthcare solutions will not only save lives but also make healthcare more accessible and affordable for everyone.</p>
    </section>

    <!-- Quick Links Section -->
    <section id="quick-links">
      <h2>Explore</h2>
      <div class="card-grid">
        <div class="info-card">
          <h3>📰 News</h3>
          <p>Stay updated with my latest achievements and milestones</p>
          <a href="{{ '/news' | relative_url }}" class="card-link">View News →</a>
        </div>
        
        <div class="info-card">
          <h3>🔬 Projects</h3>
          <p>Explore my research and development work</p>
          <a href="{{ '/projects' | relative_url }}" class="card-link">View Projects →</a>
        </div>
        
        <div class="info-card">
          <h3>👨‍🏫 Mentoring</h3>
          <p>Learn about my mentoring and teaching experience</p>
          <a href="{{ '/mentoring' | relative_url }}" class="card-link">View Mentoring →</a>
        </div>
        
        <div class="info-card">
          <h3>🏆 Awards</h3>
          <p>Recognition and achievements throughout my journey</p>
          <a href="{{ '/awards' | relative_url }}" class="card-link">View Awards →</a>
        </div>
      </div>
    </section>

    <!-- Recent Highlights -->
    <section id="highlights">
      <h2>Recent Highlights</h2>
      <ul class="highlight-list">
        <li>🎓 Started SJSU Computer Science Master Program (August 2025)</li>
        <li>🔬 Research Internship at UC Berkeley with Dr. Marti Hearst (July 2025)</li>
        <li>🎖️ Inducted into Phi Beta Kappa Honor Society (May 2025)</li>
        <li>📜 Graduated from San Francisco State University (May 2025)</li>
      </ul>
      <p style="margin-top: 20px;">
        <a href="{{ '/news' | relative_url }}" class="btn-primary">See All Updates →</a>
      </p>
    </section>

  </div>
</div>

<style>
.card-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  margin-top: 20px;
}

.info-card {
  background: #f6f8fa;
  border: 1px solid #e1e4e8;
  border-radius: 8px;
  padding: 24px;
  transition: all 0.3s ease;
}

.info-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  border-color: #0366d6;
}

.info-card h3 {
  margin-top: 0;
  color: #24292e;
  font-size: 1.3rem;
}

.info-card p {
  color: #586069;
  margin: 12px 0;
}

.card-link {
  display: inline-block;
  color: #0366d6;
  text-decoration: none;
  font-weight: 500;
  margin-top: 8px;
  transition: color 0.2s ease;
}

.card-link:hover {
  color: #0256c7;
  text-decoration: underline;
}

.highlight-list {
  list-style: none;
  padding: 0;
}

.highlight-list li {
  padding: 12px 0;
  border-bottom: 1px solid #e1e4e8;
  font-size: 1.05rem;
}

.highlight-list li:last-child {
  border-bottom: none;
}

.btn-primary {
  display: inline-block;
  padding: 10px 20px;
  background-color: #0366d6;
  color: white;
  text-decoration: none;
  border-radius: 6px;
  font-weight: 500;
  transition: background-color 0.2s ease;
}

.btn-primary:hover {
  background-color: #0256c7;
}

@media (max-width: 768px) {
  .card-grid {
    grid-template-columns: 1fr;
  }
}
</style>
