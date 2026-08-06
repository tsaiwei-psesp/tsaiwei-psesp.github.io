---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
        - title: Net-Zero Chemical Manufacturing
          content: 'Process Systems Engineering & Sustainable Production Lab · NCKU'
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
    design:
      slide_height: '420px'
  - block: markdown
    id: hero
    content:
      title: Engineering Net-Zero Chemical Manufacturing
      text: |
        At the **Department of Chemical Engineering, National Cheng Kung University (NCKU)**, we engineer the path to **net-zero chemical manufacturing** — combining process simulation, optimization, and life cycle assessment to turn decarbonization ideas into deployable processes.
    design:
      columns: '1'

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
      title: Latest Events
      subtitle:
      count: 3
      filters:
        folders:
          - post
      order: desc
    design:
      view: card
      columns: '2'

  - block: markdown
    id: awards
    content:
      title: Award and Grant News
      text: |
        <div class="award-card">
        <span class="award-date">2026 / 07</span>
        <p>Congratulations to the following students for their outstanding achievements at the <strong>2026 Taiwanese Colloid and Interface Society &amp; International Symposium on Nanomaterials and Colloidal Science (TWCIS)</strong>:</p>
        <ul>
        <li><strong>Yu-Ting Tai</strong> (戴郁庭, D2) — Best Poster Award</li>
        <li><strong>Che-An Cheng</strong> (鄭哲安, M1) — Excellent Poster Award</li>
        </ul>
        </div>
    design:
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
