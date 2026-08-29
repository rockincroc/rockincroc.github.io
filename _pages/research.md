---
layout: archive
title: "Research"
permalink: /research/
author_profile: false
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

<!-- {% include base_path %} -->

<div class="research-list">
{% for post in site.publications reversed %}
  {% include research-card.html %}
{% endfor %}
</div>

# Exploratory projects
<div class="research-list research-list--exploratory">
{% for post in site.portfolio reversed %}
  {% include research-card.html %}
{% endfor %}
</div>
