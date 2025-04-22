---
title: '[KDD24] Unified Dual-Intent Translation for Joint Modeling of Search and Recommendation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: [Yuting Zhang, Yiqing Wu, Ruidong Han, Ying Sun, Yongchun Zhu, Fuzhen Zhuang, Xiang Li, Wei Lin, Zhulin An, Yongjun Xu]

# Author notes (optional)
author_notes: []

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

abstract: "Recommendation systems, which assist users in discovering their preferred items among numerous options, have served billions of users across various online platforms. Intuitively, users' interactions with items are highly driven by their unchanging inherent intents (e.g., always preferring high-quality items) and changing demand intents (e.g., wanting a T-shirt in summer but a down jacket in winter). However, both types of intents are implicitly expressed in recommendation scenario, posing challenges in leveraging them for accurate intent-aware recommendations. Fortunately, in search scenario, often found alongside recommendation on the same online platform, users express their demand intents explicitly through their query words. Intuitively, in both scenarios, a user shares the same inherent intent and the interactions may be influenced by the same demand intent. It is therefore feasible to utilize the interaction data from both scenarios to reinforce the dual intents for joint intent-aware modeling. But the joint modeling should deal with two problems: 1) accurately modeling users' implicit demand intents in recommendation; 2) modeling the relation between the dual intents and the interactive items. To address these problems, we propose a novel model named Unified Dual-Intents Translation for joint modeling of Search and Recommendation (UDITSR). To accurately simulate users' demand intents in recommendation, we utilize real queries from search data as supervision information to guide its generation. To explicitly model the relation among the triplet <inherent intent, demand intent, interactive item>, we propose a dual-intent translation propagation mechanism to learn the triplet in the same semantic space via embedding translations. Extensive experiments demonstrate that UDITSR outperforms SOTA baselines both in search and recommendation tasks."

# Summary. An optional shortened abstract.
summary: Recommendation systems, which assist users in discovering their preferred items among numerous options, have served billions of users across various...

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