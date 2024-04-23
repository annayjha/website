---
title: "Secure aerial surveillance using split learning"
authors:
- admin
- Minjae Yoo
- Soohyun Park
- Soyi Jung
- Joongheon Kim

# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-08-01"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *International Conference on Ubiquitous and Future Networks*"
publication_short: "In *ICUFN*"

abstract: Personal monitoring devices such as cyclist helmet cameras to record accidents or dash cams to catch collisions have proliferated, with more companies producing smaller and compact recording gadgets. As these devices are becoming a part of citizens' everyday arsenal, concerns over the residents' privacy are progressing. Therefore, this paper presents SASSL, a secure aerial surveillance drone using split learning to classify whether there is a presence of a fire on the streets. This innovative split learning method transfers CCTV footage captured with a drone to a nearby server to run a deep neural network to detect a fire's presence in real-time without exposing the original data. We devise a scenario where surveillance UAVs roam around the suburb, recording any unnatural behavior. The UAV can process the recordings through its on-mobile deep neural network system or transfer the information to a server. Due to resource limitations of mobile UAVs, the UAV does not have the capacity to run an entire deep neural network on its own. This is where the split learning method comes in handy. The UAV runs the deep neural network only up to the first hidden layer and sends only the feature map to the cloud server, where the rest of the deep neural network is processed. By ensuring that the learning process is divided between the UAV and the server, the privacy of raw data is secured while the UAV does not overexert its minimal resources.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
# - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9528601
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
# slides: example
---
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
