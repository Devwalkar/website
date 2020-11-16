---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Autonomous visual inspection for part defects"
summary: "Deep Learning based screw quality inspection using robotic arm"
authors: ["Devesh Walawalkar","Mayank Pathak","Andrey Shtylenko"]
tags: ["Computer Vision","Deep Learning","Robotics","Quality Inspection","Engineering"]
categories: []
date: 2020-03-10

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
url_pdf: ""
url_slides: ""
url_video: "media/Projects/Visual_Inspection/visual_inspection_demo_video.mp4"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

<div style="text-align: justify"> Manual Inspection of Industry machine parts for critical defects is a time consuming process requiring human expertise. This project aims to automate the complete process of defect inspection using Deep learning based computer vision classification models and a robotic arm. The project setup consists of a computer controlled robotic arm with a magnetic end effector, Nvidia Jetson Nano for edge AI capabilites and 2D cameras to detect and track the position of parts being inspected.  

Firstly, screw locations holding screws are located using 2D cameras and traditional Image Processing technqiues. Then the robotic arm picks up each screw from its location using its magnetic end effector. This selected screw is then held in an inspection booth where a high focus camera takes multiple images of the screw while it is being rotated by the arm. A Deep learning based computer vision model trained to locate defects on the screw is used to determine the particular screw quality. Depending on the inspection result, the screw is transferred from the booth to respective defective and non-defective place areas. 2D cameras above both these areas help in keeping track of which place locations are occupied and where the arm should place the respective defective/non-defective screw in. The project manages to acheive over 99.5% accuracy in screw quality inspection computed over a sample of 400 inspections. </div>  