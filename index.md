# Library

��ϲ��*������*����*ͼ���*�����ĵط�����ʹ�Ҳ�ϲ�����顣��Ϊϣ������żȻ�������µ�ʱ�����ҵ����ǵĴ��ڡ�

*ͼ���*Ҳ�ռ��������˵��л�������ĸ��ע�����ߡ�

<ul>
{% assign sorted_pages = site.pages | sort: "title" | reverse %}
{% for page in sorted_pages %}
  {% if page.category == "post" %}
    <li><a href="{{ page.url }}">{{ page.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>
 
 
 
