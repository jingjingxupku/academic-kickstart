+++
title = "DP-GAN: A Diversity-Promoting Generative Adversarial Network for Generating Informative and Diversified Text"
date = 2018-08-01

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Jingjing Xu**", "Xuancheng Ren", "Junyang Lin", "Xu Sun"]

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
url_pdf = "https://arxiv.org/abs/1802.01345"
url_preprint = ""
url_code = "https://github.com/lancopku/DPGAN"
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

Existing text generation methods tend to produce
repeated and "boring" expressions. To
tackle this problem, we propose a new text
generation model, called Diversity-Promoting
Generative Adversarial Network (DP-GAN).
The proposed model assigns low reward for
repeatedly generated text and high reward
for "novel" and fluent text, encouraging the
generator to produce diverse and informative
text. Moreover, we propose a novel language model
based discriminator, which can better
distinguish novel text from repeated text without
the saturation problem compared with existing
classifier-based discriminators. The experimental
results on review generation and dialogue
generation tasks demonstrate that our
model can generate substantially more diverse
and informative text than existing baselines.
