---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "MedAL: Accurate and Robust Deep Active Learning for Medical Image Analysis"
authors: ["Asim Smailagic", "Pedro Costa", "Hae Young Noh", "Devesh Walawalkar", "Kartik Khandelwal", "Adrian Galdran", "Mostafa Mirshekari", "Jonathon Fagert", "Susu Xu", "Pei Zhang", "Aurélio Campilho"]
date: 2018-12-20
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2018-12-20

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "17th IEEE International Conference on Machine Learning and Applications 2020"
publication_short: "ICMLA-2018"

abstract: "Deep learning models have been successfully used in medical image analysis problems but they require a large amount of labeled images to obtain good performance. However, such large labeled datasets are costly to acquire. Active learning techniques can be used to minimize the number of required training labels while maximizing the model's performance. In this work, we propose a novel sampling method that queries the unlabeled examples that maximize the average distance to all training set examples in a learned feature space. We then extend our sampling method to define a better initial training set, without the need for a trained model, by using Oriented FAST and Rotated BRIEF (ORB) feature descriptors. We validate MedAL on 3 medical image datasets and show that our method is robust to different dataset properties. MedAL is also efficient, achieving 80% accuracy on the task of Diabetic Retinopathy detection using only 425 labeled images, corresponding to a 32% reduction in the number of required labeled examples compared to the standard uncertainty sampling technique, and a 40% reduction compared to random sampling."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Medical Image Analysis","Deep Learning","Image classification"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://arxiv.org/pdf/1809.09287.pdf"
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source: "https://ieeexplore.ieee.org/document/8614103"
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Overview-of-framework"
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
