+++
title = "Learning Sentiment Memories for Sentiment Modification without Parallel Data"
date = 2018-06-20

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Yi Zhang", "**Jingjing Xu**", "Pengcheng Yang", "Xu Sun"]

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
url_pdf = "https://arxiv.org/pdf/1808.07311.pdf"
url_preprint = ""
url_code = "https://github.com/lancopku/SMAE"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = "https://xusun.org/ppt_poster/zy_EMNLP2018.pdf"
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

The task of sentiment modification requires reversing the sentiment of the input and preserving the sentiment-independent content. However, aligned sentences with the same content
but different sentiments are usually unavailable. Due to the lack of such parallel data, it is
hard to extract sentiment independent content
and reverse the sentiment in an unsupervised
way. Previous work usually can not reconcile
sentiment transformation and content preservation. In this paper, motivated by the fact the
non-emotional context (e.g., “staff”) provides
strong cues for the occurrence of emotional
words (e.g., “friendly”), we propose a novel
method that automatically extracts appropriate
sentiment information from learned sentiment
memories according to specific context. Experiments show that our method substantially
improves the content preservation degree and
achieves the state-of-the-art performance.