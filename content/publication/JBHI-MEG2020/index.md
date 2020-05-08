---
title: " QuPWM:  Feature Extraction Method for MEG Epileptic Spike Detection"
authors:
- admin
- Fahad Albalawi
- Turky Nayef Alotaiby
- Majed Hamad Al-Hameed
- Saleh Alshebeili
- Taous-Meriem Laleg-Kirati

date: "2019-12-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Journal of Biomedical and Health Informatics*"
publication_short: "IEEE-JBHI"

abstract: Epilepsy is a neurological disorder  classified as the second most serious neurological disease known to humanity, after stroke. Localization of epileptogenic zone is an important step for  epileptic patient treatment, which starts with epileptic spike detection. The common practice for spike detection of brain signals  is via visual scanning of the recordings, which is a subjective and a very time-consuming task. Motivated by that, this paper focuses on using machine learning for  automatic detection of epileptic spikes in magnetoencephalography (MEG) signals. First, we used the Position Weight Matrix (PWM) method  combined with a uniform quantizer  to generate useful features. Second, the extracted features are classified using  a Support Vector Machine (SVM) for the purpose of epileptic spikes detection. The proposed technique shows great potential in improving the spike detection accuracy and reducing the feature vector size. Specifically, the proposed technique achieved average accuracy  up to  98\% in  using  5-folds cross-validation applied to a balanced dataset of 3104 samples. These  samples are  extracted from 16 subjects where eight are  healthy and eight are epileptic subjects using a sliding frame of size of 100 samples-points with a step-size of 2 sample-points.




# Summary. An optional shortened abstract.
summary: We developed a feature extraction method, called QuPWM, for epileptic spikes detection in MEG signals.  This method is based on combining the position weight matrix (PWM) method with digital quantization.

tags:
- Feature extraction
- AI
- QuPWM
- Epilepsy

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/document/8986627

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: Illustration of the brain abnormal activities for different types of epileptic seizure
  focal_point: Smart

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- AI-for-Medicine

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

Research reported in this publication was supported by King Abdullah University of Science and Technology (KAUST) in collaboration with  King Abdulaziz City for Science and Technology (KACST)  and King Saud University (KSU).
