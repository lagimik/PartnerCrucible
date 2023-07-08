
![Signal to Noise](/PartnerCrucible/Library/generativeAI-title.png)

# Why?

The **Generative  Partner Crucible** is an experiment in generative AI.

# Posts

<table>
{% for post in site.posts %}
  {% if post.layout == 'generativepartnercrucible' %}
    <tr>
      <td><a href="/PartnerCrucible{{ post.url }}">{{ post.title }}</a></td><td><img src="{{post.thumbnail}}"/></td>
    </tr>
  {% endif %}
{% endfor %}
</table>
