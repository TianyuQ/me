---
title: 'Inferring Occluded Agent Behavior in Dynamic Games from Noise Corrupted Observations'
summary: Accepted by RA-L
tags: []
date: '2024-10-22'

# Optional external URL for project (replaces project detail page).
external_link: ''

# image:
#   caption: Mobile Robot Navigating among Pedestrians
#   focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
# url_code: ''
# url_pdf: 'uploads/Master Project.pdf'
# url_slides: 'uploads/Master Project.pdf'
# url_video: 'https://www.youtube.com/watch?v=YbupW0CFuYs'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Our paper "Inferring Occluded Agent Behavior in Dynamic Games from Noise Corrupted Observations" has been accepted by RA-L!

In mobile robotics and autonomous driving, it is natural to model agent interactions as the Nash equilibrium of a noncooperative, dynamic game. These methods inherently rely on observations from sensors such as lidars and cameras to identify agents participating in the game and, therefore, have difficulty when some agents are occluded. To address this limitation, this paper presents an occlusion-aware game-theoretic inference method to estimate the locations of potentially occluded agents, and simultaneously infer the intentions of both visible and occluded agents, which best accounts for the observations of visible agents. Additionally, we propose a receding horizon planning strategy based on an occlusion-aware contingency game designed to navigate in scenarios with potentially occluded agents. Monte Carlo simulations validate our approach, demonstrating that it accurately estimates the game model and trajectories for both visible and occluded agents using noisy observations of visible agents. Our planning pipeline significantly enhances navigation safety when compared to occlusion-ignorant baseline as well.
