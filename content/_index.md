---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  # - block: about.avatar
  #   id: about
  #   content:
  #     # Choose a user profile to display (a folder name within `content/authors/`)
  #     username: admin
  #     # Override your bio text from `authors/admin/_index.md`?
  #     text:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

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
              * GPA: 3.83/4.0
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
      # phone: +1 217 200 1083
      # appointment_url: 'https://calendly.com'
      autolink: true
      coordinates:
        latitude: "40.109714957017594"
        longitude: "-88.23412380224788"

    design:
      columns: "2"
---
