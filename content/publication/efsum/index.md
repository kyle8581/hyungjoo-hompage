---
title: 'Evidence-Focused Fact Summarization for Knowledge-Augmented Zero-Shot Question Answering'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Sungho Ko
  - Hyunjin Cho
  - admin
  - Jinyoung Yeo
  - Dongha Lee

# Author notes (optional)
author_notes: []

date: '2024-03-05T00:00:00Z'
# doi: '10.48550/arXiv.2403.02966'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-05T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: EMNLP 2024
publication_short: EMNLP 2024

abstract: Recent studies have investigated utilizing Knowledge Graphs (KGs) to enhance Quesetion Answering (QA) performance of Large Language Models (LLMs), yet structured KG verbalization remains challengin. Existing methods, such as triple-form or free-form textual conversion of triple-form facts, encounter several issues. These include reduced evidence density due to duplicated entities or relationships, and reduced evidence clarity due to an inability to emphasize crucial evidence. To address these issues, we propose EFSum, an Evidence-focused Fact Summarization framework for enhanced QA with knowledge-augmented LLMs. We optimize an open-source LLM as a fact summarizer through distillation and preference alignment. Our extensive experiments show that EFSum improves LLM's zero-shot QA performance, and it is possible to ensure both the helpfulness and faithfulness of the summary.

# Summary. An optional shortened abstract.
summary: We propose EFSum, an Evidence-focused Fact Summarization framework that improves knowledge-augmented zero-shot QA by optimizing fact summarization through distillation and preference alignment.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2403.02966'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
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

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
