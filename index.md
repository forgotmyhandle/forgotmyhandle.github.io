# Diaries

我会跟你说一些过去的事情，只是想让你明白我……为什么是这样的我。

<ul>
{% assign sorted_pages = site.pages | sort: "title" | reverse %}
{% for page in sorted_pages %}
  {% if page.category == "post" %}
    <li><a href="{{ page.url }}">{{ page.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>
