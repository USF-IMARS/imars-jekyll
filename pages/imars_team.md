---
layout: page
title: IMaRS Team
---

<!-- these are generated from the members collection -->
# Staff
<ul>
{% for member in site.staff %}
    <li><a href="{{member.url}}">{{member.title}}</a></li>
{% endfor %}
</ul>
-------------------------------------------------

# Students
<ul>
{% for member in site.students %}
    <li><a href="{{member.url}}">{{member.title}}</a></li>
{% endfor %}
</ul>

------------------------------------------------

# Alumni
<ul>
{% for member in site.alumni %}
    <li><a href="{{member.url}}">{{member.title}}</a></li>
{% endfor %}
</ul>

------------------------------------------------

# Others
<ul>
{% for member in site.other_members %}
    <li><a href="{{member.url}}">{{member.title}}</a></li>
{% endfor %}
</ul>
