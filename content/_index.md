---
title: 'uLab'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: intro
    content:
      title: Urban Analytics and Interventions Research Lab
      text: A research lab advancing urban intelligibility
      primary_action:
        text: Enter lab
        url: https://hugoblox.com/templates/
        icon: rocket-launch
      secondary_action:
        text: About us
        url: https://docs.hugoblox.com
      announcement:
        text: "Transferred from a HKUrbanLab"
        link:
          text: "Read more"
          url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
  - block: research
    content:
      items:
        - name: Transport
          description: |
            Urban rail and health outcomes
        - name: Housing
          description: |
            Urban renewal and health outcomes
        - name: Public space
          description: |
            Street experiments for people-centric transition
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: people
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
  - block: featured-pubs
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
  - block: contact
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
