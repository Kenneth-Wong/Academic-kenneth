+++
title = "Importance First: Generating Scene Graph of Human Interest"
date = 2023-07-22T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Wenbin Wang", "Ruiping Wang","Shiguang Shan", "Xilin Chen"]
# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Preprint / Working Paper
# 4 = Report
# 5 = Book
# 6 = Book section 
# 7 = Thesis
# 8 = Patent
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In [*International Journal of Computer Vision*](https://www.springer.com/journal/11263)"
publication_short = "In *IJCV*"

# Abstract.
abstract = "Scene graph aims to faithfully reveal humans’ perception of image content. When humans look at a scene, they usually focus on their interested parts in a special priority. This innate habit indicates a hierarchical preference about human perception. Therefore, we argue to generate the Scene Graph of Interest which should be hierarchically constructed, so that the important primary content is firstly presented while the secondary one is presented on demand. To achieve this goal, we propose the Tree–Guided Importance Ranking (TGIR) model. We represent the scene with a hierarchical structure by firstly detecting objects in the scene and organizing them into a Hierarchical Entity Tree (HET) according to their spatial scale, considering that larger objects are more likely to be noticed instantly. After that, the scene graph is generated guided by structural information of HET which is modeled by the elaborately designed Hierarchical Contextual Propagation (HCP) module. To further highlight the key relationship in the scene graph, all relationships are re-ranked through additionally estimating their importance by the Relationship Ranking Module (RRM). To train RRM, the most direct way is to collect the key relationship annotation, which is the so-called Direct Supervision scheme. As collecting annotation may be cumbersome, we further utilize two intuitive and effective cues, visual saliency and spatial scale, and treat them as Approximate Supervision, according to the findings that these cues are positively correlated with relationship importance. With these readily available cues, the RRM is still able to estimate the importance even without key relationship annotation. Experiments indicate that our method not only achieves state-of-the-art performances on scene graph generation, but also is expert in mining image-specific relationships which play a great role in serving subsequent tasks such as image captioning and cross-modal retrieval."

# Summary. An optional shortened abstract.
summary = "Scene graph aims to faithfully reveal humans’ perception of image content. When humans look at a scene, they usually focus on their interested parts in a special priority. This innate habit indicates a hierarchical preference about human perception. Therefore, we argue to generate the Scene Graph of Interest which should be hierarchically constructed, so that the important primary content is firstly presented while the secondary one is presented on demand. To achieve this goal, we propose the Tree–Guided Importance Ranking (TGIR) model. We represent the scene with a hierarchical structure by firstly detecting objects in the scene and organizing them into a Hierarchical Entity Tree (HET) according to their spatial scale, considering that larger objects are more likely to be noticed instantly."

# Digital Object Identifier (DOI)
doi = "10.1007/s11263-023-01817-7"

# Is this a featured publication? (true/false)
featured = true  

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = "https://link.springer.com/article/10.1007/s11263-023-01817-7#citeas"
#"https://trebuchet.public.springernature.app/get_content/7692a942-a71d-43b3-91f0-e0910d57db01" # private
url_code = "https://github.com/Kenneth-Wong/TGIR"
#url_dataset = ""
#url_project = ""
#url_slides = ""
#url_video = ""
#url_poster = "#"
#url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#links = [{name = "Custom Link", url = "http://example.org"}]
links = [
#{name = "arXiv", url = ""},
#{name="IEEE Xplore", url = ""},
#{name="预印版", url = #"https://www.sciengine.com/SSI/doi/10.1360/SSI-2022-0105"}
]


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional) 
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++

