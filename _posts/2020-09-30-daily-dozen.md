---
layout: post
title: "Daily Dozen"
date: 2020-09-30
updated: 2020-10-11
published: false
categories: mind body spirit
---

As of October 7, 2020 I had a over a five week streak for all Daily Dozen:

![daily-dozen](/assets/daily-dozen.png)

## Current

# Spirit
- [Examen][examen]
- [Rosary][rosary]
- Scripture
- Mass
- Adoration

# Mind
- [Read][read]
- [Harvard Classics][hc]
- [Mindfulness][mc]
- Organize
- [Create][create]
- Journal

# Body
- [GB][gb]

## Past

# Spirit
- Office of Readings
- Morning Prayer
- Daytime Prayer
- Evening Prayer
- Night Prayer
- Spiritual Reading
- Station of the Cross
- Chaplet of Divine Mercy
- Divine Mercy Devotions

# Mind
- Violin
- Meditation
- Duolingo German
- Language
- Finances

# Body
- Brush teeth in the morning
- Brush teeth at night
- Floss
- Get sunshine
- Cold shower
- Eat Primal

## Categorized Posts

{% for tag in site.categories %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}

[examen]: {% post_url 2015-04-19-examen %}
[rosary]: https://amzn.com/1492944750
[read]: {% post_url 2020-01-01-reading-goal %}
[hc]: https://en.wikipedia.org/wiki/Harvard_Classics
[mc]: https://www.catholicpsych.com/offers/opwjJ3zW/checkout
[create]: /
[gb]: https://www.gymnasticbodies.com
