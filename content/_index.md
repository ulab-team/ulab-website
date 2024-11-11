---
title: 'uLab'
date: 2024-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Urban Analytics and Interventions Research Lab
      text: A research lab advancing urban intelligibility

    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: ""
      background:
        color: ""
        image:
          # Add your image background to `assets/media/`.
          filename: ""
          filters:
            brightness: 0.5


  - block: cta-image-paragraph
    id: about
    content:
      items:
        - title: About us
          text: A policy research led by Dr Guibo Sun. dsggf srtrt sdfd ytygfd aerth gfdrgre.
          # Upload image to `assets/media/` and reference the filename here
          image: bg3.jpg
          button:
            text: More info
            url: about/


  - block: collection
    id: res
    content:
      title: research directions
      subtitle: ''
      text: 'these are our major research directions'
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - research
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: card
      columns: '3'

  - block: markdown
    id: people


  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Featured Outputs
          text: Academic articles, reports, and more!
          feature_icon: check
          features:
            - "Reports"
            - "Articles"
            - "Seminars"
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text: Read more
            url: https://hugoblox.com/templates/
        - title: Large Community
          text: Join our large community on Discord - ask questions and get live responses
          feature_icon: bolt
          features:
            - "Dedicated support channel"
            - "3,000+ users on Discord"
            - "Share your site and get feedback"
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.jpg
          button:
            text: Join Discord
            url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"

---
