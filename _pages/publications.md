---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
redirect_from: 
  - /publications/
  - /publications.html
---
You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

Testing testing, 123


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
