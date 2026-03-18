---
layout: default
title: Projects
permalink: /projects/
---

<div class="page-content">
  <h1>Research & Projects</h1>
  <p class="page-intro">Explore my research work and development projects, from current initiatives to completed endeavors that showcase my technical skills and academic interests.</p>

  <!-- Current Projects Section -->
  <section id="current-projects">
    <h2>Current Projects</h2>
    <div id="current-project-list" class="project-grid">
      <!-- Current project items will be dynamically inserted here -->
    </div>
  </section>

  <!-- Past Projects Section -->
  <section id="past-projects">
    <h2>Past Projects</h2>
    
    <!-- Sorting Controls -->
    <div class="sort-controls">
      <label for="sort-select">Sort by:</label>
      <select id="sort-select" class="sort-dropdown">
        <option value="date-desc">Date (Newest First)</option>
        <option value="date-asc">Date (Oldest First)</option>
        <option value="tag">Technology Tag</option>
      </select>
      
      <div id="tag-filter-container" class="tag-filter-container" style="display: none;">
        <label for="tag-filter">Filter by tag:</label>
        <select id="tag-filter" class="tag-dropdown">
          <option value="all">All Tags</option>
        </select>
      </div>
    </div>
    
    <div id="past-project-list" class="project-grid">
      <!-- Past project items will be dynamically inserted here -->
    </div>
  </section>
</div>

