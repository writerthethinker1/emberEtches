---
layout: page
title: "Issues*"
picture: pages.jpeg
caption: "New year, new things to do. Move forward, never backwards..."
---

<hr/>

<div>
{% assign postsByYear = site.posts | group_by_exp:"post", "post.date | date: '%Y'" %}
  {% for year in postsByYear %}
    {% if forloop.first %}
    <a href="{{ site.baseurl }}/issues/{{ year.name }}" style="color:#9184ED;font-size:28px">{{ year.name }}*</a>
    {% else %}
    <a href="{{ site.baseurl }}/issues/{{ year.name }}" style="color:#1a1a1a;font-size:28px">{{ year.name }}* Controversies...</a>
    {% endif %}<hr/>
  {% endfor %}
</div>
