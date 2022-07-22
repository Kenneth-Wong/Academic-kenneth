+++
title = "Balanced Scene Graph Generation Assisted by Additional Biased Predictor"
date = 2022-07-18T00:00:00

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
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In [*SCIENTIA SINICA Informationis*](https://www.sciengine.com/SSI/home)"
publication_short = "In *SCIENTIA SINICA Informationis*"

# Abstract.
abstract = "A scene graph is the structural representation of a scene, consisting of the objects as nodes and relationships between any two objects as edges. The scene graph has been widely adopted in high-level vision language and reasoning applications. Therefore, scene graph generation has been a popular topic in recent years. However, it has suffered from the bias brought by the long-tailed distribution among the relationships. The scene graph generator prefers to predict the head predicates which are ambiguous and less precise. It makes the scene graph convey less information and degenerate into the stacking of objects, which restricts other applications from reasoning on the graph. In order to make the generator predict more diverse relationships and give a precise scene graph, we propose a method called Additional Biased Predictor (ABP) assisted balanced learning. It introduces an extra relationship prediction branch which is especially affected by the bias to make the generator pay more attention on tail predicates rather than tail ones. Compared to the scene graph generator which predicts relationships between any object pairs of interest, the biased branch predicts the relationships in the image without being assigned a certain object pair of interest, which is more concise. In order to train this biased branch, we construct the region-level relationship annotation using the instance-level relationship annotation automatically. Extensive experiments on the popular datasets, i.e., Visual Genome, VRD and OpenImages, show that ABP is effective on different scene graph generator, and makes the generator predict more diverse and accurate relationships and provide a more balanced and practical scene graph."

# Summary. An optional shortened abstract.
summary = "Scene graph generation has been a popular topic in recent years. However, it has suffered from the bias brought by the long-tailed distribution among the relationships. The scene graph generator prefers to predict the head predicates which are ambiguous and less precise. It makes the scene graph convey less information and degenerate into the stacking of objects, which restricts other applications from reasoning on the graph. In order to make the generator predict more diverse relationships and give a precise scene graph, we propose a method called Additional Biased Predictor (ABP) assisted balanced learning."

# Digital Object Identifier (DOI)
doi = "10.1360/SSI-2022-0105"

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
url_pdf = "https://www.sciengine.com/SSI/doi/10.1360/SSI-2022-0105"
#url_code = ""
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
#{name="预印版", url = "https://www.sciengine.com/SSI/doi/10.1360/SSI-2022-0105"}
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

