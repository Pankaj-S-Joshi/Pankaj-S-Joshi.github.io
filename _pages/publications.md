---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on [my inspire profile](https://inspirehep.net/authors/1004099?ui-citation-summary=true)


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
