---
title: "ProcessDriver: A computational pipeline to identify copy number drivers and associated disrupted biological processes in cancer"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Serdar Bozdag

# Author notes (optional)
author_notes:
- "Equal contribution"

date: "2017-07-01T00:00:00Z"
doi: "https://doi.org/10.1016/j.ygeno.2017.04.004"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Genomics*
publication_short: In *Genomics*

abstract: Copy number amplifications and deletions that are recurrent in cancer samples harbor genes that confer a fitness advantage to cancer tumor proliferation and survival. One important challenge in computational biology is to separate the causal (i.e., driver) genes from passenger genes in large, aberrated regions. Many previous studies focus on the genes within the aberration (i.e., cis genes), but do not utilize the genes that are outside of the aberrated region and dysregulated as a result of the aberration (i.e., trans genes). We propose a computational pipeline, called ProcessDriver, that prioritizes candidate drivers by relating cis genes to dysregulated trans genes and biological processes. ProcessDriver is based on the assumption that a driver cis gene should be closely associated with the dysregulated trans genes and biological processes, as opposed to previous studies that assume a driver cis gene should be the most correlated gene to the copy number of an aberrated region. We applied our method on breast, bladder and ovarian cancer data from the Cancer Genome Atlas database. Our results included previously known driver genes and cancer genes, as well as potentially novel driver genes. Additionally, many genes in the final set of drivers were linked to new tumor events after initial treatment using survival analysis. Our results highlight the importance of selecting driver genes based on their widespread downstream effects in trans.

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

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
