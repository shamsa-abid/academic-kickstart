---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Interpreting CodeBERT for Semantic Code Clone Detection"
authors: [Shamsa Abid; Xuemeng Cai; Lingxiao Jiang]
date: 2023-12-04T01:23:01+05:00
doi: "10.1109/IWSC55060.2022.00011"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-10-02T01:23:01+05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2023 30th Asia-Pacific Software Engineering Conference (APSEC)"
publication_short: ""

abstract: "Accurate detection of semantic code clones has many applications in software engineering but is challenging because of lexical, syntactic, or structural dissimilarities in code. CodeBERT, a popular deep neural network based pre-trained code model, can detect code clones with a high accuracy. However, its performance on unseen data is reported to be lower. A challenge is to interpret CodeBERT's clone detection behavior and isolate the causes of mispredictions. In this paper, we evaluate CodeBERT and interpret its clone detection behavior on the SemanticCloneBench dataset focusing on Java and Python clone pairs. We introduce the use of a black-box model interpretation technique, SHAP, to identify the core features of code that CodeBERT pays attention to for clone prediction. We first perform a manual similarity analysis over a sample of clone pairs to revise clone labels and to assign labels to statements indicating their contribution to core functionality. We then evaluate the correlation between the human and model's interpretation of core features of code as a measure of CodeBERT's trustworthiness. We observe only a weak correlation. Finally, we present examples on how to identify causes of mispredictions for CodeBERT. Our technique can help researchers to assess and fine-tune their models' performance."

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

url_pdf: "https://ieeexplore.ieee.org/abstract/document/10479370"
url_code: "https://github.com/Cxm211/CloneSHAPInterpreter"
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
  caption: "Explaining the predictions of the CodeBERT model for semantic code clone detection"
  focal_point: "Smart"
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
