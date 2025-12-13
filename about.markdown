---
layout: default
title: About
permalink: /about/
---

<div class="page-content">
  <h1>About Naing Htet</h1>
  
  <p class="page-intro">
    Welcome to my personal website! This page provides an overview of who I am, my academic journey, research interests, and personal projects.
  </p>

  <section class="about-section">
    <h2>Quick Navigation</h2>
    <p>Explore different aspects of my profile:</p>
    
    <div class="navigation-cards">
      <a href="{{ '/' | relative_url }}" class="nav-card">
        <div class="nav-card-icon">👤</div>
        <h3>About Me</h3>
        <p>Learn about my background and research interests</p>
      </a>
      
      <a href="{{ '/news' | relative_url }}" class="nav-card">
        <div class="nav-card-icon">📰</div>
        <h3>News</h3>
        <p>Recent achievements and milestones</p>
      </a>
      
      <a href="{{ '/projects' | relative_url }}" class="nav-card">
        <div class="nav-card-icon">🔬</div>
        <h3>Projects</h3>
        <p>Research work and development projects</p>
      </a>
      
      <a href="{{ '/mentoring' | relative_url }}" class="nav-card">
        <div class="nav-card-icon">👨‍🏫</div>
        <h3>Mentoring</h3>
        <p>Teaching and mentoring experience</p>
      </a>
      
      <a href="{{ '/awards' | relative_url }}" class="nav-card">
        <div class="nav-card-icon">🏆</div>
        <h3>Awards</h3>
        <p>Recognition and achievements</p>
      </a>
      
      <a href="{{ '/miscellaneous' | relative_url }}" class="nav-card">
        <div class="nav-card-icon">✨</div>
        <h3>Miscellaneous</h3>
        <p>Personal interests and fun facts</p>
      </a>
    </div>
  </section>

  <section class="about-section">
    <h2>Contact Information</h2>
    <div class="contact-info">
      <div class="contact-item">
        <strong>📧 Email:</strong> <a href="mailto:{{ site.email }}">{{ site.email }}</a>
      </div>
      <div class="contact-item">
        <strong>🐙 GitHub:</strong> <a href="https://github.com/{{ site.github_username }}" target="_blank" rel="noopener">@{{ site.github_username }}</a>
      </div>
      <div class="contact-item">
        <strong>💼 LinkedIn:</strong> <a href="https://linkedin.com/in/nainghtet" target="_blank" rel="noopener">linkedin.com/in/nainghtet</a>
      </div>
      <div class="contact-item">
        <strong>🐦 Twitter:</strong> <a href="https://twitter.com/{{ site.twitter_username }}" target="_blank" rel="noopener">@{{ site.twitter_username }}</a>
      </div>
      <div class="contact-item">
        <strong>📍 Location:</strong> Daly City, California
      </div>
    </div>
  </section>
</div>

<style>
.page-content {
  max-width: 1000px;
  margin: 0 auto;
  padding: 20px;
}

.page-intro {
  font-size: 1.1rem;
  color: #586069;
  margin-bottom: 40px;
  line-height: 1.6;
}

.about-section {
  margin-bottom: 60px;
}

.about-section h2 {
  color: #24292e;
  border-bottom: 2px solid #0366d6;
  padding-bottom: 10px;
  margin-bottom: 30px;
}

.navigation-cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 20px;
  margin-top: 30px;
}

.nav-card {
  background: white;
  border: 1px solid #e1e4e8;
  border-radius: 8px;
  padding: 24px;
  text-decoration: none;
  transition: all 0.3s ease;
  display: block;
}

.nav-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 4px 16px rgba(0, 0, 0, 0.1);
  border-color: #0366d6;
}

.nav-card-icon {
  font-size: 2.5rem;
  margin-bottom: 12px;
}

.nav-card h3 {
  margin: 0 0 8px 0;
  color: #24292e;
  font-size: 1.2rem;
}

.nav-card p {
  margin: 0;
  color: #586069;
  line-height: 1.5;
}

.contact-info {
  background: #f6f8fa;
  border: 1px solid #e1e4e8;
  border-radius: 8px;
  padding: 30px;
}

.contact-item {
  padding: 12px 0;
  border-bottom: 1px solid #e1e4e8;
  line-height: 1.6;
}

.contact-item:last-child {
  border-bottom: none;
}

.contact-item strong {
  color: #24292e;
  margin-right: 8px;
}

.contact-item a {
  color: #0366d6;
  text-decoration: none;
}

.contact-item a:hover {
  text-decoration: underline;
}

@media (max-width: 768px) {
  .page-content {
    padding: 16px;
  }
  
  .navigation-cards {
    grid-template-columns: 1fr;
  }
  
  .contact-info {
    padding: 20px;
  }
}
</style>
