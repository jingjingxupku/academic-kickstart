+++
title = "Pkuseg Toolkit"
date = 2019-02-25T11:04:02+08:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = []

# Project summary to display on homepage.
summary = """We designed a multi-domain Chinese word segmentation toolkit, called pkuseg, supporting domains like news, web, medicine, and tourism. This work has got **3K stars** on github until now."""

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Optional external URL for project (replaces project detail page).
external_link = ""

# Links (optional).
url_pdf = ""
url_code = ""
url_dataset = ""
url_slides = ""
url_video = ""
url_poster = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++



A multi-domain Chinese word segmentation toolkit. [link](https://github.com/lancopku/pkuseg-python)

## Highlights

The pkuseg-python toolkit has the following features:

1.	Supporting multi-domain Chinese word segmentation. Pkuseg-python supports multi-domain segmentation, including domains like news, web, medicine, and tourism. Users are free to choose different pre-trained models according to the domain features of the text to be segmented. If not sure the domain of the text, users are recommended to use the default model trained on mixed-domain data.

2.	Higher word segmentation results. Compared with existing word segmentation toolkits, pkuseg-python can achieve higher F1 scores on the same dataset.

3.	Supporting model training. Pkuseg-python  also supports users to train a new segmentation model with their own data.

4.	Supporting POS tagging. We also provide users POS tagging interfaces for further lexical analysis. 

## Authors

Ruixuan Luo,  Jingjing Xu, Xuancheng Ren, Yi Zhang, Bingzhen Wei，Xu Sun