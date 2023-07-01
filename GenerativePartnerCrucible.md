# Generative Partner Crucible 

![Generative Partner Crucible ](/PartnerCrucible/Library/signaltonoise-title.png)

## Why?

**Generative Partner Crucible ** is an experiment in Generative AI.

## Posts

<ul>
  {% for post in site.GenerativePartnerCrucible %}
    <li>
      <a href="/PartnerCrucible{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
