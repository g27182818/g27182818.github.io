---
# Leave the homepage title empty to use the site title
title: 'Gabriel Mejia'
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: markdown
    id: News
    content:
      title: News
      text: |-
        * <strong>\[Oct. 2023\]</strong> Our gene expression prediction method SEPAL received the best paper award in the [CVAMD 2023](https://cvamd2023.github.io/) workshop ([ICCV 2023](https://iccv2023.thecvf.com/))!! 🎉
        * <strong>\[Aug. 2023\]</strong> Paper accepted to [CVAMD 2023](https://cvamd2023.github.io/) ([ICCV 2023](https://iccv2023.thecvf.com/) workshop) on gene expression prediction from histology images. \[[Paper](https://doi.org/10.48550/arXiv.2309.01036)\] \[[Code](https://github.com/BCV-Uniandes/SEPAL)\] 
        * <strong>\[Sep. 2022\]</strong> Our cancer detection method CanDLE received the best paper award in the [CMMCA 2022](https://cmmca2022.casconf.cn/) workshop ([MICCAI 2022](https://conferences.miccai.org/2022/en/))!! 🎉
        * <strong>\[Jul. 2022\]</strong> Paper accepted to [CMMCA 2022](https://cmmca2022.casconf.cn/) ([MICCAI 2022](https://conferences.miccai.org/2022/en/) workshop) on bias correction and cancer classification on transcriptomics data. \[[Paper](https://drive.google.com/file/d/1g2BxfyNZ0nBvOoow32buBwEGm3wMRiBt/view?usp=share_link)\] \[[Code](https://github.com/g27182818/CanDLE)\]
        * <strong>\[Jan. 2022\]</strong> Started my M.Sc. at UniAndes with Pablo Arbelaez!
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      email: gm.mejia@uniandes.edu.co
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
