---
layout: archive
title: "Research Work"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

<!-- {% include base_path %} -->

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<br>
# Other Unpublished Research
{% for post in site.portfolio reversed %}
  {% include archive-single.html %}
{% endfor %}