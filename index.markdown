---
layout: default
# title: Naing Htet
---

<link rel="stylesheet" href="assets/home.css">

<div class="container">

  <!-- Sidebar Section -->
  <aside class="sidebar">
    <div class="headshot">
      <img src="assets/images/headshot.jpg" alt="Naing Htet's Professional Headshot" class="headshot-image">
    </div>
    <div class="sidebar-content">
  <p><svg class="svg-icon"><use xlink:href="assets/minima-social-icons.svg#marker"></use></svg>
      <span>Daly City, CA</span></p>
  <p>
    <a href="https://codingjackking.github.io" aria-label="Website">
      <svg class="svg-icon"><use xlink:href="/assets/minima-social-icons.svg#link"></use></svg>
      <span>codingjackking.github.io</span>
    </a>
  </p>
  <p>
    <a href="mailto:nainghtet123@gmail.com" aria-label="Email">
      <svg class="svg-icon"><use xlink:href="/assets/minima-social-icons.svg#email"></use></svg>
      <span>nainghtet123@gmail.com</span>
    </a>
  </p>
  <p>
    <a href="https://twitter.com/NaingHt33143733" aria-label="Twitter">
      <svg class="svg-icon"><use xlink:href="/assets/minima-social-icons.svg#twitter"></use></svg>
      <span>Twitter</span>
    </a>
  </p>
  <p>
    <a href="https://linkedin.com/in/nainghtet" aria-label="LinkedIn">
      <svg class="svg-icon"><use xlink:href="/assets/minima-social-icons.svg#linkedin"></use></svg>
      <span>LinkedIn</span>
    </a>
  </p>
  <p>
    <a href="https://github.com/Codingjackking" aria-label="GitHub">
      <svg class="svg-icon"><use xlink:href="/assets/minima-social-icons.svg#github"></use></svg>
      <span>GitHub</span>
    </a>
  </p>
  <!-- <p>
    <a href="https://scholar.google.com/citations?user=YOURID" aria-label="Google Scholar">
      <svg class="svg-icon"><use xlink:href="/assets/minima-social-icons.svg#google-scholar"></use></svg>
      <span>Google Scholar</span>
    </a>
  </p> -->
</div>
</aside>

  <!-- Main Content Section -->
  <div class="content">
    <!-- About Me Section -->
    <section id="about-me">
      <h2>About Me</h2>
      <p>I'm a 1st year master candidate at <a href="https://sjsu.edu" target="_blank"> San Jose State University</a>, aspiring to apply to Ph.D. programs. My interests are in artificial intelligence, data science, healthcare, education, and frontend development. I am a Cal Bridge Scholar.</p> <p>During the summer of 2024, I had the opportunity to work under Dr. Yu Zhang, an Assistant Professor in Electrical and Computer Engineering. This experience was invaluable, as it allowed me to immerse myself in the field of data analysis and machine learning, specifically focusing on <a href="https://docs.google.com/presentation/d/16D892MRAqM3MTbQpsdQFwY0wZFAPFKzs47PcMVS2vh4/edit?usp=sharing" target="_blank">load forecasting</a>.</p>
      <p>I think that Artificial Intelligence is the future, whether it be through robotics, data processing, or autonomous cars. AI has the potential to transform nearly every industry, from enhancing operational efficiency to creating entirely new ways for humans to interact with technology. My interest is in the application of AI in healthcare, where it can revolutionize diagnostics, personalize treatment plans, and improve patient outcomes. I am particularly fascinated by how machine learning algorithms can help identify patterns in complex medical data, leading to early detection of diseases and more accurate prognoses. In the long run, I believe that AI-driven healthcare solutions will not only save lives but also make healthcare more accessible and affordable for everyone.
      </p>
    </section>

  <!-- Dynamic News Section -->
  <section id="news">
    <h2>News</h2>

  <ul id="news-list">
  <!-- News items will be dynamically inserted here -->
  </ul>
  </section>

<!-- Dynamic Research/Project Section -->
<section id="projects">
  <h2>Research & Projects</h2>
  
  <!-- Current Projects Section -->
  <section id="current-projects">
    <h3>Current Projects</h3>
    <div id="current-project-list">
      <!-- Current project items will be dynamically inserted here -->
    </div>
  </section>
  
  <!-- Old Projects Section -->
  <section id="old-projects">
    <h3>Old Projects</h3>
    <div id="old-project-list">
      <!-- Old project items will be dynamically inserted here -->
    </div>
  </section>
