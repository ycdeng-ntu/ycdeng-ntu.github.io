---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

A complete list can be found in my [Google Scholar](https://scholar.google.com/citations?user=Yk3RZdoAAAAJ&hl=en&oi=ao) and [DBLP](https://dblp.org/pid/199/6564.html) profile.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
