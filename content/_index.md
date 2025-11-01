---
# Leave the homepage title empty to use the site title
title:
date: 2025-10-19
type: landing

# sections:
#   - block: hero
#     content:
#       title: Welcome
#       # Reference an image in your `assets/media/` folder
#     design:
#       background:
#         text_color_light: true
#         # gradient_end: '#1976d2'
#         # gradient_start: '#004ba0'
#         image:
#           filename: DSC_1114.jpg
#           size: cover
#           position: center
#           parallax: true
#       spacing:
#         padding: ["100px", "0", "300px", "0"]
#         
sections:
  - block: hero
    content:
      title: ''
      image:
        filename: Kibale_color_with_black_text.png
      text:
        Our aim is to advance understanding of the tropical
        forest of Kibale National Park and to support the conservation of this
        unique ecosystem. We study the behavior and ecology of red colobus and
        other primates; the population dynamics of primates and other wildlife;
        forest restoration and dynamics; disease transmission among wildlife and
        people; human–wildlife interactions; and the impacts of climate change
        and other human-driven environmental changes on the park’s flora and
        fauna. To this end, we collaborate with a broad network of partners in
        Uganda and around the world.
    design:
      background:
        text_color_light: false
        # gradient_end: '#1976d2'
        # gradient_start: '#004ba0'
        image:
          filename: ChapmanKibaleForest.jpg
          size: cover
          position: center
          parallax: true

  - block: collection
    id: projects
    content:
      title: Research Projects
      subtitle: ''
      text: ''
      filters:
        folders:
          - projects
      count: 0  # Number of items to show (0 = all)
      # Default filter UI (for future release)
      #default_button_index: 0
      # Filter toolbar (optional)
      # Add or remove as many filters as you like
    #   buttons:
    #     - name: All
    #       tag: '*'
    #     - name: Machine Learning
    #       tag: ML
    #     - name: Biology
    #       tag: Biology
    #     - name: Materials
    #       tag: Materials
    design:
      view: card
      columns: 2
  # - block: slider
  #   content:
  #     slides:
  #     - title: Primate Ecology and Behavior
  #       content: With 12 primate species varying in their diet and social systems, Kibale is an outstanding area to investigate the behavior and ecology of forest-dwelling primates. Our focus is on the leaf-eating red colobus (_Piliocolobus teophreles_).
  #       align: center
  #       background:
  #         image:
  #           filename: RedColobus_Colin.jpg
  #           filters:
  #             brightness: 0.7
  #         position: right
  #         color: '#666'
  #     - title: Forest Restoration
  #       content: 'From tree nurseries to the wild.'
  #       align: left
  #       background:
  #         image:
  #           filename: 13Nursery.jpg
  #           filters:
  #             brightness: 0.7
  #         position: center
  #         color: '#555'
  #     - title: Human-Wildlife Interactions
  #       content: Elephants, elephants, elephants…
  #       align: right
  #       background:
  #         image:
  #           filename: ChapmanForestElephant.JPG
  #           filters:
  #             brightness: 0.5
  #         position: center
  #         color: '#333'
  #     - title: Disease Ecology
  #       content: Symptoms, transmissions, wildlife, humans, …
  #       align: right
  #       background:
  #         image:
  #           filename: tyvek_suits_small.jpeg
  #           filters:
  #             brightness: 0.5
  #         position: center
  #         color: '#333'
  #     #   link:
  #           # icon: graduation-cap
  #           # icon_pack: fas
  #           # text: Join Us
  #           # url: ../contact/
  #   design:
  #     # Slide height is automatic unless you force a specific height (e.g. '400px')
  #     slide_height: ''
  #     is_fullscreen: true
  #     # Automatically transition through slides?
  #     loop: false
  #     # Duration of transition between slides (in ms)
  #     interval: 2000
  - block: people
    content:
      title: Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Project Leaders
          - Students and Postdocs
          - Alumni
          - Field Assistants
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: card
  #     columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'
  # 
  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---
