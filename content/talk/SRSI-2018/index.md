---
title: My EMBC2019 talk about epileptic spikes detection  
event: IEEE Engineering in Medicine and Biology Society
event_url: https://embc.embs.org/2019/

location: Source Themes HQ
address:
  street: Messedamm 26
  city: Stanford
  region: Berlin
  postcode: '14055'
  country: Germany

summary: In this talk, I presented how can we use quantum feature for epileptic spikes detection.
abstract: " Epilepsy is a neurological disorder classified as the second most serious neurological disease known to humanity, after stroke. Magnetoencephalography (MEG) is performed to localize the epileptogenic zone in the brain. However, the detection of epileptic spikes requires the visual assessment of long MEG recordings. This task is time-consuming and might lead to wrong decisions. Therefore, the introduction of effective machine learning algorithms for the quick and accurate epileptic spikes detection from MEG recordings would improve the clinical diagnosis of the disease. The efficiency of machine learning based algorithms requires a good characterization of the signal by extracting pertinent features. In this paper, we propose new sets of features for MEG signals. These features are based on a Semi-Classical Signal Analysis (SCSA) method, which allows a good characterization of peak shaped signals. Moreover, this method improves the spike detection accuracy and reduces the feature vector size. We could achieve up to 93.68% and 95.08% in average sensitivity and specificity, respectively. We used the 5-folds cross-validation applied to a balanced dataset of 3104 frames, extracted from eight healthy and eight epileptic subjects with a frame size of 100 samples with a step size of 2 samples, using Random Forest (RF) classifier.
 "

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2019-07-23T13:00:00Z"
date_end: "2019-07-27T15:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2019-08-01T00:00:00Z"

authors: [Abderrazak Chahid]
tags:
- AI
- SCSA

# Is this a featured talk? (true/false)
featured: true

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right


links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/Chahid_Abderraz

- icon: facebook
  icon_pack: fab
  name: Follow
  url: https://www.facebook.com/abderrazak.chahid.714


- icon: linkedin-in
  icon_pack: fab
  name: Follow
  url: https://www.linkedin.com/in/abderrazak-chahid-09b65948/




url_code: ""
url_pdf: ""
url_slides: "slides/Matlab_Tutorial.pptx"
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- AI-for-Medicine
- SCSA-project

# Enable math on this page?
math: true
---

...
