# Generative Partner Crucible 

![Generative Partner Crucible ](/PartnerCrucible/Library/signaltonoise-title.png)

## Why?

**Generative Partner Crucible ** is an experiment in Generative AI.

## Posts

<ul>
  {% for summary in site.Summary %}
    <li>
      <a href="/PartnerCrucible{{ summary.url }}">{{ summary.title }}</a>
    </li>
  {% endfor %}
</ul>
