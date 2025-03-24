---
layout: index.liquid
---
## Pulp This Blog

{% for post in collections.posts.pages %}
#### {{post.title}}
{{post.description}}
<div class="excerpt">{{post.excerpt}}</div>
<div class="postlink"><a href="{{ post.permalink }}">Oh boy! Adventure Awaits ></a></div>
{% endfor %}
