---
title: 'People'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title: People
      text: 'Meet the SM@RT people involved in my research:'
      filters:
        # user_groups: ["Researchers",
        #          "Ph.D. Students",
        #          "Former Ph.D. Students"]
        folders:
          - authors
    design:
      view: article-grid
      fill_image: false
      columns: 3
      # Show user's social networking links? (true/false)
      show_social: true
      # Show user's interests? (true/false)
      show_interests: false
---