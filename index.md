## Welcome to My Blog

I use this blog to record my life. 

### About Me

I'm a student.

### [Posts](https://xukaykay.github.io/tinyblog/posts.html)

Here are my posts.
# All My Posts Are Here

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>

### Photos

Fun photos I took. 
