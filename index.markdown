---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/img/home_1.jpg
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Moje podejście do codziennych finansów. Pasywne dochody i sposoby na niezależność finansową. Subiektywnie, finansowo, rzetelnie."
---
<h1>Najnowszy post</h1>
{% for post in site.posts limit:1 %}
  {% include archive-single.html %}
{% endfor %}
<h1>Poprzednie posty</h1>
{% for post in site.posts offset:1 limit:2 %}
  {% include archive-single.html %}
{% endfor %}