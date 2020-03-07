---
layout: page
---

# All My Posts Are Here

 {% for post in paginator.posts %}
      <article>
        <h1>{{ post.title }}</h1>
        <p>{{ post.excerpt }}</p>
        <a href="{{ site.baseurl }}/{{ post.url }}">[ Read ]</a>
      </article>
      {% endfor %}
