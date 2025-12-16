---
title: 'Home'
date: 2023-10-24
type: landing
design:
  spacing: '4rem'
sections:
  - block: biography
    content:
      username: me
      button:
        text: Download Résumé
        url: uploads/resume.pdf
    design:
      spacing:
        # Großzügiges Padding für Vollbild-Effekt
        # [Oben, Rechts, Unten, Links]
        padding: ["40vh", "0", "40vh", "0"]
      banner:
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.png
        # Parallax ausschalten für fixen Hintergrund
        parallax: false
        text_color_light: true
      # Zusätzliche CSS-Anpassungen für fixen Hintergrund
      css_style: |
        background-attachment: fixed;
        background-size: cover;
        background-position: center;
        min-height: 100vh;
      biography:
        style: 'text-align: justify; font-size: 0.8em; background: rgba(255, 255, 255, 0.95); padding: 2rem; border-radius: 10px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);'
      avatar:
        size: xl 
        shape: circle
  - block: experience
    content:
      username: me
    design:
      date_format: 'January 2006'
      is_education_first: false
  - block: skills
    content:
      title: Skills & Hobbies
      username: me
  - block: languages
    content:
      title: Languages
      username: me
---
