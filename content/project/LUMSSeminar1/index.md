---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Comparing Clustering against Deep-Learning for Semantic Code Clone Detection"
summary: "Semantic code clone detection involves the detection of functionally similar code fragments which may otherwise be lexically, syntactically, or structurally dissimilar. The detection of semantic code clones has applications in aspect mining and product line analysis. Semantic code clones have recently been used by a code recommendation system called FACER to model commonly co-occurring functionality across multiple software projects for recommending related code. In this paper, we compare the semantic code clone detection performance of FACER's API usage similarity-based clustering approach (FACER-CD) against a deep-learning based approach which uses a pre-trained programming language model called CodeBERT. We perform our evaluation on two datasets; a benchmark dataset of Java code clones (BigCloneBench) and another dataset consisting of Java code from Android applications. Our experiments indicate that CodeBERT outperforms FACER-CD on the BigCloneBench dataset by a 33% higher accuracy. However, FACER-CD outperforms CodeBERT by a 31% higher accuracy on the Android dataset. We find that by training CodeBERT on the Android dataset, the difference of accuracy between FACER-CD and CodeBERT is minimized, with CodeBERT outperforming FACER-CD by a 6% higher accuracy and FACER-CD outperforming CodeBERT by a 1% higher precision. Furthermore, we observe that CodeBERT requires a significantly higher amount of time than FACER-CD to give results on the same dataset. Our results can help researchers choose between deep learning-based models and clustering-based approaches for clone detection depending on their performance requirements." 
authors: [Shamsa Abid]
tags: []
categories: [LUMS]
date: 2021-10-03T00:11:28+05:00

# Optional external URL for project (replaces project detail page).
external_link: "https://sbasse.lums.edu.pk/node/9942"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
# image:
#   caption: "Understanding Models' Decision Making"
#   focal_point: "Smart"
#   preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
#links:
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
