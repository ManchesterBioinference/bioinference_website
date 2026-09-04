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
        
        **Manchester Bioinference** develop computational and machine learning methods to study complex biological systems using spatial and single-cell omics, imaging, and health data.
  
  - block: markdown
    content:
      title: Latest News
      subtitle:
      text: |
        Congratulations to [Dr William Morgans](http://www.manchesterbioinference.org/author/dr-william-morgans/), Research Associate, whose paper has been published in [NAR Genomics and Bioinformatics](https://academic.oup.com/nargab/article/8/3/lqag104/8780940). Bioinference is on a roll this month!

        Congratulations to [Dr Rufus Daw](http://www.manchesterbioinference.org/author/dr-rufus-daw/), Senior Biomedical Data Scientist, whose paper is now up in [Bioinformatics](https://academic.oup.com/bioinformatics/article/42/Supplement_2/btag425/8767271).

        Congratulations to [Muhammad Ahtazaz Ahsan](http://www.manchesterbioinference.org/author/muhammad-ahtazaz-ahsan/), PhD Student, whose paper has been published in [Bioinformatics](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btag643/8771241).
    design:
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


