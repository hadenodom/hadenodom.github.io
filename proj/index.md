---
layout: default
title: Projects
---

(This area will display my github projects once complete.  For now, visit my github using the link below. (the one that doesn't say "email")

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}
