# Introduction:
Write a C program in github.
# Code:

# Contributors:
{% for stu in site.stus %}
  <p>>><img src="{{stu.image}}">@{{ stu.user }} ({{ stu.name }})</p>
  <p>&emsp;>>{{ stu.content | markdownify }}</p>
{% endfor %}
