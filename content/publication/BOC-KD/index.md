---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Online Ensemble Model Compression using Knowledge Distillation"
authors: ["Devesh Walawalkar","Zhiqiang Shen","Marios Savvides"]
date: 2020-08-31
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-01

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "16th European Conference on Computer Vision (ECCV) 2020"
publication_short: "ECCV-2020"

abstract: "This paper presents a novel knowledge distillation based model compression framework consisting of a student ensemble. It enables distillation of simultaneously learnt ensemble knowledge onto each of the compressed student models. Each model learns unique representations from the data distribution due to its distinct architecture. This helps the ensemble generalize better by combining every model’s knowledge. The distilled students and ensemble teacher are trained simultaneously without requiring any pretrained weights. Moreover, our proposed method can deliver multi-compressed students with single training, which is efficient and flexible for different scenarios. We provide comprehensive experiments using state-of-the-art classification models to validate our framework’s effectiveness. Notably, using our framework a 97% compressed ResNet110 student model managed to produce a 10.64% relative accuracy gain over its individual baseline training on CIFAR100 dataset. Similarly a 95% compressed DenseNet-BC (k=12) model managed a 8.17% relative accuracy gain."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Computer Vision","Knowledge Distillation","Model Compression","Image Classification"]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Citation
  url: "media/Publications/BOC_KD/citation.txt"
  icon_pack:
  icon:

url_pdf: "https://arxiv.org/pdf/2011.07449.pdf"
url_code: "https://github.com/Devwalkar/BOC-KD"
url_dataset:
url_poster:
url_source: "https://link.springer.com/chapter/10.1007/978-3-030-58529-7_2"
url_slides: "media/Publications/BOC_KD/BOC_KD_ECCV2020.pdf"
url_video: "media/Publications/BOC_KD/BOC_KD_ECCV2020.mp4"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image: 
  caption: "Overview-of-model-compression-framework"
  focal_point: "Left"
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
