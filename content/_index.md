---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: Skills
      items:
        - name: Python
          description: 90%
          icon: python
          icon_pack: fab
        - name: C/C++
          description: 80%
          icon: c
          icon_pack: fab
        - name: Java
          description: 70%
          icon: java
          icon_pack: fab
        - name: Go
          description: 60%
          icon: golang
          icon_pack: fab
        - name: Photography
          description: 10%
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
        - title: Bachelor of Science in Computer Science
          company: University of Illinois at Urbana-Champaign
          company_url: ""
          company_logo: illini
          location: Illinois
          date_start: "2020-01-01"
          date_end: ""
          description: |2-
              * GPA: 3.93/4.0
              * Major: Computer Science
    design:
      columns: "2"

  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ""
      text: ""
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
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
      # Choose a layout view
      view: compact
      columns: "2"

  - block: portfolio
    id: projects
    content:
      title: Projects
      subtitle: Still under construction, more to come soon!
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
          tag: "*"
        # - name: Deep Learning
        #   tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: "1"
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

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

  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: "2"

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # text: |-
      #   Leave me a msg here!

      # Contact (add or remove contact options as necessary)
      email: ruoliu.nj@gmail.com
      # phone: 217 200 1083
      # appointment_url: 'https://calendly.com'
      address:
        street: 707 4th St
        city: Champaign
        region: IL
        postcode: "61820"
        country: United States
        country_code: US
      contact_links:
        - icon: weixin
          icon_pack: fab
          name: Wechat 13813390796
          link: "https://u.wechat.com/MGM85HajojLUwVLKmameq0k"
      autolink: true
      coordinates:
        latitude: "40.109714957017594"
        longitude: "-88.23412380224788"

    design:
      columns: "2"

---
