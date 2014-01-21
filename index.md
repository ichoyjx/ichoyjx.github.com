---
layout: page
title: Jinxin Yang
tagline: "University of Houston"
---
{% include JB/setup %}

## About Me
Algorithms and techniques enthusiast;

Focused, meticulous researcher and software developer;

Fast learner, problem solver, team player and group leader.

## Posts List

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Resume

I am currently looking for 2014 summer intern or full-time job, please check my [CV](https://raw.github.com/ichoyjx/CV/master/yang.pdf).


