---
# Documentation: https://docs.hugoblox.com/managing-content/

title: "On the Feasibility of Poisoning Text-to-Image AI Models via Adversarial Mislabeling"
authors: [Stanley Wu, Ronik Bhaskar, admin, Shawn Shan, Haitao Zheng, Ben Y Zhao]
date: 2025-05-11T20:24:55-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2025-05-11T20:24:55-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of ACM Conference on Computer and Communications Security (CCS)*"
publication_short: ""

abstract: "Today’s text-to-image generative models are trained on millions of images sourced from the Internet, each paired with a detailed caption produced by Vision-Language Models (VLMs). This part of the training pipeline is critical for supplying the models with large volumes of high-quality image-caption pairs during training. However, recent work suggests that VLMs are vulnerable to stealthy adversarial attacks, where adversarial perturbations are added to images to mislead the VLMs into producing incorrect captions. In this paper, we explore the feasibility of adversarial mislabeling attacks on VLMs as a mechanism to poisoning training pipelines for text-to-image models. Our experiments demonstrate that VLMs are highly vulnerable to adversarial perturbations, allowing attackers to produce benign-looking images that are consistently miscaptioned by the VLM models. This has the effect of injecting strong “dirty-label” poison samples into the training pipeline for text-to-image models, successfully altering their behavior with a small number of poisoned samples. We find that while potential defenses can be effective, they can be targeted and circumvented by adaptive attackers. This suggests a cat-and-mouse game that is likely to reduce the quality of training data and increase the cost of text-to-image model development. Finally, we demonstrate the real-world effectiveness of these attacks, achieving high attack success (over 73%) even in black-box scenarios against commercial VLMs (Google Vertex AI and Microsoft Azure)."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: '/publication/hemlock-new/hemlock_arxiv.pdf'
url_code: https://github.com/stanleykywu/amp
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
