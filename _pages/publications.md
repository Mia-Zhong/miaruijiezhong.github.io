
1. [Direct and moderating causal effects of network support on sleep quality: findings from the UC Berkeley social network study](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=WBOatjoAAAAJ&authuser=1&citation_for_view=WBOatjoAAAAJ:u-x6o8ySG0sC)

<!--
---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
-->



<!--
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{https://scholar.google.com/citations?user=WBOatjoAAAAJ&hl=en&authuser=1}}">my Google Scholar profile</a>.</div>
{% endif %} 


 {% include base_path %} 

 New style rendering if publication categories are defined
 {% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %} 

-->



