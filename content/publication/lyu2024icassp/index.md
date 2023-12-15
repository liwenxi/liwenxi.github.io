---
title: Semantic Enrichment for Video Question Answering with Gated Graph Neural Networks

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wenxi Li
  - Chenyang Lyu
  - Tianbo Ji
  - Yi Yu
  - Longyue Wang


# Author notes (optional)
# author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2024-04-14T00:00:00Z'
# doi: 'https://doi.org/10.1145/3581783.3612132'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-14T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2024 IEEE International Conference on Acoustics, Speech and Signal Processing*
publication_short: In *ICASSP 2024*

abstract: "Video Question Answering~(VideoQA) is a complex task that requires a deep understanding of a video to accurately answer questions. Existing methods often struggle to effectively integrate the visual and language-based semantic information, subsequently leading to an incomplete understanding of video content and sub-optimal performance. To address the challenge, we introduce a novel approach in this paper to enrich the semantics of video frames, questions, and answer candidates. Specifically, we parse video frames and questions into semantic graphs - visual semantic graph and question semantic graph, which captures information about objects, their attributes, and relationships. These graphs are then encoded using a Gated Graph Neural Network~(GGNN), For answer candidates, we propose to verbalize them using Large Language Models~(LLMs) to further inject more semantic information from visual and acoustic aspects. We evaluate our approach on benchmark VideoQA datasets: AVQA and Music-AVQA. Experimental results show that our approach outperforms competitive baseline models, achieving state-of-the-art performance on various question types."

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

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

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
