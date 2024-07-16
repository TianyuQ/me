---
title: Pedestrian Trajectory Prediction and Mobile Robot Navigation Based on Inverse Dynamic Games
summary: Master Thesis
tags: []
date: '2023-03-15'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Mobile Robot Navigating among Pedestrians
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
# url_code: ''
# url_pdf: 'uploads/Master Project.pdf'
url_slides: 'uploads/Master Project.pdf'
# url_video: 'https://www.youtube.com/watch?v=YbupW0CFuYs'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

With the development of relevant techniques in robotics and the maturity of application solutions, mobile robots are capable of working in more complicated scenarios and their application fields are enormously expanded. Service mobile robots tend to navigate in human-rich environments. Comparing with static obstacles, pedestrians are highly dynamic and tend to disturb the navigation of mobile robots. Navigating among pedestrians is thus challenging to mobile robots.

To tackle the inaccuracy of modelling pedestrian behaviors due to their high dynamic and randomness, we proposed an inverse dynamic game method based on model predictive control (MPC-GPred) to model pedestrians' individual and group behavior.

For the high time complexity of solving for pedestrians' trajectories caused by the nonlinear cost function, we did linear quadratic approximation and analytically solve for Nash strategy as pedestrian trajectory prediction. To achieve best prediction performance, we apply inverse dynamic game technique to identify weighting parameters according to trajectory observations. We tested our method with open-source algorithms RVO and CADRL on prediction performance and results indicate the effectiveness of our method.

In practical navigation tasks, to tackle the inaccuracy of modelling pedestrian behaviors due to interactions between pedestrians and robots, we proposed a dynamic game navigation method based on model predictive control (MPC-GNav) for mobile robots. we add the mobile robot as the new agent in dynamic games and solve for Nash strategy as the control for mobile robots. Consider the difference of dynamic model between mobile robots and the dynamic game model, we applied feedback linearization to achieve the control of robot platforms. To tackle the problem of incapability of control mobile robots in large scenarios, we proposed a layered planning method to obtain local goals. Mobile robots complete the entire navigation tasks by navigating to each local We compared our method with open-source algorithms RVO and CADRL in simulated scenarios and results indicate the effectiveness of our method in collision avoidance.

We implemented MPC-GNav on "Jiao Long" smart wheelchair in pedestrian-rich scenarios such as corridors and halls and did navigation experiments among pedestrians and compared the results with open-source method DWA. Results indicate the effectiveness of our method in improving navigation safeness.