<script>
  // Current Projects data
  const currentProjects = [
    {
      title: "DAPSS - Distributed Adaptive Publish-Subscribe System",
      collaborators: "Naing Htet, Timothy Phan",
      description: "A brokerless messaging framework addressing distributed systems challenges including scalability, consistency, and fault tolerance. Integrates gossip-based dissemination with Lamport timestamp ordering and Raft-inspired consensus for a peer-to-peer overlay with dynamic discovery. Achieves 16.89ms mean latency and 150+ msg/s throughput.",
      imageUrl: "/assets/images/dapss.png",
      github: "https://github.com/Codingjackking/DAPSS",
      presentation: "https://docs.google.com/presentation/d/1tDlr6qygCOlM3lVRPsLCk8wSiv4QcNFALcuoPg5ia6U/edit?usp=sharing",
      tags: ["Distributed Systems", "Python", "Consensus", "Fault Tolerance"],
      date: "2024-12-01"
    }
  ];

  // Past Projects data
  const pastProjects = [
    {
      title: "The Why in the Evolution of Data Visualizations on Wikipedia",
      collaborators: "Naing Htet, Jasmine Shih, PI: Dr. Marti Hearst",
      description: "Explored using Gemini and ChatGPT LLM to infer the intent behind Wikipedia image edits using Wikipedia revision comments",
      imageUrl: "/assets/images/sucb2025.png",
      github: "https://github.com/WikiVizEvolution/wiki-viz-edit-intents",
      tags: ["LLM", "Data Visualization", "NLP"],
      date: "2025-07-01"
    },
    {
      title: "Reinforcement Learning for Optimizing Multi-Vaccine Distribution",
      collaborators: "Naing Htet, Dev Modi, PI: Professor Qun Wang",
      description: "Implemented a framework that optimized COVID-19 and flu distribution using reinforcement learning algorithms.",
      imageUrl: "/assets/images/csc699.png",
      github: "https://github.com/Codingjackking/MultiVacSim",
      presentation: "https://docs.google.com/presentation/d/1oGpdoPimuHWwMQtScVbWzOm1hZcXs1GRn7JOxB7x9QU/edit?usp=sharing",
      tags: ["Reinforcement Learning", "Healthcare", "Optimization"],
      date: "2025-02-01"
    },
    {
      title: "Soccer Match Prediction System",
      collaborators: "Naing Htet, Rodrigo Oliveira, Jonathan Sum",
      description: "Machine learning-based system for predicting soccer match outcomes using historical data, team statistics, and advanced analytical models.",
      imageUrl: "/assets/images/soccer_prediction.png",
      github: "https://github.com/goleador/CSC671Project",
      tags: ["Machine Learning", "Sports Analytics", "Prediction", "Python"],
      date: "2024-12-01"
    },
    {
      title: "Pre-Hurricane Alarm",
      collaborators: "Krushna Thakkar and Akshar Gothi",
      description: "Developed during Cal Hacks 11.0, this project serves as an early warning system for hurricanes, integrating real-time data for disaster preparedness.",
      imageUrl: "/assets/images/hurr_tracker.jpg",
      devpost: "https://devpost.com/software/pre-hurricane-alarm",
      github: "https://github.com/kru2710shna/Pre_Hurricane",
      tags: ["Hackathon", "Disaster Preparedness", "Real-time Data"],
      date: "2024-10-20"
    },
    {
      title: "Anaphorna",
      collaborators: "Anmol Dhaka, Ahmed Yasser, and Awen Li",
      description: "Created for DavisHacks 2024, this project is designed to provide sustainable solutions for communities affected by environmental issues.",
      imageUrl: "/assets/images/alz_watch.png",
      devpost: "https://devpost.com/software/anaphorna",
      github: "https://github.com/ahmedryasser/Anaphorna",
      tags: ["Hackathon", "Healthcare", "Web App"],
      date: "2024-10-15"
    },
    {
      title: "Load Forecasting Models Comparison",
      collaborators: "Mentor: Yu Zhang",
      description: "A comparative analysis of load forecasting models using machine learning techniques for energy consumption prediction.",
      imageUrl: "/assets/images/lf_ml.png",
      github: "https://github.com/Codingjackking/ML-STLF",
      presentation: "https://docs.google.com/presentation/d/16D892MRAqM3MTbQpsdQFwY0wZFAPFKzs47PcMVS2vh4/edit?usp=sharing",
      tags: ["Machine Learning", "Energy", "Forecasting"],
      date: "2024-08-01"
    },
    {
      title: "Tank Game - Local Multiplayer",
      collaborators: "Naing Htet",
      description: "A local multiplayer tank battle game featuring real-time combat mechanics, multiple power-ups, and engaging gameplay designed for competitive play.",
      imageUrl: "/assets/images/tank_game.png",
      github: "https://github.com/Codingjackking/TankGame",
      tags: ["Game Development", "Java", "Multiplayer", "Real-time"],
      date: "2024-05-01"
    },
    {
      title: "AquaMate - Aquarium Builder Website",
      collaborators: "Elliot Warren, Inderpaul Bhander, Sukrit Dhawan, Miguelangel Vargas, Mohamed Deeb, Citlalin Galvan, Naing Htet",
      description: "A comprehensive web application for aquarium enthusiasts to design, plan, and manage their aquarium setups with interactive tools and community features.",
      imageUrl: "/assets/images/aquamate.png",
      github: "https://github.com/CSC-648-SFSU/AquaMate",
      tags: ["Web Development", "Full Stack", "React", "Database"],
      date: "2024-05-01"
    },
    {
      title: "Danger Tracker",
      collaborators: "Evan Teboul, Aymane-Arfaoui Arfaoui, and Vignesh Guruswami",
      description: "A project for SFHacks 2024 to help monitor and report dangerous incidents in real time, enhancing community safety.",
      imageUrl: "/assets/images/dan_tracker.jpg",
      devpost: "https://devpost.com/software/danger-tracker",
      github: "https://github.com/M-a-a-d-man/SFHacks2024",
      tags: ["Hackathon", "Public Safety", "Real-time"],
      date: "2024-04-07"
    },
    {
      title: "Java Calculator",
      collaborators: "Naing Htet",
      description: "A feature-rich calculator application built with Java, implementing standard calculation functions with an intuitive user interface.",
      imageUrl: "/assets/images/java_calculator.png",
      github: "https://github.com/Codingjackking/JavaCalculator",
      tags: ["Java", "GUI", "Desktop Application"],
      date: "2023-12-01"
    }
  ];

  // Get all unique tags from past projects
  const allTags = [...new Set(pastProjects.flatMap(p => p.tags))].sort();
  
  // Current sort state
  let currentSort = 'date-desc';
  let currentTagFilter = 'all';

  // Populate tag filter dropdown
  const tagFilter = document.getElementById('tag-filter');
  if (tagFilter) {
    allTags.forEach(tag => {
      const option = document.createElement('option');
      option.value = tag;
      option.textContent = tag;
      tagFilter.appendChild(option);
    });
  }

  // Sort projects function
  function sortProjects(projects, sortType) {
    const sorted = [...projects];
    
    switch(sortType) {
      case 'date-desc':
        return sorted.sort((a, b) => new Date(b.date) - new Date(a.date));
      case 'date-asc':
        return sorted.sort((a, b) => new Date(a.date) - new Date(b.date));
      case 'tag':
        return sorted.sort((a, b) => {
          const aTag = a.tags[0] || '';
          const bTag = b.tags[0] || '';
          return aTag.localeCompare(bTag);
        });
      default:
        return sorted;
    }
  }

  // Filter projects by tag
  function filterByTag(projects, tag) {
    if (tag === 'all') return projects;
    return projects.filter(p => p.tags.includes(tag));
  }

  // Render past projects
  function renderPastProjects() {
    const pastProjectList = document.getElementById("past-project-list");
    pastProjectList.innerHTML = ''; // Clear existing projects
    
    // Apply filter and sort
    let filtered = filterByTag(pastProjects, currentTagFilter);
    let sorted = sortProjects(filtered, currentSort);
    
    sorted.forEach(project => {
      const projectCard = createProjectCard(project);
      pastProjectList.appendChild(projectCard);
    });
  }

  // Sort dropdown change handler
  const sortSelect = document.getElementById('sort-select');
  if (sortSelect) {
    sortSelect.addEventListener('change', (e) => {
      currentSort = e.target.value;
      
      // Show/hide tag filter based on sort type
      const tagFilterContainer = document.getElementById('tag-filter-container');
      if (currentSort === 'tag') {
        tagFilterContainer.style.display = 'inline-block';
      } else {
        tagFilterContainer.style.display = 'none';
        currentTagFilter = 'all';
        if (tagFilter) tagFilter.value = 'all';
      }
      
      renderPastProjects();
    });
  }

  // Tag filter change handler
  if (tagFilter) {
    tagFilter.addEventListener('change', (e) => {
      currentTagFilter = e.target.value;
      renderPastProjects();
    });
  }

  // Populate current projects
  const currentProjectList = document.getElementById("current-project-list");
  currentProjects.forEach(project => {
    const projectCard = createProjectCard(project);
    currentProjectList.appendChild(projectCard);
  });

  // Populate past projects with initial sort (newest first)
  renderPastProjects();

  // Create project card element
  function createProjectCard(project) {
    const card = document.createElement("div");
    card.classList.add("project-card");

    const links = [];
    if (project.github) {
      links.push(`<a href="${project.github}" target="_blank" rel="noopener" class="project-link">
        <svg width="16" height="16" viewBox="0 0 16 16" fill="currentColor">
          <path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"/>
        </svg>
        GitHub
      </a>`);
    }
    if (project.devpost) {
      links.push(`<a href="${project.devpost}" target="_blank" rel="noopener" class="project-link">📱 DevPost</a>`);
    }
    if (project.presentation) {
      links.push(`<a href="${project.presentation}" target="_blank" rel="noopener" class="project-link">📊 Presentation</a>`);
    }

    const tags = project.tags ? project.tags.map(tag => 
      `<span class="project-tag">${tag}</span>`
    ).join('') : '';

    card.innerHTML = `
      <div class="project-image-wrapper">
        <img src="${project.imageUrl}" alt="${project.title}" class="project-image" loading="lazy">
      </div>
      <div class="project-info">
        <h3 class="project-title">${project.title}</h3>
        <p class="project-collaborators"><strong>Collaborators:</strong> ${project.collaborators}</p>
        <p class="project-description">${project.description}</p>
        ${tags ? `<div class="project-tags">${tags}</div>` : ''}
        <div class="project-links">
          ${links.join(' ')}
        </div>
      </div>
    `;
    return card;
  }
