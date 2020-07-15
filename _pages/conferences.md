---
layout: archive
title: "Publications"
permalink: /conferences/
author_profile: true
---

<!-- {% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

{% include base_path %}

{% assign yearArray = "2019, 2018" | split: ", " %}

{% for i in yearArray %}
### {{i}}
<table>
{% for post in site.conferences reversed %}
  {% if post.year == i %}
  <tr>{% include publication.html %}</tr>
  {% endif %}
{% endfor %}
</table>
{% endfor %}



