---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Innovate the Retail Industry with Automatic Checkout System"
summary: ""
authors: ["Xuanchi Ren","Zian Qian","Zhiwei Wang"]
tags: []
categories: []
date: 2020-03-23T23:38:11+01:00


# Optional external URL for project (replaces project detail page).
external_link: ""

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

*Automatic checkout system (ACO) has been gaining in- creasing interest in recent years due to its practical value. Different from traditional object detection and recognition problem, ACO is faced the problem of domain shifting. The model learns the pattern from single object images but pre- dicts on multi-object images which usually have totally dif- ferent distribution than the training images. Existing work tried to solve the problem by data augmentation. We further develop the data augmentation solution by using a more ef- ficient salient object detection algorithm and image inpaint- ing to improve the realism of synthesized images. We first remove the background by using salient object detection al- gorithm, and combine the objects together on a plain white background. After this, we use image inpainting to learn the image background from ground-truth images and use the model to improve the realism of synthesized images. We use the images to train a FPN detector and experiments on large scale Retail Product Checkout (RPC) dataset shows that we achieve 63.32% checkout accuracy, which is higher than the 56.68% baseline accuracy.*