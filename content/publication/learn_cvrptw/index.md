---
title: 'Learning to Solve Soft-Constrained Vehicle Routing Problems with Lagrangian Relaxation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Qiaoyue Tang
  - Yangzhe Kong
  - Lemeng Pan
  - Choonmeng Lee

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2021-05-31T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-07-20T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Arxiv*
publication_short: In *Arxiv*

abstract: Vehicle Routing Problems (VRPs) in real-world applications often come with various constraints, therefore bring additional computational challenges to exact solution methods or heuristic search approaches. The recent idea to learn heuristic move patterns from sample data has become increasingly promising to reduce solution developing costs. However, using learning-based approaches to address more types of constrained VRP remains a challenge. The difficulty lies in controlling for constraint violations while searching for optimal solutions. To overcome this challenge, we propose a Reinforcement Learning based method to solve soft-constrained VRPs by incorporating the Lagrangian relaxation technique and using constrained policy optimization. We apply the method on three common types of VRPs, the Travelling Salesman Problem with Time Windows (TSPTW), the Capacitated VRP (CVRP) and the Capacitated VRP with Time Windows (CVRPTW), to show the generalizability of the proposed method. After comparing to existing RL-based methods and open-source heuristic solvers, we demonstrate its competitive performance in finding solutions with a good balance in travel distance, constraint violations and inference speed.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_code: 'https://github.com/Yanko96/Learning-to-Solve-Soft-Constrained-Vehicle-Routing-Problems-with-Lagrangian-Relaxation'
url_pdf: 'https://arxiv.org/pdf/2207.09860'
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
  - learn_cvrptw

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
