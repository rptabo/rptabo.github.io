---
layout: post
title: "Daily Dozen"
date: 2020-09-30
updated: 2020-10-03
published: false
categories: mind body spirit
---

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

- Office of Readings
- Spiritual Reading
- Morning Prayer
- Daytime Prayer
- Violin
- Evening Prayer
- Floss
- Night Prayer
- Meditation
- Brush teeth in the morning
- Get sunshine
- Duolingo German
- Language
- Cold shower
- Station of the Cross
- Chaplet of Divine Mercy
- Divine Mercy Devotions
- Finances
- Brush teeth at night
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
