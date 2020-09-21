<!--这些是注释文本，不会显示
---
layout: archive
title: "My Posts"
permalink: /posts/
author_profile: true
---
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
{% include base_path %}
{% for post in site.posts reversed %}
  {% include archive-single.html %}
{% endfor %}
-->
