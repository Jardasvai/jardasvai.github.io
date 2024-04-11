---
title: 'Home'
date: 2023-10-24
type: landing

design:
background:
  image:
    # Name of image in `assets/media/`.
    filename: assets\media\icons\custom\background.jpg
    # Apply image filters?
    filters:
      # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
      brightness: 0.6
    #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
    size: cover
    # Image focal point. Options include `left`, `center` (default), or `right`.
    position: center
    # Use a fun parallax-like fixed background effect on desktop? true/false
    parallax: true
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
    text_color_light: true

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Résumé
        url: uploads/resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: skills
    content:
      title: Skills & Hobbies
      username: admin
  - block: awards
    content:
      title: Awards
      username: admin
  - block: languages
    content:
      title: Languages
      username: admin
---
