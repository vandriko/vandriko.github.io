---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

This page will be updated soon. In the meantime, you can find my publications on <u><a href="https://scholar.google.nl/citations?user=WZAn2CwAAAAJ&hl=en">my Google Scholar profile</a>.</u> 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="https://scholar.google.nl/citations?user=WZAn2CwAAAAJ&hl=en">my Google Scholar profile</a>.</u>
{% endif %} 

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
