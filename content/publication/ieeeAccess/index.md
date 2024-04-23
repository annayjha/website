---
title: 'Spatio-Temporal Split Learning for Privacy-Preserving Medical Platforms: Case Studies With COVID-19 CT, X-Ray, and Cholesterol Data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Minjae Yoo
  - Gusang Lee
  - Soyi Jung
  - Sae Won Choi
  - Joongheon Kim 
  - Seehwan Yoo
date: "2021-08-27"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Access, vol. 9*"
publication_short: ""

abstract: Machine learning requires a large volume of sample data, especially when it is used in high-accuracy medical applications. However, patient records are one of the most sensitive private information that is not usually shared among institutes. This paper presents spatio-temporal split learning, a distributed deep neural network framework, which is a turning point in allowing collaboration among privacy-sensitive organizations. Our spatio-temporal split learning presents how distributed machine learning can be efficiently conducted with minimal privacy concerns. The proposed split learning consists of a number of clients and a centralized server. Each client has only has one hidden layer, which acts as the privacy-preserving layer, and the centralized server comprises the other hidden layers and the output layer. Since the centralized server does not need to access the training data and trains the deep neural network with parameters received from the privacy-preserving layer, privacy of original data is guaranteed. We have coined the term, spatio-temporal split learning, as multiple clients are spatially distributed to cover diverse datasets from different participants, and we can temporally split the learning process, detaching the privacy preserving layer from the rest of the learning process to minimize privacy breaches. This paper shows how we can analyze the medical data whilst ensuring privacy using our proposed multi-site spatio-temporal split learning algorithm on Coronavirus Disease-19 (COVID-19) chest Computed Tomography (CT) scans, MUsculoskeletal RAdiographs (MURA) X-ray images, and cholesterol levels.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
# - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9524632'
# https://www.nature.com/articles/s41598-022-05615-y.pdf?pdf=button%20sticky
url_code: 'https://github.com/annayjha/'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Anna Yoo Jeong Ha**](https://annaha.net)'
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
