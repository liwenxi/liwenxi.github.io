---
title: 'Gated Multi-modal Fusion with Cross-modal Contrastive Learning for Video Question Answering'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wenxi Li
  - Chenyang Lyu
  - Tianbo Ji
  - Liting Zhou
  - Cathal Gurrin

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Corresponding author'

date: '2023-06-20T00:00:00Z'
doi: 'https://doi.org/10.1007/978-3-031-44195-0_35'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-06-20T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *32nd International Conference on Artificial Neural Networks*
publication_short: In *ICANN 2023*

abstract: Video Question Answering (VideoQA) is a challenging task that requires the model to understand the complex nature of video data and the variety of questions that can be asked about them. Existing approaches often suffer from the problem of ambiguous answer candidates with low relevance to the visual and auditory part of the video, which limits the performance of VideoQA systems. In this paper, we introduce a novel approach that leverages multi-modal fusion and cross-modal contrastive learning to utilize multi-modal information and enhance the relevance of answer candidates in VideoQA. First, we introduce a gated multi-modal fusion network that learns to combine different modalities such as visual and speech based on their relevance to the question to enrich the representations of video and improve the accuracy of finding the correct answer. Second, we introduce cross-modal contrastive learning to increase the similarity between positive example pairs (i.e., correct answers and corresponding video clips) while decreasing the similarity between negative example pairs (i.e., incorrect answers and unpaired video clips). Specifically, we use three-way contrastive learning between answer and video frame, answer and audio, answer and cross-modal features. Our proposed approach is evaluated on two benchmark audio-aware VideoQA datasets, including AVQA and Music-AVQA, and compared to several state-of-the-art methods. The results show that our approach significantly improves the performance of VideoQA, achieving new state-of-the-art results on these benchmarks.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/chapter/10.1007/978-3-031-44195-0_35'
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
