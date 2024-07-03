---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: Welcome to our Lab!
      text: |-
        First established in 2024 at the Singapore University of Social Sciences under Associate Professor Emily Ortega. 
        
        Research in Psychophysiology, Quality of Life, Stress, & Time Use (PQRST) Lab investigates how different facets of well-being, time spent and biopsychosocial models integrate into everyday activities.
      
        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>   
      image:
        # Reference an image in your `assets/media/` folder
        filename: PQRST Final Logo.jpg
          # Add your Call-To-Action (CTA) button and optional icon
      cta:
        label: Meet the team
        url: /people
        #icon_pack: fas
        #icon: download
      # Optionally, add an alternative CTA link
      cta_alt:
        label: View our publications
        url: /publication
    design:
      # Choose an optional background color, gradient, image, or video
      background:
        color: 
        text_color_light: false
  - block: features
    content:
      title: Our Research Surrounds
      #subtitle: Section subtitle
      #text: Section text
      items:
        - name: Psychophysiology & Heart Rate Variability
          description: 'The variation in time between two heartbeats, an indicator of pathological conditions related to cardiovascular health, and for treating psychological disorders and performance enhancement. Pioneering research into Singapore HRV norms, PQRST continues to investigate the correlation of said HRV norms with well-being and psychophysiology' 
          icon: HRV2
          icon_pack: custom
        - name: Time Use
          description: 'Time-use research closely monitors daily activities, times of stress and relaxation; PQRST investigates time use by surveying participants to examine predictors and expose trajectories with regard to health and systematic inequality. With the findings, PQRST aims to shed light on issues faced by vulnerable communities in Singapore and catalyse positive changes in the psychosocial state of the public'
          icon: TUD2
          icon_pack: custom
        - name: Quality of Life
          description: 'Defined as an individual’s perception of their experience in life in the context of the culture and value systems. PQRST looks into the facets of the broad-ranging concept, focusing on the enmeshment of physical and psychological states, personal beliefs, social relationships, and relationships with the environment. '
          icon: QOL2
          icon_pack: custom
  - block: portfolio
    id: research-themes
    content:
      title: Publications
      subtitle: 
      text: 
      filters:
        # Folders to display content from
        folders:
          - publication
        # Only show content with these tags
        tags: []
        # Exclude content with these tags
        exclude_tags: []
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        kinds:
          - page
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
      # Default portfolio filter button
      # 0 corresponds to the first button below and so on
      # For example, 0 will default to showing all content as the first button below shows content with *any* tag
      default_button_index: 0
      # Filter button toolbar (optional).
      # Add or remove as many buttons as you like.
      # To show all content, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the button toolbar, delete the entire `buttons` block.
      buttons:
        - name: All
          tag: '*'
        - name: Psychophysiology
          tag: psychophysiology
        - name: Quality of Life
          tag: qol
        - name: Stress
          tag: stress
        - name: Time Use
          tag: time-use
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view: compact
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
---