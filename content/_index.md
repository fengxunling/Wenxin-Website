---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Introduction about myself
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: Machine Learning
          description: I can deal with math and programming about classic machine learning and deep learning methods, especially the recurrent neural networks (RNNs), spiking neural networks (SNNs) and transfer learning models. 
          # icon: r-project
          # icon_pack: fab
        - name: Neural Imaging
          description: I know the principles about classic neural imaging, such as CT, fMRI and EEG. I can also do the analysis of EEG signals including source estimation, frequency analysis and functional connectivity.
          # icon: chart-line
          # icon_pack: fas
        - name: Programming
          description: I have excellent programming ability based on languages, including Python, MATLAB, C++ and Java.
          # icon: camera-retro
          # icon_pack: fas
  - block: experience
    content:
      title: Eduation and Research Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Department of Biomedical Engineering, SUSTech
          company: ''
          company_url: ''
          company_logo: biomedical engineering logo
          location: Supervisor - Quanying Liu
          date_start: '2021-07-01'
          date_end: ''
          description: |2-
              * Rearch about assessing generalization of cognitive tasks using multi-regional modular recurrent neural networks with transfer learning.
              * Research about transfer learning to decode brain states reflecting the relationship between cognitive tasks.
              * Infusing cognitive science into artificial general intelligence test facilitates evolution and safety of large models.
        - title: Department of Brain and Cognitive Science, MIT
          company: ''
          company_url: ''
          company_logo: MIT logo
          location: Supervisor - Guangyu Robert Yang
          date_start: '2023-07-01'
          date_end: '2023-12-31'
          description: The research is about investigating on spontaneous emergence of electromyographic signals similarity phenomenon during the execution of motor cognition task optimization using Spiking Recurrent Nueral Networks(SRNN) research models.
        - title: University of Zurich
          company: ''
          company_url: ''
          company_logo: UZH logo
          location: ''
          date_start: '2023-07-01'
          date_end: '2023-12-31'
          description: I learn courses from University of Zurich and ETH Zurich, including comparative behavioral neuroscience, bio and computational vision, models of computation.
        - title: New York Shanghai
          company: ''
          company_url: ''
          company_logo: NYU logo
          location: Supervisor - Xing Tian
          date_start: '2022-06-15'
          date_end: '2022-09-01'
          description: The research is about analysis of non-suicidal self-injury teenagers based on resting-state EEG signals, including source estimation analysis based on MNE, functional connectivity analysis based on weighted-PLI, and the linear regression of the functional connectivity in certain brain regions and medical diagnosis scores. 
        - title: Department of Computer Science and Engineering, SUSTech
          company: ''
          company_url: ''
          company_logo: CS logo
          location: Supervisor - Bo Tang
          date_start: '2020-09-01'
          date_end: '2021-06-30'
          description: I joined the SUSTech Collegiate Programming Contest (SUSTech-CPC) Team and won several gold and silver medals in the ACM-ICPC (International Collegiate Programming Contest) with my teammates.
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
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-01-01'
          description: ''
          organization: xyz
          organization_url: ''
          title: National - Project Leader | China College Student Entrepreneurship and Innovation Program
          url: ''
        - certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2021-01-01'
          description: ''
          organization: Guangdong Biomedical Engineering Association
          organization_url: https://www.edx.org
          title: Provincial - First Prize | Collegiate Biomedical Engineering Innovation Design Competition
          url: ''
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: Department of Education of Guangdong Province
          organization_url: ''
          title: Provincial - Gold Medal | Challenge Cup Entrepreneurship and Innovation Competition 
          url: ''
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: National - Gold Medal
          organization_url: 'https://icpc.global/'
          title: ACM-ICPC (International Collegiate Programming Contest) Regionals
          url: ''
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: Provincial - Gold Medal
          organization_url: ''
          title: CCPC (China Collegiate Programming Contest) Guangdong Province
          url: ''
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: National - Silver Medal
          organization_url: 'https://icpc.global/'
          title: ACM-ICPC Asia East Continent Finals
          url: ''
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: National - Bronze Medal
          organization_url: ''
          title: CCPC (China Collegiate Programming Contest) National Final 
          url: ''
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: Provincial - Winning Prize
          organization_url: ''
          title: Undergraduate Mathematical Contest in Modeling
          url: ''
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: National - 2nd, Gold Medal
          organization_url: ''
          title: CCPC (China Collegiate Programming Contest) for girls
          url: ''
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: National - Silver Medal
          organization_url: ''
          title: CCPC (China Collegiate Programming Contest) Regionals
          url: ''
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: National - Bronze Medal
          organization_url: ''
          title: CCPC (China Collegiate Programming Contest) Regionals
          url: ''
        
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
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
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
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
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Welcome to contact me!
      # Contact (add or remove contact options as necessary)
      email: chewx2020@mail.sustech.edu.cn
      phone: +1 617-256-0853
      # appointment_url: 'https://calendly.com'
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: '94305'
      #   country: United States
      #   country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
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
