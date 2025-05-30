---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: #<p class="me">👋 </p>
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: features
  #   content:
  #     title: Skills
  #     items:
  #       - name: R
  #         description: 90%
  #         icon: r-project
  #         icon_pack: fab
  #       - name: Statistics
  #         description: 100%
  #         icon: chart-line
  #         icon_pack: fas
  #       - name: Photography
  #         description: 10%
  #         icon: camera-retro
  #         icon_pack: fas
  # - block: experience
    # content:
    #   title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
    #   items:
    #     - title: CEO
    #       company: GenCoin
    #       company_url: ''
    #       company_logo: org-gc
    #       location: California
    #       date_start: '2021-01-01'
    #       date_end: ''
    #       description: |2-
    #           Responsibilities include:

    #           * Analysing
    #           * Modelling
    #           * Deploying
    #     - title: Professor of Semiconductor Physics
    #       company: University X
    #       company_url: ''
    #       company_logo: org-x
    #       location: California
    #       date_start: '2016-01-01'
    #       date_end: '2020-12-31'
    #       description: Taught electronic engineering and researched semiconductor physics.
    # design:
    #   columns: '2'

  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Awards'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.

  #     items:
  #       - certificate_url:
  #         date_end: ''
  #         date_start: '2024-10-18'
  #         description: ''
  #         organization: Proceedings of ACM Conference on Computer and Communications Security (CCS)
  #         organization_url:
  #         title: Distinguished Paper Award
  #         url: https://www.sigsac.org/ccs/CCS2024/program/awards.html 
  #       # - certificate_url: https://www.edx.org
  #       #   date_end: ''
  #       #   date_start: '2021-01-01'
  #       #   description: Formulated informed blockchain models, hypotheses, and use cases.
  #       #   organization: edX
  #       #   organization_url: https://www.edx.org
  #       #   title: Blockchain Fundamentals
  #       #   url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #   design:
  #     columns: '2'





  - block: collection
    id: publication
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      count: 4
      filters:
        folders:
          - publication 
        exclude_featured: false
    design:
      columns: '2'
      view: citation


  - block: markdown
    id: news
    content:
      title: Latest News & Travels
      subtitle:  
      text: |-
        - ✈️ &nbsp; CCS 2024 @ Salt Lake City, USA (October 14 - 18)
          - Honored to win the Distinguished Paper Award for my paper "Organic or Diffused: Can We Distinguish Human Art from
              AI-generated Images?"
        - ✈️ &nbsp; USENIX Security 2024 @ Philadelphia, PA, USA (August 14 - 16)
        - ✈️ &nbsp; IEEE S&P @ San Francisco, CA, USA (May 20 - 23)
        - ✈️ &nbsp; CCS 2023 @ Copenhagen, Denmark (Nov 26 - 30)
        - ✈️ &nbsp; USENIX Security 2023 @ Anaheim, CA, USA (Aug 9 - 11)
        - ✈️ &nbsp; ICML 2023 @ Honolulu, Hawaii, USA (July 23 - 29) 


    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
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

  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'

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


 
  - block: contact
    id: contact
    content:
      title: Contact 
      subtitle:
      text: |-
        Get in touch!
      # Contact (add or remove contact options as necessary)
      # email: annaha@uchicago.edu
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      address:
        street: 5730 S Ellis Ave
        city: Chicago
        region: IL
        postcode: '60637'
        country: United States
        country_code: US
      # directions: John Crerar Library, Office 375
      # office_hours: 
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/annaha_yj'
        # - icon: skype
        #   icon_pack: fab
        #   name: Skype Me
        #   link: 'skype:echo123?call'
        # - icon: video
        #   icon_pack: fas
        #   name: Zoom Me
        #   link: 'https://zoom.com'

        - icon: envelope
          icon_pack: fas
          name: Email me
          link: /contact

      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form: 
        provider:  #netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true 
    design:
      columns: '2'
---
