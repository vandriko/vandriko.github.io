---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

This page will be updated soon. In the meantime, you can also find my articles on <u><a href="{{ author.googlescholar }}">my Google Scholar profile</a>.</u> 

Link: {{ author.googlescholar }} or {{author.googlescholar}} or {{ googlescholar }}

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{ author.googlescholar }}">my Google Scholar profile</a>.</u>
{% endif %} 

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
