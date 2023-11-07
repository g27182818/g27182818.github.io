---
title: 'CanDLE: Illuminating Biases in Transcriptomic Pan-Cancer Diagnosis'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Natasha Bloch
  - Pablo Arbeláez

# Author notes (optional)
author_notes: []

date: '2022-09-22T00:00:00Z'
doi: 'https://doi.org/10.1007/978-3-031-17266-3_7'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-09-22T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *MICCAI workshop on Computational Mathematics Modeling in Cancer Analysis  <font color="#FFA07A">[Oral]</font>*
publication_short: In *MICCAI CMMCA Workshop*

abstract: Automatic cancer diagnosis based on RNA-Seq profiles is at the intersection of transcriptome analysis and machine learning. Methods developed for this task could be a valuable support in clinical practice and provide insights into the cancer causal mechanisms. To correctly approach this problem, the largest existing resource (The Cancer Genome Atlas) must be complemented with healthy tissue samples from the Genotype-Tissue Expression project. In this work, we empirically prove that previous approaches to joining these databases suffer from translation biases and correct them using batch z-score normalization. Moreover, we propose CanDLE, a multinomial logistic regression model that achieves state of the art performance in multilabel cancer/healthy tissue type classification (94.1% balanced accuracy) and all-vs-one cancer type detection (78.0% average max F1).

# Summary. An optional shortened abstract.
summary: <strong> <font color="#6495ED" size="+1">MICCAI workshop on Computational Mathematics Modeling in Cancer Analysis</font> <font color="#FFA07A" size="+1">[Oral]</font></strong> <br />This study shows that previous joint transcriptomic resources have translation biases, in addition we correct the bias and propose a new method that achieves state-of-the-art performance.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://drive.google.com/file/d/1g2BxfyNZ0nBvOoow32buBwEGm3wMRiBt/view?usp=share_link'
url_code: 'https://github.com/g27182818/CanDLE'
url_dataset: ''
url_poster: 'https://drive.google.com/file/d/1-iunCL8RPp_a05_OuArfcnf4B0Iq2pxO/view?usp=sharing'
url_project: ''
url_slides: 'https://docs.google.com/presentation/d/1VyR7BgHVfb27GSvXr1iq7ys021fP7SqS/edit?usp=sharing&ouid=102349276730968051995&rtpof=true&sd=true'
url_source: ''
url_video: 'https://www.youtube.com/watch?v=oL9W5Akdz7w&t=2s&ab_channel=BMLUniandes'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---