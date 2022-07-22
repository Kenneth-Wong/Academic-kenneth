+++
title = "附加偏见预测器辅助的均衡化场景图生成"
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
publication = "In [*中国科学：信息科学*](https://www.sciengine.com/SSI/home)"
publication_short = "In *中国科学：信息科学*"

# Abstract.
abstract = "场景图是以场景中的物体为结点、以物体之间的关系为边构成的图结构, 在视觉与语言交互 理解和推理相关任务中具有广泛的应用前景. 近年来, 场景图自动生成逐渐受到关注, 但生成结果中对于关系的描述受到长尾分布带来的偏见的影响, 偏向于样本量较大的头部关系. 然而头部关系往往过于空泛, 描述不够准确, 容易造成误解. 由于这种关系价值不高, 生成的场景图近似于退化为场景中物体信息的堆叠, 不利于其他应用在图结构上进行结构化推理. 为了使场景图生成器在这种不均衡的数据条件下, 能够更均衡地学习, 给出更加多样化的特别是尾部的更准确的关系, 本文提出一种 附加偏见预测器（Additional Biased Predictor, ABP）辅助的均衡化学习方法. 该方法利用一条有偏见的关系预测分支, 令场景图生成器抑制自身对头部关系的偏好, 并更加注重尾部关系的学习. 场景 图生成器需要为指定的一对物体预测关系, 这是一种实例级的关系预测, 与之相比, 有偏分支以更简 洁的方式预测出图像中的关系信息, 即不指定任何一对物体, 直接预测出图像中存在的关系, 这是一 种区域级的关系预测. 为此, 本文利用已有的实例级的关系标注, 设计算法自动构造区域级的关系标注, 以此来训练该有偏分支, 使其具有区域级关系预测的能力. 在不同场景图生成器上应用 ABP方法, 并在多个公开数据集（Visual Genome、VRD 和 OpenImages 等）上进行实验, 结果表明, ABP 方法具有通用性, 应用 ABP 方法训练得到的场景图生成器能够预测出更加多样化的、更准确的关系, 进而生成更有价值、更实用的场景图."

# Summary. An optional shortened abstract.
summary = "近年来, 场景图自动生成逐渐受到关注, 但生成结果中 对于关系的描述受到长尾分布带来的偏见的影响, 偏向于样本量较大的头部关系. 然而头部关系往往过于空泛, 描述不够准确, 容易造成误解. 由于这种关系价值不高, 生成的场景图近似于退化为场景中物体信息的堆叠, 不利于其他应用在图结构上进行结构化推理. 为了使场景图生成器在这种不均衡的数据条件下, 能够更均衡地学习, 给出更加多样化的特别是尾部的更准确的关系, 本文提出一种 附加偏见预测器（Additional Biased Predictor, ABP）辅助的均衡化学习方法. "

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

