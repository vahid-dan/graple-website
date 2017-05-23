---
layout: splash
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/unsplash-image-4.jpg
  caption:
excerpt: 'Distributed Computing Made Easy for Lake Ecology Modeling'
---
GRAPLEr is an R-based open-source software product of GRAPLE, the GLEON Research and PRAGMA Lake Expedition.

GRAPLEr brings the power of distributed computing to the fingertips of lake ecology modelers. While it is relatively easy to run one lake model simulation on a personal computer, it is more difficult to execute multiple simulations, which requires additional computing and human resources. To overcome this problem, GRAPLEr, a distributed computing system, integrates and applies overlay virtual network, high-throughput computing, and Web service technologies. GRAPLEr allows submission of hundreds or thousands of General Lake Model (GLM) simulations, runs these lake model simulations efficiently, and retrieves model output.
<a href="/about" class="btn--info">Read more</a>
{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}
