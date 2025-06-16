---
title: Tour
date: 2022-10-24

type: landing

sections:

  - block: hero
    content:
      title: |
        Green Molecules Conversion Group
      text: |
        <br>
        
        The **Green Molecules Conversion Group** focuses on the **Field enhanced Photo/electrochemistry** research, teaching, and practice since its founding in 2024.
      image:
        filename: welcome.jpg

  - block: markdown
    content:
      title: |
       **Research Topic**
      subtitle: Our main research directions
      text: |
      
       Our research addresses climate change mitigation and reducing fossil fuel-related health risks through renewable energy-driven photo/electrocatalysis. These systems enable dual-purpose conversion: producing green hydrogen while transforming greenhouse gases into valuable chemicals. Although externally applied fields (magnetic, electric, strain) enhance catalytic efficiency via charge transfer optimization and adsorption energy tuning, the atomic-scale mechanisms governing field-coupled reactions remain unclear. We focus on designing field-responsive catalysts by engineering active sites via electron spin control and ferroelectric domain modulation. Combining operando techniques (XAS, Raman, TEM) with multiscale simulations, we decode how fields regulate reaction barriers and intermediate adsorption/desorption at electronic/atomic scales. A breakthrough innovation involves scaling electrolyzers from lab prototypes to industrial flow cells sustaining working current densities >1 A/cm² while maintaining selectivity. By establishing dynamic structure-activity relationships under operational conditions, we bridge fundamental mechanisms with reactor engineering challenges.

       <div style="text-align:center;">
        <img src="/media/spin-catalysis.jpg" alt="Spin Catalysis" style="max-width:600000px;width:100%;border-radius:12px;box-shadow:0 2px 8px #aaa;" />
       </div>
  
  #- block: collection
  #  content:
  #    title: Research Topics
  #    subtitle: Our main research directions
  #    text: Our research covers multiple frontier topics in catalysis, energy, and advanced materials.
  #    count: 6
  #    filters:
  #      folders:
  #        - research    # 自动抓取 content/research/ 下所有 md 文件
  #    order: asc
  #  design:
  #    view: card
  #    columns: '1'
  
  #- block: markdown
  #  content:
  #    title: 'Projects'
  #    subtitle: ''
  #    text:
  #  design:
  #    columns: ''
  #    background:
  #      image: 
  #        filename: coders.jpg
  #        filters:
  #          brightness: 1
  #        parallax: false
  #        position: center
  #        size: cover
  #        text_color_light: true
  #    spacing:
  #      padding: ['20px', '0', '20px', '0']
  #    css_class: fullscreen
  
  - block: markdown
    content:
      title: |
       **Projects**

  - block: collection
    content:
      title: Projects
      subtitle: Ongoing projects
      text: 
      count: 6
      filters:
        folders:
          - project    # 自动抓取 content/project/ 下所有 md 文件
        status: ongoing
      order: desc
    design:
      view: compact
      columns: 1
    #design:
    #  view: card
    #  columns: '1'

  - block: collection
    content:
      title: " "
      subtitle: "Completed projects"
      count: 50
      filters:
        folders:
          - project
        status: past
      order: desc
    design:
      view: compact
      columns: 1

  - block: markdown
    content:
       title:
       subtitle:
       text: |
         {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
       columns: '1' 
---
