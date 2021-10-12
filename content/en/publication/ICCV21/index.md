+++
title = "Topic Scene Graph Generation by Attention Distillation from Caption"
date = 2021-07-23T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Wenbin Wang", "Ruiping Wang","Xilin Chen"]
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
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In [*Proceedings of the IEEE International Conference on Computer Vision (ICCV)*](http://iccv2021.thecvf.com/)"
publication_short = "In *ICCV 2021*"

# Abstract.
abstract = "If an image tells a story, the scene graph and image caption are the most popular narrators. Generally, a scene graph prefers to be an omniscient generalist, while the image caption is more willing to be a specialist, which outlines the gist. Lots of previous studies have found that as a generalist, a scene graph is not enough to serve for downstream advanced intelligent tasks unless it can reduce the trivial contents and noises. In this respect, the image caption is a good teacher. To this end, we let the scene graph borrow the ability from the image caption so that it can be a specialist on the basis of remaining all-round, resulting in the so-called **Topic Scene Graph**. What an image caption pays attention to is distilled and passed to the scene graph for estimating the importance of partial events (relationships). In addition, as this attention distillation process provides an opportunity for combining the generation of image caption and scene graph together, we further transform the scene graph into linguistic form by sharing a single generation model with image caption, making the scene graph with rich and free-form expressions. Experiments show that the attention distillation brings significant improvements on mining important relationships and demonstrate its potential for precise and controllable cross-modal retrieval."

# Summary. An optional shortened abstract.
summary = "If an image tells a story, the scene graph and image caption are the most popular narrators. Generally, a scene graph prefers to be an omniscient generalist, while the image caption is more willing to be a specialist, which outlines the gist. Lots of previous studies have found that as a generalist, a scene graph is not enough to serve for downstream advanced intelligent tasks unless it can reduce the trivial contents and noises. In this respect, the image caption is a good teacher. To this end, we let the scene graph borrow the ability from the image caption."

# Digital Object Identifier (DOI)
doi = ""

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

url_pdf = "https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Topic_Scene_Graph_Generation_by_Attention_Distillation_From_Caption_ICCV_2021_paper.pdf"
url_code = "https://github.com/Kenneth-Wong/MMSceneGraph"
#url_dataset = ""
#url_project = ""
#url_slides = ""
#url_video = ""
#url_poster = "#"
url_source = "https://openaccess.thecvf.com/content/ICCV2021/html/Wang_Topic_Scene_Graph_Generation_by_Attention_Distillation_From_Caption_ICCV_2021_paper.html"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#links = [{name = "Custom Link", url = "http://example.org"}]
links = [
#{name = "arXiv", url = ""},
#{name="IEEE Xplore", url = ""},
{name="supp", url = "https://openaccess.thecvf.com/content/ICCV2021/supplemental/Wang_Topic_Scene_Graph_ICCV_2021_supplemental.pdf" }
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

