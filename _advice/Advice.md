---
layout: default
permalink: /advice/
---

# All Travel Advice

<section class="TA">
  {% for page in site.advice %}
  <div class="ADD">
    <a href="{{ site.baseurl }}{{ page.url }}">
      <img src="{{ site.baseurl }}/img/{{ page.image }}" alt="{{ page.title }}">
    </a>
    <a href="{{ site.baseurl }}{{ page.url }}">
      <p class="ADT">{{ page.title }}</p>
    </a>
    <p class="ADP">{{ page.excerpt }}</p>
  </div>
  {% endfor %}
</section>
