---
title: 'Inferring Occluded Agent Behavior in Dynamic Games with Noise-Corrupted Observations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - David Fridovich-Keil

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-07-13'
doi: 'https://doi.org/10.48550/arXiv.2303.09744'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-07-13'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-journal']

# Publication name and optional abbreviated publication name.
publication: Submitted to IEEE Robotics and Automation Letters
publication_short: Submitted to RA-L

abstract: In mobile robotics and autonomous driving, it is natural to model agent interactions as the Nash equilibrium of a noncooperative, dynamic game. These methods inherently rely on observations from sensors such as lidars and cameras to identify agents participating in the game and, therefore, have difficulty when some agents are occluded. To address this limitation, this paper presents an occlusion-aware game-theoretic inference method to estimate the locations of potentially occluded agents, and simultaneously infer the intentions of both visible and occluded agents, which best accounts for the observations of visible agents. Additionally, we propose a receding horizon planning strategy based on an occlusion-aware contingency game designed to navigate in scenarios with potentially occluded agents. Monte Carlo simulations validate our approach, demonstrating that it accurately estimates the game model and trajectories for both visible and occluded agents using noisy observations of visible agents. Our planning pipeline significantly enhances navigation safety when compared to occlusion-ignorant baseline as well.

# Summary. An optional shortened abstract.
summary: This paper presents an occlusion-aware game-theoretic inference method to estimate the locations of potentially occluded agents, and simultaneously infer the intentions of both visible and occluded agents, which best accounts for the observations of visible agents. Additionally, we propose a receding horizon planning strategy based on an occlusion-aware contingency game designed to navigate in scenarios with potentially occluded agents.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2303.09744.pdf'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Occlusion-aware contingency game planner in an intersection scenario. The green vehicle can only see the red vehicle in the adjacent lane and is uncertain about the existence of occluded vehicles in the horizontal lanes. The green vehicles makes two assumptions: either 1) occluded vehicles exist. It can then use our proposed approach to estimate their trajectories by observing the red vehicle’s deceleration and plans the dark green trajectory; or 2) there are no occluded vehicles. It then only interacts with the red vehicle and plans the light green trajectory. Our contingency planning approach blends these two alternative strategies, while accounting for the fact that any occluded agents will be visible in the near future as the green vehicle approaches the intersection.'
  focal_point: 'Smart'
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---



<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
