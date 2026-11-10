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
      # Ho commentato queste tre righe per far sparire il bottone:
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
      headings:
        about: 'About me'  # <-- Inserisci qui il tuo nuovo titolo (es. Chi Sono, Su di me, ecc.)
        education: ''
        interests: ''
    design:
      # Nasconde gli SVG SOLO dentro i titoli h2 e h3, preservando le icone social
      css_class: '[&_h2_svg]:hidden [&_h3_svg]:hidden'
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
---
