---
title: '[KDD24] An Energy-centric Framework for Category-free Out-of-distribution Node Detection in Graphs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: [Zheng Gong, Ying Sun]

# Author notes (optional)
author_notes: ["", "Corresponding author"]

date: '2024-05-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-05-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In Proceedings of The 30th SIGKDD conference on Knowledge Discovery and Data Mining
publication_short: KDD 2024

abstract: Graph neural networks have garnered notable attention for effectively processing graph-structured data. Prevalent models prioritize improving in-distribution (IND) data performance, frequently overlooking the risks from potential out-of-distribution (OOD) nodes during training and inference. In real-world graphs, the automated network construction can introduce noisy nodes from unknown distributions. Previous research into OOD node detection, typically referred to as entropy-based methods, calculates OOD measurements from the prediction entropy alongside category classification training. However, the nodes in the graph might not be pre-labeled with specific categories, rendering entropy-based OOD detectors inapplicable in such category-free situations. To tackle this issue, we propose an energy-centric density estimation framework for OOD node detection, referred to as EnergyDef. Within this framework, we introduce an energy-based GNN to compute node energies that act as indicators of node density and reveal the OOD uncertainty of nodes. Importantly, EnergyDef can efficiently identify OOD nodes with low-resource OOD node annotations, achieved by sampling hallucinated nodes via Langevin Dynamics and structure estimation, along with training through Contrastive Divergence. Our comprehensive experiments on real-world datasets substantiate that our framework markedly surpasses state-of-the-art methods in terms of detection quality, even under conditions of scarce or entirely absent OOD node annotations.

# Summary. An optional shortened abstract.
summary: Graph neural networks have garnered notable attention for effectively processing graph-structured data. Prevalent models prioritize improving in-distribution...

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