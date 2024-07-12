---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "An API Usage-based Code Recommendation Tool for Android Studio"
summary: "Android developers often need to search for example code to complete their development tasks. While existing code search systems for Android can deliver code against a search query, they do not recommend code for features that a developer might later need to implement. We present FACER-AS (FACER for Android Studio); an Android Studio plugin provides relevant code against natural language queries (Stage 1) and also recommends code of multiple related features (Stage 2) to facilitate opportunistic code reuse. The FACER-AS tool uses FACER (Feature-driven API usage-based Code Examples Recommender) as its back-end code search and recommendation engine. FACER first constructs a code fact repository by parsing the source code of open-source Java projects to obtain methods' textual information, call graphs, and Application Programming Interface (API) usages. It then detects unique features by clustering methods based on similar API usages, where each cluster represents a feature or functionality. Finally, it detects frequently co-occurring features across projects using frequent pattern mining and recommends related methods from the mined patterns. To evaluate FACER-AS, we perform a user study involving one professional Android developer who uses our tool for the development of their ongoing live Android projects. We analyze the developer's usage of our tool over a span of seven days and find that FACER-AS achieves a 79% success rate for retrieving code against user queries (Stage 1) and a 41% success rate for recommending code for related features (Stage 2). We also observe a 43% reuse rate of Stage 1 recommendations and a 45% reuse rate of Stage 2 recommendations. Our tool's performance analysis and the developer's positive feedback show that FACER-AS can help Android developers with their coding activities." 
authors: [Shamsa Abid]
tags: []
categories: [LUMS]
date: 2021-09-03T00:11:28+05:00

# Optional external URL for project (replaces project detail page).
external_link: "https://sbasse.lums.edu.pk/node/9908"

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
