---
title: "Composable computation in discrete chemical reaction networks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- David Haley
- David Doty

date: "2013-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1","2"]

# Publication name and optional abbreviated publication name.
publication: In *Distributed Computing 2020* and *Principals of Distributed Computing 2019*
publication_short: In *DIST 2020* (Journal) and *PODC 2019* (Conference)

abstract: We study the composability of discrete chemical reaction networks (CRNs) that stably compute (i.e., with probability 0 of error) integer-valued functions $f:\mathbb{N}^d\rightarrow \mathbb{N}. We consider output-oblivious CRNs in which the output species is never a reactant (input) to any reaction. The class of output-oblivious CRNs is fundamental, appearing in earlier studies of CRN computation, because it is precisely the class of CRNs that can be composed by simply renaming the output of the upstream CRN to match the input of the downstream CRN. Our main theorem precisely characterizes the functions $f$ stably computable by output-oblivious CRNs with an initial leader. The key necessary condition is that for sufficiently large inputs, $f$ is the minimum of a finite number of nondecreasing quilt-affine functions. (An affine function is linear with a constant offset; a quilt-affine function is linear with a periodic offset).

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Journal Publication
  url: https://link.springer.com/article/10.1007/s00446-020-00378-z
- name: Conference Publication
  url: https://dl.acm.org/doi/10.1145/3293611.3331615
- name: Full Paper on Arxiv
  url: https://arxiv.org/abs/1903.02637

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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}
