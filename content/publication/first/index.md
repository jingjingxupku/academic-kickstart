+++
title = "Dependency-based Gated Recursive Neural Network for Chinese Word Segmentation"
date = 2016-04-20

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Jingjing Xu**", "Xu Sun"]

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
summary = "ACL 2016"

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
url_pdf = "https://www.aclweb.org/anthology/P16-2092"
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
Recently, many neural network models
have been applied to Chinese word segmentation. However, such models focus
more on collecting local information while
long distance dependencies are not well
learned. To integrate local features with
long distance dependencies, we propose a
dependency-based gated recursive neural
network. Local features are first collected by bi-directional long short term memory network, then combined and refined to
long distance dependencies via gated recursive neural network. Experimental results show that our model is a competitive
model for Chinese word segmentation.