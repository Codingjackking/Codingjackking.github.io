---
layout: default
title: News
permalink: /news/
---

<div class="page-content">
  <h1>News & Updates</h1>
  <p class="page-intro">Stay updated with my latest achievements, milestones, and activities in my academic and professional journey.</p>

  <div id="news-container">
    <ul id="news-list" class="timeline-list">
      <!-- News items will be dynamically inserted here -->
    </ul>
  </div>
</div>

<script>
  // News data - sorted by date (newest first)
  const news = [
    { date: "2025-08-05", content: "Started my SJSU computer science master program", category: "education" },
    { date: "2025-07-01", content: "Started my 8 weeks research internship at UC Berkeley under Dr. Marti Hearst", category: "research" },
    { date: "2025-06-23", content: "Received SFSU official digital diploma", category: "education" },
    { date: "2025-05-23", content: "Attended San Francisco State University Commencement", category: "education" },
    { date: "2025-05-08", content: "Initiated and took the Phi Beta Kappa Omicron Chapter oath with a cohort of 10+ other recipients", category: "award" },
    { date: "2025-04-30", content: "Accepted into San Jose State University Computer Science Master Program with specialization in Artificial Intelligence", category: "education" },
    { date: "2025-04-12", content: "Was invited into the prestigious Phi Beta Kappa Honor Society", category: "award" },
    { date: "2025-02-07", content: "Started my independent study under Professor Qun Wang with Dev Modi", category: "research" },
    { date: "2024-10-20", content: "Attended a 3 day Cal Hacks 11.0, implementing hurricane tracker prototype with a team of 2", category: "project" },
    { date: "2024-10-15", content: "Attended a 48 hour UC Davis Hackathon, implementing a web app prototype version for an Alzheimer Watch with a team of 3", category: "project" },
    { date: "2024-09-14", content: "Presented at Cal Bridge 2024 Fall Conference Symposium", category: "presentation" },
    { date: "2024-08-16", content: "Presented at UC Santa Cruz for Cal Bridge 2024 Summer Research Internship", category: "presentation" },
    { date: "2024-06-23", content: "Started my 8 weeks research internship at UC Santa Cruz under Dr. Yu Zhang", category: "research" },
    { date: "2024-04-07", content: "Won Best Use of Google Cloud in SFHacks 2024 with a team of 3, implementing a prototype danger tracker", category: "award" },
    { date: "2024-01-11", content: "Became a learning assistant for CSC215", category: "teaching" },
    { date: "2023-06-30", content: "Accepted into Cal Bridge Program", category: "education" },
  ];

  // Category icons and colors
  const categoryConfig = {
    education: { icon: "🎓", color: "#0366d6" },
    research: { icon: "🔬", color: "#6f42c1" },
    award: { icon: "🏆", color: "#d73a49" },
    project: { icon: "💻", color: "#28a745" },
    presentation: { icon: "📊", color: "#fd7e14" },
    teaching: { icon: "👨‍🏫", color: "#17a2b8" }
  };

  // Sort news items by date (newest first)
  news.sort((a, b) => new Date(b.date) - new Date(a.date));

  // Populate the news section
  const newsList = document.getElementById("news-list");
  news.forEach((item, index) => {
    const li = document.createElement("li");
    li.classList.add("timeline-item");
    
    const config = categoryConfig[item.category] || { icon: "📰", color: "#586069" };
    
    li.innerHTML = `
      <div class="timeline-marker" style="background-color: ${config.color}">
        <span class="timeline-icon">${config.icon}</span>
      </div>
      <div class="timeline-content">
        <div class="timeline-date">${formatDate(item.date)}</div>
        <div class="timeline-text">${item.content}</div>
        <span class="timeline-category" style="background-color: ${config.color}">${item.category}</span>
      </div>
    `;
    newsList.appendChild(li);
  });

  // Format date nicely
  function formatDate(dateString) {
    const options = { year: 'numeric', month: 'long', day: 'numeric' };
    return new Date(dateString).toLocaleDateString('en-US', options);
  }
</script>

<style>
.page-content {
  max-width: 900px;
  margin: 0 auto;
  padding: 20px;
}

.page-intro {
  font-size: 1.1rem;
  color: #586069;
  margin-bottom: 40px;
  line-height: 1.6;
}

.timeline-list {
  list-style: none;
  padding: 0;
  position: relative;
}

.timeline-list::before {
  content: '';
  position: absolute;
  left: 20px;
  top: 0;
  bottom: 0;
  width: 2px;
  background: #e1e4e8;
}

.timeline-item {
  position: relative;
  padding-left: 60px;
  padding-bottom: 30px;
  margin-bottom: 20px;
}

.timeline-marker {
  position: absolute;
  left: 0;
  top: 0;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.15);
  z-index: 1;
}

.timeline-icon {
  font-size: 1.2rem;
}

.timeline-content {
  background: #f6f8fa;
  border: 1px solid #e1e4e8;
  border-radius: 8px;
  padding: 16px 20px;
  transition: all 0.3s ease;
}

.timeline-item:hover .timeline-content {
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  transform: translateX(4px);
}

.timeline-date {
  font-size: 0.9rem;
  color: #0366d6;
  font-weight: 600;
  margin-bottom: 8px;
}

.timeline-text {
  color: #24292e;
  line-height: 1.6;
  margin-bottom: 10px;
}

.timeline-category {
  display: inline-block;
  padding: 4px 12px;
  border-radius: 12px;
  font-size: 0.75rem;
  color: white;
  text-transform: uppercase;
  font-weight: 600;
  letter-spacing: 0.5px;
}

@media (max-width: 768px) {
  .timeline-list::before {
    left: 15px;
  }
  
  .timeline-item {
    padding-left: 50px;
  }
  
  .timeline-marker {
    width: 32px;
    height: 32px;
  }
  
  .timeline-icon {
    font-size: 1rem;
  }
}
</style>
