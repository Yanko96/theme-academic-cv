---
title: 'Path-Link Graph Neural Network for IP Network Performance Prediction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yangzhe Kong
  - Dmitry Petrov
  - Vilho Raisanen 
  - Alexander Ilin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2020-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-05-17T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2021 IFIP/IEEE International Symposium on Integrated Network Management*
publication_short: In *IM 2021*

abstract: Dynamic resource provisioning and quality assurance for the plethora of end-to-end slices running over 5G and B5G networks require advanced modeling capabilities. Graph Neural Networks (GNN) have already proven their efficiency for network performance prediction. GNN architecture matches well the structures usually met in communications networks. In this paper, the focus is on the IP transport network as one of the end-to-end 5G architecture domains. The recently published RouteNet GNN is taken as a reference and starting point for our study. RouteNet performance is verified by a new implementation in the PyTorch ML library. Next, an alternative Path-Link neural network (PLNet) architecture is proposed and evaluated. After hyper-parameter tuning for both models, the results show that PLNet and RouteNet achieve a similar accuracy level. The advantage of PLNet is in parallel architecture. It is demonstrated that its inference speed is not sensitive to the length of the network's paths.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_code: 'https://github.com/Yanko96/Path-Link-Graph-Nerural-Network-for-IP-Performance-Prediction'
url_pdf: 'https://dl.ifip.org/db/conf/im/im2021/211123.pdf'
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
projects:
  - plnet

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

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
