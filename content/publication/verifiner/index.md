---
title: 'VERIFINER: Verification-augmented NER via Knowledge-grounded Reasoning with Large Language Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Seoyeon Kim
  - Kwangwook Seo 
  - admin
  - Jinyoung Yeo
  - Dongha Lee
 

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-01-13T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-13T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: ACL 2024
publication_short: ACL 2024

abstract: Recent approaches in domain-specific named entity recognition (NER), such as biomedical NER, have shown remarkable advances. However, they still lack of faithfulness, producing erroneous predictions. We assume that knowledge of entities can be useful in verifying the correctness of the predictions. Despite the usefulness of knowledge, resolving such errors with knowledge is nontrivial, since the knowledge itself does not directly indicate the ground-truth label. To this end, we propose VerifiNER, a post-hoc verification framework that identifies errors from existing NER methods using knowledge and revises them into more faithful predictions. Our framework leverages the reasoning abilities of large language models to adequately ground on knowledge and the contextual information in the verification process. We validate effectiveness of VerifiNER through extensive experiments on biomedical datasets. The results suggest that VerifiNER can successfully verify errors from existing models as a model-agnostic approach. Further analyses on out-of-domain and low-resource settings show the usefulness of VerifiNER on real-world applications. 


# Summary. An optional shortened abstract.
summary: In this paper, we introduce VerifiNER, a post-hoc verification framework that identifies errors from existing NER methods using knowledge and revises them into more faithful predictions.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2402.18374'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
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
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
