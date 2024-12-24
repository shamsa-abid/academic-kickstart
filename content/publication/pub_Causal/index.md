---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Measuring model alignment for code clone detection using causal interpretation"
authors: [Shamsa Abid; Xuemeng Cai; Lingxiao Jiang]
date: 2024-12-19T01:23:01+05:00
doi: "https://doi.org/10.1007/s10664-024-10583-0"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-10-02T01:23:01+05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Empirical Software Engineering"
publication_short: "EMSE"

abstract: "Deep Neural Network-based models have demonstrated high accuracy for semantic code clone detection. However, the lack of generalization poses a threat to the trustworthiness and reliability of these models. Furthermore, the black-box nature of these models makes interpreting the model’s decisions very challenging. Currently, there is only a limited understanding of the semantic code clone detection behavior of existing models. There is a lack of transparency in understanding how a model identifies semantic code clones and the exact code components influencing its prediction. In this paper, we introduce the use of a causal interpretation framework based on the Neyman-Rubin causal model to gain insight into the decision-making of four state-of-the-art clone detection models. Using the causal interpretation framework, we derive causal explanations of models’ decisions by performing interventions guided by expert-labeled data. We measure the alignment of models’ decision-making with expert intuition by evaluating the causal effects of code similarities and differences on the clone predictions of the models. Additionally, we evaluate the similarity intuition alignment, robustness to confounding influences, and prediction consistency of the models. Finally, we rank the models in order of most aligned and thus most reliable to least aligned and thus least reliable for semantic code clone detection. Our contributions lay a foundation for building and evaluating trustworthy semantic code clone detection systems."

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

url_pdf: "https://link.springer.com/article/10.1007/s10664-024-10583-0"
url_code: "https://github.com/shamsa-abid/Code-Clone-Causal-Interpretation"
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
  caption: "Methodology for comparing human intuition with model intuition for semantic code clone detection"
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
