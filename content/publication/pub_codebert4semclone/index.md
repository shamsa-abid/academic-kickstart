---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Comparative Analysis of Clone Detection Techniques on SemanticCloneBench"
authors: [Sohaib Masood Rabbani; Nabeel Ahmad Gulzar; Saad Arshad; Shamsa Abid; Shafay Shamail]
date: 2022-10-02T01:23:01+05:00
doi: "10.1109/IWSC55060.2022.00011"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-10-02T01:23:01+05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2022 IEEE 16th International Workshop on Software Clones (IWSC)"
publication_short: ""

abstract: "Semantic code clone detection involves the detection of functionally similar code fragments which may otherwise be lexically, syntactically, or structurally dissimilar. The detection of semantic code clones has important applications in aspect mining and product line analysis. The accurate detection of semantic code clones is a challenging task and various techniques have been proposed. However, the evaluation of these techniques is performed using various datasets and we do not have a clear picture of the performance of these techniques relative to each other. Recently, SemanticCloneBench has been introduced as a benchmark for semantic clones. Now, we can use the SemanticCloneBench to effectively evaluate and compare the performance of semantic code clone detection techniques. In this paper, we compare the semantic code clone detection performance of three different code clone detection techniques namely FACER-CD, CodeBERT and NIL for Java code clones using SemanticCloneBench. FACER-CD performs API usage similarity-based clustering to detect clones, while CodeBERT is a deep-learning based approach which uses a pre-trained programming language model, and NIL is a token-based large-gapped code clones detector. FACER-CD, NIL, and CodeBERT show a recall of 64.3%, 12.7%, and 83.2% respectively on SemanticCloneBench. Using all three techniques together on the SemanticCloneBench dataset gives us an overall recall of 95.5% which is currently the best performance achieved on SemanticCloneBench."

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

url_pdf: "https://ieeexplore.ieee.org/abstract/document/9978250"
url_code: "https://github.com/sohaibrabbani/Comparative-Analysis-of-Clone-Detection-Techniques"
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
