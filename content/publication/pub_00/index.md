---
title: 'Self-supervised Feature Enhancement Networks for Small Object Detection in Noisy Images'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Geonsoo Lee
  - Sungeun Hong
  - Donghyeon Cho

# Author notes (optional)
author_notes:
  - 'Equal Contribution'
  - 'Equal Contribution'

date: '2021-05-17'
doi: '10.1109/LSP.2021.3081041'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-05-17'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: IEEE Signal Processing Letters
publication_short: IEEE Signal Processing Letters(SPL)

abstract: Recent CNN-based approaches have shown impressive improvements in object detection, but detecting small objects in images is still a challenging task. Small object detection becomes more difficult if the image contains a lot of noise, which is frequent in real environments. The main reason is that the ratio of visual signal to noise on small objects is very low, making it difficult to extract rich features for detection. To address this issue, we propose a feature enhancement network (FEN) that is trained in a self-supervised manner. Specifically, FEN takes features from input images whose values randomly were erased, then predicts the erased values by aggregating neighboring values. This scheme enables FEN to improve features using surrounding values, which have great effects on enriching features from small-object regions during the test phase. To verify the robustness of our method against small object detection from noisy images, we adopt vehicle detection in aerial images as the main target task. The proposed method consistently outperformed the baseline methods in our experiments. We further present a variety of empirical studies, quantitatively and qualitatively, for in-depth analysis.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Object Detection, Hyperspectral Imaging(HSI), Image Coding]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/9432743'
url_code: 'https://github.com/2gunsu/SPL2021-FEN'
url_dataset: ''
url_poster: ''
url_project: 'https://github.com/2gunsu/SPL2021-FEN'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
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
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->