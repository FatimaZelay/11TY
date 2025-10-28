--- 
title: My Learning Journal
layout: "base.njk"

---

Sprints

{% for sprint in collections.sprints %}
- [{{ sprint.data.title }}]({{ sprint.url | url }})
{% endfor %}
