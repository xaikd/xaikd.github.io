---
title: '[MM24] Tag Tree-Guided Multi-grained Alignment for Multi-Domain Short Video Recommendation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: [Yuting Zhang, Zhao Zhang, Yiqing Wu, Ying Sun, Fuzhen Zhuang, Wenhui Yu, Lantao Hu, Han Li, Kun Gai, Zhulin An, Yongjun Xu]

# Author notes (optional)
author_notes: []

date: '2024-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-07-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In Proceedings of The 32nd ACM International Conference on Multimedia
publication_short: ACM MM-2024

abstract: "Multi-Domain Rcommendation (MDR) aims to leverage data from multiple domains to enhance recommendations through overlapping users or items. However, extreme overlap sparsity in some applications makes it challenging for existing multi-domain models to capture domain-shared information. Moreover, the sparse overlapping users or items result in a cold start problem in every single domain and hinder feature space alignment of different domains, posing a challenge for joint optimization across domains. However, in multi-domain short video recommendation, we identify two key characteristics that can greatly alleviate the overlapping sparsity issue and enable domain alignment. (1) The following relations between users and publishers exhibit strong preferences and a concentration effect, as popular video publishers, who constitute a small portion of all users, are followed by a majority of users across various domains. (2) The tag tree structure shared by all videos can help facilitate multi-grained alignment across multiple domains. Based on these characteristics, we propose tag tree-guided multi-grained alignment with publisher enhancement for multi-domain video recommendation. Our model integrates publisher and tag nodes into the user-video bipartite graph as central nodes, enabling user and video alignment across all domains via graph propagation. Then, we propose a tag tree-guided decomposition method to obtain hierarchical graphs for multi-grained alignment. Further, we design tree-guided contrastive learning methods to capture the intra-level and inter-level node relations respectively. Finally, extensive experiments on two real-world short video recommendation datasets demonstrate the effectiveness of our model."

# Summary. An optional shortened abstract.
summary: Multi-Domain Recommendation (MDR) aims to leverage data from multiple domains to enhance recommendations through overlapping users or items...

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