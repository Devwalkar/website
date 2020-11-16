---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Real Time Object Detection on Jetson Xavier"
summary: "Research on compressing state-of-the-art algorithms for edge AI applications"
authors: ["Devesh Walawalkar"]
tags: ["Research","Object Detection","DL Model Compression","Real-Time Inference"]
categories: []
date: 2019-12-01

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Real time inference demonstration for object detection on Nvidia Xavier"
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
url_pdf: ""
url_slides: ""
url_video: "media/Projects/JIDO_detection/JIDO_demo.mp4"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

<div style="text-align: justify"> This project focuses on developing a real-time edge processing object detection framework that contains two main components: (a) object detector trained on objects at various scales, and (b) various model compression techniques for fast processing platform deployment.

Today, object detection algorithms have achieved real-time detection speed and accuracy primarily due to the use of Single shot multibox detector and deep learning models. However, the heavy computation load of these deep neural networks makes them ideal only for GPU specific processing. This project aims at applying various state-of-the-art research techniques to refine the original deep learning model(s), including: model compression (e.g. prune and fine-tune), model re-training, improved inferencing (i.e. weight quantization) and network slimming. This is carried out in a way which preserves model accuracy, while generating a smart optimization to increase the speed that fits real-time low power, easily deployable, mini-form factor edge processing platforms. 

The goal is to drastically reduce the size of the neural network models, yet achieve comparable accuracy to their uncompressed counterparts. The objective is to use these smaller models to achieve real-time detection speed on smaller processor units designed for use at the edge. This project demonstrate a completed prototype deployed on a miniature low-power neural processing unit (i.e., Nvidia Jetson Xavier). Potential applications include: Processing on the edge device and only sending relevant information to the user/processing station for exploitation. For example, a UAS used by the military to locate enemy bunkers, vehicles, missile launchers, etc., and drones in order to inspect important areas for suspicious activities/alerting can quickly communicate only relevant information. Ultimately deploying, embedding and linking edge processors with optimized deep neural networks will allow a tremendous advantage to various edge node sensor capabilities. </div>
