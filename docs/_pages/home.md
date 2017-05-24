---
layout: single
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/unsplash-image-4.jpg
  cta_label: "Latest Release"
  cta_url: "releases/v3.1.0-released/"
excerpt: 'Distributed Computing Made Easy for Lake Ecology Modeling'
excerpt: 'Distributed Computing Made Easy for Lake Ecology Modeling<br /> <small><a href="https://github.com/GRAPLE/GRAPLEr/releases/tag/v3.1.0">Latest release v3.1.0</a></small><br /><br /> {::nomarkdown}<iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=GRAPLE&repo=GRAPLEr&type=star&count=true&size=large" frameborder="0" scrolling="0" width="160px" height="30px"></iframe> <iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=GRAPLE&repo=GRAPLEr&type=fork&count=true&size=large" frameborder="0" scrolling="0" width="158px" height="30px"></iframe>{:/nomarkdown}'
---
GRAPLEr is an R-based open-source software product of GRAPLE, the GLEON Research and PRAGMA Lake Expedition.

GRAPLEr brings the power of distributed computing to the fingertips of lake ecology modelers. [Read more](about){: .btn .btn--info}

## GRAPLE Project Repositories

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}
