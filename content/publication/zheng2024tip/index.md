---
title: 'Sparsely-Supervised Object Tracking'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jilai Zheng
  - Wenxi Li
  - Chao Ma
  - Xiaokang Yang

# Author notes (optional)
# author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2024-05-30T00:00:00Z'
doi: 'https://doi.org/10.1109/TIP.2024.3404257'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-05-30T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Image Processing
publication_short: TIP 2024

abstract: "Recent years have witnessed the incredible performance boost of data-driven deep visual object trackers. Despite the success, these trackers require millions of sequential manual labels on videos for supervised training, implying the heavy burden of human annotating. This raises a crucial question: how to train a powerful tracker from abundant videos using limited manual annotations? In this paper, we challenge the conventional belief that frame-by-frame labeling is indispensable, and show that providing a small number of annotated bounding boxes in each video is sufficient for training a strong tracker. To facilitate that, we design a novel SParsely-supervised Object Tracking (SPOT) framework. It regards the sparsely annotated boxes as anchors and progressively explores in the temporal span to discover unlabeled target snapshots. Under the teacher-student paradigm, SPOT leverages the unique transitive consistency inherent in the tracking task as supervision, extracting knowledge from both anchor snapshots and unlabeled target snapshots. We also utilize several effective training strategies, i.e., IoU filtering, asymmetric augmentation, and temporal calibration to further improve the training robustness of SPOT. The experimental results demonstrate that, given less than 5 labels for each video, trackers trained via SPOT perform on par with their fully-supervised counterparts. Moreover, our SPOT exhibits two desirable properties: 1) SPOT enables us to fully exploit large-scale video datasets by efficiently allocating sparse labels to more videos even under a limited labeling budget; 2) when equipped with a target discovery module, SPOT can even learn from purely unlabeled videos for performance gain. We hope this work could inspire the community to rethink the current annotation principles and make a step towards practical label-efficient deep tracking."

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
