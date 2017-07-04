---
layout: default
title: Projects
---

## My Projects

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
  > {{repository.project_tagline}}
{% endfor %}
