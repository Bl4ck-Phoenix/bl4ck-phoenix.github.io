---
layout: default
title: /
permalink: /
date: 2025-04-07
---

# 🖥️ Bl4ck Phoenix researches

## 🛡️ Anti-Cheat Posts

{%- assign ac_posts = site.posts | where: "category", "ac" -%}
{% for post in ac_posts %}
[{{ post.date | date: "%Y-%m-%d" }}] : [{{ post.title }}]({{ post.url }})
{% endfor %}


---

## ☣️ Malware Posts

{%- assign ac_posts = site.posts | where: "category", "malware" -%}
{% for post in ac_posts %}
[{{ post.date | date: "%Y-%m-%d" }}] : [{{ post.title }}]({{ post.url }})
{% endfor %}


---

## 👾 CTF Posts

{% for post in site.posts %}
  {% if post.category == "ctf" %}
- [ {{ post.date | date: "%Y-%m-%d" }} ] : [{{ post.title }}]({{ post.url }})
  {% endif %}
{% endfor %}

---
<br>
Thanks for stopping by! More posts coming soon.


![Smile](https://i.pinimg.com/originals/6d/58/32/6d5832ce27eaa1e8850321f8ef7555c1.gif)

