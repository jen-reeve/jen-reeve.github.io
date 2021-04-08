---
layout: archive
title: "Resources"
permalink: /resources/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

{: .success title="My Collapsible Panel" .x}
Some text

<!---
This is a comment. Below this is commented liquid syntax.
--->

{% comment%}
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
{% endcomment %}
