---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

Testing testing, 123




{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
