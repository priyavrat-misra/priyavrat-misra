[![website](https://img.shields.io/badge/p--v.pages.dev-grey?logo=rss)](https://p-v.pages.dev)
[![profile views](https://komarev.com/ghpvc/?username=priyavrat-misra)](https://www.youtube.com/watch?v=dQw4w9WgXcQ)
## Latest blog posts

{% for post in latest_blog_posts -%}
- [{{ post.title }}]({{ post.link }}) - *{{post.published.strftime("%a, %d %b %Y") }}*
{% endfor %}
