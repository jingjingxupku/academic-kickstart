+++
title = "Transfer Deep Learning for Low-Resource Chinese Word Segmentation with a Novel Neural Network"
date = 2017-05-20

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Jingjing Xu**", "Shuming Ma", "Yi Zhang", "Bingzhen Wei", "Xiaoyan Cai",  "Xu Sun"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = ""
publication_short = ""

# Abstract.
abstract = ""

# Summary. An optional shortened abstract.
summary = "NLPCC 2017"

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
url_pdf = "https://arxiv.org/abs/1702.04488"
url_preprint = ""
url_code = "https://github.com/jingjingxupku/Low-Resource-CWS-"
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

Recent studies have shown effectiveness in using neural networks for Chinese word segmentation. However, these models rely on large-scale data and are less effective for low-resource datasets because of insufficient training data. We propose a transfer learning method to improve low-resource word segmentation by leveraging high-resource corpora. First, we train a teacher model on high-resource corpora and then use the learned knowledge to initialize a student model. Second, a weighted data similarity method is proposed to train the student model on low-resource data. Experiment results show that our work significantly improves the performance on low-resource datasets: 2.3% and 1.5% F-score on PKU and CTB datasets. Furthermore, this paper achieves state-of-the-art results: 96.1%, and 96.2% F-score on PKU and CTB datasets.