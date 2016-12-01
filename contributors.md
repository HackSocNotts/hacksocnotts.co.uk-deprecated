---
layout: page
title: Contributors
permalink: /contributors/
---

### Contributors

We'd like to say a huge thank you to the following members for their contributions to the site:

{% for contributor in site.github.contributors %}
- <img height="32px" src="{{ contributor.avatar_url}}"/>&nbsp;[{{ contributor.login}}]({{contributor.html_url}}), {{ contributor.contributions}} contributions
{% endfor %}

