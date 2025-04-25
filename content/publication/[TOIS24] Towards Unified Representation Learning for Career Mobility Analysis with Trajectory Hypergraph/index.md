---
title: '[TOIS25] Towards Unified Representation Learning for Career Mobility Analysis with Trajectory Hypergraph'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: [Rui Zha, Ying Sun, Chuan Qin, Le Zhang, Tong Xu, Hengshu Zhu, Enhong Chen]

# Author notes (optional)
author_notes: []

date: '2024-02-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-02-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: ACM Transactions on Information Systems
publication_short: ACM TOIS

abstract: Career mobility analysis aims at understanding the occupational movement patterns of talents across distinct labor market entities, which enables a wide range of talent-centered applications, such as job recommendation, labor demand forecasting, and company competitive analysis. Existing studies in this field mainly focus on a single fixed scale, investigating either individual trajectories at the micro-level or crowd flows among market entities at the macro-level. Consequently, the intrinsic cross-scale interactions between talents and the labor market are largely overlooked. To bridge this gap, we propose UniTRep, a novel unified representation learning framework for cross-scale career mobility analysis. Specifically, we first introduce a trajectory hypergraph structure to organize the career mobility patterns in a low-information-loss manner, where market entities and talent trajectories are represented as nodes and hyperedges, respectively. Then, for learning the market-aware talent representations, we attentively propagate the node information to the hyperedges and incorporate the market contextual features into the process of individual trajectory modeling. For learning the trajectory-enhanced market representations, we aggregate the message from hyperedges associated with a specific node to integrate the fine-grained semantics of trajectories into labor market modeling. Moreover, we design two auxiliary tasks to optimize both intra-scale and cross-scale learning with a self-supervised strategy. Extensive experiments on a real-world dataset clearly validate that UniTRep can significantly outperform state-of-the-art baselines for various tasks.

# Summary. An optional shortened abstract.
summary: Career mobility analysis aims at understanding the occupational movement patterns of talents across distinct labor market entities, which enables...

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