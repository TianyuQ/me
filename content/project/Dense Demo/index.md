---
title: 'Dense Dynamics-Aware Reward Synthesis: Integrating Prior Experience with Demonstrations'
summary: Submitted to ICML 24'
tags: []
date: '2024-02-01'

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

Many continuous control problems can be formulated as sparse-reward reinforcement learning tasks. In principle, online reinforcement learning methods can automatically explore the state space to solve each new task. However, discovering sequences of actions which lead to a non-zero reward becomes exponentially more difficult as the task horizon increases. Manually shaping rewards can accelerate learning for a fixed task, but it can be an arduous process that must be repeated for each new environment. This work introduces a systematic reward-shaping framework which distills the information contained in 1) a task-agnostic prior data set and 2) a small number of task-specific expert demonstrations, and then uses these priors to synthesize dense dynamics-aware rewards for the given task. This supervision substantially accelerates learning in our experiments, and we provide analysis demonstrating how the approach can effectively guide online learning agents to faraway goals.
