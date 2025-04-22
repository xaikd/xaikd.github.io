---
title: '[WWW25] Exploring Hypergraph Condensation via Variational Hyperedge Generation and Multi-Aspectual Amelioration'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: [Zheng Gong, Shuheng Shen, Changhua Meng, Ying Sun]

# Author notes (optional)
author_notes: ["", "", "", "Corresponding author"]

date: '2025-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In Proceedings of The Web Conference 2025
publication_short: WWW-2025

abstract: Hypergraph neural networks (HyperGNNs) show promise in modeling online networks with high-order correlations. Despite notable progress, training these models on large-scale raw hypergraphs entails substantial computational and storage costs, thereby increasing the need of hypergraph size reduction. However, existing size reduction methods primarily capture pairwise association pattern within conventional graphs, making them challenging to adapt to hypergraphs with high-order correlations. To fill this gap, we introduce a novel hypergraph condensation framework, HG-Cond, designed to distill large-scale hypergraphs into compact, synthetic versions while maintaining comparable HyperGNN performance. Within this framework, we develop a Neural Hyperedge Linker to capture the high-order connectivity pattern through variational inference, achieving linear complexity with respect to the number of nodes. Moreover, We propose a multi-aspectual amelioration strategy including a Gradient-Parameter Synergistic Matching objective to holistically refine synthetic hypergraphs by coordinating improvements in node attributes, high-order connectivity, and label distributions. Extensive experiments demonstrate the efficacy of HG-Cond in hypergraph condensation, notably outperforming the original test accuracy on the 20News dataset while concurrently reducing the hypergraph size to a mere 5% of its initial scale. Furthermore, the condensed hypergraphs demonstrate robust cross-architectural generalizability and potential for expediting neural architecture search. This research represents a significant advancement in hypergraph processing, providing a scalable approach for hypergraph-based learning in resource-limited environments.

# Summary. An optional shortened abstract.
summary: Hypergraph neural networks (HyperGNNs) show promise in modeling online networks with high-order correlations. Despite notable progress, training these models...

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