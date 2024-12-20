---
# Leave the homepage title empty to use the site title
title: Multimodal Analysis, Generation and InteraCtion Research Group at Bath
date: 2024-10-29
type: landing

sections:
  - block: hero
    content:
      title: |
        MAGIc@Bath
        Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Multimodal Analysis, Generation and InteraCtion research group at Bath** is a center of excellence for Visual Computing and Artificial Intelligence research, teaching, and practice. More about our projects can be seen [here](https://magic-at-bath.github.io/project)
  
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
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

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
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
