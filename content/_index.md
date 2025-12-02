---
title: ""
date: 2022-10-24
type: landing

design:
  spacing: "6rem"

sections:

  # 1) PROFESSIONAL SUMMARY + EDUCATION + INTERESTS
  - block: resume-biography-3
    content:
      username: admin
      text: |-
        I am an integrative biologist studying how the environment shapes the development and behaviour of marine animals. I specifically focus on how rising ocean temperatures during early life influence how nervous systems form and how organisms function later on.

        Using behavioural tracking, live imaging and large-scale molecular analyses in the sea-anemone *N. vectensis*, I link environmental change to its effects on cells, genes and behaviour. My goal is to identify the most vulnerable stages of development to better predict how climate change will alter animal behaviour and marine ecosystems, and to provide evidence that can guide policymakers toward necessary environmental decisions.

        Please reach out for potential collaborations, seminars or to discuss projects.
      headings:
        about: "Professional summary"
        education: "Education"
        interests: "Research interests"
    design:
      background:
        gradient_mesh:
          enable: true
      avatar:
        size: large
        shape: circle

  # 2) FEATURED PUBLICATIONS
  - block: collection
    id: papers
    content:
      title: "Featured publications"
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: card
      columns: 3

  # 3) RECENT PUBLICATIONS
  - block: collection
    content:
      title: "Recent publications"
      text: ""
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  # 4) EXPERIENCE (OVERVIEW)
  - block: markdown
    content:
      title: "Experience"
      text: |-
        - **2025–present – Postdoctoral Scientist, IBPC (CNRS, Paris)**  
          Circadian regulation, promoter architecture and gene regulatory networks in  
          *Phaeodactylum tricornutum*.

        - **2019–2024 – Postdoctoral Scientist, Bar-Ilan University, Israel**  
          Molecular chronobiology, sleep regulation and DNA-damage responses in  
          *Nematostella vectensis* and *Cassiopea andromeda*.

        - **2014–2017 – PhD Student, Centre de Biologie du Développement (CBD), Toulouse**  
          Development of the zebrafish olfactory system, linking progenitor heterogeneity  
          to morphogenesis and neurogenesis.
    design:
      columns: "1"

  # 5) FELLOWSHIPS & FUNDING
  - block: markdown
    content:
      title: "Fellowships & funding"
      text: |-
        - **Azrieli International Postdoctoral Fellowship** – Azrieli Foundation (2021–2024)  
        - **Gonda Brain Research Center Fellowship** – Bar-Ilan University (2020–2021)  
        - **Kolman Tzoref Postdoctoral Fellowship** – Kolman Tzoref Foundation (2019–2020)  
        - **French Ministry of Research PhD Fellowship (MESR)** – 2014–2017
    design:
      columns: "1"

  # 6) RECENT NEWS & PRESS
  - block: collection
    id: news
    content:
      title: "Recent news & press"
      text: ""
      page_type: post
      count: 5
      filters:
        folders:
          - post
        exclude_featured: false
        exclude_future: false
        exclude_past: false
    design:
      view: card
---
