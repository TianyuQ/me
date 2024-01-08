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

date: '2023-09-24'
doi: 'https://doi.org/10.48550/arXiv.2303.09744'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-09-24'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: ArXiv
publication_short: ArXiv

abstract: Robots and autonomous vehicles must rely on sensor observations, e.g., from lidars and cameras, to comprehend their environment and provide safe, efficient services. In multi-agent scenarios, they must additionally account for other agents' intrinsic motivations, which ultimately determine the observed and future behaviors. Dynamic game theory provides a theoretical framework for modeling the behavior of agents with different objectives who interact with each other over time. Previous works employing dynamic game theory often overlook occluded agents, which can lead to risky navigation decisions. To tackle this issue, this paper presents an inverse dynamic game technique which optimizes the game model itself to infer unobserved, occluded agents' behavior that best explains the observations of visible agents. Our framework concurrently predicts agents' future behavior based on the reconstructed game model. Furthermore, we introduce and apply a novel receding horizon planning pipeline in several simulated scenarios. Results demonstrate that our approach offers 1) robust estimation of agents' objectives and 2) precise trajectory predictions for both visible and occluded agents from observations of only visible agents. Experimental findings also indicate that our planning pipeline leads to safer navigation decisions compared to existing baseline methods.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2303.09744'
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
  caption: 'A traffic scenario in which the view of the autonomous vehicle in green is occluded by the red vehicle, so it cannot observe the blue pedestrian running across the street. With our proposed method, the green vehicle notices the red vehicle’s deceleration. It then infers that an agent is crossing the road from the occluded area. Consequently, it can brake to avoid a collision.'
  focal_point: ''
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



{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