</section>

  <!-- Teaching/Mentor Section -->
  <section id="mentor">
    <h2>Mentoring</h2>
    <ul>
        <li>Mentor in the <a href="https://chss.sfsu.edu/p2p" target="_blank">Peer2Peer Mentor Collective</a> (July - November 2023), where I provided guidance and support to peers, helping them navigate academic and personal challenges.</li>
        <li>Learning Assistant for <a href="https://csme.sfsu.edu/learning-assistants" target="_blank">CSC215 (Intermediate Computer Programming)</a> (January - May 2024), assisting students with programming concepts and enhancing their understanding of course material.</li>
    </ul>
  </section>

   <!-- Dynamic Awards Section (Commented Out) -->
<!--
  <section id="awards">
    <h2>Awards</h2>
    <ul id="awards-list">
      // Uncomment and add awards data dynamically here if needed
    </ul>
  </section>
-->
  <!-- Dynamic Publications Section
  <section id="publications">
    <h2>Publications</h2>
    <ul id="publications-list">
      <!-- Publications data will be dynamically inserted here 
    </ul>
  </section> -->

  <!-- Miscellaneous Section -->
  <section id="misc">
    <h2>Miscellaneous</h2>
    <ul>
      <li>Born with Cleft Palate</li>
      <li>Considers drinking Ramune as an alternative to alcohol</li>
      <li>Participates in hackathons for fun</li>
    </ul>
  </section>

  </div>
</div>

<script>
  // Sample news data
  const news = [
    { date: "2025-7-1", content: "Started my 8 weeks research internship at UC Berkeley" },
    { date: "2025-6-23", content: "Received SFSU official digital diploma" },
    { date: "2025-5-23", content: "Attended San Francisco State University Commencement" },
    { date: "2025-4-30", content: "Accepted into San Jose State University Computer Science Master Program with specialization in Artifical Intelligence." },
    { date: "2025-4-12", content: "Was invited into the prestigious Phi Beta Kappa Honor Society" },
    { date: "2025-5-08", content: "Inititated and took the Phi Beta Kappa Omicron Chapter oath with a cohort of 10+ other recipicent" },
    { date: "2025-4-12", content: "Was invited into the prestigious Phi Beta Kappa Honor Society" },
    { date: "2025-2-7", content: "Started my independent study under Proessor Qun Wang with Dev Modi" },
    { date: "2024-10-20", content: "Attended a 3 days Cal Hacks 11.0, implementing hurricane tracker protype with a team of 2" },
    { date: "2024-9-14", content: "Presented at Cal Bridge 2024 Fall Conference Symporium" },
    { date: "2024-8-16", content: "Presented at UC Santa Cruz for Cal Bridge 2024 Summer Research Internship" },
    { date: "2024-6-23", content: "Started my 8 weeks research internship at UC Santa Cruz" },
    { date: "2024-10-15", content: "Attended a 48 hour UC Davis Hackathon, implementing a web app protype version for a Alzheimer Watch with a team of 3" },
    { date: "2024-4-7", content: "Won Best Use of Google Cloud in SFHacks 2024 with a team of 3, implementing a protype danger tracker" },
    { date: "2024-1-11", content: "Become a learning assistant for CSC215" },
    { date: "2023-6-30", content: "Got accepted into Cal Bridge Program" },
  ];

  // Sort news items by date (newest first)
  news.sort((a, b) => new Date(b.date) - new Date(a.date));

  // Populate the news section
  const newsList = document.getElementById("news-list");
  news.forEach(item => {
    const li = document.createElement("li");
    li.textContent = `${item.date} - ${item.content}`;
    newsList.appendChild(li);
  });

  // Project data
  const currentProjects = [
  {
    title: "The Why in the Evolution of Data Visualizations on Wikipedia",
    collaborators: "Naing Htet, Jasmine Shih, PI: Dr. Marti Hearst",
    description: "Explored using Gemini and ChatGPT LLM to infer the intent behind wikipedia image edit using wikipedia revision commments",
    imageUrl: "../assets/images/sucb2025.png", // Replace with the appropriate image
    // github: "https://github.com/WikiVizEvolution/wiki-viz-edit-intents", // Update with the relevant link if available
    // presentation: "https://example.com/presentation" // Update with the relevant link if available
  }
];

