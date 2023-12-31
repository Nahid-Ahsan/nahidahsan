---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  
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
          # description: 90%
          icon: fab fa-python
          icon_pack: fab
        - name: Computer Vision
          # description: 100%
          icon: fas fa-camera-retro
          icon_pack: fas

        - name: NLP
          # description: 10%
          icon: fas fa-robot
          icon_pack: fas

        - name: Deep Learning
          # description: 10%
          icon: fas fa-brain
          icon_pack: fas

        - name: Tensorflow
          # description: 10%
          icon: fas fa-cubes
          icon_pack: fas

        - name: Pytorch
          # description: 10%
          icon: fas fa-lightbulb
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
        - title: Artificial Intelligence Engineer
          company: Dream71 Bangladesh Ltd.
          company_url: ''
          # company_logo: org-gc
          location: Dhaka, Bangladesh
          date_start: '2022-08-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Conducted research and designed a Transformer ( Encoder-Decoder with
                attention mechanism) based assistance system (chatbot) for Bangla language.
              * Developed an end-to-end pipeline for efficient data collection.
              * Built a smart web app using Django framework and Rest API.
              * Implemented a digital preservation system with OCR capabilities.

        - title: Data Analyst
          company: Sohopathi
          company_url: ''
          # company_logo: org-x
          location: Dhaka, Bangladesh
          date_start: '2022-04-04'
          date_end: '2022-06-01'
          description: |2-
              Responsibilities include:
              * Built a data collection system from the production database.
              * Ensured data integrity through collaboration with operations teams and implementing corrective actions.
              * Conducted feature engineering on real-world data using Python.
              * Utilized MongoDB and wrote queries for data manipulation.
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://coursera.org/share/18a99acff3b1bf35fc5dee897633b49f
          date_end: ''
          date_start: '2023-07-25'
          description: ''
          organization: Deeplearning.ai
          organization_url: https://www.deeplearning.ai/
          title: Natural Language Processing Specialization
          url: 'https://www.coursera.org/specializations/natural-language-processing'
        - certificate_url: https://coursera.org/share/ef9a76780e6f68e0cafbdbe96b931974
          date_end: '2021-08-30'
          date_start: '2021-03-01'
          description: ''
          organization: Google
          organization_url: https://www.google.com
          title: Google Data Analytics Certification
          url: https://www.coursera.org/professional-certificates/google-data-analytics?utm_source=link&utm_medium=certificate&utm_content=cert_image&utm_campaign=sharing_cta&utm_product=course

    design:
      columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
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
  #     view: compact
  #     columns: '2'
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Other
  #         tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
  # # - block: markdown
  # #   content:
  # #     title: Gallery
  # #     subtitle: ''
  # #     text: |-
  # #       {{< gallery album="demo" >}}
  # #   design:
  # #     columns: '1'

  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card

  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation



  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact



  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'


  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-

      # Contact (add or remove contact options as necessary)
      email: nahidahsan74@gmail.com
      phone: +8801322588126
      # appointment_url: 'https://calendly.com'
      address:
        street: Nikunja 2
        city: Dhaka
        region: Dhaka
        postcode: '1229'
        country: Bangladesh
        country_code: BN
      directions: ''
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
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
