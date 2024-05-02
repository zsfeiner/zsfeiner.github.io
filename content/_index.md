---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Freshwater ecology and fisheries management
      image:
        caption: 'Photo credit: Rachel Benedict, WDNR'
        filename: WalleyeInFyke.jpg
        width: 570px
      text: |
        <br>
        
        We combine field research, experimental approaches, and quantitative modeling to understand how anthropogenic stressors influence freshwater fisheries, and develop new approaches to help important fisheries deal with a changing world. 
        <br>
        <span style="font-size:0.75em">*Photo: Rachel Benedict, WDNR.*</span>
      design:
        background:
          image:
            filename: WalleyeInFyke.jpg
            width: 1000px
            
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./research/" cta_text="See what we do →" %}}
    design:
      columns: '1'
      background:
        image: 
          filename: CFLPano.jpg
          width: 200px
          height: 20px
          caption: 'Photo credit: Zach Feiner'
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']

      
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
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: IceFishingUpNorth.jpg
          width: 2000px
          caption: 'Photo credit: Zach Feiner'
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
