---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find the updated list of my articles on my <u><a href="https://scholar.google.com/citations?user=IpcxRxMAAAAJ&hl=en" target="_blank">Google Scholar profile</a></u>.

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