const oldProjects = [
  {
    title: "Reinforcement Learning for Optimizing Multi-Vaccine Distribution",
    collaborators: "Naing Htet, Dev Modi, PI: Professor Qun Wang",
    description: "Implemented a framework that optimized covid-19 and flu distribution.",
    imageUrl: "../assets/images/csc699.png", // Replace with the appropriate image
    github: "https://github.com/Codingjackking/MultiVacSim", // Update with the relevant link if available
    presentation: "https://docs.google.com/presentation/d/1oGpdoPimuHWwMQtScVbWzOm1hZcXs1GRn7JOxB7x9QU/edit?usp=sharing" // Update with the relevant link if available
  },
  {
    title: "Pre-Hurricane Alarm",
    collaborators: "Krushna Thakkar and Akshar Gothi",
    description: "Developed during Cal Hacks 11.0, this project serves as an early warning system for hurricanes, integrating real-time data for disaster preparedness.",
    imageUrl: "../assets/images/hurr_tracker.jpg",
    devpost: "https://devpost.com/software/pre-hurricane-alarm",
    github: "https://github.com/kru2710shna/Pre_Hurricane"
  },
  {
    title: "Load Forecasting Models Comparison",
    collaborators: "Mentor: Yu Zhang",
    description: "A comparative analysis of load forecasting models using machine learning techniques.",
    imageUrl: "../assets/images/lf_ml.png",
    github: "https://github.com/Codingjackking/ML-STLF",
    presentation: "https://docs.google.com/presentation/d/16D892MRAqM3MTbQpsdQFwY0wZFAPFKzs47PcMVS2vh4/edit?usp=sharing"
  },
  {
    title: "Anaphorna",
    collaborators: "Anmol Dhaka, Ahmed Yasser, and Awen Li",
    description: "Created for DavisHacks 2024, this project is designed to provide sustainable solutions for communities affected by environmental issues.",
    imageUrl: "../assets/images/alz_watch.png",
    devpost: "https://devpost.com/software/anaphorna",
    github: "https://github.com/ahmedryasser/Anaphorna"
  },
  {
    title: "Danger Tracker",
    collaborators: "Evan Teboul, Aymane-Arfaoui Arfaoui, and Vignesh Guruswami",
    description: "A project for SFHacks 2024 to help monitor and report dangerous incidents in real time, enhancing community safety.",
    imageUrl: "../assets/images/dan_tracker.jpg",
    devpost: "https://devpost.com/software/danger-tracker",
    github: "https://github.com/M-a-a-d-man/SFHacks2024"
  }
];

// Populate the current projects section
const currentProjectList = document.getElementById("current-project-list");
currentProjects.forEach(project => {
  const projectDiv = document.createElement("div");
  projectDiv.classList.add("project");

  projectDiv.innerHTML = `
    <div class="project-image">
      <img src="${project.imageUrl}" alt="${project.title}">
    </div>
    <div class="project-details">
      <h3>${project.title}</h3>
      <p><strong>Collaborators:</strong> ${project.collaborators}</p>
      <p>${project.description}</p>
      <a href="${project.github}" target="_blank">GitHub</a>
      ${project.presentation ? `| <a href="${project.presentation}" target="_blank">Presentation</a>` : ""}
    </div>
  `;
  currentProjectList.appendChild(projectDiv);
});

// Populate the old projects section
const oldProjectList = document.getElementById("old-project-list");
oldProjects.forEach(project => {
  const projectDiv = document.createElement("div");
  projectDiv.classList.add("project");

  projectDiv.innerHTML = `
    <div class="project-image">
      <img src="${project.imageUrl}" alt="${project.title}">
    </div>
    <div class="project-details">
      <h3>${project.title}</h3>
      <p><strong>Collaborators:</strong> ${project.collaborators}</p>
      <p>${project.description}</p>
      <a href="${project.devpost}" target="_blank">DevPost</a> |
      <a href="${project.github}" target="_blank">GitHub</a>
      ${project.presentation ? `| <a href="${project.presentation}" target="_blank">Presentation</a>` : ""}
    </div>
  `;
  oldProjectList.appendChild(projectDiv);
});

  // Populate the publications section
  const publicationsList = document.getElementById("publications-list");
  publications.forEach(publication => {
    const li = document.createElement("li");
    li.innerHTML = `<a href="${publication.link}" target="_blank"><strong>${publication.title}</strong></a> - ${publication.authors} (${publication.year}), ${publication.journal}`;
    publicationsList.appendChild(li);
  });

  // Awards Data (Commented Out)
  
  const awards = [
    { title: "Phi Beta Kappa Key", year: "2024" }
    { title: "Best Hack at SFHacks2024", year: "2024" },
  ];

  const awardsList = document.getElementById("awards-list");
  awards.forEach(award => {
    const li = document.createElement("li");
    li.textContent = `${award.year}: ${award.title}`;
    awardsList.appendChild(li);
  });
  */
</script>
