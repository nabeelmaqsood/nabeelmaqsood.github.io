---
layout: archive
title: "Work in Progress"
permalink: /Research/
author_profile: true
---


{% remove upper and lower brackets when you have a google profile to activate below comment %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
