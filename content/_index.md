---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: | 
        **Turbulence and Energy Systems Laboratory (TESLa)**
      subtitle: |
        **Paul M. Rady Department of Mechanical Engineering, University of Colorado, Boulder**
        {style="color: white"}
    design:
      columns: '1'
      background:
        image: 
          filename: /headers/Flatirons_Winter.jpg
          filters:
            brightness: 0.4
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ["50px", "0px", "10px", "0"]

  - block: portfolio
    id: project
    content:
      title: Research Areas
      filters:
        folders:
          - project
    design:
      spacing:
        padding: ["15px", "100px", "0px", "100px"]
#   - block: collection
#     content:
#       title: Latest News
#       subtitle:
#       text:
#       count: 5
#       filters:
#         author: ''
#         category: ''
#         exclude_featured: false
#         publication_type: ''
#         tag: ''
#       offset: 0
#       order: desc
#       page_type: post
#     design:
#       view: card
#       columns: '1'
  
#   - block: markdown
#     content:
#       title:
#       subtitle: ''
#       text:
#     design:
#       columns: '1'
#       background:
#         image: 
#           filename: coders.jpg
#           filters:
#             brightness: 1
#           parallax: false
#           position: center
#           size: cover
#           text_color_light: true
#       spacing:
#         padding: ['20px', '0', '20px', '0']
#       css_class: fullscreen
  
#   - block: markdown
#     content:
#       title:
#       subtitle:
#       text: |
#         {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
#     design:
#       columns: '1'
---
