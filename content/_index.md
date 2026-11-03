---
title: ''
date: 2026-11-03
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      username: admin
  - block: markdown
    id: news
    content:
      title: News
      text: |-
        - **2026:** Three papers accepted to **NeurIPS 2026**: AWP, SpanFormer, and BiHashFormer.
        - **2026:** ElasticFormer accepted to **CVPR 2026**; GigaMoE and 2D-CrossScan Mamba accepted to **AAAI 2026**.
        - **Autumn 2026:** Teaching **Computer Vision** and **Deep Learning** at ECNU.
        - **November 2025:** Joined the **School of Statistics, East China Normal University** as a **Pre-Tenure Associate Professor**.
        - **June 2025:** Received my Ph.D. and the **Outstanding Graduate** honor from Shanghai Jiao Tong University.
        - **December 2024:** Awarded the **National Scholarship for Doctoral Students**.
    design:
      columns: '2'
  - block: markdown
    id: featured
    content:
      title: Selected Publications
      text: |-
        1. **[AWP: Activation-based Window Pruning for Gigapixel Object Detection](/publication/awp-2026/)**<br>
           *NeurIPS 2026*

        2. **[SpanFormer: Multi-Level Adaptive Sparsity for Object Detection in High-Resolution Wide Shots](/publication/spanformer-2026/)**<br>
           *NeurIPS 2026*

        3. **[BiHashFormer: Hash-Driven Dual-Branch Transformer for Efficient Object Detection in HRW Shots](/publication/bihashformer-2026/)**<br>
           *NeurIPS 2026*

        4. **[ElasticFormer: Detecting Objects in HRW Shots via Elastic Computing Vision Transformer](/publication/elasticformer-2026/)**<br>
           *CVPR 2026*

        5. **[GigaMoE: Sparsity-Guided Mixture of Experts for Efficient Gigapixel Object Detection](/publication/gigamoe-2026/)**<br>
           *AAAI 2026*

        6. **[2D-CrossScan Mamba: Enhancing State Space Models with Spatially Consistent Multi-Path 2D Information Propagation](/publication/2d-crossscan-mamba-2026/)**<br>
           *AAAI 2026*

        7. **[SparseFormer: Detecting Objects in HRW Shots via Sparse Vision Transformer](/publication/li2024mm/)**<br>
           *ACM Multimedia 2024*

        8. **[SaccadeDet: A Novel Dual-Stage Architecture for Rapid and Accurate Detection in Gigapixel Images](/publication/li2024ecml/)**<br>
           *ECML/PKDD 2024*

        9. **[SaccadeMOT: Enhancing Object Detection and Tracking in Gigapixel Images via Scale-Aware Density Estimation](/publication/li2024ecai/)**<br>
           *ECAI 2024*

        10. **[GigaHumanDet: Exploring Full-Body Detection on Gigapixel-Level Images](/publication/liu2024aaai/)**<br>
           *AAAI 2024*

        [Browse all publications →](/publication/)
    design:
      columns: '2'
  - block: markdown
    id: teaching
    content:
      title: Teaching
      text: |-
        **East China Normal University · School of Statistics**

        - **Autumn 2026 — Computer Vision:** Instructor.
        - **Autumn 2026 — Deep Learning:** Instructor.
        - **Spring 2026 — Statistical Machine Learning:** Teaching assistant; supported course teaching, answered student questions, and assisted with related teaching activities.

        My teaching connects AI foundations with current research and practical work, encouraging students to develop technical knowledge, creative thinking, and hands-on skills.
    design:
      columns: '2'
  - block: markdown
    id: honors
    content:
      title: Honors & Awards
      text: |-
        - **June 2025:** Outstanding Graduate, Shanghai Jiao Tong University.
        - **December 2024:** National Scholarship for Doctoral Students.
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
        - name: Gigapixel
          tag: Gigapixel
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
  - block: markdown
    content:
      title: Global Nexus of Intelligent Research
      text: |-      
        <style>
        .content-wrapper {
          max-width: 200px; /* 设置内容的最大宽度 */
          margin: 0 auto; /* 居中显示 */
        }
        .limited-size {
          max-width: 100%; /* 确保内部内容不会超出容器宽度 */
          max-height: 100px;
          overflow: hidden;
        }
        </style>
        <div class="content-wrapper">
          <script type="text/javascript" id="clstr_globe" class="limited-size" src="//clustrmaps.com/globe.js?d=9qYQma5Tl05H7vBYvhJ4gH0wANqVjPRWZASy00WUnNA"></script>
        </div>
    design:
      # Choose a layout view
      # view: list
      columns: '2'
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
  # - block: contact
  #   id: contact
  #   content:
  #     title: Contact
  #     subtitle:
  #     text: |-
  #       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
  #     # Contact (add or remove contact options as necessary)
  #     email: wenxi.li@sjtu.edu.cn
  #     # phone: 888 888 88 88
  #     appointment_url: 'https://calendly.com'
  #     address:
  #       street: 450 Serra Mall
  #       city: Stanford
  #       region: CA
  #       postcode: '94305'
  #       country: United States
  #       country_code: US
  #     directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #     office_hours:
  #       - 'Monday 10:00 to 13:00'
  #       - 'Wednesday 09:00 to 10:00'
  #     # Choose a map provider in `params.yaml` to show a map from these coordinates
  #     coordinates:
  #       latitude: '37.4275'
  #       longitude: '-122.1697'  
  #     contact_links:
  #       - icon: twitter
  #         icon_pack: fab
  #         name: DM Me
  #         link: 'https://twitter.com/Twitter'
  #       - icon: skype
  #         icon_pack: fab
  #         name: Skype Me
  #         link: 'skype:echo123?call'
  #       - icon: video
  #         icon_pack: fas
  #         name: Zoom Me
  #         link: 'https://zoom.com'
  #     # Automatically link email and phone or display as text?
  #     autolink: true
  #     # Email form provider
  #     form:
  #       provider: netlify
  #       formspree:
  #         id:
  #       netlify:
  #         # Enable CAPTCHA challenge to reduce spam?
  #         captcha: false
  #   design:
  #     columns: '2'
---
