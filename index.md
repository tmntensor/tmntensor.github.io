---
layout: page
title: 27 сентября 2018
excerpt:
comments: true
---

Мы расскажем, как уместили в одном решении 20 различных приложений, которыми пользуется каждая  2-я российская  компания!  А  также,  как добились высокого  коэффициента «переиспользования» кода... Научим, как расставить приоритеты и выполнить все задачи в срок в условиях многозадачности!

Ведущие JS разработчики компании «Тензор» поделятся уникальным опытом на TTF 18!

И, конечно, как без подарков! Тебя ждет сюрприз – лотерея с памятными призами!

[**Регистрируйся**][register] и приходи – мы ждем тебя!
	

Доклады
-------

<ul class="post-list">
{% for post in site.categories.talks %}
  {% if post.talk == "meetup_tmn4" %}
    {% if post.author %}
      {% capture authorslist %}
        {% for a in post.author %}
          {% assign author = site.data.authors[a] %}
          {% if author %} {{ author.name }}{% if author.company %}, {{ author.company }}{% endif %}{% endif %}{% unless forloop.last %};{% endunless %}
        {% endfor %}
      {% endcapture %}
    {% endif %}
  {% if post.announce %}
  <li><a href="{{ site.url }}{{ post.url }}"><b>{{ post.title }}</b><br/>{{ authorslist }}</a></li>
  {% endif %}
  {% endif %}
{% endfor %}
</ul>

Когда
-----

Итак, 27 сентября в 19:00 состоится четвертая встреча программистов в рамках TTF – 2018. На все доклады отведено 3 часа. Между выступлениями запланирован 10-минутный кофе-брейк, чтобы вы могли перекусить. Для первых 30-ти зарегистрировавшихся after-party за счет компании!))

Дата: 27/09/2018, четверг.

Время: с 19.00 до 22.00.

__Вход – free.__


Где
---

Встреча пройдет по адресу: г. Тюмень, ул. Республики, 159, Отель Восток, конференц-зал Юпитер.

Маршрут от остановки общественного транспорта указан на карте. 

Места для парковки автомобилей указаны на карте зеленым цветом.

Контактные телефоны: +7 919 937-94-42 Елена



<script type="text/javascript" charset="utf-8" async src="https://api-maps.yandex.ru/services/constructor/1.0/js/?um=constructor%3A05bf7f1fee214053b937414958cb54975b4b9558d213a4f1eaef058db8d8da1c&amp;width=772&amp;height=546&amp;lang=ru_RU&amp;scroll=true"></script>


<!--
<ul class="post-list">
{% for post in site.posts limit:10 %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></article></li>
{% endfor %}
</ul>
-->

[register]: /register/
[place]: http://rybinsk.vikonda.ru/
[tensor]: http://tensor.ru/
[speakers]: /speakers/
