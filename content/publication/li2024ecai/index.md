---
title: 'SaccadeMOT: Enhancing Object Detection and Tracking in Gigapixel Images via Scale-Aware Density Estimation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wenxi Li
  - Ruxin Zhang
  - Haozhe Lin
  - Yuchen Guo
  - Chao Ma
  - Xiaokang Yang

# Author notes (optional)
# author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2024-07-05T00:00:00Z'
# doi: 'https://doi.org/10.1109/TIP.2024.3404257'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-07-05T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In "27th European Conference on Artificial Intelligence"
publication_short: In *ECAI 2024*

abstract: "The advancement of deep learning in object detection and tracking has predominantly focused on megapixel images, leaving a critical gap in efficient processing of gigapixel images. These super high-resolution images present unique challenges due to their immense size and computational demands. To address this, we introduce SaccadeMOT, an innovative architecture for gigapixel-level multi-object tracking, inspired by the human eye saccadic movement. The cornerstone of SaccadeMOT is its ability to strategically select and process image regions, dramatically reducing computational load. The part of the detection phase is achieved through a two-stage process: the 'saccade' stage, which identifies regions of probable interest, and the 'gaze' stage, which refines detection in these targeted areas. Based on detection results, we track every object by a combination of head tracking and body tracking. Our approach, evaluated on the PANDA dataset, not only achieves a 8x speed increase over the state-of-the-art methods but also demonstrates significant potential in gigapixel-level pathology analysis through its application to Whole Slide Imaging."

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: yes

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: 'https://dl.acm.org/doi/10.1145/3581783.3612132'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
