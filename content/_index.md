---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "1rem"


sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: CV
        url: uploads/resume.pdf
    design:
      css_class: light 
      # set the color theme of the section
      background:
        color: '' #no color
        image:
          # Add your image background to `assets/media/`.
          filename: ''
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
      # spacing: 
        # padding: ['0px', '0', '0px', '0']  # Customize the section spacing. Order is top, right, bottom, left.

  - block: markdown
    # id: section-1
    content:
      title: Section
      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!

  - block: markdown
    # id: section-1
    content:
      title: Section 1
      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!

  # - block: collection
  #   content:
  #     title: JMP
  #     text: ""
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: false
  #   design:
  #     # View.
  #     #   1 = List
  #     #   2 = Compact
  #     #   3 = Card
  #     #   4 = Citation
  #     #   5 = Showcase
  #     #   6 = Masonry
  #     view: citation
      # spacing: 
      #   padding: ['0px', '0', '0px', '0']  # Customize the section spacing. Order is top, right, bottom, left.


  # - block: collection
  #   content:
  #     title: Work in Progress
  #     text: ""
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: false
  #   design:
  #     view: citation
      # spacing: 
      #   padding: ['0px', '0', '0px', '0']  # Customize the section spacing. Order is top, right, bottom, left.


  # - block: markdown
  #   content:
  #     title: '📚 My Research'
  #     subtitle: ''
  #     text: |-
  #       Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

  #       I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
  #       Please reach out to collaborate 😃
  #   design:
  #     columns: '1'

  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publication
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid #several picture of the publication
  #     columns: 2

  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1

  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]

---

