---
title: " Poly(A) prediction signals in human genomic DNA"
authors:
  - Fahad Albalawi
  - admin
  - Xingang Guo
  - Somayah Albaradei
  - Arturo Magana-Mora
  - Boris R. Jankovic
  - Mahmut Uludag
  - Christophe Van Neste
  - Magbubah Essack
  - Taous-Meriem Laleg-Kirati
  - Vladimir B. Bajic

date: "2019-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Methods*"
publication_short: "Methods"

abstract: Polyadenylation signals (PAS) are found in most protein-coding and some non-coding genes in eukaryotes. Their accurate recognition improves understanding gene regulation mechanisms and recognition of the 3′-end of transcribed gene regions where premature or alternate transcription ends may lead to various diseases. Although different methods and tools for in-silico prediction of genomic signals have been proposed, the correct identification of PAS in genomic DNA remains challenging due to a vast number of non-relevant hexamers identical to PAS hexamers. In this study, we developed a novel method for PAS recognition. The method is implemented in a hybrid PAS recognition model (HybPAS), which is based on deep neural networks (DNNs) and logistic regression models (LRMs). One of such models is developed for each of the 12 most frequent human PAS hexamers. DNN models appeared the best for eight PAS types (including the two most frequent PAS hexamers), while LRM appeared best for the remaining four PAS types. The new models use different combinations of signal processing-based, statistical, and sequence-based features as input. The results obtained on human genomic data show that HybPAS outperforms the well-tuned state-of-the-art Omni-PolyA models, reducing the classification error for different PAS hexamers by up to 57.35% for 10 out of 12 PAS types, with Omni-PolyA models being better for two PAS types. For the most frequent PAS types, ‘AATAAA’ and ‘ATTAAA’, HybPAS reduced the error rate by 35.14% and 34.48%, respectively. On average, HybPAS reduces the error by 30.29%. HybPAS is implemented partly in Python and in MATLAB available at https://github.com/EMANG-KAUST/PolyA_Prediction_LRM_DNN.

# Summary. An optional shortened abstract.
summary: We developed New hybrid model for poly(A) signal prediction in human DNA is developed. It contains 8 deep neural networks and 4 logistic regression models. A novel feature generation method is used to extract relevant patterns in the DNA sequences.

tags:
  - Feature extraction
  - AI
  - PWM
  - DNA
  - Deep learning

featured: true

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/Chahid_Abderraz

  - icon: linkedin-in
    icon_pack: fab
    name: Follow
    url: https://www.linkedin.com/in/chahidabderrazak/

url_pdf: https://doi.org/10.1016/j.ymeth.2019.04.001
url_source: https://github.com/EMANG-KAUST/QuPWM
url_dataset: "http://dx.doi.org/10.17632/n9snfr7m59.1"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: Development framework to obtain the best predictive model for an individual PAS variant.
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

his work has been supported by the King Abdullah University of Science and Technology (KAUST) Base Research Fund (BAS/1/1606-01-01) to VBB, (BAS/1/1627-01-01) to TMLK, and KAUST Office of Sponsored Research (OSR) under Awards No CARF – FCC/1/1976-17-01.

Supplementary notes can be added here, including [code and dataset](https://github.com/EMANG-KAUST/QuPWM).
