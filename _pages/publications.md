---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}



{% assign postsByYear = site.publications | group_by_exp:"post", "post.date | date: '%Y'" %}
{% for year in postsByYear reversed %}
  <h2>{{ year.name }}</h2>
    {% for post in year.items %}
      {% include archive-single.html %}
    {% endfor %}
{% endfor %}



{% comment %}
{% assign cur_year = site.time | date: '%Y' %}
<h3>{{cur_year}}</h3>

{% for post in site.publications reversed %}
  {% assign pub_year = post.date | date: "%Y" %}
  {% if pub_year < cur_year %}
    <h2> pub_year </h2>
    {% assign cur_year = pub_year %}
  {% endif % }
  {% include archive-single.html %}
{% endfor %}
{% endcomment %}


{% comment %} 
{% assign my_array = "" | split: ',' %}
{% for post in site.publications reversed %}
  {{ capture p_year = post.date | date: "%Y" }}
  {% assign my_array = my_array | push: p_year %}
{% endfor %}

{% for item in my_array %}
  <h2>{{item}}</h2>
  {% assign pubs = site.publications | where:year, item %}
  {% for post in pubs %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}


{% endcomment %}



{% comment %} 
  {% assign pub_year = site.publications | where:"year","2021" %}
  <h2>2021</h2>
  {% for post in pub_year %}
    {% include archive-single.html %}
  {% endfor %}


  {% assign pub_year = site.publications | where:"year","2009" %}
  <h2>2009</h2>
  {% for post in pub_year %}
    {% include archive-single.html %}
  {% endfor %}
{% endcomment %}

{% comment %} 
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endcomment %}
