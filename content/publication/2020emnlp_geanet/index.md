---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Biomedical Event Extraction with Hierarchical Knowledge Graphs"
authors: ["**Kung-Hsiang Huang**", "Mu Yang", "Nanyun Peng"]
date: 
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-09-01

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Empirical Methods in Natural Language Processing 2020 (Short-Findings)"
publication_short: "*EMNLP 2020 (Short-Findings)*"

abstract: "Biomedical event extraction is critical in understanding biomolecular interactions described in scientific corpus. One of the main challenges is to identify nested structured events that are associated with non-indicative trigger words. We propose to incorporate domain knowledge from Unified Medical Language System (UMLS) to a pre-trained language model via Graph Edge-conditioned Attention Networks (GEANet) and hierarchical graph representation. To better recognize the trigger words, each sentence is first grounded to a sentence graph based on a jointly modeled hierarchical knowledge graph from UMLS. The grounded graphs are then propagated by GEANet, a novel graph neural networks for enhanced capabilities in inferring complex events. On BioNLP 2011 GENIA Event Extraction task, our approach achieved 1.41% F1 and 3.19% F1 improvements on all events and complex events, respectively. Ablation studies confirm the importance of GEANet and hierarchical KG."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Preprint
#   url: https://arxiv.org/abs/2009.09335

# links:
# - name: Code
#   url: https://github.com/PlusLabNLP/GEANet-BioMed-Event-Extraction    
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2009.09335
url_code: https://github.com/PlusLabNLP/GEANet-BioMed-Event-Extraction    
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
