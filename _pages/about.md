---
permalink: /
title: "👋Hello there, I'm Evan!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

🏫 I'm currently an undergraduate student at [Cornell CS](https://www.cs.cornell.edu/).

🔬 My undergraduate research interests are in computer vision and graphics. I'm also a member of Cornell University Artificial Intelligence ([CUAI](https://cuai.github.io/)).

🎾 I'm also a big gym guy, a eight ball player, and a badminton enthusiast.

# Projects #
<div class="project-container" style="max-width:800px; margin:0 auto; padding:20px; border:1px solid #e0e0e0; box-shadow:0 2px 4px rgba(0,0,0,0.1);">
  <!-- Header Section: Title and Credits -->
  <header class="project-header" style="text-align:center; margin-bottom:20px;">
    <h2 style="margin:0 0 10px;">Auto-Riggable Gaussian Characters</h2>
    <p style="margin:0; font-style:italic; color:#666;"><strong>Credits:</strong> Evan Zhang, Sean Brynjólfsson, Justin Tien-Smith</p>
  </header>

  <!-- Image Gallery Section: GRIG GIFs -->
  <section class="project-images" style="display:flex; flex-wrap:wrap; gap:10px; justify-content:center; margin-bottom:20px;">
    <img src="/images/grig1.gif" alt="GRIG1 Animation" style="max-width:100%; height:auto; border:1px solid #ccc;">
    <img src="/images/grig2.gif" alt="GRIG2 Animation" style="max-width:100%; height:auto; border:1px solid #ccc;">
    <img src="/images/grig3.gif" alt="GRIG3 Animation" style="max-width:100%; height:auto; border:1px solid #ccc;">
  </section>

  <!-- Detailed Description Section -->
  <section class="project-description" style="line-height:1.6;">
    <p>
      Recently, techniques for solving gaussian splats of dynamic scenes 
      (<a href="https://github.com/JonathonLuiten/Dynamic3DGaussians" target="_blank"><em>Dynamic3DGaussians</em></a>, 2024) have found success in using local rigidity constraints to enforce spatial and temporal consistency.
    </p>
    <p>
      We use this detailed representation and decompose it into the rigid parts and joints which describe their movement. This procedure makes no assumptions about the anatomy of the dynamic entities within the scene and therefore should work equally well for all people, animals, or machines—anything that moves about a discrete set of joints. We're currently implementing the joint solver after obtaining promising results for our clustering algorithm to find the bones.
    </p>
    <p>
      Our final deliverable will be an animation-ready gaussian rig and a portable format for it. Clustering also significantly downsizes the storage requirements because local rigidity means gaussians are predictive of their neighbors—no need to track all of them. We are also developing more visualizations to better understand the limitations of the representation. In doing so, we have observed some new failure modes of the original method, such as how some regions gradually creep into neighboring areas over time.
    </p>
  </section>
</div>
