---
title: "A Feature Selection Algorithm to Compute Gene Centric Methylation from Probe Level Methylation Data"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Serdar Bozdag

# Author notes (optional)
author_notes:
- "Equal contribution"

date: "2016-02-01T00:00:00Z"
doi: "https://doi.org/10.1371/journal.pone.0148977"

# Schedule page publish date (NOT publication's date).
publishDate: "2016-02-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *PLOS ONE*
publication_short: In *PLOS ONE*

abstract: DNA methylation is an important epigenetic event that affects gene expression during development and various diseases such as cancer. Understanding the mechanism of action of DNA methylation is important for downstream analysis. In the Illumina Infinium HumanMethylation 450K array, there are tens of probes associated with each gene. Given methylation intensities of all these probes, it is necessary to compute which of these probes are most representative of the gene centric methylation level. In this study, we developed a feature selection algorithm based on sequential forward selection that utilized different classification methods to compute gene centric DNA methylation using probe level DNA methylation data. We compared our algorithm to other feature selection algorithms such as support vector machines with recursive feature elimination, genetic algorithms and ReliefF. We evaluated all methods based on the predictive power of selected probes on their mRNA expression levels and found that a K-Nearest Neighbors classification using the sequential forward selection algorithm performed better than other algorithms based on all metrics. We also observed that transcriptional activities of certain genes were more sensitive to DNA methylation changes than transcriptional activities of other genes. Our algorithm was able to predict the expression of those genes with high accuracy using only DNA methylation data. Our results also showed that those DNA methylation-sensitive genes were enriched in Gene Ontology terms related to the regulation of various biological processes.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**]()'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
