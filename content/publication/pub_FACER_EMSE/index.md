---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "FACER: An API Usage-based Code-example Recommender for Opportunistic Reuse"
authors: [Shamsa Abid, Shafay Shamail, Hamid Abdul Basit, Sarah Nadi]
date: 2021-08-17
doi: "10.1007/s10664-021-10000-w"

# Schedule page publish date (NOT publication's date).
# publishDate: 2019-11-29T15:38:16+05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Empirical Software Engineering"
publication_short: ""

abstract: "To save time, developers often search for code examples that implement their desired software features. Existing code search techniques typically focus on finding code snippets for a single given query, which means that developers need to perform a separate search for each desired functionality. In this paper, we propose FACER (Feature-driven API usage-based Code Examples Recommender, a technique that avoids repeated searches through opportunistic reuse. Specifically, given the selected code snippet that matches the initial search query, FACER finds and suggests related code snippets that represent features that the developer may want to implement next. FACER first constructs a code fact repository by parsing the source code of open-source Java projects to obtain methods' textual information, call graphs, and Application Programming Interface (API) usages. It then detects unique features by clustering methods based on similar API usages, where each cluster represents a feature or functionality. Finally, it detects frequently co-occurring features across projects using frequent pattern mining and recommends related methods from the mined patterns. To evaluate FACER, we run it on 120 Java Android apps from GitHub. We first manually validate that the detected method clusters represent methods with similar functionality. We then perform an automated evaluation to determine the best parameters (e.g., similarity threshold) for FACER. We recruit 10 professional developers along with 39 experienced students to judge FACER's recommendation of related methods. Our results show that, on average, FACER's recommendations are 80% precise. We also survey a total of 20 professional Android and Java developers to understand their code search and reuse experiences, and also to obtain their feedback on the usability and usefulness of FACER. The survey results show that 95% of our surveyed professional developers find the idea of related method recommendations useful during code reuse."

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

url_pdf: https://doi.org/10.21203/rs.3.rs-260432/v1
url_code: https://github.com/shamsa-abid/FACER_Artifacts
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
