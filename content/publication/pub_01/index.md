---
title: 'Channel Sampler in Hyperspectral Images for Vehicle Detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Geonsoo Lee
  - Jaekyu Lee
  - Jeonghyun Baek
  - Hoseong Kim
  - Donghyeon Cho

# Author notes (optional)
author_notes:
  - '1st Author'
#   - 'Equal Contribution'

date: '2021-10-01'
doi: '10.1109/LGRS.2021.3111907'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-10-01'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: IEEE Geoscience and Remote Sensing Letters
publication_short: IEEE Geoscience and Remote Sensing Letters(GRSS)

abstract: Since hyperspectral images (HSIs) contain visual information of multiple wavelengths, invisible signals to human eyes can also be detected. Therefore, it can be widely used for target object detection in bad weather and disaster environments. However, the channel dimension of the HSI is very large, and thus it is very inefficient to apply the existing object detector naively. In this letter, we present a lightweight convolutional neural network (CNN)-based channel sampler to estimate the importance score of each channel in the HSI. Based on the importance score of each channel, we can generate single-channel images that achieve the best object detection performance, as well as analyze the impact of the wavelength in the HSI on object detection performance. The proposed sampler is trained by a self-supervised adversarial learning method that recovers the original input HSI from the generated single-channel image. Therefore, our channel sampler can be seamlessly combined with any existing detectors. For experiments, we build a hyperspectral dataset for vehicle detection and then show the effectiveness of our method through various ablation studies.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Object Detection, Feature Enhancement, Self-Supervised Learning(SSL)]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'GRSS2021.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
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
