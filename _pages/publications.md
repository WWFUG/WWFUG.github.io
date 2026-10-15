---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

For my complete and most up-to-date publication record, see [Google Scholar]({{ site.author.googlescholar }}) or [DBLP]({{ site.author.dblp }}).

## Selected Publications

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
