---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/CV___Harvard_like-1.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '🔬 My Research'
      subtitle: ''
      text: |-
        I am an undergraduate researcher in Cell and Molecular Biology at Shahid Beheshti University. My research interests focus on metabolic engineering, synthetic biology, and natural product biosynthesis.

        I am particularly interested in developing sustainable, cost-effective biosynthetic pathways for the pharmaceutical and food industries. I have hands-on laboratory experience in molecular genetics, including DNA extraction, PCR, and gel electrophoresis.

        I am currently seeking research opportunities to further develop my skills in enzymology and analytical chemistry. Please feel free to reach out to collaborate!
    design:
      columns: '1'
---