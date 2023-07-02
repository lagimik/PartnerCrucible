# Signal:Noise

![Signal to Noise](/PartnerCrucible/Library/signaltonoise-title.png)

## Why?

**signal:noise** aims to provide points of view from experts and practitioners to help you identify the paths that carry the most signal and can accelerate your digital (or cloud) ambitions. In doing so, the blog may challenge popular narratives, openly highlight uncertainty, and test your comfort levels for engaging at the edge.

## Posts

<ul>
  {% for post in site.posts %}
    {% if page.flag == 'SignalNoise' %}
    <li>
      <a href="/PartnerCrucible{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
