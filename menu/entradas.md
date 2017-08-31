---
layout: page
title: Entradas
author: Román Contreras
---
<ul class="posts">
  {% for post in site.posts %}

    {% unless post.next %}
      <h3>{{ post.date | date: '%Y' }}</h3>
    {% else %}
      {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
      {% capture nyear %}{{ post.next.date | date: '%Y' }}{% endcapture %}
      {% if year != nyear %}
        <h3>{{ post.date | date: '%Y' }}</h3>
      {% endif %}
    {% endunless %}

    <li itemscope>
      <a href="{{ site.github.url }}{{ post.url }}">{{ post.title }}</a>
      <p class="post-date"><span><i class="fa fa-calendar" aria-hidden="true"></i> {% assign m = post.date | date: "%-m" %}
{{ post.date | date: "%-d" }}
de {% case m %}
  {% when '1' %}enero
  {% when '2' %}febrero
  {% when '3' %}marzo
  {% when '4' %}abril
  {% when '5' %}mayo
  {% when '6' %}junio
  {% when '7' %}julio
  {% when '8' %}agosto
  {% when '9' %}septiembre
  {% when '10' %}octubre
  {% when '11' %}noviembre
  {% when '12' %}diciembre
{% endcase %}
de {{ post.date | date: "%Y" }} - <i class="fa fa-clock-o" aria-hidden="true"></i> {% include read-time.html %}</span></p>
    </li>

  {% endfor %}
</ul>
