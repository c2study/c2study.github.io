---
layout: archive
title: "论文发表"
permalink: /publications/
author_profile: true
---

论文发表

**论文发表情况**



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

