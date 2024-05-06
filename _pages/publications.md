---
layout: archive
title: "Published"
permalink: /publications/
author_profile: true
---

<!-- {% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %} -->

{% include base_path %}

{% for post in site.publications reversed %}
  {% unless post.permalink contains 'preprint' %}
  <div style="font-size: 0.8em;">
    {% include archive-single.html %}
  </div>
  <div style="margin-top: -20px;"></div>
  {% endunless %}
{% endfor %}

<!-- Add space between sections -->
<div style="margin-top: 50px;"></div>

# Preprints
{% for post in site.publications reversed %}
  {% if post.permalink contains 'preprint' %}
  <div style="font-size: 0.8em;">
    {% include archive-single.html %}
  </div>
  <div style="margin-top: -20px;"></div>
  {% endif %}
{% endfor %}
