---
title: '[TOIS25] Market-aware Long-term Job Skill Recommendation with Explainable Deep Reinforcement Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: [Ying Sun, Yang Ji, Hengshu Zhu, Fuzhen Zhuang, Qing He, Hui Xiong]

# Author notes (optional)
author_notes: []

date: '2024-11-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-11-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: ACM Transactions on Information Systems
publication_short: ACM TOIS

abstract: Continuously learning new skills is essential for talents to gain a competitive advantage in the labor market. Despite extensive efforts on relevance- or preference-based skill recommendations, little attention has been given to the practical effects of job skills in the market. To bridge this gap, we propose an explainable personalized skill learning recommendation system that considers the long-term learning benefits and costs. Specifically, we model skill learning utilities based on salary and learning cost associated with job positions and propose a multi-objective deep reinforcement learning framework to model and maximize long-term utilities. Furthermore, we propose a Self-explaining Skill Recommendation Deep Q-network (SeSRDQN) that captures and prototypes prevalent skill sets in the market into representative exemplars for decision-making. SeSRDQN quantitatively decomposes the talent’s long-term learning utility into contributions from each exemplar, offering a comprehensive and multi-factorial explanation across various skill learning options. To tackle the combinatorial complexity of the skill space, we develop an MCTS-based optimization-decoding iterative training procedure for explanation fidelity and human understandability. In this way, talents will receive a tailored roadmap of essential skills, complemented by exemplar-based explanations, to effectively plan their careers. Extensive experiments on a real-world dataset validate the effectiveness and explainability of our approach.

# Summary. An optional shortened abstract.
summary: Continuously learning new skills is essential for talents to gain a competitive advantage in the labor market. Despite extensive efforts...

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