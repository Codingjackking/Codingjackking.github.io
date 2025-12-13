---
layout: default
title: Achievements & Awards
permalink: /awards/
---

<div class="page-content">
  <h1>Achievements & Awards</h1>
  <p class="page-intro">Recognition and honors I've received throughout my academic journey, celebrating milestones and accomplishments in my field.</p>

  <div id="awards-container">
    <!-- Awards will be dynamically inserted here -->
  </div>
</div>

<script>
  const awards = [
    {
      year: "2025",
      title: "Phi Beta Kappa Key",
      description: "Inducted into the prestigious Phi Beta Kappa Honor Society, recognizing exceptional academic achievement and intellectual rigor. Took the Phi Beta Kappa Omicron Chapter oath with a cohort of 10+ other recipients.",
      icon: "🔑",
      color: "#d73a49"
    },
    {
      year: "2025",
      title: "San Francisco State University Diploma",
      description: "Successfully completed Bachelor's degree at San Francisco State University with distinction, earning membership in Phi Beta Kappa.",
      icon: "🎓",
      color: "#0366d6"
    },
    {
      year: "2024",
      title: "Best Use of Google Cloud at SFHacks 2024",
      description: "Won Best Use of Google Cloud award at SFHacks 2024 with a team of 3, implementing an innovative prototype danger tracker that leveraged Google Cloud technologies.",
      icon: "☁️",
      color: "#28a745"
    },
    {
      year: "2024",
      title: "Cal Bridge Scholar",
      description: "Selected as a Cal Bridge Scholar, a competitive program designed to increase the number of California community college transfer students earning bachelor's degrees in STEM fields who continue on to earn PhD degrees.",
      icon: "🌉",
      color: "#6f42c1"
    },
    {
      year: "2023",
      title: "Cal Bridge Program Acceptance",
      description: "Accepted into the Cal Bridge Program, joining a community of scholars dedicated to pursuing graduate education in STEM fields.",
      icon: "🎯",
      color: "#fd7e14"
    }
  ];

  const awardsContainer = document.getElementById("awards-container");
  
  awards.forEach((award, index) => {
    const awardCard = document.createElement("div");
    awardCard.classList.add("award-card");
    awardCard.style.animationDelay = `${index * 0.1}s`;
    
    awardCard.innerHTML = `
      <div class="award-icon" style="background-color: ${award.color}">
        <span>${award.icon}</span>
      </div>
      <div class="award-content">
        <div class="award-header">
          <h2 class="award-title">${award.title}</h2>
          <span class="award-year" style="background-color: ${award.color}">${award.year}</span>
        </div>
        <p class="award-description">${award.description}</p>
      </div>
    `;
    
    awardsContainer.appendChild(awardCard);
  });
</script>

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

#awards-container {
  display: grid;
  gap: 24px;
}

.award-card {
  background: white;
  border: 1px solid #e1e4e8;
  border-radius: 8px;
  padding: 24px;
  display: flex;
  gap: 24px;
  transition: all 0.3s ease;
  animation: fadeInUp 0.5s ease forwards;
  opacity: 0;
}

@keyframes fadeInUp {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.award-card:hover {
  box-shadow: 0 4px 16px rgba(0, 0, 0, 0.1);
  transform: translateY(-4px);
}

.award-icon {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 2.5rem;
  flex-shrink: 0;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
}

.award-content {
  flex-grow: 1;
}

.award-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin-bottom: 12px;
  gap: 16px;
}

.award-title {
  margin: 0;
  color: #24292e;
  font-size: 1.4rem;
  line-height: 1.3;
  flex-grow: 1;
}

.award-year {
  display: inline-block;
  padding: 6px 16px;
  border-radius: 20px;
  color: white;
  font-weight: 700;
  font-size: 1rem;
  flex-shrink: 0;
}

.award-description {
  color: #586069;
  line-height: 1.6;
  margin: 0;
}

/* Decorative elements */
.page-content h1::after {
  content: '';
  display: block;
  width: 60px;
  height: 4px;
  background: linear-gradient(to right, #0366d6, #6f42c1);
  margin-top: 12px;
  border-radius: 2px;
}

@media (max-width: 768px) {
  .page-content {
    padding: 16px;
  }
  
  .award-card {
    flex-direction: column;
    padding: 20px;
  }
  
  .award-icon {
    width: 60px;
    height: 60px;
    font-size: 2rem;
    margin: 0 auto;
  }
  
  .award-header {
    flex-direction: column;
    align-items: flex-start;
  }
  
  .award-year {
    align-self: flex-start;
  }
}
</style>
