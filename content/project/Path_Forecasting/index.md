---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Forecasting Path from Expert Demonstrations"
summary: "Research on path forecasting for self driving vehicle using CARLA simulator"
authors: ["Nikhil Mohan","Devesh Walawalkar"]
tags: ["Research","Computer Vision","Deep Reinforcement Learning","Self Driving Simulation"]
categories: []
date: 2019-05-01

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: "media/Projects/Path_Forecasting/Path_forecasting.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

<div style="text-align: justify"> Path Forecasting is an active research problem which has seen multiple different methods applied to it.  This project attempts to approach this problem using Deep Convolutional Neural networks and recurrent networks like LSTMs to predict probablefuture locations an entity could take. The project focuses its attention on stochastic path forecasting for an autonomous vehicle with the entire environment simulated through the comprehensive CARLA simulator. Training data is collected using this simulator for the purpose of sampling expert path locations. Models are trained jointly using our dataset on the publicly available KITTI odometry dataset. </div>