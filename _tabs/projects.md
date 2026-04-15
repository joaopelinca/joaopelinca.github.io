---
layout: page
title: Projects & Skills
icon: fas fa-diagram-project
order: 2
---

{% assign sorted_posts = site.posts | sort: "order" %}
{% for post in sorted_posts %}
### [{{ post.title }}]({{ post.url }})

{{ post.excerpt }}

---
{% endfor %}