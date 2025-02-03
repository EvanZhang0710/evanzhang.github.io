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


![Illustration of what GRIG does](images\grig1.gif){: .align-left width="300px"}
## Auto-Riggable Gaussian Characters
**Credits**: Evan Zhang, Sean Brynjólfsson, Justin Tien-Smith
**Description**: Recently, techniques for solving gaussian splats of dynamic scenes ([*Dynamic3DGaussians*](https://github.com/JonathonLuiten/Dynamic3DGaussians), 2024) have found success in using local rigidity constraints to enforce spatial and temporal consistency.

We use this detailed representation and decompose it into the rigid parts and joints which describe their movement. This procedure makes no assumptions about the anatomy of the dynamic entities within the scene and therefore should work equally well for all people, animals, machines---anything that moves about a discrete set of joints. We're currently implementing the joint solver after getting promising results for our clustering algorithm to find the bones.

Our final deliverable will be an animation-ready gaussian rig and a portable format for them. Clustering also massively downsizes the storage requirements because local rigidity means gaussians are predictive of their neighbors---no need to track all of them. We are also developing more visualizations to help understand the limitations of the representation present. In doing so, we have spotted some new failure modes of the original method, like how some regions gradually creep into neighboring regions over time.