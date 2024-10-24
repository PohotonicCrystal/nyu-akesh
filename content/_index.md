---
# Leave the homepage title empty to use the site title
title: 'Akesh'
date: 2024-4-8
type: landing

sections:
  - block: hero
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: Hugo Academic Theme
      image:
        filename: hero-academic.png
      cta:
        label: '**Get Started**'
        url: https://hugoblox.com/templates/
      cta_alt:
        label: Ask a question
        url: https://discord.gg/z8wNYzb
      cta_note:
        label: >-
          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Hugo Blox Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/theme-academic-cv" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
        **Generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 500,000+ sites.**

        **Easily build anything with blocks - no-code required!**

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: experience
    id: Experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: People & Culture Intern
          company: Authentic Brands Group 
          company_url: 'https://corporate.authentic.com/'
          company_logo: authentic
          location: New York, USA
          date_start: '2024-06-01'
          date_end: '2024-08-30'
          description: |2-
              * Spearheaded job profile nomenclature and competency matrices framework for Mgmt. and IC job tracks
              * Analyzed overhaul of bonus & equity program design and executive compensation through public peer financial data
              * Established a global framework for travel insurance across 16 countries, and project-managed execution
        - title: Research Assistant
          company: Human Capital Analytics Laboratory (NYU)
          company_url: 'https://game.engineering.nyu.edu/human-capital-analytics/'
          company_logo: NYU
          location: New York, USA
          date_start: '2024-01-01'
          date_end: ''
          description: |2-
              * Analyzed and visualized 10,000+ texts and assessment data related to human resources with Excel and R
              * Processed unstructured text data from job applicants' interview responses using Natural Language Processing methods
              * Trained Convolutional Neural Network (CNN) models to predict job applicants' Big Five Personality Traits scores
        - title: Summer Business Analyst
          company: StratOp Group Management Consulting Co., Ltd.
          company_url: 'https://www.stratopgroup.com/en/'
          company_logo: startop
          location: Beijing, China
          date_start: '2023-06-01'
          date_end: '2023-07-31'
          description: |2-
              * Collaborated with team members to conduct interviews with more than 15 experts in 5 different industries
              * Generated crosscheck methods to avoid overestimation by over 100K on the quantity of a crucial factor
              * Established a cost-accounting model with Excel V/HLOOKUP etc., promoted 6+ work streams of a $74K project
        - title: Part-time Assistant
          company: Roland Berger Enterprise Management Co., Ltd.
          company_url: 'https://www.rolandberger.com'
          company_logo: RolandBerger
          location: Beijing, China
          date_start: '2023-03-01'
          date_end: '2023-06-30'
          description: |2-
              * Conducted an independent research on the business model of the Integrated Energy Services provider
              * Integrated thousands of market information and data about China’s new-energy development within 3 hours
        - title: Training Instructor, Teaching Assistant
          company: Peking University, Department of PE.
          company_url: 'https://pe.pku.edu.cn/ywz1/Home.htm'
          company_logo: PKU
          location: Beijing, China
          date_start: '2023-02-01'
          date_end: '2023-07-31'
          description: |2-
              * Supervised 50+ students in hiking and camping teamwork and outdoor leadership training
              * In charge of co-construction visits between Peking University and the National Rock-Climbing Teams
        - title: Human Resources Intern
          company: Hubei Dinglong Holding Co., Ltd.
          company_url: 'https://en.dl-kg.com/#page1'
          company_logo: dinglong
          location: Wuhan, China
          date_start: '2022-02-01'
          date_end: '2022-03-31'
          description: |2-
              * Composed an HR practices consulting proposal, delivered management optimization advice to C-suite
              * Masterminded recruitment interviews in a cross-department environment, reached 130% of the recruitment mandate
              * Independently responsible for subsidiaries’ entire recruitment, includes resume selection, interview arrangement, etc.
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.linkedin.com/learning/certificates/6bcd335d022c6bb34c7d7dd17d6a3c1b3ef4a5e37badff11f97f0a1d8aa27333?u=2131553
          date_end: ''
          date_start: '2023-10-01'
          description: Identify challenges and promote success of Diversity, Inclusion, and Belonging in organizations.
          icon: linkedIn_icon
          organization: LinkedIn
          organization_url: https://www.linkedin.com/
          title: Diversity, Inclusion, and Belonging
          url: https://www.linkedin.com/learning/diversity-inclusion-and-belonging-2019?trk=learning-certificate_detail_search-card&upsellOrderOrigin=default_guest_learning
        # - certificate_url: https://www.edx.org
        #   date_end: ''
        #   date_start: '2021-01-01'
        #   description: Formulated informed blockchain models, hypotheses, and use cases.
        #   icon: edx
        #   organization: edX
        #   organization_url: https://www.edx.org
        #   title: Blockchain Fundamentals
        #   url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
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
        - name: Organizational Development
          tag: Organizational Development
        - name: Job Analysis
          tag: Job Analysis
        - name: Human Capital Management
          tag: Human Capital Management
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    id: Gallery
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
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
---
