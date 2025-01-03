---
title: 'Evaluating Robustness of Reward Models for Mathematical Reasoning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Sunghwan Kim
  - Dongjin Kang
  - Taeyoon Kwon
  - admin
  - Jungsoo Won
  - Dongha Lee
  - Jinyoung Yeo

# Author notes (optional)
author_notes: []

date: '2024-10-02T00:00:00Z'
# doi: '10.48550/arXiv.2410.01729'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-10-02T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: arXiv preprint / Under review at ICLR 2025
publication_short: arXiv preprint / Under review at ICLR 2025

abstract: Reward models are key in reinforcement learning from human feedback (RLHF) systems, aligning the model behavior with human preferences. Particularly in the math domain, there have been plenty of studies using reward models to align policies for improving reasoning capabilities. Recently, as the importance of reward models has been emphasized, RewardBench is proposed to understand their behavior. However, we figure out that the math subset of RewardBench has different representations between chosen and rejected completions, and relies on a single comparison, which may lead to unreliable results as it only see an isolated case. Therefore, it fails to accurately present the robustness of reward models, leading to a misunderstanding of its performance and potentially resulting in reward hacking. In this work, we introduce a new design for reliable evaluation of reward models, and to validate this, we construct RewardMATH, a benchmark that effectively represents the robustness of reward models in mathematical reasoning tasks. We demonstrate that the scores on RewardMATH strongly correlate with the results of optimized policy and effectively estimate reward overoptimization, whereas the existing benchmark shows almost no correlation. The results underscore the potential of our design to enhance the reliability of evaluation, and represent the robustness of reward model. We make our code and data publicly available.

# Summary. An optional shortened abstract.
summary: We introduce RewardMATH, a benchmark for evaluating the robustness of reward models in mathematical reasoning tasks.

tags: []
url_pdf: 'https://arxiv.org/pdf/2410.01729'
url_code: 'https://huggingface.co/spaces/RewardMATH/RewardMATH_project'
# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

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
