---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
        - title: Process Systems Engineering & Sustainable Production Lab
          content: 'Engineering the path to net-zero chemical manufacturing at NCKU'
          align: center
          background:
            image:
              filename: IMG_9864.jpg
              filters:
                brightness: 0.6
            position: center
            color: '#203a43'
        - title: Meet the Team
          content: 'CCUS · Life Cycle Assessment · Adsorption Separation · Process Systems Engineering'
          align: center
          background:
            image:
              filename: S__38871079.jpg
              filters:
                brightness: 0.6
            position: center
            color: '#203a43'
        - title: Toward Net-Zero Chemical Manufacturing
          content: 'Department of Chemical Engineering, National Cheng Kung University'
          align: center
          background:
            image:
              filename: IMG_9866.JPG
              filters:
                brightness: 0.6
            position: center
            color: '#203a43'
    design:
      slide_height: '420px'
  - block: hero
    id: hero
    content:
      title: |
        Process Systems Engineering &
        Sustainable Production Lab
      text: |
        <br>

        At the **Department of Chemical Engineering, National Cheng Kung University (NCKU)**, we engineer the path to **net-zero chemical manufacturing** — combining process simulation, optimization, and life cycle assessment to turn decarbonization ideas into deployable processes.

  - block: features
    id: directions
    content:
      title: What We're Building
      subtitle: Three directions where we're looking for industry partners
      items:
        - name: Electrify & Quantify
          icon: bolt
          icon_pack: fas
          description: 'Simulating electrified chemical processes and quantifying their carbon-and-cost payoff through life cycle assessment.'
        - name: From Capture to Storage
          icon: route
          icon_pack: fas
          description: 'Optimizing the full CO₂ supply chain — from emission sources through pipelines to geological sinks — with network-level LCA.'
        - name: LCA at Machine Speed
          icon: robot
          icon_pack: fas
          description: 'LLM-driven pipelines that turn process documents into auditable life-cycle inventories, cutting LCA turnaround time.'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./research/" cta_text="Explore our research →" %}}
    design:
      columns: '1'

  - block: collection
    content:
      title: Recent Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title: About the Lab
      subtitle:
      text: |
        The lab is led by **Prof. Tsai-Wei Wu**, who brings six years of
        industrial process-development experience, a PhD in Process Systems
        Engineering from National Taiwan University, and international
        collaborations built at Tohoku University, Japan. We pair hands-on
        process know-how with sustainability analysis — and we welcome students
        and industry partners who want to build a net-zero chemical industry.

        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
