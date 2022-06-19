# Hi there, I'm Priyavrat 👋

[![website](https://img.shields.io/badge/website-p--v.pages.dev-brightgreen)](https://p-v.pages.dev)
[![profile views](https://komarev.com/ghpvc/?username=priyavrat-misra&style=flat)](https://www.youtube.com/watch?v=dQw4w9WgXcQ)

## Latest blog posts

{% for post in latest_blog_posts -%}
- [{{ post.title }}]({{ post.link }}) - *{{post.published.strftime("%a, %d %b %Y") }}*
{% endfor %}
