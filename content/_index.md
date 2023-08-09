---
title: Not empy
date: 2022-10-24
type: landing

sections:
# Leave the homepage title empty to use the site title
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: Python
          description: 90%
          icon: r-project
          icon_pack: fab
        - name: Machine learning
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: Computer Vision
          description: 0%
          icon: camera-retro
          icon_pack: fas 
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Software developer
          company: Google Summer of Code (The Mifos Initiative)
          company_url: ''
          company_logo: org-gc
          location: United States
          date_start: '2023-05-29'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Developing a chatbot utilizing Java and Rasa Natural Language Processing (NLP) framework. Involved in designing and coding conversational flows, and training the chatbot to understand user queries.
              * Leveraged Java programming skills to develop the backend functionalities and integrate Mifos APIs, while leveraging Rasa's NLP capabilities for effective natural language understanding.
        - title: Software engineer
          company: Quinbay Technologies (Blibli.com)
          company_url: ''
          company_logo: org-gc
          location: India
          date_start: '2021-02-01'
          date_end: '2022-06-30'
          description: |2-
              Responsibilities include:

              * Automated the manual process of uploading products and saved business team 100 hours per week. Went on to optimize the code to improve performance by 86%.
              * Led a team of 4 to revamp multiple microservices to build price segmentation model in the application that positively impacted the GMV of the application.
              * Improved search query performance by 58% which enhanced user experience and took complete ownership of handling Elastic Search for team.
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
      # Contact (add or remove contact options as necessary)
      email: meghnabajoria8@gmail.com
      phone: +1 (620)-391-3957
      address:
        city: San Jose
        region: CA
        postcode: '95113'
        country: United States
        country_code: US
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
