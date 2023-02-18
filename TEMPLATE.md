[![website](https://img.shields.io/badge/priyavr.at-grey?logo=rss)](https://priyavr.at)
[![profile views](https://komarev.com/ghpvc/?username=priyavrat-misra)](https://priyavr.at)
## Latest blog posts

{% for post in latest_blog_posts -%}
- [{{ post.title }}]({{ post.link }}) - *{{post.published.strftime("%a, %d %b %Y") }}*
{% endfor %}
