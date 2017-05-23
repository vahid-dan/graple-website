---
layout: splash
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/unsplash-image-4.jpg
  caption:
excerpt: 'Distributed Computing Made Easy for Lake Ecology Modeling'
---
{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}