</script>

<style>
.page-content {
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

.page-intro {
  font-size: 1.1rem;
  color: #586069;
  margin-bottom: 40px;
  line-height: 1.6;
}

#current-projects, #past-projects {
  margin-bottom: 60px;
}

#current-projects h2, #past-projects h2 {
  color: #24292e;
  border-bottom: 2px solid #0366d6;
  padding-bottom: 10px;
  margin-bottom: 30px;
}

.sort-controls {
  margin-bottom: 25px;
  display: flex;
  align-items: center;
  gap: 15px;
  flex-wrap: wrap;
  padding: 15px;
  background: #f6f8fa;
  border-radius: 6px;
  border: 1px solid #e1e4e8;
}

.sort-controls label {
  font-weight: 600;
  color: #24292e;
  font-size: 0.9rem;
}

.sort-dropdown, .tag-dropdown {
  padding: 8px 12px;
  border: 1px solid #d1d5da;
  border-radius: 6px;
  background: white;
  font-size: 0.9rem;
  color: #24292e;
  cursor: pointer;
  transition: border-color 0.2s ease;
}

.sort-dropdown:hover, .tag-dropdown:hover {
  border-color: #0366d6;
}

.sort-dropdown:focus, .tag-dropdown:focus {
  outline: none;
  border-color: #0366d6;
  box-shadow: 0 0 0 3px rgba(3, 102, 214, 0.1);
}

