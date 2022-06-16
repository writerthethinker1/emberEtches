---
layout: page
title: "Issues*"
picture: pages.jpeg
---

<hr/>

<div>
{% assign postsByYear = site.posts | group_by_exp:"post", "post.date | date: '%Y'" %}
  {% for year in postsByYear %}
    {% if forloop.first %}
    <a href="{{ site.baseurl }}/issues/{{ year.name }}" style="font-size:28px">{{ year.name }}*</a>
    {% else %}
    <a href="{{ site.baseurl }}/issues/{{ year.name }}" style="color:#1a1a1a;font-size:28px">{{ year.name }}* Controversies...</a>
    {% endif %}<hr/>
  {% endfor %}
</div>
