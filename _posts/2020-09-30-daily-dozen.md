---
layout: post
title: "Daily Dozen"
date: 2020-09-30
updated: 2020-10-13
categories: mind body spirit
---

I use [Org mode][org] within [Emacs][emacs] and one of the features is [habit tracking][habits]. I haven't always been consistent, but there have been a few times I built up what I call the "Daily Dozen": twelve habits I complete every day that support [growth][growth] in spirit, mind, and body.

As of October 7, 2020 I had a over a five week streak for all Daily Dozen:

![daily-dozen](/assets/daily-dozen.png)

[The default view only shows those five weeks so I list the actual streak in parentheses next to the habit to further encourage not "breaking the chain" as Jerry Seinfeld made famous.]

Below are some more details on my current and past habits.

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
- Pimsleur French
- Finances

# Body
- Brush teeth in the morning
- Brush teeth at night
- Floss
- Get sunshine
- Cold shower
- Eat "Primal" (Paleo + dairy)

## Categorized Posts

{% for tag in site.categories %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      {% if post.id != page.id %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
  </ul>
{% endfor %}

[org]: https://orgmode.org/
[emacs]: https://www.gnu.org/software/emacs/
[habits]: https://orgmode.org/manual/Tracking-your-habits.html
[growth]: {% post_url 2020-09-10-growth-or-decay %}
[examen]: {% post_url 2015-04-19-examen %}
[rosary]: https://amzn.com/1492944750
[read]: {% post_url 2020-01-01-reading-goal %}
[hc]: https://en.wikipedia.org/wiki/Harvard_Classics
[mc]: https://www.catholicpsych.com/offers/opwjJ3zW/checkout
[create]: /
[gb]: https://www.gymnasticbodies.com
