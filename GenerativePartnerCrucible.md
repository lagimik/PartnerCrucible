# Generative Partner Crucible

![Signal to Noise](/PartnerCrucible/Library/generativeAI-title.png)

## Why?

**General Partner Crucible** is an experiment in generative AI.

## Posts

<ul>
{% for post in site.posts %}
  {% if post.layout == 'generativepartnercrucible' %}
    <li>
      <a href="/PartnerCrucible{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endif %}
{% endfor %}
</ul>
