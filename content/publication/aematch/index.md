+++
title = "An Auto-Encoder Matching Model for Learning Utterance-Level Semantic Dependency in Dialogue Generation"
date = 2018-07-21

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Liangchen Luo*", "**Jingjing Xu***", "Junyang Lin", "Qi Zeng", "Xu Sun"]

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
summary = "EMNLP 2018"

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
url_pdf = "https://arxiv.org/pdf/1808.08795.pdf"
url_preprint = ""
url_code = "https://github.com/lancopku/AMM"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = "https://xusun.org/ppt_poster/llc_EMNLP2018.pdf"
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

Generating semantically coherent responses is
still a major challenge in dialogue generation. Different from conventional text generation tasks, the mapping between inputs and
responses in conversations is more complicated, which highly demands the understanding of utterance-level semantic dependency, a
relation between the whole meanings of inputs and outputs. To address this problem, we
propose an Auto-Encoder Matching (AEM)
model to learn such dependency. The model
contains two auto-encoders and one mapping
module. The auto-encoders learn the semantic representations of inputs and responses,
and the mapping module learns to connect the
utterance-level representations. Experimental
results from automatic and human evaluations
demonstrate that our model is capable of generating responses of high coherence and fluency compared to baseline models.