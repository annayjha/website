---
title: 'Identifying Provenance of Generative Text-to-Image Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Wenxin Ding
  - Stanley Wu
  - Shawn Shan
  - Haitao Zheng
  - Ben Y Zhao
date: "2025-12-04"
doi: ""


# Schedule page publish date (NOT publication's date).
publishDate: "2024-04-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of USENIX Security Symposium (USENIX Security 26)*"
# award: "Distinguished Paper Award at CCS 2024"
publication_short: ""

abstract: Fine-tuning provides a fast and cheap way to produce new text-to-image models that are often indistinguishable from ones trained from scratch. Unfortunately, misrepresentation of fine-tuned models creates problems for AI companies and users alike, by disincentivizing competition and misleading users on model quality and ethics of its training process. In this paper, we propose a model provenance system that identifies models produced by fine-tuning on existing text-to-image models, using only black-box query access. Our design is informed by analysis showing that one can quantify the feature space difference between text-to-image models by analyzing their responses to detailed prompts. Our system analyzes model output, extracts visual features using a generic feature extractor, and compares their distributions against those from a reference pool of base models using Jensen-Shannon divergence. Applying statistical hypothesis testing then determines if a target model is trained from scratch or fine-tuned, and if the latter, the likely base (parent) model. We evaluate our system across seven widely used diffusion models and numerous fine-tuned variants. Our results show high accuracy in attributing model lineage, even under adversarial conditions such as image post-processing or weight perturbations. Finally, we demonstrate real world efficacy of our system by tracing provenance of in-the-wild models from popular online platforms.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
# - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
# url_pdf: '/publication/detectai/detectai_v1.pdf'
# https://www.nature.com/articles/s41598-022-05615-y.pdf?pdf=button%20sticky
# url_code: 'https://github.com/annayjha/'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Anna Yoo Jeong Ha**](https://annaha.net)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
