---
title: 'Bridging the gap between object detection in close-up and high-resolution wide shots'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wenxi Li
  - Yuchen Guo
  - Jilai Zheng
  - Haozhe Lin
  - Chao Ma
  - Lu Fang
  - Xiaokang Yang

# Author notes (optional)
# author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2024-09-05T00:00:00Z'
# doi: 'https://doi.org/10.1145/3664647.3681043'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-09-05T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In "Computer Vision and Image Understanding"
publication_short: In *CVIU*

abstract: "Recent years have seen a significant rise in gigapixel-level image/video capture systems and benchmarks with high-resolution wide (HRW) shots. Different from close-up shots like MS COCO, the higher resolution and wider field of view raise new research and application problems, such as how to perform accurate and efficient object detection with such large input in low-power edge devices like UAVs. There are several unique challenges in HRW shots. (1) Sparse information: the objects of interest cover less area. (2) Various scale: there is 10 to 100$\times$ object scale change in one single image. (3) Incomplete objects: the sliding window strategy to handle the large input leads to truncated objects at the window edge. (4) Multi-scale information: it is unclear how to use multi-scale information in training and inference. Consequently, directly using a close-up detector leads to inaccuracy and inefficiency. In this paper, we systematically investigate this problem and bridge the gap between object detection in close-up and HRW shots, by introducing a novel sparse architecture that can be integrated with common networks like ConvNet and Transformer. It leverages alternative sparse learning to complementarily fuse coarse-grained and fine-grained features to (1) adaptively extract valuable information from (2) different object scales. We also propose a novel Cross-window Non-Maximum Suppression (C-NMS) algorithm to (3) improve the box merge from different windows. Furthermore, we propose a (4) simple yet effective multi-scale training and inference strategy to improve accuracy. Experiments on two benchmarks with HRW shots, PANDA and DOTA-v1.0, demonstrate that our methods significantly improve accuracy (up to 5.8%) and speed (up to 3$\times$) over SotAs, for both ConvNet or Transformer based detectors, on edge devices. Our code is open-sourced and available at https://github.com/liwenxi/SparseFormer. "

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: no

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
