+++
title = "Unpaired Sentiment-to-Sentiment Translation: A Cycled Reinforcement Learning Approach"
date = 2018-07-20

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Jingjing Xu***", "Xu Sun*","Qi Zeng", "Xiaodong Zhang", "Xuancheng Ren", "Houfeng Wang", "Wenjie Li"]

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
url_pdf = "https://arxiv.org/pdf/1805.05181.pdf"
url_preprint = ""
url_code = "https://github.com/lancopku/unpaired-sentiment-translation"
url_dataset = ""
url_project = ""
url_slides = "https://xusun.org/ppt_poster/xjj_ACL2018.pdf"
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

The goal of sentiment-to-sentiment “translation” is to change the underlying sentiment of a sentence while keeping its content. The main challenge is the lack of
parallel data. To solve this problem, we
propose a cycled reinforcement learning
method that enables training on unpaired
data by collaboration between a neutralization module and an emotionalization
module. We evaluate our approach on two
review datasets, Yelp and Amazon. Experimental results show that our approach significantly outperforms the state-of-the-art
systems. Especially, the proposed method
substantially improves the content preservation performance. The BLEU score is
improved from 1.64 to 22.46 and from
0.56 to 14.06 on the two datasets, respectively.