---
<!-- layout: archive
title: "Publications"
permalink: /publications/
author_profile: true -->

My publication list can be found [here](https://scholar.google.com/citations?user=pm9i5OwAAAAJ).
The pre-print files of my papers can be found [here](https://www.researchgate.net/profile/Xin-Qin-10).
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
