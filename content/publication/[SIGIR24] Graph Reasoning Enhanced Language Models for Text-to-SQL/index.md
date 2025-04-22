---
title: '[SIGIR24] Graph Reasoning Enhanced Language Models for Text-to-SQL'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: [Zheng Gong, Ying Sun]

# Author notes (optional)
author_notes: ["", "Corresponding author"]

date: '2024-03-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In Proceedings of The 47th International ACM SIGIR Conference on Research and Development in Information Retrieval
publication_short: SIGIR-2024

abstract: "Text-to-SQL parsing has attracted substantial attention recently due to its potential to remove barriers for non-expert end users interacting with databases. A key challenge in Text-to-SQL parsing is developing effective encoding mechanisms to capture the complex relationships between question words, database schemas, and their associated connections within the heterogeneous graph structure. Existing approaches typically introduce some useful multi-hop structures manually and then incorporate them into graph neural networks (GNNs) by stacking multiple layers, which (1) ignore the difficult-to-identify but meaningful semantics embedded in the multi-hop reasoning path, and (2) are limited by the expressive capability of GNN to capture long-range dependencies among the heterogeneous graph. To address these shortcomings, we introduce GRL-SQL, a graph reasoning enhanced language model, which innovatively applies structure encoding to capture the dependencies between node pairs, encompassing one-hop, multi-hop and distance information, subsequently enriched through self-attention for enhanced representational power over GNNs. Furthermore, GRL-SQL incorporates an interaction module that enables joint reasoning and fusion over the question-schema representations for enhancing global context modeling. Comprehensive experiments demonstrate the effectiveness and robustness of our proposed GRL-SQL."

# Summary. An optional shortened abstract.
summary: Text-to-SQL parsing has attracted substantial attention recently due to its potential to remove barriers for non-expert end users...

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