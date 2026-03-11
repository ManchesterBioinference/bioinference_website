---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Bioinference @ University of Manchester
      image:
        filename: IMG_8134.png
      text: |
        <br>
        
        The **Manchester Bioinference** develops computational and machine learning methods to study complex biological systems using spatial and single-cell omics, imaging, and health data.
  
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
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
      offset: 0
      order: desc
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


