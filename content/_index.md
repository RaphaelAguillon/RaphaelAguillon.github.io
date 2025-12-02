---
title: ""
date: 2022-10-24
type: landing

design:
  spacing: "6rem"

sections:
  # MAIN BIO SECTION (Fabian-style)
  - block: markdown
    content:
      title: "Raphaël Aguillon"
      subtitle: "Integrative biologist – circadian systems, eco-evo-devo, environmental sensing"
      text: |-
        I am an integrative biologist at the Institut de Biologie Physico-Chimique (CNRS, Paris),
        interested in how environmental cues such as light, temperature and cellular stress
        reshape gene regulatory networks, development and behaviour.

        My work combines circadian systems biology in the marine diatom *Phaeodactylum tricornutum*
        with developmental and behavioural chronobiology in cnidarians, to understand how biological
        rhythms emerge, evolve, break and reorganize across marine ecosystems.

        **Research themes**

        - Circadian transcriptional architecture in microalgae  
        - Sleep and DNA-damage responses in cnidarians  
        - Environmental sensing during neural development  
        - Eco-evo-devo of marine resilience

        [Full bio →](/authors/admin/) · [All publications →](/publications/)

        <!-- Optional portrait on the main page:
        ![Raphaël Aguillon](/uploads/avatar.jpg)
        -->
    design:
      columns: "1"

  # FEATURED PUBLICATIONS
  - block: collection
    id: papers
    content:
      title: "Featured publications"
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  # RECENT PUBLICATIONS (LIST)
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
---
