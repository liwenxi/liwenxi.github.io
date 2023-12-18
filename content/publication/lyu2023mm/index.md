---
title: 'Graph-Based Video-Language Learning with Multi-Grained Audio-Visual Alignment'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wenxi Li
  - Chenyang Lyu
  - Tianbo Ji
  - Longyue Wang
  - Liting Zhou
  - Cathal Gurrin
  - Linyi Yang
  - Yi Yu
  - Yvette Graham
  - Jennifer Foster

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Corresponding author'

date: '2023-07-20T00:00:00Z'
doi: 'https://doi.org/10.1145/3581783.3612132'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-07-20T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *31st ACM International Conference on Multimedia*
publication_short: In *ACM MM 2023*

abstract: Video-language learning has attracted significant attention in the fields of multimedia, computer vision and natural language processing in recent years. One of the key challenges in this area is how to effectively integrate visual and linguistic information to enable machines to understand video content and query information. In this work, we leverage graph-based representations and multi-grained audio-visual alignment to address this challenge. First, our approach starts by transforming video and query inputs into visual-scene graphs and semantic role graphs using a visual-scene parser and semantic role labeler respectively. These graphs are then encoded using graph neural networks to obtain enriched representations and combined to obtain a video-query joint representation that enhances the semantic expressivity of the inputs. Second, to achieve accurate matching of relevant parts of audio and visual features, we propose a multi-grained alignment module that aligns the audio and visual features at multiple scales. This enables us to effectively fuse the audio and visual information in a way that is consistent with the semantic-level information captured by the graph-based representations. Experiments on five representative datasets collected for Video Retrieval and Video Question Answering tasks show that our approach outperforms the literature on several metrics. Our extensive ablation studies demonstrate the effectiveness of graph-based representation and multi-grained audio-visual alignment.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3581783.3612132'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

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