.tag-filter-container {
  display: flex;
  align-items: center;
  gap: 10px;
}

.project-grid {
  display: grid;
  gap: 30px;
}

.project-card {
  background: white;
  border: 1px solid #e1e4e8;
  border-radius: 8px;
  overflow: hidden;
  transition: all 0.3s ease;
  display: grid;
  grid-template-columns: 300px 1fr;
  gap: 20px;
}

.project-card:hover {
  box-shadow: 0 4px 16px rgba(0, 0, 0, 0.1);
  transform: translateY(-4px);
}

.project-image-wrapper {
  background: #f6f8fa;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 20px;
}

.project-image {
  width: 100%;
  height: auto;
  object-fit: cover;
  border-radius: 4px;
}

.project-info {
  padding: 24px 24px 24px 0;
  display: flex;
  flex-direction: column;
}

.project-title {
  margin: 0 0 12px 0;
  color: #24292e;
  font-size: 1.4rem;
}

.project-collaborators {
  color: #586069;
  font-size: 0.9rem;
  margin: 0 0 12px 0;
}

.project-description {
  color: #24292e;
  line-height: 1.6;
  margin: 0 0 16px 0;
  flex-grow: 1;
}

.project-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-bottom: 16px;
}

.project-tag {
  background: #e1e4e8;
  color: #24292e;
  padding: 4px 12px;
  border-radius: 12px;
  font-size: 0.8rem;
  font-weight: 500;
}

.project-links {
  display: flex;
  gap: 16px;
  flex-wrap: wrap;
}

.project-link {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  color: #0366d6;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.2s ease;
}

.project-link:hover {
  color: #0256c7;
  text-decoration: underline;
}

.project-link svg {
  vertical-align: middle;
}

@media (max-width: 968px) {
  .project-card {
    grid-template-columns: 1fr;
  }
  
  .project-info {
    padding: 0 24px 24px 24px;
  }
  
  .project-image-wrapper {
    min-height: 200px;
  }
}

@media (max-width: 768px) {
  .page-content {
    padding: 16px;
  }
}
</style>
