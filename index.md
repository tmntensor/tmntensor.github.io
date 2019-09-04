---
layout: page
title: 19 сентября 2019
excerpt:
comments: true
---
TTF- ежегодная тусовка любителей кода, где можно обсудить дела насущные, пожаловаться на "любимых" инвесторов, узнать о новинках в IT мире и просто круто провести время в кругу единомышленников.

Как перестать чувствовать дискомфорт при разработке и начать получать удовольствие?

Ведущие разработчики Тензора готовы раскрыть секреты преодоления боли при создании сложных программных продуктов.

Интересно?

[**Регистрируйся**][register] и приходи на Meetup "50 оттенков Enterprise".
	

Доклады
-------

<ul class="post-list">
{% for post in site.categories.talks %}
  {% if post.talk == "meetup_tmn5" %}
    {% if post.author %}
      {% capture authorslist %}
        {% for a in post.author %}
          {% assign author = site.data.authors[a] %}
          {% if author %} {{ author.name }}{% if author.company %}, {{ author.company }}{% endif %}{% endif %}{% unless forloop.last %};{% endunless %}
        {% endfor %}
      {% endcapture %}
    {% endif %}
  {% if post.announce %}
  <li><a href="{{ site.url }}{{ post.url }}">{{ authorslist }}<br/><b>{{ post.title }}</b></a></li>
  {% endif %}
  {% endif %}
{% endfor %}
</ul>

Когда
-----

Итак, 19 сентября в 19:00 состоится пятая встреча программистов в рамках TTF – 2019.
На все доклады отведено 2,5 часа.
Между выступлениями запланирован 10-минутный кофе-брейк, чтобы вы могли перекусить.
Для первых 30-ти зарегистрировавшихся after-party за счет компании!))

Дата: 19/09/2019, четверг.

Время: с 19.00 до 22.00.

__Вход – free.__


Где
---
<iframe src="https://yandex.ru/map-widget/v1/?um=constructor%3A54eaf86410f7effcdc9c33774d3193862bf6c46521fc0f874210e83fac0d80e7&amp;source=constructor" width="700" height="450" frameborder="0"></iframe>

Встреча пройдет по адресу: г. Тюмень, ул. Республики, 159, Отель Восток, конференц-зал Юпитер.

Маршрут от остановки общественного транспорта указан на карте.

Места для парковки автомобилей указаны на карте зеленым цветом.

Контактные телефоны: +7 906 875-06-47 Алёна

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
