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

# Projects

<div style="display: flex; align-items: flex-start;">
  <!-- Left Column: Vertical Stack of GIFs -->
  <div style="flex: 0 0 auto; margin-right: 20px;">
    <!-- GRIG1 GIF -->
    <img src="images/grig1.gif" alt="GRIG1" width="300px" style="display: block; margin-bottom: 10px;">
    <!-- GRIG2 GIF -->
    <img src="images/grig2.gif" alt="GRIG2" width="300px" style="display: block; margin-bottom: 10px;">
    <!-- GRIG3 GIF -->
    <img src="images/grig3.gif" alt="GRIG3" width="300px" style="display: block;">
  </div>
  
  <!-- Right Column: Text Content -->
  <div style="flex: 1;">
    <h2>Auto-Riggable Gaussian Characters</h2>
    
    <p><strong>Credits</strong>: Evan Zhang, Sean Brynjólfsson, Justin Tien-Smith</p>
    
    <p>
      <strong>Description</strong>: Recently, techniques for solving gaussian splats of dynamic scenes 
      (<a href="https://github.com/JonathonLuiten/Dynamic3DGaussians"><em>Dynamic3DGaussians</em></a>, 2024) have found success in using local rigidity constraints to enforce spatial and temporal consistency.
    </p>
    
    <p>
      We use this detailed representation and decompose it into the rigid parts and joints which describe their movement. This procedure makes no assumptions about the anatomy of the dynamic entities within the scene and therefore should work equally well for all people, animals, machines—anything that moves about a discrete set of joints. We're currently implementing the joint solver after getting promising results for our clustering algorithm to find the bones.
    </p>
    
    <p>
      Our final deliverable will be an animation-ready gaussian rig and a portable format for them. Clustering also massively downsizes the storage requirements because local rigidity means gaussians are predictive of their neighbors—no need to track all of them. We are also developing more visualizations to help understand the limitations of the representation present. In doing so, we have spotted some new failure modes of the original method, like how some regions gradually creep into neighboring regions over time.
    </p>
  </div>
</div>
