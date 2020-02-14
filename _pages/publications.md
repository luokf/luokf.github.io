---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

Full list please find on my Google Scholar profile.

---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
