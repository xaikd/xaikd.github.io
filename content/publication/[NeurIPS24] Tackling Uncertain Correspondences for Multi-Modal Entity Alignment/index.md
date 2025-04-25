---
title: '[NeurIPS24] Tackling Uncertain Correspondences for Multi-Modal Entity Alignment'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: [Liyi Chen, Ying Sun, Shengzhe Zhang, Yuyang Ye, Wei Wu, Hui Xiong]

# Author notes (optional)
author_notes: []

date: '2024-09-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-09-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: The 38th Annual Conference on Neural Information Processing Systems
publication_short: NeurIPS-2024

abstract: "Recently, multi-modal entity alignment has emerged as a pivotal endeavor for the integration of Multi-Modal Knowledge Graphs (MMKGs) originating from diverse data sources. Existing works primarily focus on fully depicting entity features by designing various modality encoders or fusion approaches. However, uncertain correspondences between inter-modal or intra-modal cues, such as weak inter-modal associations, description diversity, and modality absence, still severely hinder the effective exploration of aligned entity similarities. To this end, in this paper, we propose a novel Tackling uncertain correspondences method for Multi-modal Entity Alignment (TMEA). Specifically, to handle diverse attribute knowledge descriptions, we design alignment-augmented abstract representation that incorporates the large language model and in-context learning into attribute alignment and filtering for generating and embedding the attribute abstract. In order to mitigate the influence of the modality absence, we propose to unify all modality features into a shared latent subspace and generate pseudo features via variational autoencoders according to existing modal features. Then, we develop an inter-modal commonality enhancement mechanism based on cross-attention with orthogonal constraints, to address weak semantic associations between modalities. Extensive experiments on two real-world datasets validate the effectiveness of TMEA with a clear improvement over competitive baselines."

# Summary. An optional shortened abstract.
summary: Recently, multi-modal entity alignment has emerged as a pivotal endeavor for the integration of Multi-Modal Knowledge Graphs (MMKGs)...

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