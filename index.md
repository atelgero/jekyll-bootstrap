---
layout: page
title: The wall
tagline: мой хомячок.
---

    Вот с этим добром я планирую поработать некоторое ближайшее время вместо ВКонтактика итд.

## Todo:
- расписать "+" и "-" статического блогогенератора;
- поработать с темкой:
    + шрифт с поддержкой кириллицы;
    + посветлее как-то чтоли
- поддержка кириллицы в рейк-файле
    + мб стратегии в конфиг: транслит или перевод

    

## Links
http://www.layouts-the.me/ - неплохая светло-серая [темка](http://www.layouts-the.me/img/minimum.png).


## Posts:
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


