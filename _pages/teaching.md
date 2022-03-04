---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<!-- What happens if I write here? -->

<h2>Courses</h2>
{% for post in site.teaching reversed %}
  {% if post.pubtype == 'Courses' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Supervision</h2>
{% for post in site.teaching reversed %}
  {% if post.pubtype == 'Supervision' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

<!-- <h2>Under Review</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'UnderReview' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %} -->


