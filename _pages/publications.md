---
layout: archive
title: "Publications"
permalink: /publications
author_profile: true
---

You can also find an updated list of articles on my [Google Scholar Profile](https://scholar.google.com/citations?user=piSn5gQAAAAJ&hl=en)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-pub.html %}
{% endfor %}
