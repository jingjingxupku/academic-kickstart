+++
title = "A Skeleton-Based Model for Promoting Coherence Among Sentences in Narrative Story Generation"
date = 2018-08-01

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Jingjing Xu**", "Yi Zhang", "Qi Zeng", "Xuancheng Ren", "Xiaoyan Cai", "Xu Sun"]

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
url_pdf = "https://arxiv.org/pdf/1808.06945.pdf"
url_preprint = ""
url_code = "https://github.com/lancopku/Skeleton-Based-Generation-Model"
url_dataset = ""
url_project = ""
url_slides = "https://xusun.org/ppt_poster/xjj_EMNLP2018b.pdf"
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

Narrative story generation is a challenging
problem because it demands the generated
sentences with tight semantic connections,
which has not been well studied by most existing
generative models. To address this problem,
we propose a skeleton-based model to
promote the coherence of generated stories.
Different from traditional models that generate
a complete sentence at a stroke, the proposed
model first generates the most critical phrases,
called skeleton, and then expands the skeleton
to a complete and fluent sentence. The skeleton
is not manually defined, but learned by a
reinforcement learning method. Compared to
the state-of-the-art models, our skeleton-based
model can generate significantly more coherent
text according to human evaluation and automatic
evaluation. The G-score is improved
by 20.1% in human evaluation