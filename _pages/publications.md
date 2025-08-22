---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
redirect_from: 
  - /publications.html
---

### Below are recent/highlighted works. For a complete publications list, see my [Google Scholar profile](https://scholar.google.com/citations?user=2VgJ4loAAAAJ&hl=en).


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
