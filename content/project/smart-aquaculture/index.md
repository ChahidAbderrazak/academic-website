---
title: Smart Aquaculture
summary: Implement a data-driven control for smart aquaculture.  The proposed approach will take advantage of the recent developments in computer vision technology to assess and inspect fish behavior and feedback information on fish behavior
tags:
  - Artificial Intelligence
  - Computer Vision
  - Image Processing
  - Embedded System Deployment
date: "2020-01-01"

# Optional external URL for project (replaces project detail page).
#external_link: ""

image:
  caption: Example of using AI for epileptic diagnosis.
  focal_point: Smart

links:
  - icon: linkedin-in
    icon_pack: fab
    name: Follow
    url: https://www.linkedin.com/in/chahidabderrazak/

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

In our research, We propose to combine these advanced techniques for fish activity recognition taking into consideration the limitations related to water clarity, turbulences ... etc. From the control point of view, we will track the fish using motion modeling-based techniques and classify the fish activity based on its trajectory and its spatiotemporal speed variation. Overall, we aim to learn fish behavior, which will be used as an additional input to the control system design.

{{< figure library="true" src="aquaculture.png" title="Types of aquaculture." lightbox="true" >}}

Our proposed smart aquaculture system focuses on the following points:


1. Studying the effect of the the environmental conditions on fish health and growth using Reinforcement learning. ([GitHub](https://github.com/ChahidAbderrazak/Q-Learning-in-aquaculture))

{{< figure library="true" src="RL-Q-learning.png" title="Model predictive control" lightbox="true" >}}

2. Optimal feeding control using MPC controller.([GitHub](https://github.com/ChahidAbderrazak/EMPC-based_control-for-Aquacuture))

{{< figure library="true" src="MPC.png" title="Model predictive control" lightbox="true" >}}

3. **Industrial application**: Fish health assessment using computer vision . ([GitHub](https://github.com/ChahidAbderrazak/smart-fish-diagnosis.git))
{{< figure library="true" src="aquash-detection.jpeg" title="Fish monitoring based on Object detection model deployed using NVIDIA Jetson Nano " lightbox="true" >}}

**NB**: The project was motivated by the innovative idea of the ([Aquash Startup team](https://www.linkedin.com/posts/chahidabderrazak_aquash-junctionxkaust-startup-activity-6578968922740060160-_5so?utm_source=share&utm_medium=member_desktop)) 


This reseach project (parts 1 and 2) will be led by a team of three professors. Prof. Laleg’s team has significant expertise in developing control, optimization and monitoring methods. She has been working on simulations and lab experimental testing of her algorithms. Prof. Ghanem’s team is particularly well suited to performing the computer vision tasks. Prof. Berumen’s team will provide their expertise in fish behavior and will help in collecting data. In particular, they will work on labelling the fish behavior and will support the experimental setup with their ongoing aquaria work in KAUST’s marine core lab ([CMRCL](https://corelabs.kaust.edu.sa/labs/coastal-and-marine-resources-core-lab)).
