---
# Leave the homepage title empty to use the site title
title: 
date: 2024-11-29
type: landing

sections:
  - block: resume-biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: 
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: max-fray-unsplash.jpg
          filters:
            brightness: 0.9
          size: cover
          position: center
          parallax: false

  # - block: stats
  #   content:
  #      items:
  #       - statistic: "82"
  #         description: |
  #           Publications
  #       - statistic: "1,000+"
  #         description: |
  #           Citations

    # design:
    #   # Section background color (CSS class)
    #   css_class: "bg-gray-100 dark:bg-gray-900"
    #   # Reduce spacing
    #   spacing:
    #     padding: [0, 0, 0, 0]
  - block: markdown
    content:
      title: 'Welcome! 👋'
      subtitle: ''
      text:  
             I am a public health risk expert dedicated to teaching, application, and scientific development of quantitative risk analysis and decision-making in public health. You will find more about my specialty in these areas including quality risk management (QRM), multiple criteria decision making (MCDM) on this website.  
    design:
      columns: '1'
  - block: collection
    content:
      title: Recent Posts
      font-size: M
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: '5'
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      design:
        view: showcase
          
  - block: collection
    content:
      title: Events
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: event
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view date-title-summary, article-grid, citation, card
      view: article-grid
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
