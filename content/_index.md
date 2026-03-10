---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Manchester Bioinference
      image:
        filename: IMG_8134.png
      text: |
        <br>
        
        The *Manchester Bioinference* group develops computational modelling and machine learning approaches to understand the complexity of biological systems. We develop a range of computational methods for probabilistic modelling, multi-modal machine learning and system biology modelling. We apply these methods to diverse applications involving spatial and single-cell omics technologies, various imaging modalities and longitudinal health data. We collaborate with scientists working on cancer research, industrial biotechnology, developmental biology and immunology. Our research is funded by awards from the UKRI, Wellcome Trust, CRUK and industry partners. 
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: news
    design:
      view: card
      columns: '1'
  
  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./team_members/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
