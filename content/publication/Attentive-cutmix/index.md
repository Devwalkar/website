---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Attentive CutMix: An Enhanced Data Augmentation Approach for Deep Learning Based Image Classification"
authors: ["Devesh Walawalkar", "Zhiqiang Shen", "Zechun Liu", "Marios Savvides"]
date: 2020-01-20
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-02

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "45th IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) 2020"
publication_short: "ICASSP-2020"

abstract: "Convolutional neural networks (CNN) are capable of learning robust representation with different regularization methods and activations as convolutional layers are spatially correlated. Based on this property, a large variety of regional dropout strategies have been proposed, such as Cutout, DropBlock, CutMix, etc. These methods aim to promote the network to generalize better by partially occluding the discriminative parts of objects. However, all of them perform this operation randomly, without capturing the most important region(s) within an object. In this paper, we propose Attentive CutMix, a naturally enhanced augmentation strategy based on CutMix. In each training iteration, we choose the most descriptive regions based on the intermediate attention maps from a feature extractor, which enables searching for the most discriminative parts in an image. Our proposed method is simple yet effective, easy to implement and can boost the baseline significantly. Extensive experiments on CIFAR-10/100, ImageNet datasets with various CNN architectures (in a unified setting) demonstrate the effectiveness of our proposed method, which consistently outperforms the baseline CutMix and other methods by a significant margin."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Computer Vision","Data Augmentation","Image Processing"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Citation
  url: "media/Publications/attentive_cutmix/citation.txt"
  icon_pack:
  icon:


url_pdf: https://arxiv.org/abs/2003.13048
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Overview-of-augmentation-technique"
  focal_point: "Right"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
