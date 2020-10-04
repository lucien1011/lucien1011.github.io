---
layout: archive
title: "HEP Publications"
permalink: /heppublications/
author_profile: true
---

{% include base_path %}

{% for post in site.heppublications reversed %}
  {% include archive-single.html %}
{% endfor %}
