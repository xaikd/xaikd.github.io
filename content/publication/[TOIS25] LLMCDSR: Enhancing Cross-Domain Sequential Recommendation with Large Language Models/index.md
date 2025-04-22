---
title: '[TOIS25] LLMCDSR: Enhancing Cross-Domain Sequential Recommendation with Large Language Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: [Haoran Xin, Ying Sun, Chao Wang, Hui Xiong]

# Author notes (optional)
author_notes: ["", "Corresponding author", "", "Corresponding author"]

date: '2025-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: ACM Transactions on Information Systems
publication_short: ACM TOIS

abstract: Cross-Domain Sequential Recommendation (CDSR) aims to predict users’ preferences based on historical sequential interactions across multiple domains. Existing works focus on the overlapped users who interact in multiple domains to capture the cross-domain correlations. These methods often underperform in practical scenarios featuring both overlapped and non-overlapped users due to the limited cross-domain interactions and knowledge transfer misalignment for non-overlapped users. To address this, we leverage Large Language Models (LLMs) to facilitate CDSR by fully exploiting single-domain interactions. However, LLMs exhibit inherent limitations in handling extensive item repositories and sequential collaborative signals. Moreover, the generation reliability is compromised by the hallucination problem, potentially causing noisy and unstable outputs. To this end, we propose a novel LLMCDSR framework, which employs LLMs to predict unobserved cross-domain interactions, termed pseudo items, within single-domain interactions. Specifically, we first prompt LLMs to execute the Candidate-Free Cross-Domain Interaction Generation task. Then, we devise a Collaborative-Textual Contrastive Pre-Training strategy, learning to infuse collaborative information into textual features. Afterwards, we present a novel Relevance-Aware Meta Recall Network (RMRN) to selectively identify and retrieve high-quality pseudo items from the dataset, where the parameters are optimized in a meta-learning manner. Finally, extensive experiments on two public datasets validate the effectiveness of LLMCDSR in enhancing CDSR.

# Summary. An optional shortened abstract.
summary: Cross-Domain Sequential Recommendation (CDSR) aims to predict users’ preferences based on historical sequential interactions across multiple domains...

tags: []

# Display this page in the Featured widget?
featured: true

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
---