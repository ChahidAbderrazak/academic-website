---
title: Automated Smart Industrial Inspection
summary: Automated smart industrial inspection software for X-ray CT images and 3D volumes.

tags:
  - Artificial Intelligence
  - Feature Extraction
  - Computer Vision
  - Data Analysis
date: "2021-04-01"

# Optional external URL for project (replaces project detail page).
#external_link: ""

image:
  caption: Example of defect inspection using 3D CT data.
  focal_point: Smart

links:
  - icon: linkedin-in
    icon_pack: fab
    name: Follow
    url: https://www.linkedin.com/in/chahidabderrazak/

url_code: ""
url_pdf: "https://www.mdpi.com/2076-3417/12/4/2175"
url_slides: ""
url_video: "https://www.youtube.com/watch?v=LQN5pb7hH_k&list=PLVCBcL0peR4KjnnBTELtmdAKa0Qh1Ug0M"
# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

In our research, we propose to combine image processing with machine learning for an automated smart industrial inspection software for CT images and 3D volumes.
{{< figure library="true" src="ctims-framework.jpeg" title="The CTIMS inspection framework." lightbox="true" >}}

The designed software has three main modules:

1. Database management module, which handles the database and reads/writes queries to retrieve or save the CT data
2. Pre-processing module for registration and background subtraction
3. Defect inspection module to detect all the potential defects (missing parts, damaged screws, etc.) based on a hybrid system composed of computer vision and deep learning techniques.

{{< figure library="true" src="ctims-gui.png" title="The user-interface of the proposed CTIMS software." lightbox="true" >}}

This project was led by Prof. [Hossam A. Gabbar](https://hossamgaber.com/) and me as the postdoctoral researcher of the team (composed of two master's students [ [Md Jamiul Alam Khan](https://www.linkedin.com/in/jamiul/) ,[Oluwabukola Grace](https://www.linkedin.com/in/oluwabukolaadegboro/)] and a lab engineer) in collaboration with [New Vision Systems Canada Inc.](https://www.nvscanada.ca/) (NVS) and [Mitacs](https://www.mitacs.ca/).

For a CTIMS demo, please feel free to send an email to Amr Barakat(amrb@nvscanada.ca)
