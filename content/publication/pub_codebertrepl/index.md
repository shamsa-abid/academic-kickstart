---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "CodeBERT for Code Clone Detection: A Replication Study"
authors: [Saad Arshad; Shamsa Abid; Shafay Shamail]
date: 2022-12-14T01:23:01+05:00
doi: "10.1109/IWSC55060.2022.00015"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-12-14T01:23:01+05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2022 IEEE 16th International Workshop on Software Clones (IWSC)"
publication_short: ""

abstract: "Large pre-trained models have dramatically improved the state-of-the-art on a variety of natural language processing (NLP) tasks. CodeBERT is one such pre-trained model for natural language (NL) and programming language (PL) which captures the semantics in natural language and programming language, and produces general-purpose representations. While it has been shown to support natural language code search and code documentation generation tasks, its effectiveness for code clone detection is not explored in depth. In this paper, we aim to replicate and evaluate the performance of CodeBERT for code clone detection on multiple datasets with varying functionalities to understand (1) whether CodeBERT can generalize to unseen code, (2) how fine-tuning can effect CodeBERT’s performance on unseen code, and (3) how CodeBERT performs for detecting various code clone types. To this end, we consider three different datasets of Java methods. We derive the first dataset from Big-CloneBench. We use Java clone pairs from SemanticCloneBench to derive our second dataset, and our third dataset consists of Java methods from Android applications. Our experiments indicate that CodeBERT performs the best for detecting Type-1 and Type-4 clones with a 100% and 96% recall on average respectively. We also find that there is limited generalizability on unseen functionalities where recall drops by 15% and 40% on the SemanticCloneBench and Android datasets respectively. Furthermore, we observe that fine-tuning can improve the recall by 22% and 30% on the SemanticCloneBench and Android datasets respectively."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://ieeexplore.ieee.org/abstract/document/9978260"
url_code: "https://zenodo.org/record/6361315"
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
  caption: ""
  focal_point: ""
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
