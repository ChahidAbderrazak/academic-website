---
title: " Residual Water Suppression Using the Squared Eigenfunctions of the Schrödinger Operator"
authors:
- admin
- Sourav Bhaduri
- Mohamed Maoui
- Eric Achten
- Hacene Serrai
- Taous-Meriem Laleg-Kirati


date: "2019-05-22T00:00:00Z"
doi: "10.1109/ACCESS.2019.2918286"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-05-22T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Access*"
publication_short: "IEEE-Access"

abstract: Water suppression, in proton magnetic resonance spectroscopy (MRS) using post-processing techniques, is very challenging due to the large amplitude of the water line, which shadows the metabolic peaks with small amplitudes and complicates their quantification. In addition, the peak-shaped structure of these spectra and the relatively small number of data points representing them makes the suppression process more cumbersome. In this paper, a post-processing water suppression technique based on the Schrödinger operator is proposed. The method is based on the decomposition of the input MRS spectrum, using the squared eigenfunctions of a semi-classical Schrödinger operator. The proposed approach proceeds in three steps: first, the water peak is estimated using an optimal choice of the value of h to reconstruct the MRS spectrum with a minimum number of eigenfunctions. Second, these estimated eigenfunctions are further refined to ensure that they only represent the water line with no contribution from the metabolite peaks. Finally, the estimated water peak is subtracted from the input MRS spectrum. The proposed method is tested on simulated in vitro and real in vivo MRS data and compared with the Hankel-Lanczos singular value decomposition with partial reorthogonalization (HLSVD-PRO) method. The results obtained show that the semi-classical signal analysis (SCSA) performs comparably to the HLSVD-PRO in accurately suppressing the water peak.




# Summary. An optional shortened abstract.
summary: We developed a post-processing water suppression technique based on the squared eigenfunctions of the Schrödinger operator.

tags:
- MRS
- SCSA
- Diagnosis

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8720157

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: Example of water residue attenuation.
  focal_point: Smart

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- Biosignal-processing

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

Research reported in this publication was supported by King Abdullah University of Science and Technology (KAUST) in collaboration with Gent university. The authors would like to thank Dr. Sabine Van Huffel from the University of Leuven for the use of the HLSVD software, Ms. Patricia Clement and Ghent Institute for Functional and Metabolic Imaging (GIfMI) team for their help in the in vivo data acquisition.
