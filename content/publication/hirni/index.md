---
title: 'Hirni: Segmentation of Brain Tumors in Multi-parametric Magnetic Resonance Imaging Scans'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Danniel Moreno
  - Daniela Ruiz
  - Nicolas Aparicio

# Author notes (optional)
author_notes: []

date: '2021-10-15T00:00:00Z'
doi: 'https://doi.org/10.1109/CI-IBBI54220.2021.9626115'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-10-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2021 IEEE 2nd International Congress of Biomedical Engineering and Bioengineering  <font color="#DF7A34">[Oral]</font>*
publication_short: In *CI-IB&BI*

abstract: "Glioma is a type of tumor that develops in the brain and causes cancer in nervous system. They are normally associated with a bad prognosis due to its heterogeneity and the difficulty to resect them. Taking this into account, we developed an algorithm capable of segmenting the brain into four parts: background (brain without tumor), necrotic core (NRC), edematous region (ED) and Active and non-enhancing/necrotic tumor regions (AT). First we approached the problem as a binary case (tumor/non-tumor segmentation) and then we used these masks to improve our multi-class case. For descriptors of each pixel, we used the intensities associated to the four different MRIs contrast media and the prior probability distribution of the training set (two for binary and four for multi-class), and we trained a Random Forest classifier with them. Taking into account the limitation of the computational resources with which we work, our results are outstanding (Dice coefficient 0.806 in the binary case) and competitive with state of the art methods."

# Summary. An optional shortened abstract.
summary: <strong> <font color="#3C94B4" size="+1">International Congress of Biomedical Engineering and Bioengineering</font> </strong> <br />Random forests for 3D semantic segmentation of brain tumors in multi-parametric MRIs.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://drive.google.com/file/d/1_txMQSDEaY6Pn1u6Q2XQPO5if008Pgdz/view?usp=sharing'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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