+++
title = "Cross-Domain and Semi-Supervised Named Entity Recognition in Chinese Social Media: A Unified Model"
date = 2018-06-20

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Jingjing Xu***", "Hangfeng He", "Xu Sun", "Xuancheng Ren", "Sujian Li"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = ""
publication_short = ""

# Abstract.
abstract = ""

# Summary. An optional shortened abstract.
summary = "TASLP 2018"

# Digital Object Identifier (DOI)
doi = ""

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = "https://ieeexplore.ieee.org/document/8411523"
url_preprint = ""
url_code = "https://github.com/lancopku/ChineseNER"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{name = "Custom Link", url = "http://example.org"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

Named entity recognition (NER) in Chinese social media is an important, but challenging task because Chinese social media language is informal and noisy. Most previous methods on NER focus on in-domain supervised learning, which is limited by scarce annotated data in social media. In this paper, we present that sufficient corpora in formal domains and massive unannotated text can be combined to improve the NER performance in social media. We propose a unified model which can learn from out-of-domain corpora and in-domain unannotated text. The unified model is composed of two parts. One is for cross-domain learning and the other is for semisupervised learning. Cross-domain learning can learn out-of-domain information based on domain similarity. Semisupervised learning can learn in-domain unannotated information by self-training. Experimental results show that our unified model yields a 9.57% improvement over strong baselines and achieves the state-of-the-art performance.