<!-- ---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
--- -->

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}


<h2>Journal Articles</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'Journal' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Conference Papers</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'Conference' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Under Review</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'UnderReview' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}


