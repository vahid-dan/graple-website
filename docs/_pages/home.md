---
layout: splash
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/unsplash-image-4.jpg
  cta_label: "Latest Release"
  cta_url: "releases/v3.1.0-released/"
excerpt: 'Distributed Computing Made Easy for Lake Ecology Modeling'
---
GRAPLEr is an R-based open-source software product of GRAPLE, the GLEON Research and PRAGMA Lake Expedition.

GRAPLEr brings the power of distributed computing to the fingertips of lake ecology modelers. [Read more](about){: .btn .btn--info}

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}
