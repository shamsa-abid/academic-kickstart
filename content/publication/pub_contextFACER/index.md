---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Context-aware code recommendation in Intellij IDEA"
authors: [Shamsa Abid; Hamid Abdul Basit; Shafay Shamail]
date: 2022-11-07T01:23:01+05:00
doi: "10.1145/3540250.3558937"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-11-07T01:23:01+05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "30th ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering"
publication_short: ""

abstract: "Developers spend a lot of time online, searching for code to help them implement their desired features. While code recommenders help improve developers’ productivity, there is currently no support for context-aware code recommendation for opportunistic code reuse on-the-go. Typical code recommendation systems provide recommendations against a search query, whereas a code recommender that supports opportunistic reuse can recommend related code snippets that represent features that the developer may want to implement next. In this paper, we present a novel Context-aware Feature-driven API usage-based Code Recommender (CA-FACER) tool, which is an Intellij IDEA plugin that leverages a developer’s development context to recommend related code snippets. We consider the methods having API usages in a developer’s active project as part of the development context. Our approach uses contextual data from a developer’s active project to find similar projects and recommends code from popular features of those projects. The popular features are identified as frequently occurring API usage based Method Clone Classes. From our experimental evaluation on 120 Android Java projects from GitHub, we observe a 46% improvement of precision using our proposed context-aware approach over a baseline system. Our technique recommends related code examples with an average precision (P@5) of 94% and 83% and a success rate of 90% and 95% for initial and evolved development stages respectively. A video demonstration of our tool is available at https://youtu.be/UjuM8WRc318."

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

url_pdf: "https://ieeexplore.ieee.org/document/9609182"
url_code: ""
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: "https://youtu.be/UjuM8WRc318"

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
