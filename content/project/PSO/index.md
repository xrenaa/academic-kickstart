---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "On the Performance Benefits of Zeroth Order Methods in the Context of Adversarial Training"
summary: ""
authors: ["XAlice Biryukov","Nicolas Dutly","Xuanchi Ren"]
tags: []
categories: []
date: 2020-03-23T23:38:11+01:00


# Optional external URL for project (replaces project detail page).
external_link: "https://github.com/Jumpst3r/Opt_ML_project"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Benchmark our batch particle swarm optimization (PSO) algorithm in the context of adversarial attacks / adversarial training, comparing it with to a set of reference whitebox attacks.

**The main question:** Whether zeroth order optimization (such as PSO) methods bring any benefits in terms of speed or GPU memory consuption in the context of adverserial training / attacks as they do not rely on computational graphs and gradients like many classical whitebox attacks do.

**Why do we care:** adverserial attacks can be used in a benign way to augment existing datasets with new adverserial data. In this context speed and GPU memory consumption are relevant factors which can have a large impact on practical limitations and adversarial image generation rates.