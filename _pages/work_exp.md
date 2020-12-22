---
layout: archive
title: "Work Experience"
permalink: /work_exp/
author_profile: true
---

{% include base_path %}

{% for post in site.work_exp reversed %}
  {% include archive-single.html %}
{% endfor %}
