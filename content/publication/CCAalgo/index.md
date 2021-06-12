---
title: "A Canonical Correlation Analysis-Based Dynamic Bayesian Network Prior to Infer Gene Regulatory Networks from Multiple Types of Biological Data"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Serdar Bozdag

# Author notes (optional)
author_notes:
- "Equal contribution"

date: "2015-04-01T00:00:00Z"
doi: "https://doi.org/10.1089/cmb.2014.0296"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Journal of Computational Biology*
publication_short: In *J Comp Bio*

abstract: One of the challenging and important computational problems in systems biology is to infer gene regulatory networks (GRNs) of biological systems. Several methods that exploit gene expression data have been developed to tackle this problem. In this study, we propose the use of copy number and DNA methylation data to infer GRNs. We developed an algorithm that scores regulatory interactions between genes based on canonical correlation analysis. In this algorithm, copy number or DNA methylation variables are treated as potential regulator variables, and expression variables are treated as potential target variables. We first validated that the canonical correlation analysis method is able to infer true interactions in high accuracy. We showed that the use of DNA methylation or copy number datasets leads to improved inference over steady-state expression. Our results also showed that epigenetic and structural information could be used to infer directionality of regulatory interactions. Additional improvements in GRN inference can be gleaned from incorporating the result in an informative prior in a dynamic Bayesian algorithm. This is the first study that incorporates copy number and DNA methylation into an informative prior in dynamic Bayesian framework. By closely examining top-scoring interactions with different sources of epigenetic or structural information, we also identified potential novel regulatory interactions.

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
