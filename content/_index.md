---
# Leave the homepage title empty to use the site title
title: Ruben Interian
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: ruben-interian
  - block: experience
    id: experience
    content:
      title: Experience
      subtitle: (selected positions)
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Professor of Computer Science
          company: Universidade Estadual de Campinas
          company_url: 'https://www.topuniversities.com/universities/universidade-estadual-de-campinas-unicamp'
          company_logo: logounicamp
          location: Campinas, São Paulo
          date_start: '2023-12-01'
          date_end: ''
          description:
        - title: FAPESP Postdoctoral Research Fellow
          company: Universidade de São Paulo
          company_url: 'https://www.topuniversities.com/universities/universidade-de-sao-paulo'
          company_logo: logousp
          date_start: '2022-12-01'
          date_end: '2023-11-30'
          description:
        - title: Lead Data Analyst and Consultant
          company: The World Bank
          company_url: 'https://www.worldbank.org/en/home'
          company_logo: logoworldbank
          date_start: '2019-02-01'
          date_end: '2021-11-30'
          description:
    design:
      columns: '2'
  # - block: collection
  #  id: posts
  #  content:
  #    title: Recent Posts
  #    subtitle: ''
  #    text: ''
  #    # Choose how many pages you would like to display (0 = all pages)
  #    count: 5
  #    # Filter on criteria
  #    filters:
  #      folders:
  #        - post
  #      author: ""
  #      category: ""
  #      tag: ""
  #      exclude_featured: false
  #      exclude_future: false
  #      exclude_past: false
  #      publication_type: ""
  #    # Choose how many pages you would like to offset by
  #    offset: 0
  #    # Page order: descending (desc) or ascending (asc) date.
  #    order: desc
  #  design:
  #    # Choose a layout view
  #    view: compact
  #    columns: '2'
  #- block: portfolio
  #  id: projects
  #  content:
  #    title: Projects
  #    filters:
  #      folders:
  #        - project
  #    # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #    default_button_index: 0
  #    # Filter toolbar (optional).
  #    # Add or remove as many filters (`filter_button` instances) as you like.
  #    # To show all items, set `tag` to "*".
  #    # To filter by a specific tag, set `tag` to an existing tag name.
  #    # To remove the toolbar, delete the entire `filter_button` block.
  #    buttons:
  #      - name: All
  #        tag: '*'
  #      - name: Deep Learning
  #        tag: Deep Learning
  #      - name: Other
  #        tag: Demo
  #  design:
  #    # Choose how many columns the section has. Valid values: '1' or '2'.
  #    columns: '1'
  #    view: showcase
  #    # For Showcase view, flip alternate rows?
  #    flip_alt_rows: false
  # - block: markdown
  #  content:
  #    title: Gallery
  #    subtitle: ''
  #    text: |-
  #      {{< gallery album="demo" >}}
  #  design:
  #    columns: '1'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      # view: card
      view: citation
  # - block: collection
  #  content:
  #    title: Recent Publications
  #    text: |-
  #      {{% callout note %}}
  #      Quickly discover relevant content by [filtering publications](./publication/).
  #      {{% /callout %}}
  #    filters:
  #      folders:
  #        - publication
  #      exclude_featured: true
  #  design:
  #    columns: '2'
  #    view: citation
  - block: collection
    id: talks
    content:
      # title: Recent & Upcoming Talks
      title: Newspaper, Talks & Interviews
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  # - block: tag_cloud
  #  content:
  #    title: Popular Topics
  #  design:
  #    columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      # email: ruben@icmc.usp.br
      # address:
      #  street: Av. Trab. São Carlense 400
      #  city: São Carlos
      #  region: São Paulo
      #  postcode: '13566-590'
      #  country: Brazil
      #  country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # contact_links:
      #  - icon: twitter
      #    icon_pack: fab
      #    name: RubenUH
      #    link: 'https://twitter.com/RubenUH'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
---
