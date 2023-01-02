![Signal to Noise](/PartnerCrucible/Library/signaltonoise-title.png)

[< Back to Crucible](./)

# Why?

**signal:noise** aims to provide points of view from experts and practitioners to help you identify the paths that carry the most signal and can accelerate your digital (or cloud) ambitions. In doing so, the blog may challenge popular narratives, openly highlight uncertainty, and test your comfort levels for engaging at the edge.

# Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="/PartnerCrucible{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.content | markdownify | strip_html | truncatewords: 50 }}</p>
    </li>
  {% endfor %}
</ul>

[< Back to Crucible](./)