---
# Leave the homepage title empty to use the site title
title:

date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to **GMC**
        content: Advancing Carbon Neutrality and Green Hydrogen via Field-Enhanced Electrolysis.
        align: center
        background:
          image:
            filename: groupimage.jpg
            filters:
              brightness: 0.8
          position: right
          size: contain
          color: '#666'
        link:
          icon: 
          icon_pack: fas
          text: Check our research...
          url: ../tour/

      - title: New publication
        content: 'Coordination Engineering Modulates Spin-Polarization in Ruthenium Oxide to Enhance Acidic Oxygen Evolution Reaction'
        align: left
        background:
          image:
            filename: tan.jpg
            filters:
              brightness: 0.8
          position: center
          size: contain
          color: '#555'
        link:
          icon: enjoy
          icon_pack: fas
          text: latest News
          url: ../post/

      - title:  " "
        content: "                                          "                                             
        align: right
        background:
          image:
            #filename: welcome.jpg
            filename: jtc-b3.jpg
            filters:
              brightness: 0.8
          position: center
          size: contain
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          #text: Join Us
          text: JTC
          #url: ../contact/
          url: ../project/fee-jtc/

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      #slide_height: ''
      slide_height: '80vh'
      is_fullscreen: false
      #is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 5000

  - block: hero
    content:
      title: |
        Green Molecules Conversion Group (GMC)
      text: |   
       <br>
        
        Our group is dedicated to advancing electrocatalysis and energy conversion by leveraging external field effects-such as electric and magnetic fields-to boost electrochemical reactions. We focus on developing efficient solutions for green hydrogen production and CO₂ reduction, aiming to contribute to carbon neutrality through innovative field-enhanced catalytic strategies.

      image:
         filename: H2.jpg
         

 # - block: markdown
 #   content:
 #     title: |
 #      Research Topic
 #     subtitle: ""
 #     text: |
      
 #      Our research advances carbon neutrality by developing renewable energy-driven photo/electrocatalytic systems that efficiently produce green hydrogen and convert greenhouse gases into valuable chemicals. By engineering field-responsive catalysts and leveraging operando techniques with multiscale simulations, we reveal how external fields optimize catalytic performance at the atomic level. Our work bridges fundamental science and industrial application, accelerating the scale-up of electrolyzers to deliver sustainable, high-rate green hydrogen production.

 #      <div style="text-align:center;">
 #       <img src="/media/spin-catalysis.jpg" alt="Spin Catalysis" style="max-width:600000px;width:100%;border-radius:12px;box-shadow:0 2px 8px #aaa;" />
 #      </div>
  - block: collection
    content:
      title: Latest News
      count: 5
      filters:
        page_type: post
      order: desc
    design:
      view: compact
      columns: '1'

  - block: collection
    content:
      title: Latest publications
      count: 5
      filters:
        folders:
          - publication
        
      
    design:
      view: citation
      columns: '1'
      showTags: true         # ← 打开标签显示
      meta:
        - date               # 也可以把日期放回去
        - tags               # 按顺序展示：日期、标签

  - block: markdown
    content:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}

  - block: markdown
    content:
      text: |
        <div style="width:100%;text-align:center;">
          <img src="/media/funding.jpg" alt="Funding" style="
            display:inline-block;
            max-width:1000px;
            width:80vw;
            min-width:120px;
            height:auto;
            margin:0 auto;
            border:none;
            background:transparent;" />
        </div>

---
