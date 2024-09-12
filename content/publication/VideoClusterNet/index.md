---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "VideoClusterNet: Self-Supervised and Adaptive Face Clustering for Videos"
authors: ["Devesh Walawalkar","Pablo Garrido"]
date: 2024-08-05
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-08-05

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "18th European Conference on Computer Vision (ECCV) 2024"
publication_short: "ECCV-2024"

abstract: "With the rise of digital media content production, the need for analyzing movies and TV series episodes to locate the main cast of characters precisely is gaining importance.Specifically, Video Face Clustering aims to group together detected video face tracks with common facial identities. This problem is very challenging due to the large range of pose, expression, appearance, and lighting variations of a given face across video frames. Generic pre-trained Face Identification (ID) models fail to adapt well to the video production domain, given its high dynamic range content and also unique cinematic style. Furthermore, traditional clustering algorithms depend on hyperparameters requiring individual tuning across datasets. In this paper, we present a novel video face clustering approach that learns to adapt a generic face ID model to new video face tracks in a fully self-supervised fashion. We also propose a parameter-free clustering algorithm that is capable of automatically adapting to the finetuned model's embedding space for any input video. Due to the lack of comprehensive movie face clustering benchmarks, we also present a first-of-kind movie dataset: MovieFaceCluster. Our dataset is handpicked by film industry professionals and contains extremely challenging face ID scenarios. Experiments show our method's effectiveness in handling difficult mainstream movie scenes on our benchmark dataset and state-of-the-art performance on traditional TV series datasets."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Computer Vision", "Self-Supervised Learning","Video Face Clustering","Representation Learning"]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Citation
  url: "media/Publications/videoclusternet/citation.txt"
  icon_pack:
  icon:

url_pdf: "https://arxiv.org/abs/2407.12214"
url_code: 
url_dataset: "https://www.flawlessai.com/dataset/"
url_poster: "media/Publications/videoclusternet/poster_videoclusternet.pdf"
url_source: 
url_slides: "media/Publications/videoclusternet/videoclusternet_slides.pdf"
url_video: "media/Publications/videoclusternet/presentation_videoclusternet.mp4"
url_citation: 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image: 
  caption: "Overview-of-framework"
  focal_point: "TopLeft"
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

## 
---
