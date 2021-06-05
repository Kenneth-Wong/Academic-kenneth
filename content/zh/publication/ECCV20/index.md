+++
title = "Sketching Image Gist: Human-Mimetic Hierarchical Scene Graph Generation"
date = 2020-07-03T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Wenbin Wang", "Ruiping Wang","Shiguang Shan","Xilin Chen"]
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
publication = "In [*Proceedings of European Conference on Computer Vision (ECCV)*](https://eccv2020.eu/)"
publication_short = "In *ECCV 2020, Glasgow, UK*"

# Abstract.
abstract = "Scene graph aims to faithfully reveal humans’ perception of image content. When humans analyze a scene, they usually prefer to describe image gist ﬁrst, namely major objects and key relations in a scene graph, which contains essential image content. This humans’ inherent perceptive habit implies that there exists a hierarchical structure about humans’ preference during the scene parsing procedure. Therefore, we argue that a desirable scene graph should be also hierarchically constructed, and introduce a new scheme for modeling scene graph. Concretely, a scene is represented by a human-mimetic Hierarchical Entity Tree (HET) consisting of a series of image regions. The levels of HET reﬂect the perception priority level of humans. To generate a scene graph based on HET, we parse HET with our designed Hybrid Long Short-Term Memory (Hybrid-LSTM) network which speciﬁcally encodes hierarchy and siblings context to capture the structured information embedded in HET. To further prioritize key relations in the scene graph, we devise a Relation Ranking Module (RRM) to dynamically adjust their rankings by learning to capture humans’ subjective perceptive habits from objective entity saliency and size. Experiments are conducted on VRD, Visual Genome (VG), and VG-KR dataset (an extended version of VG we create by adding indicative annotations of key relations). Results demonstrate that our method not only achieves state-of-the-art performances for scene graph generation, but also is expert in mining image-speciﬁc relations which play a great role in serving downstream tasks."

# Summary. An optional shortened abstract.
summary = "Scene graph aims to faithfully reveal humans’ perception of image content. When humans analyze a scene, they usually prefer to describe image gist ﬁrst, namely major objects and key relations in a scene graph, which contains essential image content. This humans’ inherent perceptive habit implies that there exists a hierarchical structure about humans’ preference during the scene parsing procedure. Therefore, we argue that a desirable scene graph should be also hierarchically constructed, and introduce a new scheme for modeling scene graph."

# Digital Object Identifier (DOI)
doi = "10.1007/978-3-030-58601-0_14"

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
url_pdf = "https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580222.pdf"
url_code = "https://github.com/Kenneth-Wong/het-eccv20"
url_dataset = "https://github.com/Kenneth-Wong/het-eccv20"
#url_project = ""
url_slides = "https://drive.google.com/file/d/1_47wtPPesR5C2Oz9uD2Poi-ANXzv07Yh/view?usp=sharing"
url_video = "https://drive.google.com/file/d/1bbICb2oh4A4nLtSkf45mSBrxpksf7FNn/view?usp=sharing"
#url_poster = "#"
#url_source = "http://openaccess.thecvf.com/content_CVPR_2019/html/Wang_Exploring_Context_and_Visual_Pattern_of_Relationship_for_Scene_Graph_CVPR_2019_paper.html"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#links = [{name = "Custom Link", url = "http://example.org"}]
links = [{name = "arXiv", url = "https://arxiv.org/pdf/2007.08760.pdf"},
{name="Springer", url = "https://link.springer.com/content/pdf/10.1007%2F978-3-030-58601-0_14.pdf"},
{name="ECCV proc.", url = "https://link.springer.com/content/pdf/10.1007%2F978-3-030-58601-0.pdf"},
{name="supp", url = "https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580222-supp.pdf" }]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional) 
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++

