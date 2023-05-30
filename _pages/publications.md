---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

For the complete list of publications, please [download my CV here](https://mukund-bhandari.github.io/files/cv.pdf) or refer to my [Google Scholar Profile](https://scholar.google.com/citations?user=IftooZgAAAAJ&hl=en).

## Featured Publications:

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
