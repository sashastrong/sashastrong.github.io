---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Click on individual titles to view the full abstract and download a self-archived version.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
