---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">Below are the full lists of my publications. You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

--------------------------------------------------

{% include base_path %}

# Journal and Conference

{% for post in site.publications reversed %}

  {% include archive-single.html %}

{% endfor %}

