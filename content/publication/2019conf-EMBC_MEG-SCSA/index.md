---
title: "Quantum epileptic Spikes Detection"
authors:
  - admin
  - Turky Nayef Alotaiby
  - Saleh Alshebeili
  - Meriem Laleg-Kirati

date: "2019-05-04T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *41st Annual International Conference of the IEEE Engineering in Medicine and Biology Society*
publication_short: In *EMBC2019*

abstract: Epilepsy is a neurological disorder classified as the second most serious neurological disease known to humanity, after stroke. Magnetoencephalography (MEG) is performed to localize the epileptogenic zone in the brain. However, the detection of epileptic spikes requires the visual assessment of long MEG recordings. This task is time-consuming and might lead to wrong decisions. Therefore, the introduction of effective machine learning algorithms for the quick and accurate epileptic spikes detection from MEG recordings would improve the clinical diagnosis of the disease. The efficiency of machine learning based algorithms requires a good characterization of the signal by extracting pertinent features. In this paper, we propose new sets of features for MEG signals. These features are based on a Semi-Classical Signal Analysis (SCSA) method, which allows a good characterization of peak shaped signals. Moreover, this method improves the spike detection accuracy and reduces the feature vector size. We could achieve up to 93.68% and 95.08% in average sensitivity and specificity, respectively. We used the 5-folds cross-validation applied to a balanced dataset of 3104 frames, extracted from eight healthy and eight epileptic subjects with a frame size of 100 samples with a step size of 2 samples, using Random Forest (RF) classifier.

# Summary. An optional shortened abstract.
summary: New Feature extraction method based on the Quantization-based Semi-Classical Signal Analysis designed explicitly for   epileptic spikes  using  Magnetoencephalography (MEG) signals.

tags:
  - AI
  - Feature Extraction
  - SCSA
  - Signal Processing

featured: true

links:
  - icon: linkedin-in
    icon_pack: fab
    name: Follow
    url: https://www.linkedin.com/in/chahidabderrazak/

#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
#url_dataset: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: "The framework of proposed method for MEG signals"
  focal_point: Smart
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - AI
-for-Medicine
  - SCSA-project
# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
