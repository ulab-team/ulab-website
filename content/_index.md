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


  - block: markdown
    content:
      title: About Us
      subtitle: A policy research led by Dr Guibo Sun
      text: Placeholder. I want to add an image on the left and text on the right


  - block: collection
    id: posts
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

  - block: features
    id: people
    content:
      title: People
      text: Our members come from diverse backgrounds and are united by URBAN
      items:
        - name: Dr Guibo Sun
          icon: magnifying-glass
          description: ULab principle investigator, leading academic
        - name: Dr Jieun Lee
          icon: bolt
          description: Urban economist, Postdoc Fellow at HKU
        - name: Dr Kristen Zhao
          icon: sparkles
          description: Urban researcher, Postdoc Fellow at HKU
        - name: Dr Yao Du
          icon: code-bracket
          description: Social scientist, Postdoc Fellow at HKU
        - name: Dongsheng He
          icon: star
          description: Urban researcher, PhD Candidate at HKU
        - name: Scarlet Tong
          icon: rectangle-group
          description: Architect, PhD Candidate at HKU
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
  - block: testimonials
    content:
      title: Contact
      text: Collaboration, join us, and more
      items:
        - name: Guibo
          role: "Director and PI"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          email: ulab.partners@gmail.com
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Build your future-proof website
      text: As easy as 1, 2, 3!
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
