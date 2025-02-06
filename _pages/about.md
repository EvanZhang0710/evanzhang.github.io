---
permalink: /
# title: "👋Hello there, I'm Evan!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- Page Title Styled Consistently with Other Headers -->
<h2 style="font-size: 2em; margin: 0 0 20px 0;">👋Hello there, I'm Evan!</h2>

<div class="about-section" style="margin: 20px 0; font-size: 1.2em; line-height: 1.4;">
  <p>🏫 I'm currently an undergraduate student at 
    <a href="https://www.cs.cornell.edu/" style="color: #007acc; text-decoration: none; font-weight: bold;">Cornell CS</a>.
  </p>
  <p>🔬 My undergraduate research interests are in computer vision and graphics. I'm also a member of Cornell University Artificial Intelligence 
    (<a href="https://cuai.github.io/" style="color: #007acc; text-decoration: none; font-weight: bold;">CUAI</a>).
  </p>
  <p>🎾 I'm a big gym guy, an eight ball player, and a badminton enthusiast.</p>
</div>

<!-- Projects Section with ID for navigation -->
<div id="projects" class="projects-section">
  <!-- Section Heading: Using similar style as Teaching Experiences -->
  <h2 style="font-size: 2em; margin-bottom: 20px;">💻 Projects</h2>
  
  <!-- Project 1 -->
  <div class="project-teaser" style="display: flex; align-items: flex-start; margin: 20px 0;">
    <!-- Left Column: Teaser Image -->
    <div class="teaser-image" style="flex: 0 0 200px;">
      <img src="/images/grig2.gif" alt="GRIG Teaser" style="width: 100%; border: 1px solid #ccc;">
    </div>
    <!-- Right Column: Short Description and Links -->
    <div class="teaser-description" style="flex: 1; padding-left: 20px;">
      <!-- Title -->
      <h3 style="margin-top: 0;">Auto-Riggable Gaussian Characters (WIP)</h3>
      <!-- Credit line: only the label "Credit:" is bolded -->
      <p class="credit" style="margin: 5px 0; font-size: 0.9em; color: #666;">
        <strong>Credit:</strong> Evan Zhang,
        <a href="https://jolfss.github.io/" target="_blank" rel="noopener noreferrer" style="color: blue; text-decoration: underline;">Sean Brynjólfsson</a>,
        Justin Tien-Smith
      </p>
      <!-- Description -->
      <p style="margin: 5px 0;">
        Leveraging dynamic gaussian splats with local rigidity constraints, this project decomposes moving subjects into animation-ready rigs.
      </p>
      <!-- Links displayed side by side -->
      <a href="https://github.com/jolfss/grig" target="_blank" rel="noopener noreferrer" style="color: #007acc; text-decoration: none; font-weight: bold; margin-right: 15px;">[GitHub]</a>
      <a href="/projects/grig.html" style="color: #007acc; text-decoration: none; font-weight: bold;">[Detail]</a>
    </div>
  </div>

  <!-- Project 2 -->
  <div class="project-teaser" style="display: flex; align-items: flex-start; margin: 20px 0;">
    <!-- Left Column: Teaser Image -->
    <div class="teaser-image" style="flex: 0 0 200px;">
      <img src="/images/clickbait.png" alt="Gaussian_seg Teaser" style="width: 100%; border: 1px solid #ccc;">
    </div>
    <!-- Right Column: Short Description and Links -->
    <div class="teaser-description" style="flex: 1; padding-left: 20px;">
      <h3 style="margin-top: 0;">Compositional Splatting for Construction Sites</h3>
      <p class="credit" style="margin: 5px 0; font-size: 0.9em; color: #666;">
        <strong>Credit:</strong> Evan Zhang,
        <a href="https://jolfss.github.io/" target="_blank" rel="noopener noreferrer" style="color: blue; text-decoration: underline;">Sean Brynjólfsson</a>,
        Dyllan Hofflich,
        Natalie Leung,
        Danish Qureshi
      </p>
      <p style="margin: 5px 0;">
        Leveraging gaussian splatting for digital twin capture on construction sites, this project aims to simulate realistic construction environments and record the construction process.
      </p>
      <!-- Links displayed side by side -->
      <a href="files/SplatConstruction.pdf" target="_blank" rel="noopener noreferrer" style="color: #007acc; text-decoration: none; font-weight: bold; margin-right: 15px;">[Project Paper]</a>
    </div>
  </div>

  <!-- Project 3 -->
  <div class="project-teaser" style="display: flex; align-items: flex-start; margin: 20px 0;">
    <!-- Left Column: Teaser Image -->
    <div class="teaser-image" style="flex: 0 0 200px;">
      <img src="/images/TheOne .png" alt="Gaussian_seg Teaser" style="width: 100%; border: 1px solid #ccc;">
    </div>
    <!-- Right Column: Short Description and Links -->
    <div class="teaser-description" style="flex: 1; padding-left: 20px;">
      <h3 style="margin-top: 0;">Zelda: Catch the Koroks</h3>
      <p class="credit" style="margin: 5px 0; font-size: 0.9em; color: #666;">
        <strong>Credit:</strong> Evan Zhang,
        Ethan Lin,
        Justin Tien-Smith
      </p>
      <p style="margin: 5px 0;">
        This project uses rasterization to render a mini game that is inspired by Zelda. Customized shaders are created to simulate grass, trees, terrain, etc.
      </p>
      <!-- Links displayed side by side -->
      <a href="files/Zelda.pdf" target="_blank" rel="noopener noreferrer" style="color: #007acc; text-decoration: none; font-weight: bold; margin-right: 15px;">[Project Paper]</a>
      <a href="https://youtu.be/AhoNw9ofmpk" style="color: #007acc; text-decoration: none; font-weight: bold;">[Project Video]</a>
    </div>
  </div>

  <!-- Project 4 -->
  <div class="project-teaser" style="display: flex; align-items: flex-start; margin: 20px 0;">
    <!-- Left Column: Teaser Image -->
    <div class="teaser-image" style="flex: 0 0 200px;">
      <img src="/images/up.png" alt="Gaussian_seg Teaser" style="width: 100%; border: 1px solid #ccc;">
    </div>
    <!-- Right Column: Short Description and Links -->
    <div class="teaser-description" style="flex: 1; padding-left: 20px;">
      <h3 style="margin-top: 0;">Apple Is All You Need</h3>
      <p class="credit" style="margin: 5px 0; font-size: 0.9em; color: #666;">
        <strong>Credit:</strong> Evan Zhang,
        Taylor Wang
      </p>
      <p style="margin: 5px 0;">
        This project implements a raytracer that renders a fun scene that only contains apples. Various graphics techniques are used including constructive solid geometry, fresnel refraction, defocus blur, etc.
      </p>
      <!-- Links displayed side by side -->
      <a href="files/apple.pdf" target="_blank" rel="noopener noreferrer" style="color: #007acc; text-decoration: none; font-weight: bold; margin-right: 15px;">[Project Paper]</a>
    </div>
  </div>
</div>

<!-- Teaching Experiences Section with ID for navigation -->
<div id="teaching" class="teaching-experiences" style="margin: 40px 0;">
  <!-- Section Heading -->
  <h2 style="font-size: 2em; margin-bottom: 20px;">🎓 Teaching Experiences</h2>
  
  <!-- List of Experiences -->
  <ul style="list-style-type: none; padding: 0;">
    <li style="margin-bottom: 10px;">
      <strong>2025:</strong> TA for CS 4670: Introduction to Computer Vision | Spring 2025
    </li>
    <li style="margin-bottom: 10px;">
      <strong>2024:</strong> TA for CS 4820: Introduction to Analysis of Algorithms | Fall 2024
    </li>
    <li style="margin-bottom: 10px;">
      <strong>2024:</strong> TA for CS 1112: Introduction to Computing: An Engineering and Science Perspective | Spring 2024
    </li>
    <li style="margin-bottom: 10px;">
      <strong>2023:</strong> TA for CS 1112: Introduction to Computing: An Engineering and Science Perspective | Fall 2023
    </li>
  </ul>
</div>
