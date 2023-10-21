---
title: 'SEPAL: Spatial Gene Expression Prediction from Local Graphs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Paula Cárdenas
  - Daniela Ruiz
  - Angela Castillo
  - Pablo Arbeláez

# Author notes (optional)
author_notes:
  - 
  - 'Equal contribution'
  - 'Equal contribution'
  -
  -

date: '2023-10-01T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2309.01036'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ICCV workshop on Computer Vision for Automated Medical Diagnosis <font color="#FFA07A">[Oral]</font>*
publication_short: In *ICCV CVAMD Workshop*

abstract: Spatial transcriptomics is an emerging technology that aligns histopathology images with spatially resolved gene expression profiling. It holds the potential for understanding many diseases but faces significant bottlenecks such as specialized equipment and domain expertise. In this work, we present SEPAL, a new model for predicting genetic profiles from visual tissue appearance. Our method exploits the biological biases of the problem by directly supervising relative differences with respect to mean expression, and leverages local visual context at every coordinate to make predictions using a graph neural network. This approach closes the gap between complete locality and complete globality in current methods. In addition, we propose a novel benchmark that aims to better define the task by following current best practices in transcriptomics and restricting the prediction variables to only those with clear spatial patterns. Our extensive evaluation in two different human breast cancer datasets indicates that SEPAL outperforms previous state-of-the-art methods and other mechanisms of including spatial context

# Summary. An optional shortened abstract.
summary: SEPAL is a method that predicts 256 heat maps of gene expression using only histology images as input. It does so by performing local spatial analysis with graph neural networks.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2309.01036.pdf'
url_code: 'https://github.com/BCV-Uniandes/SEPAL'
url_dataset: ''
url_poster: 'https://drive.google.com/file/d/1u_IJ3Mso63KkqW_3mtMQ-z7wP-AYHzH_/view?usp=share_link'
url_project: ''
url_slides: 'https://docs.google.com/presentation/d/1Ir5foHKPMAVDRb1VJi8XzYuZa8kTXKLH/edit?usp=share_link&ouid=102349276730968051995&rtpof=true&sd=true'
url_source: ''
url_video: 'https://youtu.be/7YivLcSlcm4'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: true

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