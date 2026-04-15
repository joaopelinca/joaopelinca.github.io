---
layout: page
title: Projects & Skills
icon: fas fa-diagram-project
order: 2
---

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})

{{ post.excerpt }}

---
{% endfor %}